# My-mini-app
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Mini App</title>
  <!-- Load Telegram Web Apps API -->
  <script src="https://telegram.org/js/telegram-webapp.js"></script>
  <script>
    function onLoad() {
      if (window.Telegram && window.Telegram.WebApp) {
        // Notify Telegram that your mini app is ready
        Telegram.WebApp.ready();
        console.log("Telegram WebApp initialized");
      }
    }
  </script>
</head>
<body onload="onLoad()">
  <h1>Welcome to My Mini App!</h1>
  <p>This mini app is integrated with Telegram.</p>
</body>
</html>
