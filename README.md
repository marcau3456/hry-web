


[Uploading <!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.HRY.com</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            background: white;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
        }
        .post {
            border-bottom: 1px solid #ddd;
            padding-bottom: 20px;
            margin-bottom: 20px;
        }
        .post h2 {
            color: #333;
        }
        .post p {
            color: #666;
        }
        .login-container {
            text-align: center;
            margin-top: 20px;
        }
        .login-container input {
            padding: 10px;
            margin: 5px;
            width: 80%;
            max-width: 300px;
        }
        .login-container button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
        }
        .login-container button:hover {
            background-color: #555;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #333;
            color: white;
            margin-top: 20px;
        }
    </style>
    <script>
        function login() {
            var username = document.getElementById("username").value;
            var password = document.getElementById("password").value;
            if (username && password) {
                alert("Prihlásenie úspešné! Vitaj, " + username + "!");
            } else {
                alert("Zadajte správne prihlasovacie údaje.");
            }
        }
    </script>
</head>
<body>
    <header>
        <h1>www.HRY.com</h1>
    </header>
    <div class="container">
        <div class="post">
            <h2>10 Zaujímavostí o Hrách</h2>
            <p>Vedeli ste, že prvá komerčná videohra, <strong>Computer Space</strong>, vyšla už v roku 1971? Herný svet sa odvtedy neuveriteľne zmenil!</p>
        </div>
        <div class="post">
            <h2>Najpredávanejšia Hra Všetkých Čias</h2>
            <p><strong>Minecraft</strong> si drží rekord ako najpredávanejšia hra všetkých čias s viac ako 300 miliónmi predaných kópií!</p>
        </div>
        <div class="post">
            <h2>Prvý Esport Turnaj</h2>
            <p>Prvý známy esports turnaj sa odohral v roku 1972 na Stanforde v hre <strong>Spacewar!</strong>. Víťazi získali ročné predplatné časopisu Rolling Stone!</p>
        </div>
        <div class="post">
            <h2>Ktorá Platforma je Najlepšia?</h2>
            <p>Hráči sa často pýtajú, či je lepšie hrať na <strong>PlayStation, Xbox, PC, iOS alebo Android</strong>. Pravda je, že každá platforma má svoje výhody:</p>
            <ul>
                <li><strong>PlayStation</strong> - Skvelé exkluzívne tituly ako God of War a The Last of Us.</li>
                <li><strong>Xbox</strong> - Game Pass ponúka obrovskú knižnicu hier za výhodnú cenu.</li>
                <li><strong>PC</strong> - Najlepší výkon a grafika, možnosť modifikácií.</li>
                <li><strong>iOS & Android</strong> - Skvelé na casual gaming, mobilné verzie obľúbených hier.</li>
            </ul>
        </div>
        <div class="login-container">
            <h2>Prihlásenie</h2>
            <input type="text" id="username" placeholder="Používateľské meno"><br>
            <input type="password" id="password" placeholder="Heslo"><br>
            <button onclick="login()">Prihlásiť sa</button>
        </div>
    </div>
    <footer>
        &copy; 2025 www.HRY.com
    </footer>
</body>
</html>index.html…]()
