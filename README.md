# My-mini-app
<!DOCTYPE html>
<html>
<head>
    <title>My Mini App</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Optionally, include a stylesheet here -->
</head>
<body>
    <h1>Welcome to My Mini App!</h1>
    <p>This page is loaded inside Telegram.</p>
    
    <!-- Telegram Web App initialization -->
    <script>
        // Check if the Telegram Web App object is available
        if (window.Telegram && Telegram.WebApp) {
            Telegram.WebApp.ready();
            // You can also access parameters sent by Telegram if needed:
            console.log('Web App initialized', Telegram.WebApp.initData);
        }
    </script>
</body>
</html>
