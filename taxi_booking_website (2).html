<!doctype html>
<html lang="nl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>XGROUP – Taxi Service</title>
  <style>
    :root {
      --bg: #0b0c10;
      --card: #0f1115;
      --muted: #aab0b6;
      --accent: #f5c400;
      --radius: 12px;
      font-family: 'Inter', sans-serif;
    }
    body { margin:0; padding:0; background: var(--bg); color:#e9eef3; }
    a { color: var(--accent); text-decoration:none; }
    nav { display:flex; justify-content:space-between; align-items:center; padding:20px; }
    nav .logo img { height:50px; }
    nav .nav-links { display:flex; gap:20px; }
    header { text-align:center; padding:60px 20px; }
    header h1 { font-size:36px; margin:0; }
    header p { color: var(--muted); margin-top:8px; }
    .section { padding:60px 20px; max-width:800px; margin:auto; }
    .section h2 { font-size:28px; margin-bottom:20px; }
    .contact-form { background: var(--card); padding:20px; border-radius: var(--radius); }
    .contact-form label { display:block; margin-top:12px; color: var(--muted); }
    .contact-form input, .contact-form textarea { width:100%; padding:10px; border:1px solid rgba(255,255,255,0.1); border-radius: var(--radius); background:transparent; color:inherit; margin-top:6px; }
    .contact-form button { margin-top:20px; padding:12px 20px; border:none; background: var(--accent); color:#0b0c10; font-weight:bold; border-radius: var(--radius); cursor:pointer; }
    .contact-note { margin-top:10px; font-size:14px; color: var(--muted); }
    footer { text-align:center; padding:20px 0; color: var(--muted); }
    .notify { margin-top:10px; padding:10px; border-radius: var(--radius); }
    .success { background: rgba(0,128,0,0.1); border:1px solid rgba(0,128,0,0.2); color:#bde6bd; }
    .error { background: rgba(255,0,0,0.1); border:1px solid rgba(255,0,0,0.2); color:#f5bcbc; }
  </style>
</head>
<body>
  <nav>
    <div class="logo"><img src="assets/logo.png" alt="XGROUP logo"></div>
    <div class="nav-links">
      <a href="#diensten">Diensten</a>
      <a href="#contact">Boek Taxi</a>
    </div>
  </nav>

  <header>
    <h1>Professionele taxi via XGROUP</h1>
    <p>Rijd veilig. Boek gemakkelijk. 24/7 beschikbaar.</p>
  </header>

  <section class="section" id="diensten">
    <h2>Onze Diensten</h2>
    <p>Wij bieden ritten voor stad, luchthaven en privé vervoer — snel, veilig, betrouwbaar.</p>
  </section>

  <section class="section" id="contact">
    <h2>Boek je Taxi</h2>
    <div class="contact-form">
      <form id="taxiForm">
        <label for="name">Naam</label>
        <input id="name" name="name" type="text" required>

        <label for="pickup">Adres ophalen</label>
        <input id="pickup" name="pickup_address" type="text" required>

        <label for="destination">Bestemming</label>
        <input id="destination" name="destination" type="text" required>

        <label for="datetime">Datum & tijd</label>
        <input id="datetime" name="datetime" type="datetime-local" required>

        <label for="phone">Telefoonnummer</label>
        <input id="phone" name="phone" type="tel" required>

        <button type="submit">Boek taxi</button>
        <div id="status"></div>
      </form>
      <p class="contact-note">Je gegevens worden gestuurd naar <strong>alhaririplay@gmail.com</strong></p>
    </div>
  </section>

  <footer>
    © 2025 XGROUP. Alle rechten voorbehouden.
  </footer>

  <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
  <script>
    // EmailJS instellingen
    const SERVICE_ID = 'service_1bozkdd'; // jouw service ID
    const TEMPLATE_ID = 'template_pbk318x'; // jouw template ID
    const USER_ID = '5fTvRF4xrvdOmA77d'; // jouw public key

    (function(){ if(window.emailjs){ emailjs.init(USER_ID); }})();

    const form = document.getElementById('taxiForm');
    const statusDiv = document.getElementById('status');

    form.addEventListener('submit', function(e){
      e.preventDefault();
      const data = {
        name: form.name.value,
        pickup_address: form.pickup_address.value,
        destination: form.destination.value,
        datetime: form.datetime.value,
        phone: form.phone.value
      };
      statusDiv.innerHTML = '<div class="notify">Verzenden...</div>';
      emailjs.send(SERVICE_ID, TEMPLATE_ID, data)
        .then(() => {
          statusDiv.innerHTML = '<div class="notify success">Boeking verstuurd!</div>';
          form.reset();
        }, (err) => {
          statusDiv.innerHTML = '<div class="notify error">Error bij verzenden.</div>';
          console.error(err);
        });
    });
  </script>
</body>
</html>
