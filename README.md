# Shrutika-
This is first project
<!DOCTYPE html>
<html>
<head>
    <title>DarkWeb Lab</title>

    <style>
        body {
            background-color: #080808;
            color: #00ff88;
            font-family: Arial;
            text-align: center;
            margin: 0;
        }

        header {
            background-color: #111;
            padding: 20px;
            border-bottom: 1px solid #00ff88;
        }

        h1 {
            color: #00ff88;
        }

        .box {
            background-color: #111;
            width: 80%;
            margin: 30px auto;
            padding: 20px;
            border: 1px solid #333;
            border-radius: 10px;
        }

        button {
            background-color: #00ff88;
            color: #000;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #00cc70;
        }

        footer {
            margin-top: 50px;
            color: gray;
        }
    </style>
</head>

<body>

    <header>
        <h1>🌐 DARKWEB LAB</h1>
        <p>Educational Cyber Security Dashboard</p>
    </header>

    <div class="box">
        <h2>System Status</h2>
        <p>🟢 System Online</p>
        <p>🔒 Security: Protected</p>

        <button onclick="showMessage()">
            Check Network
        </button>

        <p id="message"></p>
    </div>

    <footer>
        <p>© 2026 DarkWeb Lab | Educational Project</p>
    </footer>

    <script>
        function showMessage() {
            document.getElementById("message").innerHTML =
                "Network scan simulation completed.";
        }
    </script>

</body>
</html>
