<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <title>Вход</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    img {
      max-width: 100%;
      max-height: 100%;
      display: block;
    }
  </style>
</head>
<body>

<img src="open_browser.jpg" alt="Открой в браузере" />

<script>
  // Проверяем реферер
  const ref = document.referrer || '';
  
  // Если нет реферера (или не TikTok), считаем что открыт в браузере
  if (!ref.includes('tiktok.com')) {
    // Делаем редирект
    window.location.href = "https://prev.affomelody.com/click?pid=107337&offer_id=25";
  }
</script>

</body>
</html>

