<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benvenuto!</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Benvenuto alla nostra rete WiFi!</h1>
    <p>Per favore, segui la nostra pagina Instagram per accedere a Internet:</p>
    <a id="follow-link" href="https://www.instagram.com/alsoleresort_/" target="_blank">
        <button onclick="grantAccess()">Segui su Instagram</button>
    </a>
    <script>
        function grantAccess() {
            setTimeout(function() {
                window.location.href = "http://www.google.com";
            }, 3000); // tempo di attesa dopo il clic
        }
    </script>
    <p>Dopo aver seguito la pagina, attendi qualche secondo per l'accesso.</p>
</body>
</html>
