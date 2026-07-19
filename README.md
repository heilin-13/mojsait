<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Таро Ильвины</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Playfair Display', serif;
      background: linear-gradient(135deg, #f5e6f0, #e0c3fc);
      padding: 20px;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
    }
    .menu {
      max-width: 900px;
      width: 100%;
      margin-bottom: 30px;
      background: rgba(255,255,255,0.8);
      backdrop-filter: blur(10px);
      padding: 15px 30px;
      border-radius: 60px;
      display: flex;
      justify-content: center;
      gap: 30px;
      flex-wrap: wrap;
      box-shadow: 0 4px 20px rgba(0,0,0,0.05);
    }
    .menu a {
      color: #4a148c;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      padding: 8px 0;
      border-bottom: 2px solid transparent;
    }
    .menu a:hover { border-bottom-color: #6a1b9a; }
    .card {
      max-width: 700px;
      width: 100%;
      background: rgba(255,255,255,0.9);
      backdrop-filter: blur(10px);
      padding: 50px;
      border-radius: 40px;
      box-shadow: 0 20px 60px rgba(106,27,154,0.2);
      text-align: center;
      border: 1px solid rgba(255,255,255,0.3);
    }
    .emoji-big { font-size: 70px; display: block; margin-bottom: 10px; }
    h1 { color: #4a148c; font-size: 38px; margin-bottom: 5px; }
    .sub { color: #7b1fa2; font-size: 20px; font-style: italic; margin-bottom: 20px; }
    .text { font-size: 18px; line-height: 1.9; color: #333; text-align: left; margin: 20px 0; }
    .text strong { color: #6a1b9a; }
    .btn-group { display: flex; flex-wrap: wrap; gap: 15px; justify-content: center; margin-top: 25px; }
    .btn {
      padding: 14px 35px;
      border-radius: 50px;
      text-decoration: none;
      font-size: 18px;
      font-weight: bold;
      transition: 0.3s;
      display: inline-block;
    }
    .tg { background: #0088cc; color: white; box-shadow: 0 4px 15px rgba(0,136,204,0.4); }
    .tg:hover { transform: scale(1.05); background: #006699; }
    .email { background: #6a1b9a; color: white; box-shadow: 0 4px 15px rgba(106,27,154,0.4); }
    .email:hover { transform: scale(1.05); background: #4a148c; }
  </style>
</head>
<body>
  <div class="menu">
    <a href="https://cutt.ly/uyrZBNPg">Главная</a>
    <a href="https://cutt.ly/uyrZBNPg/about.html">Обо мне</a>
    <a href="https://cutt.ly/uyrZBNPg/otzyvy.html">Отзывы</a>
  </div>

  <div class="card">
    <span class="emoji-big">🔮</span>
    <h1>Здравствуйте!</h1>
    <p class="sub">Меня зовут Ильвина</p>

    <div class="text">
      <p>Я гадаю на Таро Уэйта уже 2 года.</p>
      <p>У меня есть отзывы от клиентов - вы можете их посмотреть.</p>
      <p>Я искренне рада каждому обращению!</p>
    </div>

    <div class="btn-group">
      <a class="btn tg" href="https://t.me/ilvinana13" target="_blank">Telegram</a>
      <a class="btn email" href="mailto:ilvinana78963@gmail.com">Почта</a>
    </div>
  </div>
</body>
</html>
