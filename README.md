<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat Simples</title>
    <link rel="stylesheet" href="styles.css">
    <!-- Firebase -->
    <script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-firestore.js"></script>
</head>
<body>
    <div class="container">
        <header>
            <h1>Bem-vindo ao Chat Simples</h1>
        </header>
        <main>
            <div id="chat" class="chat-box"></div>
            <div id="message-input" class="message-input">
                <input type="text" id="message" placeholder="Digite sua mensagem">
                <button id="send-button">Enviar</button>
            </div>
        </main>
        <footer>
            <img src="Logo.png" alt="Logo" class="logo">
        </footer>
    </div>
    <script src="app.js"></script>
</body>
</html>
