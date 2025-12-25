<html lang="ru">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Аня — Джун-тестировщик | Портфолио</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
  :root{
    --bg:#f7f5f2;          /* тёплый светлый беж */
    --card:#ffffff;
    --muted:#8c8c87;       /* мягкий серо‑оливковый */
    --accent:#9aa88f;      /* спокойный оливковый */
    --accent-light:#dfe4db;
    --radius:14px;
    --maxw:900px;
    color-scheme: light;
  }

  *{box-sizing:border-box}
  body{
    font-family:Inter,system-ui,Segoe UI,Roboto,Arial;
    margin:0;
    background:linear-gradient(180deg,var(--bg) 0%, #f2f0ec 100%);
    color:#2a2a28;
  }

  .wrap{max-width:var(--maxw); margin:36px auto; padding:28px;}
  .card{
    background:var(--card);
    border-radius:var(--radius);
    padding:28px;
    box-shadow:0 8px 30px rgba(40,40,40,0.06);
    display:grid;
    grid-template-columns: 1fr 320px;
    gap:24px;
    align-items:start;
  }

  header{display:flex; gap:16px; align-items:center}
  .avatar{
    width:84px; height:84px;
    border-radius:12px;
    background:linear-gradient(135deg,var(--accent),var(--accent-light));
    display:flex; align-items:center; justify-content:center;
    color:white; font-weight:700; font-size:28px;
  }

  h1{font-size:20px; margin:0; color:#7365a3;}
  p.lead{margin:6px 0 0; color:var(--muted)}

  .role{
    margin-top:10px;
    padding:8px 12px;
    background:var(--accent-light);
    border-radius:10px;
    display:inline-block;
    font-weight:600;
    color:#4e584b;
  }

  .contacts{display:flex; flex-direction:column; gap:10px}
  .contact a{
    display:inline-flex; align-items:center; gap:10px;
    padding:10px 12px;
    border-radius:10px;
    text-decoration:none; color:#2e2e2e;
    background:#fafafa;
    /* УБРАНА ГРАНИЦА: border:1px solid #ececec; */
  }
  .contact a small{color:var(--muted);}

  .section{margin-top:18px}
  .section h2{font-size:14px; margin:0 0 10px; text-transform:uppercase; letter-spacing:0.08em; color:#a6a1b8;}

  .bio{line-height:1.5}

  .experience{display:flex; flex-direction:column; gap:12px}
  .job{
    padding:12px;
    border-radius:10px;
    background:#fafafa;
    /* УБРАНА ГРАНИЦА: border:1px solid #e9e9e9; */
  }
  .job .title{font-weight:600; color:#3b3b38}
  .job .meta{font-size:13px; color:var(--muted)}

  .skills{display:flex; flex-wrap:wrap; gap:8px}
  .tag{
    padding:8px 10px;
    background:#ffffff;
    border-radius:999px;
    /* УБРАНА ГРАНИЦА: border:1px solid #ebeae7; */
    font-size:13px;
    color:#474742;
  }

  .right{padding:12px}
  .card-aside{position:sticky; top:28px}

  footer{
    margin-top:16px;
    text-align:center;
    color:var(--muted);
    font-size:13px;
  }

  @media (max-width:880px){
    .card{grid-template-columns:1fr;}
    .right{order:2}
  }

  /* Новые стили для основного контента */
  .main-content {
    max-width: 900px;
    margin: 0 auto;
    padding: 0;
  }
  
  .content-card {
    background: var(--card);
    border-radius: var(--radius);
    padding: 32px;
    box-shadow: 0 8px 30px rgba(40,40,40,0.06);
    /* УБРАНА ГРАНИЦА: border: 1px solid #f0f0f0; */
  }
  
  .profile-photo{
    width:170px;
    height:170px;
    object-fit:cover;
    border-radius:14px;
    /* УБРАНА ГРАНИЦА: border:3px solid var(--accent-light); */
    box-shadow:0 4px 16px rgba(0,0,0,0.08);
    margin-bottom:12px;
  }
  
  #about, #skills, #contacts {
    /* УБРАНЫ ГРАНИЦЫ ВОКРУГ СЕКЦИЙ */
  }
  
  h1.text-4xl {
    font-size: 28px;
    font-weight: 700;
    color: #2a2a28;
    margin: 0 0 16px 0;
  }
  
  h2.text-2xl {
    font-size: 18px;
    font-weight: 600;
    color: #7365a3;
    margin: 0 0 12px 0;
    text-transform: uppercase;
    letter-spacing: 0.05em;
  }
  
  ul.list-disc {
    padding-left: 20px;
    margin: 0;
  }
  
  ul.list-disc li {
    margin-bottom: 6px;
  }
  
  .space-y-12 > * + * {
    margin-top: 24px;
  }
  
  .space-y-4 > * + * {
    margin-top: 12px;
  }
  
  .space-y-3 > * + * {
    margin-top: 10px;
  }
  
  .space-y-2 > * + * {
    margin-top: 8px;
  }
  
  .leading-relaxed {
    line-height: 1.6;
  }
  
  .text-lg {
    font-size: 16px;
  }
  
  .text-gray-700 {
    color: #4a4a46;
  }
  </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">
  <div class="wrap">
    <div class="card" role="region" aria-label="Сайт-визитка Ани">
      <main class="main-content">
        <div class="content-card">
          <section id="about">
            <img src="me.jpg" alt="Фото Ани" class="profile-photo">
            <h1>Привет! Я Аня, 27</h1>
            <p class="text-gray-700 leading-relaxed text-lg">
              Джун-тестировщик в поиске классной позиции. Раньше 6+ лет работала автором и аналитиком контента — поэтому у меня очень развита логика, внимание к деталям и умение находить несостыковки. Люблю тщательно проверять ошибки, чтобы всё работало так, как должно.
            </p>
            <p class="text-gray-700 leading-relaxed text-lg">
              Учусь тестированию, делаю тест-планы, чек-листы и тест-кейсы, оформляю баг-репорты. Хочу расти в классной продуктовой команде.
            </p>
          </section>

          <section id="skills">
            <h2>Навыки</h2>
            <ul class="list-disc text-gray-700 text-lg">
              <li>Тест-дизайн: чек-листы, тест-кейсы</li>
              <li>Оформление баг-репортов</li>
              <li>Postman, Charles, Devtools, MongoDB, MYSQL, Test-it, Jira, Figma</li>
              <li>Работа с документацией (и без тоже ок!)</li>
              <li>HTML, CSS </li>
              <li>Английский C1</li>
            </ul>
          </section>

          <section id="contacts">
            <h2>Контакты</h2>
            <ul class="text-gray-700 text-lg">
              <li>📍 Москва</li>
              <li>📧 braveblackbirdy@gmail.com</li>
              <li>🔗 Telegram: @braveblackbirdy</li>
            </ul>
          </section>
        </div>
      </main>

      <aside class="right">
        <div class="card-aside">
          <div class="contacts">
            <div style="display:flex;gap:10px;align-items:center;justify-content:space-between">
              <div>
                <strong>Аня, 27</strong>
                <div style="color:var(--muted);font-size:13px">Москва (готова к переезду)</div>
              </div>
              <div style="text-align:right; font-size:12px; color:var(--muted)">Джун</div>
            </div>

            <div class="contact">
              <a href="mailto:braveblackbirdy@gmail.com" aria-label="Email"><span>📧 braveblackbirdy@gmail.com</span></a>
              <a href="tel:+79267960720" aria-label="Телефон"><span>📱 +7 (926) 796-07-20</span></a>
              <a href="https://t.me/braveblackbirdy" target="_blank" rel="noopener noreferrer" aria-label="Telegram">🔗 Telegram</a>
            </div>

          </div>

          <div class="section" style="margin-top:16px">
            <h2>Навыки и инструменты</h2>
            <div class="skills" role="list">
              <div class="tag">Postman</div>
              <div class="tag">Devtools</div>
              <div class="tag">SoapUI</div>
              <div class="tag">Metabase</div>
              <div class="tag">Charles</div>
              <div class="tag">Kibana</div>
              <div class="tag">Grafana</div>
              <div class="tag">Yandex.Tracker</div>
              <div class="tag">Jira</div>
              <div class="tag">Составление тест‑кейсов</div>
              <div class="tag">Баг‑репорты</div>
              <div class="tag">Русский / English / Farsi / Turkish</div>
            </div>
          </div>

          <div class="section" style="margin-top:16px">
            <h2>Когда-то</h2>
            <ul>
              <li>Съездила на стажировку в Иран</li>
              <li>Создала контент для курсов, которые прошли ~70 000 человек (#Sekta).</li>
              <li>Собрала онлайн‑сообщество из 800+ психологов для коворкинга.</li>
            </ul>
          </div>

        </div>
      </aside>
    </div>

    <footer>
      <div>© Аня — джун‑тестировщик • Готова к собеседованиям и тестовым заданиям.</div>
    </footer>
  </div>
</body>
</html>
