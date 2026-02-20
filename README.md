<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no, viewport-fit=cover">
    
    <!-- This makes it run as a standalone app without Safari bars -->
    <meta name="apple-mobile-web-app-capable" content="yes">
    
    <!-- Changes the status bar color (default, black, or black-translucent) -->
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
    
    <!-- The name shown under the home screen icon -->
    <meta name="apple-mobile-web-app-title" content="MyLocalApp">
    
    <!-- The icon (Place a 180x180px PNG in the same folder) -->
    <link rel="apple-touch-icon" href="icon.png">

    <title>My Web App</title>
    <style>
        body { font-family: sans-serif; padding: env(safe-area-inset-top) 20px; }
        .card { background: #f0f0f0; padding: 20px; border-radius: 15px; }
    </style>
</head>
<body>
    <div class="card">
        <h1>Local Web App</h1>
        <p>This is running locally on your iPhone.</p>
    </div>
</body>
</html>
