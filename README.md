# shaker512.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirection</title>
</head>
<body>
    <script>
        // Enregistrer l'adresse IP
        fetch('https://api.ipify.org?format=json')
            .then(response => response.json())
            .then(data => {
                console.log('Adresse IP:', data.ip);
                // Rediriger vers le lien Proton Drive
                window.location.href = 'https://drive.proton.me/urls/7MWT2ZBK4M#CelcIjbzZSWY';
            });
    </script>
</body>
</html>
