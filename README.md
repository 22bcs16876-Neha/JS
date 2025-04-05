<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic-Tac-Toe Game</title>
    <link rel="stylesheet" href="tictactoe.css">
    <link rel="stylesheet" href="styles.css">

</head>
<body>
    <header>
        <a href="index.htm" class="logo">TapQuest</a>
        <div class="header-buttons">
            <span id="theme-icon" class="theme-icon">🌞</span>
            <label class="theme-toggle-switch">
                <input type="checkbox" id="theme-toggle">
                <span class="theme-toggle-slider"></span>
            </label>
            <a href="index.htm"><button class="about-btn">Home</button></a>
        </div>
    </header>
    <div class="msg-container hide">
        <p id = "msg">Winner</p>
        <button id = "new-btn">New Game</button>
    </div>
    <h1>Tic Tac Toe </h1>
    <div class="container">
        <div class="game">
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
            <button class = "box"></button>
        </div>
    </div>
    <button id ="reset-btn"> Reset Game</button>
    <footer>
        <div>TapQuest Inc.</div>
        <div>Copyright @2025</div>
    </footer>
    <script src = "ticapp.js"></script>
    <script src="script.js"></script>
    <script src="mode.js"></script>
    
</body>
</html>
