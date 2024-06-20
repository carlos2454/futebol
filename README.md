<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Futebol</title>
    <style>
        /* Reset básico e estilos globais */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5em;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            margin: 20px 0;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        section p {
            font-size: 1.1em;
            line-height: 1.8;
        }

        section img {
            max-width: 100%;
            height: auto;
            display: block;
            margin-top: 10px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }

        .noticia, .time {
            margin-bottom: 20px;
        }

        .noticia h3, .time h3 {
            font-size: 1.5em;
            margin-bottom: 5px;
        }

        form {
            margin-top: 20px;
        }

        form label {
            display: block;
            font-size: 1.2em;
            margin-bottom: 5px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
        }

        form button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            border-radius: 4px;
            font-size: 1.1em;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        form button:hover {
            background-color: #555;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        footer p {
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Bem-vindo ao Site de Futebol</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#noticias">Notícias</a></li>
                    <li><a href="#times">Times</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home">
        <div class="container">
            <h2>Home</h2>
            <p>Bem-vindo ao melhor site de futebol, onde você encontra as últimas notícias e informações sobre os times.</p>
            <img src="img/home.jpg" alt="Imagem de futebol">
        </div>
    </section>

    <section id="noticias">
        <div class="container">
            <h2>Notícias</h2>
            <div class="noticia">
                <h3>Notícia 1</h3>
                <p>Detalhes da notícia 1...</p>
                <img src="img/noticia1.jpg" alt="Imagem da notícia 1">
            </div>
            <div class="noticia">
                <h3>Notícia 2</h3>
                <p>Detalhes da notícia 2...</p>
                <img src="img/noticia2.jpg" alt="Imagem da notícia 2">
            </div>
        </div>
    </section>

    <section id="times">
        <div class="container">
            <h2>Times</h2>
            <div class="time">
                <h3>Time 1</h3>
                <p>Detalhes do time 1...</p>
                <img src="img/time1.jpg" alt="Imagem do time 1">
            </div>
            <div class="time">
                <h3>Time 2</h3>
                <p>Detalhes do time 2...</p>
                <img src="img/time2.jpg" alt="Imagem do time 2">
            </div>
        </div>
    </section>

    <section id="contato">
        <div class="container">
            <h2>Contato</h2>
            <form id="carlospossent@gmail.com">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Site de Futebol. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
