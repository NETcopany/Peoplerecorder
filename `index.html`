<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PeopleRecorder</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
            background-color: #f0f0f0;
        }
        h1 {
            font-size: 48px;
            color: #333;
            margin-bottom: 30px;
        }
        textarea {
            width: 300px;
            height: 100px;
            font-size: 16px;
            padding: 10px;
            border: 2px solid #ccc;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        #square {
            width: 400px; /* Aumentado de 200px para 400px */
            height: 400px; /* Aumentado de 200px para 400px */
            background-color: white;
            border: 2px solid #000;
            margin: 20px auto;
            display: none; /* Oculto inicialmente */
        }
    </style>
</head>
<body>
    <h1>PeopleRecorder</h1>
    <p>The watcher will observe</p>
    <textarea id="inputText" placeholder="Digite aqui..."></textarea>
    <div id="square"></div>
    
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const inputText = document.getElementById('inputText');
            const square = document.getElementById('square');
            
            inputText.addEventListener('keydown', function(event) {
                if (event.key === 'Enter') {
                    square.style.display = 'block'; // Mostra o quadrado ao pressionar Enter
                }
            });
        });
    </script>
</body>
</html>
