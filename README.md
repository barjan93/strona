<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Move Point Studio — fizjoterapia i trening motoryczny w Łodzi (Łąkowa 11)</title>
  <meta name="description" content="Move Point Studio: fizjoterapia, rehabilitacja i trening motoryczny w Łodzi. Umów kontakt — Łąkowa 11. Zadzwoń lub napisz na Instagramie i Facebooku." />
  <meta name="color-scheme" content="light">
  <meta name="theme-color" content="#ffffff" />

  <!-- Open Graph / Twitter -->
  <meta property="og:title" content="Move Point Studio — fizjoterapia i trening w Łodzi" />
  <meta property="og:description" content="Fizjoterapia, rehabilitacja i trening motoryczny — Łąkowa 11, Łódź. Skontaktuj się z nami!" />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="Assets/Favicon.png" />
  <meta name="twitter:card" content="summary" />

  <!-- Favicon -->
  <link rel="icon" href="Assets/Favicon.png" type="image/png">

  <!-- JSON-LD: LocalBusiness -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Move Point Studio",
    "slogan": "This the Point",
    "image": "Assets/Orientation=Vertical, Color=Black.svg",
    "logo": "Assets/Orientation=Vertical, Color=Black.svg",
    "address": {
      "@type": "PostalAddress",
      "streetAddress": "Łąkowa 11",
      "addressLocality": "Łódź",
      "postalCode": "90-505",
      "addressCountry": "PL"
    },
    "geo": { "@type": "GeoCoordinates", "latitude": 51.76145325600176, "longitude": 19.439943203395647 },
    "hasMap": "https://maps.google.com/?q=%C5%81%C4%85kowa%2011,%20%C5%81%C3%B3d%C5%BA",
    "sameAs": [
      "https://www.instagram.com/movepointstudio/?utm_source=ig_web_button_share_sheet",
      "https://www.facebook.com/profile.php?id=61579200637444"
    ],
    "contactPoint": [
      { "@type": "ContactPoint", "telephone": "+48 605 607 042", "contactType": "customer service", "areaServed": "PL", "availableLanguage": "pl" },
      { "@type": "ContactPoint", "telephone": "+48 791 542 539", "contactType": "physiotherapy", "areaServed": "PL", "availableLanguage": "pl" },
      { "@type": "ContactPoint", "telephone": "+48 668 802 147", "contactType": "physiotherapy", "areaServed": "PL", "availableLanguage": "pl" }
    ],
    "areaServed": "Łódź, Polska",
    "keywords": "trening, trening motoryczny, fizjoterapia, rehabilitacja, zdrowie, Łódź, Łąkowa 11",
    "knowsAbout": ["trening", "trening motoryczny", "fizjoterapia", "rehabilitacja", "zdrowie", "profilaktyka urazów", "powrót do sportu"]
  }
  </script>

  <!-- JSON-LD: FAQPage -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
      { "@type": "Question", "name": "Na czym polega trening motoryczny w Move Point Studio?", "acceptedAnswer": { "@type": "Answer", "text": "Trening motoryczny to indywidualny program poprawy siły, mocy, stabilności i mobilności. Łączymy diagnostykę z ćwiczeniami dopasowanymi do celu: powrót do sportu, lepsza forma lub profilaktyka urazów." } },
      { "@type": "Question", "name": "Kiedy wybrać fizjoterapię, a kiedy rehabilitację?", "acceptedAnswer": { "@type": "Answer", "text": "Fizjoterapia obejmuje diagnostykę i terapię bólu oraz dysfunkcji, a rehabilitacja to proces powrotu do pełnej sprawności po urazie lub operacji. W Move Point Studio projektujemy plan łączący oba podejścia." } },
      { "@type": "Question", "name": "Czy potrzebuję skierowania na wizytę?", "acceptedAnswer": { "@type": "Answer", "text": "Nie. Skontaktuj się z nami telefonicznie lub przez Instagram — ustalimy termin i dobierzemy odpowiednią formę terapii lub treningu." } },
      { "@type": "Question", "name": "Gdzie nas znajdziesz?", "acceptedAnswer": { "@type": "Answer", "text": "Jesteśmy w Łodzi przy ul. Łąkowa 11 (90-505). Zobacz dojazd w Google Maps: https://maps.google.com/?q=%C5%81%C4%85kowa%2011,%20%C5%81%C3%B3d%C5%BA" } }
    ]
  }
  </script>

  <style>
