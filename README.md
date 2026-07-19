<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Таро Ильвины</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Inter', sans-serif;
      background: #0a0a0a;
      color: #fff;
    }
    .menu {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(10, 10, 10, 0.8);
      backdrop-filter: blur(10px);
      z-index: 100;
    }
    .logo { font-size: 24px; font-weight: 700; color: #fff; }
    .nav-links a {
      color: #fff;
      text-decoration: none;
      margin-left: 30px;
      font-size: 16px;
      font-weight: 500;
      transition: color 0.2s;
    }
    .nav-links a:hover { color: #a855f7; }
    .hero {
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
      padding: 20px;
    }
    .hero-content { max-width: 800px; }
    .hero-content h1 {
      font-family: 'Playfair Display', serif;
      font-size: 72px;
      font-weight: 700;
      margin-bottom: 20px;
      background: linear-gradient(to right, #a855f7, #d946ef);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    .hero-content p {
      font-size: 20px;
      line-height: 1.6;
      color: #cbd5e1;
      margin-bottom: 40px;
    }
    .btn-group {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .btn {
      padding: 16px 40px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      font-size: 18px;
      transition: all 0.3s;
    }
    .btn-primary {
      background: #a855f7;
      color: #fff;
      box-shadow: 0 4px 15px rgba(168, 85, 247, 0.4);
    }
    .btn-primary:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 30px rgba(168, 85, 247, 0.5);
    }
    .btn-secondary {
      background: transparent;
      color: #fff;
      border: 2px solid rgba(255,255,255,0.3);
    }
    .btn-secondary:hover {
      border-color: #a855f7;
      background: rgba(168, 85, 247, 0.1);
    }
    .cards-section {
      max-width: 1200px;
      margin: 80px auto;
      padding: 0 20px;
    }
    .cards-section h2 {
      font-size: 36px;
      text-align: center;
      margin-bottom: 50px;
      color: #fff;
    }
    .cards-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }
    .card {
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 30px;
      border: 1px solid rgba(255,255,255,0.08);
      transition: 0.3s;
      text-align: left;
    }
    .card:hover {
      transform: translateY(-10px);
      border-color: #a855f7;
    }
    .card h3 {
      font-size: 24px;
      margin-bottom: 15px;
      color: #a855f7;
    }
    .card p {
      color: #cbd5e1;
      line-height: 1.6;
    }
    .footer {
      text-align: center;
      padding: 40px 20px;
      border-top: 1px solid rgba(255,255,255,0.05);
      color: #64748b;
    }
    @media (max-width: 768px) {
      .menu { padding: 15px 20px; }
      .nav-links a { margin-left: 15px; font-size: 14px; }
      .hero-content h1 { font-size: 42px; }
      .hero-content p { font-size: 18px; }
    }
  </style>
</head>
<body>

  <div class="menu">
    <div class="logo">✦ Ильвина</div>
    <div class="nav-links">
      <a href="https://cutt.ly/uyrZBNPg">Главная</a>
      <a href="https://cutt.ly/uyrZBNPg/about.html">Обо мне</a>
      <a href="https://cutt.ly/uyrZBNPg/otzyvy.html">Отзывы</a>
    </div>
  </div>

  <section class="hero">
    <div class="hero-content">
      <h1>Таро Уэйта</h1>
      <p>Гадаю уже 2 года. Помогаю найти ответы на важные вопросы через мудрость карт.</p>
      <div class="btn-group">
        <a href="https://t.me/ilvinana13" class="btn btn-primary">Написать в Telegram</a>
        <a href="https://cutt.ly/uyrZBNPg/about.html" class="btn btn-secondary">Узнать больше</a>
      </div>
    </div>
  </section>

  <!-- Только расклады, без обучения -->
  <section class="cards-section">
    <h2>Мои расклады</h2>
    <div class="cards-grid">
      <div class="card">
        <h3>🔮 На отношения</h3>
        <p>Разбор текущей ситуации в паре, чувств партнёра и перспектив развития отношений.</p>
      </div>
      <div class="card">
        <h3>На карьеру</h3>
        <p>Помогаю понять, в каком направлении двигаться, какие возможности ждут и как преодолеть препятствия.</p>
      </div>
      <div class="card">
        <h3>Личностный рост</h3>
        <p>Расклады на самопознание, поиск внутренних ресурсов и ответов на сложные жизненные вопросы.</p>
      </div>
      <div class="card">
        <h3>❓ Вопрос-ответ</h3>
        <p>Быстрый расклад на один конкретный вопрос — чёткий ответ без воды.</p>
      </div>
    </div>
  </section>

  <div class="footer">
    <p>© 2026 Ильвина. Сделано с душой.</p>
  </div>

</body>
</html>
