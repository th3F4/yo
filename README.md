<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carta para mi Novia</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffecb3;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        
        .container {
            text-align: center;
            position: relative;
        }
        
        .letter {
            width: 300px;
            height: auto;
            background-color: #fff;
            border: 2px solid #f57c00;
            position: relative;
            overflow: hidden;
            transform-origin: top;
        }
        
        .page {
            width: 100%;
            background-color: #fff;
            padding: 20px;
            box-sizing: border-box;
        }
        
        h1 {
            color: #f57c00;
        }
        
        p {
            color: #333;
            font-size: 18px;
            margin-bottom: 10px;
        }
        
        #heart {
            font-size: 80px;
            color: #e91e63;
            animation: beat 1s infinite alternate;
        }
        
        @keyframes beat {
            to {
                transform: scale(1.2);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="letter">
            <div class="page">
                <h1>Para Jessica</h1>
                <p>Hola Jessica,</p>
                <p>Quería dedicarte unas palabras especiales en esta pequeña carta.</p>
                <p>Desde que llegaste a mi vida, cada día ha sido más hermoso.</p>
                <p>Eres mi luz en los días oscuros y la alegría en los días buenos.</p>
                <p>No puedo imaginar un futuro sin ti a mi lado.</p>
                <p>Te amo más de lo que las palabras pueden expresar.</p>
                <p>Con todo mi amor,</p>
                <p>Leo</p>
                <p><i class="fas fa-heart" id="heart"></i></p>
            </div>
        </div>
    </div>
</body>
</html>