/* ===== FONTY ===== */
@font-face{ font-family:'Space Mono'; src:url('assets/fonts/SpaceMono-Regular.ttf') format('truetype'); font-weight:400; font-style:normal; font-display:swap; }
@font-face{ font-family:'Space Mono'; src:url('assets/fonts/SpaceMono-Bold.ttf') format('truetype'); font-weight:700; font-style:normal; font-display:swap; }

/* ===== PALETA ===== */
:root{
  --bg-base:#ffffff;
  --g-orange:#FA4616;
  --g-teal:#84CEC3;
  --g-deep:#00313C;
  --text:#000;
  --muted:#4b5563;
  --radius:20px;
  --shadow:0 10px 30px rgba(0,0,0,.06);

  --ig-1:#833AB4; --ig-2:#FD1D1D; --ig-3:#F77737;
  --fb-1:#1877F2; --fb-2:#3b5998;
}

/* ===== RESET / LAYOUT ===== */
*{ box-sizing:border-box; }
html,body{ height:100%; margin:0; font-family:'Space Mono', monospace; color:var(--text); }
body{ background:var(--bg-base); }
.bg-fixed{
  position:fixed; inset:0; z-index:-1; pointer-events:none;
  background:
    radial-gradient(1300px 1000px at -35% -20%, var(--g-orange) 0%, rgba(250,70,22,0) 80%),
    radial-gradient(1500px 1100px at 88% 88%, var(--g-teal) 0%, rgba(132,206,195,0) 78%),
    radial-gradient(700px 700px at 83% 85%, var(--g-deep) 0%, rgba(0,49,60,0) 70%),
    var(--bg-base);
}
.container{ width:100%; max-width:1040px; margin:24px auto 48px; padding:0 24px; }
.card{
  width:100%; background:#ffffffcc; border:1px solid #e5e7eb; border-radius:var(--radius);
  padding:28px; backdrop-filter:saturate(120%) blur(4px); box-shadow:var(--shadow);
}

/* ===== HEADER ===== */
.logo-wrap{ display:flex; justify-content:center; margin-bottom:10px; }
.logo{ max-width:240px; width:100%; height:auto; }

/* TAGLINE ===== */
.tagline{ text-align:center; font-size:20px; font-weight:700; margin:2px 0 18px; letter-spacing:1px; text-transform:uppercase; overflow:hidden; }
.tagline .orange{ color:var(--g-orange); display:inline-block; opacity:0; animation:slideInLeft .8s ease forwards; }
.tagline .teal{ color:var(--g-teal); display:inline-block; opacity:0; animation:slideInRight .8s ease .15s forwards; }
@keyframes slideInLeft{ from{ transform:translateX(-12px); opacity:0; } to{ transform:translateX(0); opacity:1; } }
@keyframes slideInRight{ from{ transform:translateX(12px); opacity:0; } to{ transform:translateX(0); opacity:1; } }

h1{ font-size:clamp(26px,4vw,38px); text-align:center; margin:6px 0 8px; }
/* zmniejszona czcionka tylko dla konkretnego nagłówka */
.announcement{ font-size:clamp(20px,3.2vw,28px); }
.lead{ color:var(--muted); text-align:center; margin:0 0 24px; font-size:clamp(15px,2.2vw,18px); }

/* ===== GRID KONTAKT ===== */
.grid{ display:grid; gap:18px; grid-template-columns:1fr; margin-top:22px; }
@media (min-width:720px){ .grid{ grid-template-columns:1fr 1fr; } }

.section{
  border:1px solid #e5e7eb; border-radius:14px; padding:18px; background:#ffffffa6;
  animation:fadeUp .6s ease both;
}
@keyframes fadeUp{ from{opacity:0; transform:translateY(10px);} to{opacity:1; transform:translateY(0);} }

.section-header{ display:block; margin:0 auto 12px; max-height:40px; }
@media (min-width:720px){ .section-header{ max-height:44px; } }

.section .person{
  display:flex; justify-content:space-between; align-items:center; gap:10px;
  padding:12px 0; border-top:1px dashed #e5e7eb;
}
.section .person:first-of-type{ border-top:none; }
.name{ font-weight:700; }

