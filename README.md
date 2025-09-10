---
title: Konrad Szatan – Apache Kafka & Confluent Specialist
layout: default
---

<style>
  :root { --accent:#0b74d1; }
  body { font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Arial, sans-serif; line-height:1.65; color:#222; background:#fafafa; margin:0; }
  .wrap { max-width: 860px; margin: 0 auto; padding: 24px; background:#fff; }
  h1 { margin: 0.2em 0 0.1em; font-weight:700; }
  h2 { border-bottom:2px solid #eee; padding-bottom:.25em; margin-top:2em; }
  .tagline { color:#555; font-style:italic; margin-bottom:1.2em; }
  .lang { display:none; }
  .lang.active { display:block; }
  .lang-switch { text-align: right; margin-bottom: 12px; }
  .lang-switch button { background:none; border:none; color:var(--accent); text-decoration:underline; cursor:pointer; font:inherit; margin-left:8px; }
  .lang-switch button.active { color:#000; font-weight:700; text-decoration:none; cursor:default; }
  .profile { float:right; width:160px; height:160px; border-radius:50%; object-fit:cover; margin:0 0 1rem 1rem; }
  ul { margin: 0 0 1em 1.2em; }
  .contact-info a { color: var(--accent); }
  form { max-width: 460px; }
  label { display:block; margin:.6em 0 .2em; }
  input, textarea { width:100%; padding:.6em; border:1px solid #ddd; border-radius:8px; font:inherit; background:#fff; }
  textarea { min-height:110px; resize:vertical; }
  button[type="submit"] { margin-top:.9em; padding:.7em 1.2em; background:var(--accent); color:#fff; border:none; border-radius:10px; font-weight:700; cursor:pointer; }
  button[type="submit"]:hover { filter:brightness(.95); }
  @media (max-width:640px){ .profile{ float:none; margin:0 auto 1rem; display:block; } .lang-switch{ text-align:center; } }
  footer { margin-top:2.4rem; font-size:.9rem; color:#666; }
</style>

<div class="wrap">

  <div class="lang-switch">
    <button id="btn-pl" class="active" onclick="showLang('pl')">Polski</button> |
    <button id="btn-en" onclick="showLang('en')">English</button>
  </div>

  <!-- ======== POLSKI ======== -->
  <section id="pl" class="lang active">
    <h1>Konrad Szatan</h1>
    <div class="tagline">Specjalista Apache Kafka i ekosystemu Confluent</div>

    <!-- Zdjęcie: podmień ścieżkę na własny plik w repo -->
    <img src="assets/konrad.jpg" alt="Konrad Szatan" class="profile" />

    <h2>O mnie</h2>
    <p>Projektuję i wdrażam architektury przetwarzania danych w czasie rzeczywistym oparte o <strong>Apache Kafka</strong> i platformę <strong>Confluent</strong>. Pomagam zespołom budować skalowalne, odporne i przewidywalne systemy streamingowe – od koncepcji, przez POC, po produkcję.</p>

    <h2>Oferta</h2>
    <ul>
      <li><strong>Konsultacje i doradztwo:</strong> projektowanie i przeglądy architektur event-driven, dobór komponentów Confluent (Kafka Connect, Schema Registry, ksqlDB, Kafka Streams), najlepsze praktyki i standardy.</li>
      <li><strong>Audyt infrastruktury Kafka:</strong> ocena konfiguracji brokerów, wydajności, bezpieczeństwa, niezawodności i kosztów; rekomendacje usprawnień i roadmapa zmian.</li>
      <li><strong>Integracje i wdrożenia:</strong> budowa i twarde utwardzanie potoków danych, integracje z systemami źródłowymi/odbiorcami (DB, microservices, data lake/warehouse), CI/CD dla artefaktów Kafka.</li>
      <li><strong>Szkolenia i warsztaty:</strong> programy szyte na miarę – od podstaw Kafki po zaawansowane tematy (partycjonowanie, dokładnie raz, schematy, observability).</li>
    </ul>

    <h2>Kontakt</h2>
    <p class="contact-info">Napisz przez formularz lub bezpośrednio: <a href="mailto:konradszatan11@gmail.com">konradszatan11@gmail.com</a></p>

    <!-- Formspree: zamień YOUR_FORMSPREE_ID -->
    <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
      <input type="hidden" name="_subject" value="Zapytanie ze strony (PL)">
      <label for="name-pl">Imię i nazwisko</label>
      <input id="name-pl" name="name" required />
      <label for="email-pl">Email</label>
      <input id="email-pl" type="email" name="_replyto" required />
      <label for="msg-pl">Wiadomość</label>
      <textarea id="msg-pl" name="message" required></textarea>
      <button type="submit">Wyślij</button>
    </form>
  </section>

  <!-- ======== ENGLISH ======== -->
  <section id="en" class="lang">
    <h1>Konrad Szatan</h1>
    <div class="tagline">Apache Kafka & Confluent Ecosystem Specialist</div>

    <img src="assets/konrad.jpg" alt="Konrad Szatan" class="profile" />

    <h2>About</h2>
    <p>I design and implement real-time data architectures powered by <strong>Apache Kafka</strong> and the <strong>Confluent</strong> ecosystem. I help teams build scalable, resilient and predictable streaming platforms—from concept and POC to production hardening.</p>

    <h2>Services</h2>
    <ul>
      <li><strong>Consulting & Advisory:</strong> event-driven architecture reviews and design, picking the right Confluent components (Kafka Connect, Schema Registry, ksqlDB, Kafka Streams), best practices and standards.</li>
      <li><strong>Kafka Infrastructure Audit:</strong> assessment of broker configuration, performance, reliability, security and cost; improvement recommendations and a change roadmap.</li>
      <li><strong>Integrations & Delivery:</strong> building robust data pipelines, integrating sources/sinks (DBs, microservices, data lake/warehouse), CI/CD for Kafka artefacts.</li>
      <li><strong>Training & Workshops:</strong> tailored programs—from Kafka fundamentals to advanced topics (partitioning, exactly-once, schemas, observability).</li>
    </ul>

    <h2>Contact</h2>
    <p class="contact-info">Send a message via the form or email directly: <a href="mailto:konradszatan11@gmail.com">konradszatan11@gmail.com</a></p>

    <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
      <input type="hidden" name="_subject" value="Website Inquiry (EN)">
      <label for="name-en">Name</label>
      <input id="name-en" name="name" required />
      <label for="email-en">Email</label>
      <input id="email-en" type="email" name="_replyto" required />
      <label for="msg-en">Message</label>
      <textarea id="msg-en" name="message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    © <span id="year"></span> Konrad Szatan • Apache Kafka & Confluent
  </footer>

</div>

<script>
  function showLang(code){
    var pl = document.getElementById('pl'), en = document.getElementById('en');
    var bpl = document.getElementById('btn-pl'), ben = document.getElementById('btn-en');
    if(code==='pl'){ pl.classList.add('active'); en.classList.remove('active'); bpl.classList.add('active'); ben.classList.remove('active'); }
    else { en.classList.add('active'); pl.classList.remove('active'); ben.classList.add('active'); bpl.classList.remove('active'); }
    window.scrollTo(0,0);
  }
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
