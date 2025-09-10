<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Konrad Szatan – Apache Kafka & Confluent Specialist</title>
  <meta name="description" content="Konrad Szatan – Specjalista Apache Kafka i ekosystemu Confluent. Konsultacje, audyty infrastruktury i architektury streamingowej.">
  <style>
    /* --- Minimalist CSS Styling --- */
    body {
      font-family: Arial, Helvetica, sans-serif;
      margin: 0; padding: 0;
      line-height: 1.6;
      background: #fafafa;  /* light gray background for subtle contrast */
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-bottom: 0.5em;
      font-weight: normal;
    }
    h1 {
      font-size: 2em;
      margin-top: 0.5em;
    }
    h2 {
      font-size: 1.4em;
      margin-top: 2em;
      border-bottom: 2px solid #ccc;
      padding-bottom: 0.2em;
    }
    .tagline {
      font-size: 1.1em;
      font-style: italic;
      color: #555;
      margin-bottom: 1.5em;
    }
    p {
      margin-bottom: 1em;
    }
    ul {
      margin: 0 0 1em 1em;
      padding: 0;
    }
    ul li {
      margin-bottom: 0.5em;
    }
    /* Image styling */
    .profile-pic {
      float: right;          /* Float to the right of text on larger screens */
      margin: 0 0 1em 1em;   /* space around the image */
      width: 150px;
      border-radius: 50%;    /* make it a circle */
    }
    /* Contact form styling */
    .contact-info {
      margin-bottom: 1em;
    }
    form {
      max-width: 400px;
    }
    form label {
      display: block;
      margin: 0.5em 0 0.2em;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.5em;
      border: 1px solid #ccc;
      border-radius: 4px;
      font: inherit;
    }
    form textarea {
      height: 100px;
      resize: vertical;
    }
    form button {
      margin-top: 1em;
      padding: 0.6em 1.2em;
      font: inherit;
      font-weight: bold;
      color: #fff;
      background: #007acc;  /* bluish button */
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    form button:hover {
      background: #005f99;
    }
    /* Language switch buttons */
    .lang-switch {
      text-align: right;
      margin-top: 1em;
    }
    .lang-switch button {
      font: inherit;
      background: none;
      border: none;
      color: #007acc;
      cursor: pointer;
      margin-left: 10px;
      text-decoration: underline;
    }
    .lang-switch button.active {
      font-weight: bold;
      text-decoration: none;
      cursor: default;
      color: #000;
    }
    /* Responsive adjustments */
    @media (max-width: 600px) {
      .profile-pic {
        float: none;
        margin: 0 auto 1em auto;
        display: block;
      }
      .lang-switch {
        text-align: center;
      }
    }
  </style>
</head>
<body>

<div class="container">

  <!-- Language Switch (toggle buttons) -->
  <div class="lang-switch">
    <button id="btn-pl" class="active" onclick="showLang('pl')">Polski</button> | 
    <button id="btn-en" onclick="showLang('en')">English</button>
  </div>

  <!-- Polish Content -->
  <div id="pl-content">
    <h1>Konrad Szatan</h1>
    <div class="tagline">Specjalista Apache Kafka i ekosystemu Confluent</div>
    <!-- Profile photo -->
    <img src="https://www.sages.pl/static/0df9a35ee347ab66075d5d9be167c547/5de9a/IMG_0729_1_1_1_8d420b33bb.webp" alt="Konrad Szatan" class="profile-pic" />
    <!-- About Me in Polish -->
    <h2>O mnie</h2>
    <p>Od ponad dekady specjalizuję się w projektowaniu i wdrażaniu rozwiązań Big Data oraz architektur przetwarzania danych w czasie rzeczywistym opartych o Apache Kafka (w tym platformę Confluent):contentReference[oaicite:7]{index=7}. Pełniłem różne role w projektach – od branży FinTech, przez trading, aż po wysoko obciążone systemy reklamy online:contentReference[oaicite:8]{index=8}. Skupiam się na efektywnym rozwiązywaniu problemów i unikam zbędnego komplikowania projektów:contentReference[oaicite:9]{index=9}.</p>
    <p>Jestem współzałożycielem społeczności inżynierów danych wspierającej rozwój praktycznych umiejętności i wymianę wiedzy w branży. Jako prelegent na konferencjach i meetupach (Java, Scala, DevOps) dzielę się najnowszymi trendami i wyzwaniami w obszarze Big Data i streamingu danych:contentReference[oaicite:10]{index=10}. Pełniłem także rolę niezależnego eksperta Apache Kafka dla dużych organizacji – m.in. przeprowadziłem audyt wykorzystania Kafki i opracowałem plan usprawnień w Raiffeisen Bank International:contentReference[oaicite:11]{index=11}. Prowadząc szkolenia z Apache Kafka, łączę teorię z praktyką i pomagam uczestnikom szybko wdrażać nowe umiejętności w projektach:contentReference[oaicite:12]{index=12}.</p>
    <!-- Services/Offer in Polish -->
    <h2>Oferta</h2>
    <ul>
      <li><strong>Konsultacje i doradztwo:</strong> Pomoc w projektowaniu, wdrażaniu i skalowaniu platform przetwarzania danych w czasie rzeczywistym opartych o Apache Kafka. Doradzam w doborze rozwiązań z ekosystemu Confluent dostosowanych do potrzeb Twojego biznesu.</li>
      <li><strong>Audyt infrastruktury Kafka:</strong> Przegląd obecnej architektury i wykorzystania Apache Kafka w Twojej organizacji. Identyfikuję wąskie gardła, potencjalne ryzyka oraz przygotowuję szczegółowe rekomendacje usprawnień wydajności i architektury:contentReference[oaicite:13]{index=13}.</li>
      <li><strong>Integracja ekosystemu Confluent:</strong> Wsparcie we wdrożeniu i konfiguracji komponentów platformy Confluent (np. Schema Registry, Kafka Connect, ksqlDB) oraz integracji Kafki z istniejącymi systemami w Twojej infrastrukturze.</li>
      <li><strong>Szkolenia i warsztaty:</strong> Praktyczne szkolenia dopasowane do potrzeb zespołu z zakresu Apache Kafka – od podstaw po zaawansowane tematy (Kafka Streams, ksqlDB, itp.). Umożliwiam Twojemu zespołowi szybkie zdobycie praktycznych umiejętności w obszarze streamingu danych.</li>
    </ul>
    <!-- Contact section in Polish -->
    <h2>Kontakt</h2>
    <p class="contact-info">Skontaktuj się ze mną poprzez formularz poniżej lub pisząc na adres email: <a href="mailto:konradszatan11@gmail.com">konradszatan11@gmail.com</a>. Chętnie odpowiem na Twoje pytania.</p>
    <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
      <label for="name-pl">Imię i Nazwisko:</label>
      <input type="text" id="name-pl" name="name" required>
      
      <label for="email-pl">Email:</label>
      <input type="email" id="email-pl" name="_replyto" required>
      
      <label for="message-pl">Wiadomość:</label>
      <textarea id="message-pl" name="message" required></textarea>
      
      <!-- The _language field is optional, just to know language of submission -->
      <input type="hidden" name="_language" value="PL">
      <!-- Optionally, set a custom email subject for form submissions -->
      <input type="hidden" name="_subject" value="Zapytanie ze strony (PL)">
      
      <button type="submit">Wyślij</button>
    </form>
  </div> <!-- end of #pl-content -->

  <!-- English Content (hidden by default) -->
  <div id="en-content" style="display:none;">
    <h1>Konrad Szatan</h1>
    <div class="tagline">Apache Kafka & Confluent Ecosystem Specialist</div>
    <!-- Profile photo (can reuse the same image source) -->
    <img src="https://www.sages.pl/static/0df9a35ee347ab66075d5d9be167c547/5de9a/IMG_0729_1_1_1_8d420b33bb.webp" alt="Konrad Szatan" class="profile-pic" />
    <!-- About Me in English -->
    <h2>About Me</h2>
    <p>I am a Big Data and real-time streaming solutions specialist with over a decade of experience in designing and implementing data architectures powered by Apache Kafka (including the Confluent Platform):contentReference[oaicite:14]{index=14}. I have held various roles in projects across industries – from FinTech and trading to high-volume online advertising systems:contentReference[oaicite:15]{index=15}. My approach emphasizes solving problems efficiently and avoiding unnecessary complexity in projects:contentReference[oaicite:16]{index=16}.</p>
    <p>I am also a co-founder of a data engineers community in Poland, which fosters the development of practical skills and knowledge-sharing in the industry. As a speaker at tech conferences and meetups (Java, Scala, DevOps), I share the latest trends and challenges in Big Data and data streaming:contentReference[oaicite:17]{index=17}. I have served as an independent Apache Kafka expert for large organizations – for example, I conducted a Kafka usage audit and improvement plan for Raiffeisen Bank International:contentReference[oaicite:18]{index=18}. In addition, as a Kafka trainer, I combine theory with hands-on practice, helping participants quickly apply new skills in their projects:contentReference[oaicite:19]{index=19}.</p>
    <!-- Services/Offer in English -->
    <h2>Services</h2>
    <ul>
      <li><strong>Consulting & Advisory:</strong> Guidance in designing, implementing, and scaling real-time data processing platforms using Apache Kafka. I advise on adopting the right Confluent ecosystem tools tailored to your business needs, ensuring an efficient event-driven architecture.</li>
      <li><strong>Kafka Infrastructure Audit:</strong> A thorough review of your current Apache Kafka setup and usage. I identify performance bottlenecks and potential risks, then provide detailed recommendations to optimize your Kafka deployment’s performance and architecture:contentReference[oaicite:20]{index=20}.</li>
      <li><strong>Confluent Ecosystem Integration:</strong> Support with deploying and configuring Confluent Platform components (e.g., Schema Registry, Kafka Connect, ksqlDB) and integrating Kafka with your existing systems, to achieve a seamless streaming data pipeline.</li>
      <li><strong>Training & Workshops:</strong> Hands-on training sessions tailored to your team’s needs, covering Apache Kafka from fundamentals to advanced topics (Kafka Streams, ksqlDB, etc.). These workshops help your team quickly gain practical expertise in building streaming solutions.</li>
    </ul>
    <!-- Contact section in English -->
    <h2>Contact</h2>
    <p class="contact-info">Feel free to reach out by filling the form below or by emailing me at <a href="mailto:konradszatan11@gmail.com">konradszatan11@gmail.com</a>. I will be happy to answer any questions or discuss how I can help your project.</p>
    <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
      <label for="name-en">Name:</label>
      <input type="text" id="name-en" name="name" required>
      
      <label for="email-en">Email:</label>
      <input type="email" id="email-en" name="_replyto" required>
      
      <label for="message-en">Message:</label>
      <textarea id="message-en" name="message" required></textarea>
      
      <!-- hidden field to indicate the language (optional) -->
      <input type="hidden" name="_language" value="EN">
      <!-- custom email subject for English form submissions -->
      <input type="hidden" name="_subject" value="Website Inquiry (EN)">
      
      <button type="submit">Send Message</button>
    </form>
  </div> <!-- end of #en-content -->

</div> <!-- end of .container -->

<!-- Language toggle script: shows one language, hides the other -->
<script>
  function showLang(lang) {
    var pl = document.getElementById('pl-content');
    var en = document.getElementById('en-content');
    var btnPl = document.getElementById('btn-pl');
    var btnEn = document.getElementById('btn-en');
    if (lang === 'pl') {
      pl.style.display = 'block';
      en.style.display = 'none';
      btnPl.classList.add('active');
      btnEn.classList.remove('active');
    } else if (lang === 'en') {
      pl.style.display = 'none';
      en.style.display = 'block';
      btnPl.classList.remove('active');
      btnEn.classList.add('active');
    }
    // Scroll back to top whenever language is switched (optional):
    window.scrollTo(0, 0);
  }
</script>

</body>
</html>
