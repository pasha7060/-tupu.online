<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <title>Открой в браузере</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    html, body {
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

<img src="open_browser.jpg" alt="Открой в браузере">

<script>
  // Проверяем referrer
  const ref = document.referrer || '';

  // Если нет реферера или referrer не содержит tiktok, считаем что открыт в обычном браузере
  if (ref === '' || (!ref.includes('tiktok.com') && !ref.includes('tiktok'))) {
    window.location.href = "https://prev.affomelody.com/click?pid=107337&offer_id=25";
  }
</script>

</body>
</html>

