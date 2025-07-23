## HELLO, WORLD 

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Interface</title>
    <style>
      * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    text-align: center;
}

header {
    background-color: #4CAF50;
    padding: 20px;
    color: white;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    border: none;
    background-color: #007BFF;
    color: white;
    border-radius: 5px;
}

button:hover {
    background-color: #0056b3;
}

#message {
    margin-top: 20px;
    font-size: 18px;
    color: #333;
}

    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo à minha interface!</h1>
    </header>
    
    <section class="content">
        <button id="clickButton">Clique Aqui</button>
        <p id="message"></p>
    </section>

    <script>document.getElementById("clickButton").addEventListener("click", function() {
    document.getElementById("message").textContent = "Você clicou no botão!";
});
</script>
</body>
</html>
