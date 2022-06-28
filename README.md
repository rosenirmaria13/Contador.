# Contador.
Contador com JavaScript, HTML5 e CSS3

Link do Projeto: 


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTADOR</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
    <main>
        <h1 id="contador">0</h1> 
        <button onclick="incrementar()">+</button>
        <button onclick="decrementar()">-</button>
        <button onclick="zerar()">zerar</button>
    </main>
    <script>
        let contador = document.getElementById("contador");
        function incrementar() {
            contador.innerHTML = parseInt(contador.innerText) + 1;
        }
        function decrementar() {
            contador.innerHTML = parseInt(contador.innerText) - 1;
        }     
        function zerar() {
            contador.innerHTML = "0"
        }  
    </script>
</body>
</html>
