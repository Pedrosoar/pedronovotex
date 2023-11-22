<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lugares Turísticos da Europa</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }

        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .destination-card {
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px 0;
            overflow: hidden;
        }

        .destination-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .destination-info {
            padding: 15px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Lugares Turísticos da Europa</h1>
    </header>

    <section>
        <div class="destination-card">
            <img src="paris.jpg" alt="Torre Eiffel, Paris">
            <div class="destination-info">
                <h2>Paris, França</h2>
                <p>Descubra a beleza da Cidade Luz, com seus monumentos icônicos e charme inigualável.</p>
                <a href="paris.html">Saiba mais</a>
            </div>
        </div>

        <div class="destination-card">
            <img src="rome.jpg" alt="Coliseu, Roma">
            <div class="destination-info">
                <h2>Roma, Itália</h2>
                <p>Explore a história e a cultura da capital italiana, com seus monumentos históricos e culinária incrível.</p>
                <a href="rome.html">Saiba mais</a>
            </div>
        </div>

        <div class="destination-card">
            <img src="santorini.jpg" alt="Vista de Santorini, Grécia">
            <div class="destination-info">
                <h2>Santorini, Grécia</h2>
                <p>Relaxe nas deslumbrantes praias e admire as vistas espetaculares dessa ilha grega pitoresca.</p>
                <a href="santorini.html">Saiba mais</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Lugares Turísticos da Europa. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
