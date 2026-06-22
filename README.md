<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ЖК Зеленый мыс — Дом Моцарт</title>
<style>
  :root{
    --bg:#f5f7fb;
    --text:#1f2937;
    --muted:#6b7280;
    --accent:#0b7d35;
    --gold:#d4af37;
    --card:#ffffff;
    --line:#e5e7eb;
  }

  *{box-sizing:border-box}
  html{scroll-behavior:smooth}
  body{
    margin:0;
    font-family:Arial,sans-serif;
    color:var(--text);
    line-height:1.6;
    background:linear-gradient(180deg,#ffffff 0%,#f6f8fb 100%);
  }

  .hero{
    background:linear-gradient(135deg,#111827 0%,#1f2937 55%,#0f172a 100%);
    color:#fff;
    text-align:center;
    padding:84px 20px 72px;
  }

  .hero h1{
    margin:0 0 12px;
    font-size:clamp(28px,4vw,52px);
    line-height:1.1;
  }

  .hero h2{
    margin:0 0 14px;
    font-size:clamp(18px,2.2vw,26px);
    font-weight:400;
    color:#d1d5db;
  }

  .hero p{
    margin:0 0 10px;
    color:#e5e7eb;
    font-size:18px;
  }

  .container{
    max-width:1200px;
    margin:auto;
    padding:36px 20px;
  }

  .section-title{
    margin:0 0 18px;
    font-size:clamp(24px,2.6vw,34px);
    line-height:1.15;
  }

  .lead{
    max-width:900px;
    font-size:18px;
    color:#374151;
  }

  .price{
    font-size:clamp(38px,5vw,58px);
    color:var(--gold);
    font-weight:700;
    margin:18px 0 8px;
  }

  .gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:15px;
  }

  .photo-card{
    overflow:hidden;
    border-radius:16px;
    border:1px solid var(--line);
    background:#fff;
    box-shadow:0 8px 24px rgba(15,23,42,.06);
  }

  .photo-card img{
    display:block;
    width:100%;
    height:240px;
    object-fit:cover;
    background:#e5e7eb;
  }

  .photo-card figcaption{
    padding:12px 14px;
    font-size:14px;
    color:var(--muted);
    border-top:1px solid var(--line);
    background:#fff;
  }

  .grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
  }

  .card{
    background:var(--card);
    padding:24px;
    border-radius:16px;
    border:1px solid var(--line);
    box-shadow:0 8px 24px rgba(15,23,42,.06);
  }

  .card h2{margin-top:0}
  .card ul{
    margin:0;
    padding-left:20px;
  }

  .contact{
    background:#111827;
    color:white;
    text-align:center;
    padding:44px 20px;
  }

  .contact p{
    margin:8px 0;
    color:#e5e7eb;
  }

  .btn{
    display:inline-block;
    padding:12px 24px;
    background:var(--gold);
    color:#111;
    text-decoration:none;
    border-radius:8px;
    font-weight:700;
    transition:transform .2s ease, box-shadow .2s ease;
    box-shadow:0 6px 18px rgba(212,175,55,.25);
  }

  .btn:hover{transform:translateY(-1px)}

  .link{
    color:#93c5fd;
    text-decoration:none;
  }

  .link:hover{text-decoration:underline}

  @media (max-width: 640px){
    .hero{padding:64px 16px 56px}
    .container{padding:28px 16px}
    .card{padding:20px}
    .photo-slot{min-height:140px}
  }
</style>
</head>
<body>

<section class="hero">
  <h1>3-комнатная квартира с видом на море</h1>
  <h2>ЖК «Зеленый мыс» • Дом «Моцарт» • Одесса</h2>
  <p>102 м² • 4 этаж • Автономное отопление</p>
  <div class="price">115 000 $</div>
  <p><a class="btn" href="#contacts">Связаться</a></p>
</section>

<div class="container">
  <h2 class="section-title">Описание</h2>
  <p class="lead">
    Полноценная 3-комнатная квартира площадью 102 м² в доме «Моцарт» жилого комплекса «Зеленый мыс».
    Из гостиной открывается вид на море. Квартира подготовлена для реализации собственного дизайн-проекта.
    Автономное газовое отопление, двухконтурный котел, два санузла.
  </p>
</div>

<div class="container">
  <h2 class="section-title">Фотогалерея</h2>
