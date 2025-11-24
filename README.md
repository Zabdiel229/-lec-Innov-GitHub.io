<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Élec'Innov -- Solutions électriques</title>
  <meta name="description" content="Élec'Innov -- Installations électriques, panneaux solaires, dépannage 24/7. Devis gratuit." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{--blue:#0b66d0;--dark:#172a3a;--orange:#ff7a1a;--muted:#6b7280;--card:#0f2a44}
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Poppins,system-ui,Segoe UI,Roboto,'Helvetica Neue',Arial}
    body{color:#0b2540;background:#f6f8fb;line-height:1.45}
    .container{max-width:1100px;margin:0 auto;padding:20px}/* Header / Hero */
header{background:linear-gradient(180deg,var(--blue),#176fd6);color:#fff;padding:36px 0;border-radius:8px}
.brand{display:flex;gap:16px;align-items:center}
.logo{width:72px;height:72px;flex:0 0 72px;background:#fff;border-radius:14px;display:flex;align-items:center;justify-content:center}
.logo svg{width:44px;height:44px}
h1{margin:0;font-size:28px;letter-spacing:-0.5px}
p.lead{margin:6px 0 0;opacity:.95}

.grid{display:grid;grid-template-columns:1fr;gap:20px;margin-top:20px}
@media(min-width:880px){.grid{grid-template-columns:1fr 360px}}

.card{background:#fff;padding:20px;border-radius:10px;box-shadow:0 6px 18px rgba(11,34,70,0.08)}

/* Services */
.services h2{margin-top:0}
.services-list{display:grid;gap:12px}
.service{display:flex;gap:12px;align-items:flex-start}
.ico{width:44px;height:44px;border-radius:8px;background:linear-gradient(180deg,var(--blue),#0b57c5);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700}

/* Contact panel */
.contact-panel{display:flex;flex-direction:column;gap:12px}
.big-phone{font-weight:700;font-size:18px;color:var(--dark)}
.btn{display:inline-block;background:var(--orange);color:#fff;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:600}
.whatsapp{background:#25D366}

/* About */
.about{display:grid;grid-template-columns:1fr;gap:18px}
@media(min-width:880px){.about{grid-template-columns:1fr 1fr}}

/* Footer */
footer{margin-top:28px;padding:18px 0;color:var(--muted);font-size:14px}
.footer-flex{display:flex;flex-direction:column;gap:8px}
@media(min-width:800px){.footer-flex{flex-direction:row;justify-content:space-between;align-items:center}}

/* Utilities */
.muted{color:var(--muted)}
a.nolink{color:inherit;text-decoration:none}
.socials{display:flex;gap:10px}
.badge{background:var(--card);color:#fff;padding:8px 12px;border-radius:8px;font-weight:600}

/* Contact form simple */
form label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
form input,form textarea{width:100%;padding:10px;border:1px solid #e6e9ef;border-radius:8px;font-size:14px}
form textarea{min-height:120px}
form .row{display:grid;grid-template-columns:1fr;gap:10px}
@media(min-width:600px){form .row{grid-template-columns:1fr 1fr}}

  </style>
</head>
<body>
  <header>
    <div class="container">
      <div style="display:flex;align-items:center;justify-content:space-between;gap:20px;flex-wrap:wrap">
        <div class="brand">
          <div class="logo" aria-hidden>
            <!-- inline SVG logo -->
            <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" aria-hidden>
              <rect width="24" height="24" rx="6" fill="none" />
              <path d="M12 3.5c-2.5 0-4.5 2-4.5 4.5 0 1.1.4 2.1 1.1 2.9.3.3.4.7.3 1.2-.2 1.3-.8 2.5-1.6 3.5-.3.4-.1.9.3 1.1.4.2.9.1 1.2-.2 1.6-1.3 2.8-2.3 3.5-4 .2-.6.8-1.1 1.5-1.1.9 0 1.6-.7 1.6-1.6 0-2.5-2-4.5-4.5-4.5z" fill="white"/>
              <path d="M10.8 8.5h2.4l-1.2 2.8L10.8 8.5z" fill="#ff7a1a"/>
            </svg>
          </div>
          <div>
            <h1>Élec'Innov</h1>
            <p class="lead">Votre partenaire en solutions électriques innovantes</p>
          </div>
        </div>
        <div style="text-align:right">
          <div class="badge">RCCM: N°RB/PNO/25 A 118360</div>
          <div class="muted" style="margin-top:6px">IFU: 0202324962895</div>
        </div>
      </div>
    </div>
  </header>  <main class="container">
    <section class="grid" aria-label="Services et contact">
      <div>
        <div class="card services">
          <h2>Des installations sûres, modernes et éco‑responsables</h2>
          <div class="services-list">
            <div class="service"><div class="ico">💡</div><div><strong>Éclairage intelligent & domestique</strong><div class="muted">Automatisation & économiseurs d'énergie</div></div></div>
            <div class="service"><div class="ico">🔋</div><div><strong>Panneaux solaires & énergies renouvelables</strong><div class="muted">Étude, installation, maintenance</div></div></div>
            <div class="service"><div class="ico">🔧</div><div><strong>Rénovation électrique</strong><div class="muted">Conforme aux normes NFC 15‑100</div></div></div>
            <div class="service"><div class="ico">⚡</div><div><strong>Dépannage 24h/24</strong><div class="muted">Intervention rapide pour particuliers et entreprises</div></div></div>
          </div>
        </div><div style="height:20px"></div>

    <div class="card about">
      <div>
        <h3>À propos</h3>
        <p class="muted">Élec'Innov propose des solutions complètes pour vos installations électriques, de la conception à la maintenance. Notre équipe est qualifiée pour intervenir en milieu domestique et professionnel.</p>
      </div>
      <div>
        <h3>Nos engagements</h3>
        <ul class="muted">
          <li>Sécurité & conformité</li>
          <li>Matériel de qualité</li>
          <li>Respect des délais</li>
        </ul>
      </div>
    </div>

  </div>

  <aside>
    <div class="card contact-panel">
      <div>
        <div class="muted">Contactez-nous</div>
        <div class="big-phone">☎ 01 51 84 34 83</div>
        <div class="big-phone">☎ 01 65 83 31 77</div>
        <div style="margin-top:8px">✉ <a href="mailto:zabdielhounhouizi63@gmail.com" class="nolink">zabdielhounhouizi63@gmail.com</a></div>
      </div>

      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-top:6px">
        <a class="btn" href="#contact">Demander un devis</a>
        <!-- WhatsApp quick link (Benin number if you use it), keeps common prefix -->
        <a class="btn whatsapp" href="https://wa.me/22992208091" target="_blank">WhatsApp +229 92 20 80 91</a>
      </div>

      <div style="margin-top:12px;font-size:13px;color:var(--muted)">Adresse : Cotonou / Avotrou</div>
    </div>

    <div style="height:14px"></div>

    <div class="card">
      <h4 style="margin:0 0 8px 0">Envoyer un message</h4>
      <form action="#" onsubmit="event.preventDefault();alert('Formulaire de contact simulé -- copiez les infos et contactez par email ou WhatsApp.');">
        <div class="row">
          <div>
            <label for="name">Nom</label>
            <input id="name" placeholder="Votre nom" />
          </div>
          <div>
            <label for="phone">Téléphone</label>
            <input id="phone" placeholder="Téléphone" />
          </div>
        </div>
        <div style="margin-top:10px">
          <label for="msg">Message</label>
          <textarea id="msg" placeholder="Détaillez votre demande"></textarea>
        </div>
        <div style="margin-top:10px;display:flex;gap:8px">
          <button class="btn" type="submit">Envoyer</button>
          <a class="btn" href="mailto:zabdielhounhouizi63@gmail.com">Envoyer par email</a>
        </div>
      </form>
    </div>

  </aside>
</section>

<section style="margin-top:26px" id="projects">
  <div class="card">
    <h3>Projets récents</h3>
    <p class="muted">Installation d'éclairage LED pour une résidence, rénovation complète d'un tableau électrique, installation solaire pour magasin local. (Photos et études disponibles sur demande)</p>
  </div>
</section>

<section id="contact" style="margin-top:22px">
  <div class="card">
    <h3>Contact</h3>
    <div style="display:flex;flex-direction:column;gap:14px">
      <div>
        <strong>Zabdiel HOUNHOU I‑ZI</strong><br>
        Tél : 01 51 84 34 83 / 01 65 83 31 77<br>
        Email : <a href="mailto:zabdielhounhouizi63@gmail.com" class="nolink">zabdielhounhouizi63@gmail.com</a>
      </div>

      <div>
        <strong>RCCM :</strong> N°RB/PNO/25 A 118360<br>
        <strong>IFU :</strong> 0202324962895
      </div>

    </div>
  </div>
</section>

  </main>  <footer>
    <div class="container">
      <div class="footer-flex">
        <div>
          © Élec'Innov -- Tous droits réservés
        </div>
        <div class="muted">Conception visuelle -- pack Élec'Innov • Email : zabdielhounhouizi63@gmail.com</div>
      </div>
    </div>
  </footer></body>
</html> -lec-Innov-GitHub.io