/* ===== PHONE ===== */
.phone a{
  text-decoration:none; padding:8px 14px; border-radius:10px; display:inline-block;
  font-weight:700; transition:background .25s ease, transform .15s ease; color:#fff;
}
.phone a.orange{ background:#FA4616; }
.phone a.teal{ background:#84CEC3; color:#0b2b2f; }
.phone a.orange:hover{ background: color-mix(in srgb, #FA4616 80%, white); transform: scale(1.05); }
.phone a.teal:hover{ background: color-mix(in srgb, #84CEC3 85%, white); transform: scale(1.05); }
.phone a:active{ transform: scale(0.98); }

/* ===== UNIWERSALNY BLOK SOCIAL ===== */
.socials-universal{
  margin: 12px auto 6px; text-align:center; animation:fadeUp .6s ease both;
}
.socials-universal .label{
  color:#111; font-weight:800; margin-bottom:10px;
}
.socials-row{
  display:flex; gap:12px; justify-content:center; flex-wrap:wrap;
}
.social-btn{
  display:inline-flex; align-items:center; gap:10px;
  padding:12px 16px; border-radius:14px; border:1px solid #e5e7eb; background:#ffffff;
  text-decoration:none; color:#111; font-weight:700; box-shadow:0 8px 20px rgba(0,0,0,.06);
  transition: transform .18s ease, box-shadow .2s ease, color .2s ease, border-color .2s ease, background .35s ease;
  will-change: transform;
}
.social-btn svg{ width:22px; height:22px; fill: currentColor; }
.social-btn.instagram:hover{
  color:#fff; background:linear-gradient(45deg,var(--ig-1),var(--ig-2),var(--ig-3));
  border-color:var(--ig-1); transform:translateY(-1px) scale(1.03); box-shadow:0 10px 26px rgba(131,58,180,.25);
}
.social-btn.facebook:hover{
  color:#fff; background:linear-gradient(45deg,var(--fb-1),var(--fb-2));
  border-color:var(--fb-1); transform:translateY(-1px) scale(1.03); box-shadow:0 10px 26px rgba(24,119,242,.25);
}

/* ===== WHY CONTACT ===== */
.why{ margin-top:28px; text-align:center; }
.why h2{ font-size:22px; margin-bottom:16px; }
.reasons{ display:grid; gap:16px; grid-template-columns:1fr; }
@media (min-width:600px){ .reasons{ grid-template-columns:1fr 1fr 1fr; } }
.reason{ background:#fff; border:1px solid #e5e7eb; border-radius:12px; padding:16px; box-shadow:var(--shadow); }
.reason h3{ margin:8px 0; font-size:16px; }

/* ===== LOKALIZACJA / MAPA (MNIEJSZA) ===== */
.location{ margin-top:28px; }
.location h2{ text-align:center; font-size:22px; margin-bottom:10px; }
.addr{
  display:flex; gap:10px; justify-content:center; align-items:center; flex-wrap:wrap; margin-bottom:12px; color:#111;
}
.addr .pill{
  border:1px solid #e5e7eb; background:#fff; padding:8px 12px; border-radius:999px; box-shadow:var(--shadow); font-weight:700;
}
.addr a.map-link{
  text-decoration:none; font-weight:700; color:#fff; background:#111; padding:10px 14px; border-radius:12px;
  transition: transform .15s ease, filter .2s ease; display:inline-flex; align-items:center; gap:8px;
}
.addr a.map-link:hover{ filter:brightness(1.05); transform:translateY(-1px); }
.addr a.map-link:active{ transform:translateY(0); }

.map-card{
  background:#ffffffcc; border:1px solid #e5e7eb; border-radius:14px; box-shadow:var(--shadow);
  overflow:hidden; max-width:560px; margin:0 auto;
}
.map-wrap{ position:relative; width:100%; aspect-ratio:4 / 3; }
.map-wrap iframe{ position:absolute; inset:0; width:100%; height:100%; border:0; }

/* ===== STOPKA ===== */
.footer{ margin-top:26px; font-size:12px; color:#6b7280; text-align:center; }

/* ===== STICKY BAR (MOBILE) ===== */
.sticky-actions{
  position:fixed; left:0; right:0; bottom:0; z-index:50;
  display:grid; grid-template-columns:1fr 1fr 1fr; gap:8px;
  padding:10px 12px calc(10px + env(safe-area-inset-bottom));
  background:rgba(255,255,255,.85); backdrop-filter:saturate(120%) blur(8px);
  border-top:1px solid #e5e7eb;
}
.sticky-actions a{
  display:flex; align-items:center; justify-content:center; gap:8px;
  height:52px; border-radius:12px; text-decoration:none; font-weight:800; letter-spacing:.2px;
  color:#fff; box-shadow:0 8px 20px rgba(0,0,0,.10); transition:transform .15s ease, filter .15s ease;
}
.sticky-actions a svg{ width:20px; height:20px; fill:#fff; }
.sticky-actions .call{ background:var(--g-orange); }
.sticky-actions .ig{ background:var(--g-teal); color:#0b2b2f; }
.sticky-actions .ig svg{ fill:#0b2b2f; }
.sticky-actions .map{ background:#111; }
.sticky-actions a:active{ transform:scale(.98); }

@media (max-width:719.98px){ .container{ padding-bottom:calc(84px + env(safe-area-inset-bottom)); } }
@media (min-width:720px){ .sticky-actions{ display:none; } }

/* DOSTĘPNOŚĆ */
@media (prefers-reduced-motion: reduce){
  .tagline .orange, .tagline .teal, .section, .social-btn{ animation:none !important; }
  .social-btn, .sticky-actions a{ transition:none !important; }
}

{
  /* większe odstępy między sekcjami */
  .grid{ gap:32px; }
  @media (min-width:720px){ .grid{ gap:40px; } }

  /* większe separatory pomiędzy głównymi blokami */
  .socials-universal{ margin:24px auto 18px; }
  .why{ margin-top:40px; }
  .location{ margin-top:40px; }
  .footer{ margin-top:48px; }

  /* silniejsze odstępy między blokami i lepsza separacja wizualna */
  .grid{ gap:48px; }
  @media (min-width:720px){ .grid{ gap:56px; } }

  .socials-universal{ margin:32px auto 20px; }
  .why{ margin-top:56px; }
  .location{ margin-top:64px; }
  .footer{ margin-top:72px; }

  /* większe paddingi w sekcjach, żeby treść miała "oddech" */
  .section{ padding:22px; }
  @media (min-width:720px){ .section{ padding:24px; } }

  /* opcjonalnie: wyraźniejszy odstęp pomiędzy kartami wewnątrz gridu */
  .section + .section{ margin-top:8px; } /* działające gdy sekcje w pionie */
  @media (min-width:720px){ .section + .section{ margin-top:0; } }
}
  </style>
</head>
<body>
  <div class="bg-fixed" aria-hidden="true"></div>
  <div class="container">
    <main class="card" role="main">
      <!-- LOGO -->
      <div class="logo-wrap">
        <img src="Assets/Orientation=Vertical, Color=Black.svg" alt="Move Point Studio — logo" class="logo" />
      </div>

      <!-- HASŁO POD LOGO -->
      <p class="tagline"><span class="orange">This is</span> <span class="teal">the Point</span></p>

      <h1 class="announcement">🚧JESZCZE KILKA POWTÓRZEŃ I STRONA GOTOWA!🚧</h1>
      <p class="lead">Do tego czasu – dzwoń lub wpadaj na social media.</p>

      <!-- SEKCJE KONTAKTU -->
      <div class="grid">
        <!-- TRENINGI -->
        <section class="section">
          <img src="assets/Color=Orange.svg" alt="TRENINGI — Move Point Studio" class="section-header">
          <div class="person">
            <div><div class="name">BARTEK</div></div>
            <div class="phone"><a class="orange" href="tel:+48605607042">+48 605 607 042</a></div>
          </div>
        </section>

        <!-- FIZJO -->
        <section class="section">
          <img src="assets/Color=Green.svg" alt="FIZJOTERAPIA — Move Point Studio" class="section-header">
          <div class="person">
            <div><div class="name">IZA</div></div>
            <div class="phone"><a class="teal" href="tel:+48791542539">+48 791 542 539</a></div>
          </div>
          <div class="person">
            <div><div class="name">ADAM</div></div>
            <div class="phone"><a class="teal" href="tel:+48668802147">+48 668 802 147</a></div>
          </div>
        </section>
      </div>

      <!-- UNIWERSALNE SOCIALE (tuż pod całym gridem) -->
      <div class="socials-universal" aria-label="Napisz do nas w social media">
        <div class="label">…albo napisz do nas:</div>
        <div class="socials-row">
          <a class="social-btn instagram" href="https://www.instagram.com/movepointstudio/?utm_source=ig_web_button_share_sheet" target="_blank" rel="noopener" aria-label="Instagram — Move Point Studio">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 2h10a5 5 0 015 5v10a5 5 0 01-5 5H7a5 5 0 01-5-5V7a5 5 0 015-5zm0 2a3 3 0 00-3 3v10a3 3 0 003 3h10a3 3 0 003-3V7a3 3 0 00-3-3H7zm5 3.5A5.5 5.5 0 116.5 13 5.5 5.5 0 0112 7.5zm6-1.25a1.25 1.25 0 11-1.25 1.25A1.25 1.25 0 0118 6.25z"/></svg>
            <span>Instagram</span>
          </a>
          <a class="social-btn facebook" href="https://www.facebook.com/profile.php?id=61579200637444" target="_blank" rel="noopener" aria-label="Facebook — Move Point Studio">
            <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M13.5 22v-8.2h2.8l.4-3.2h-3.2V8.5c0-.9.3-1.6 1.6-1.6h1.7V4c-.3 0-1.3-.1-2.5-.1-2.5 0-4.2 1.5-4.2 4.3v2.3H8v3.2h2.1V22h3.4z"/></svg>
            <span>Facebook</span>
          </a>
        </div>
      </div>

      <!-- WHY CONTACT -->
      <div class="why">
        <h2>Dlaczego warto się odezwać?</h2>
        <div class="reasons">
          <div class="reason">
            <h3>📞 Jesteśmy na wyciągnięcie ręki</h3>
            <p>Telefon, wiadomość, social media – wybierz, co Ci wygodniej.</p>
          </div>
          <div class="reason">
            <h3>💪 Profesjonalna opieka</h3>
            <p>Łączymy fizjoterapię i trening, żeby dać Ci pełne wsparcie.</p>
          </div>
          <div class="reason">
            <h3>⚡ Nowoczesna fizjoterapia i trening</h3>
            <p>Innowacyjne rozwiązania i profesjonalne podejście sprawiają, że Twój trening i terapia są precyzyjne, skuteczne i dopasowane do Ciebie.</p>
          </div>
        </div>
      </div>

      <!-- LOKALIZACJA (mapa mniejsza) -->
      <section class="location" aria-label="Lokalizacja Move Point Studio">
        <h2>Fizjoterapia i trening w Łodzi — Łąkowa 11</h2>
        <div class="addr">
          <span class="pill">Łąkowa 11, 90-505 Łódź</span>
          <a class="map-link" href="https://maps.google.com/?q=%C5%81%C4%85kowa%2011,%20%C5%81%C3%B3d%C5%BA" target="_blank" rel="noopener" aria-label="Otwórz w Google Maps">Otwórz w Mapach</a>
        </div>
        <div class="map-card">
          <div class="map-wrap">
            <iframe
              title="Mapa — Łąkowa 11, Łódź"
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d154.34037499308621!2d19.439943203395647!3d51.76145325600176!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x471a352e6fb787fd%3A0xbe92d7670c4c24a3!2zxYHEhWtvd2EgMTEsIDkwLTUwNSDFgcOzZMW6!5e0!3m2!1spl!2spl!4v1757635111047!5m2!1spl!2spl"
              loading="lazy" referrerpolicy="no-referrer-when-downgrade" allowfullscreen>
            </iframe>
          </div>
        </div>
      </section>

      <div class="footer">
        © <span id="year"></span> Move Point Studio / Wszystkie prawa zastrzeżone
      </div>
    </main>
  </div>

  <!-- STICKY BAR: tylko na telefonach -->
  <nav class="sticky-actions" aria-label="Szybkie akcje">
    <a class="call" href="tel:+48605607042" aria-label="Zadzwoń do Move Point Studio">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6.6 10.8a15.9 15.9 0 006.6 6.6l2.2-2.2a1 1 0 011.1-.23 12.7 12.7 0 004.1 1.1 1 1 0 011 1V20a1 1 0 01-1 1A17 17 0 013 4a1 1 0 011-1h2.9a1 1 0 011 1 12.7 12.7 0 001.1 4.1 1 1 0 01-.23 1.1L6.6 10.8z"/></svg>
      Zadzwoń
    </a>
    <a class="ig" href="https://www.instagram.com/movepointstudio/?utm_source=ig_web_button_share_sheet" target="_blank" rel="noopener" aria-label="Napisz na Instagramie">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M7 2h10a5 5 0 015 5v10a5 5 0 01-5 5H7a5 5 0 01-5-5V7a5 5 0 015-5zm0 2a3 3 0 00-3 3v10a3 3 0 003 3h10a3 3 0 003-3V7a3 3 0 00-3-3H7zm5 3.5A5.5 5.5 0 116.5 13 5.5 5.5 0 0112 7.5zm6-1.25a1.25 1.25 0 11-1.25 1.25A1.25 1.25 0 0118 6.25z"/></svg>
      Instagram
    </a>
    <a class="map" href="https://maps.google.com/?q=%C5%81%C4%85kowa%2011,%20%C5%81%C3%B3d%C5%BA" target="_blank" rel="noopener" aria-label="Otwórz w Google Maps">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2a7 7 0 00-7 7c0 5.25 7 13 7 13s7-7.75 7-13a7 7 0 00-7-7zm0 9.5A2.5 2.5 0 119.5 9 2.5 2.5 0 0112 11.5z"/></svg>
      Mapa
    </a>
  </nav>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