<div class="gallery">
    <figure class="photo-card">
      <img alt="Гостиная с видом на море" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%231f2937'/><stop offset='55%25' stop-color='%233b82f6'/><stop offset='100%25' stop-color='%23dbeafe'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='70' y='90' width='760' height='410' rx='28' fill='rgba(255,255,255,.16)'/><rect x='120' y='150' width='260' height='190' rx='18' fill='rgba(255,255,255,.24)'/><rect x='410' y='160' width='340' height='120' rx='18' fill='rgba(255,255,255,.28)'/><rect x='410' y='300' width='250' height='90' rx='18' fill='rgba(255,255,255,.22)'/><circle cx='706' cy='185' r='58' fill='rgba(255,255,255,.35)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Гостиная • Вид на море</text></svg>" />
      <figcaption>Гостиная и вид из окна</figcaption>
    </figure>
    <figure class="photo-card">
      <img alt="Кухня и обеденная зона" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%230f172a'/><stop offset='55%25' stop-color='%231a365d'/><stop offset='100%25' stop-color='%23f59e0b'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='80' y='100' width='740' height='400' rx='30' fill='rgba(255,255,255,.14)'/><rect x='120' y='155' width='300' height='110' rx='18' fill='rgba(255,255,255,.24)'/><rect x='120' y='285' width='210' height='150' rx='18' fill='rgba(255,255,255,.20)'/><rect x='360' y='255' width='300' height='55' rx='16' fill='rgba(255,255,255,.28)'/><rect x='360' y='330' width='190' height='95' rx='16' fill='rgba(255,255,255,.22)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Кухня • Обеденная зона</text></svg>" />
      <figcaption>Кухня и обеденная зона</figcaption>
    </figure>
    <figure class="photo-card">
      <img alt="Мастер-спальня" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%231e293b'/><stop offset='55%25' stop-color='%236b7280'/><stop offset='100%25' stop-color='%23e5e7eb'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='90' y='110' width='720' height='390' rx='28' fill='rgba(255,255,255,.18)'/><rect x='155' y='190' width='260' height='120' rx='18' fill='rgba(255,255,255,.25)'/><rect x='430' y='175' width='280' height='160' rx='18' fill='rgba(255,255,255,.20)'/><rect x='430' y='355' width='180' height='70' rx='18' fill='rgba(255,255,255,.24)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Спальня</text></svg>" />
      <figcaption>Основная спальня</figcaption>
    </figure>
    <figure class="photo-card">
      <img alt="Вторая спальня" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%23111827'/><stop offset='55%25' stop-color='%230b7d35'/><stop offset='100%25' stop-color='%23d1fae5'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='85' y='110' width='730' height='380' rx='30' fill='rgba(255,255,255,.14)'/><rect x='145' y='180' width='250' height='130' rx='18' fill='rgba(255,255,255,.24)'/><rect x='430' y='170' width='300' height='100' rx='18' fill='rgba(255,255,255,.22)'/><rect x='430' y='300' width='220' height='120' rx='18' fill='rgba(255,255,255,.20)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Вторая спальня</text></svg>" />
      <figcaption>Вторая спальня</figcaption>
    </figure>
    <figure class="photo-card">
<img alt="Планировка и холл" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%23212529'/><stop offset='55%25' stop-color='%236366f1'/><stop offset='100%25' stop-color='%23c7d2fe'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='105' y='105' width='690' height='390' rx='28' fill='rgba(255,255,255,.15)'/><rect x='150' y='160' width='170' height='260' rx='18' fill='rgba(255,255,255,.20)'/><rect x='340' y='160' width='150' height='170' rx='18' fill='rgba(255,255,255,.28)'/><rect x='510' y='160' width='240' height='120' rx='18' fill='rgba(255,255,255,.22)'/><rect x='510' y='300' width='160' height='120' rx='18' fill='rgba(255,255,255,.24)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Холл • Планировка</text></svg>" />
      <figcaption>Холл и общая планировка</figcaption>
    </figure>
    <figure class="photo-card">
      <img alt="Вид с балкона" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 900 600'><defs><linearGradient id='g' x1='0' y1='0' x2='1' y2='1'><stop offset='0%25' stop-color='%230f172a'/><stop offset='50%25' stop-color='%230ea5e9'/><stop offset='100%25' stop-color='%23f8fafc'/></linearGradient></defs><rect width='900' height='600' fill='url(%23g)'/><rect x='80' y='115' width='740' height='365' rx='30' fill='rgba(255,255,255,.12)'/><circle cx='700' cy='170' r='64' fill='rgba(255,255,255,.35)'/><rect x='120' y='180' width='270' height='95' rx='16' fill='rgba(255,255,255,.22)'/><rect x='120' y='300' width='440' height='60' rx='16' fill='rgba(255,255,255,.20)'/><text x='450' y='520' font-family='Arial,sans-serif' font-size='34' text-anchor='middle' fill='white'>Вид с балкона</text></svg>" />
      <figcaption>Панорамный вид</figcaption>
    </figure>
  </div>
</div>

<div class="container">
  <div class="grid">
    <div class="card">
      <h2>Планировка</h2>
      <ul>
        <li>Гостиная — 28,1 м²</li>
        <li>Спальня — 16,2 м²</li>
        <li>Спальня — 13,8 м²</li>
        <li>Кухня — 13,9 м²</li>
        <li>Холл — 16,7 м²</li>
        <li>Два санузла</li>
        <li>Высота потолков — 3 м</li>
      </ul>
    </div>

    <div class="card">
      <h2>Преимущества</h2>
      <ul>
        <li>Вид на море</li>
        <li>Автономное газовое отопление</li>
        <li>Двухконтурный котел</li>
        <li>Закрытая охраняемая территория</li>
        <li>Дом бизнес-класса</li>
        <li>Возможность перепланировки</li>
        <li>Кухня-гостиная около 42 м²</li>
      </ul>
    </div>
  </div>
</div>

<div class="container">
  <h2 class="section-title">Возможность перепланировки</h2>
  <p class="lead">
    При желании кухню 13,9 м² можно объединить с гостиной 28,1 м² и получить просторную
    кухню-гостиную около 42 м² с видом на море, сохранив две отдельные спальни.
  </p>
</div>

<div class="contact" id="contacts">
  <h2 class="section-title" style="color:#fff;margin-bottom:12px;">Контакты</h2>
  <p><strong>Игорь</strong></p>
  <p>Телефон: <a class="link" href="tel:+380679161176">+380 67 916 11 76</a></p>
  <p>WhatsApp: <a class="link" href="https://wa.me/380959042179" target="_blank" rel="noopener noreferrer">+380 95 904 21 79</a></p>
  <p>Русский • Українська • English • Deutsch</p>
</div>

</body>
</html>
