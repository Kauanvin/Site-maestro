<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Maestro Luca</title>
    <style>
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #111;
            color: white;
        }
        header {
            background: rgba(0, 0, 0, 0.8);
            padding: 20px 40px;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 10;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.1em;
        }
        .hero {
            background: url('luca-foto.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding-top: 80px;
        }
        .hero h1 {
            font-size: 4em;
            margin: 0;
        }
        section {
            padding: 100px 40px;
        }
        h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li::before {
            content: "♪ ";
            color: #1e90ff;
        }
        a {
            color: #1e90ff;
        }
    </style>
</head>
<body>
    <header>
        <div><strong>Luca</strong></div>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#obras">Obras</a>
            <a href="#midia">Mídia</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Maestro Luca</h1>
    </div>

    <section id="sobre">
        <h2>Sobre</h2>
        <p>Este é o release do maestro fictício Luca. Ele é um maestro de carreira internacional, com destaque por reger repertórios sinfônicos e operísticos.</p>
    </section>

    <section id="obras">
        <h2>Obras Regidas</h2>
        <ul>
            <li>Beethoven - Sinfonia nº 5</li>
            <li>Mahler - Sinfonia nº 2</li>
            <li>Stravinsky - A Sagração da Primavera</li>
        </ul>
    </section>

    <section id="midia">
        <h2>Mídia</h2>
        <p><a href="https://www.youtube.com">YouTube</a> | <a href="https://www.estadao.com.br">Estadão</a></p>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Email: maestro.luca@email.com</p>
        <p>Instagram: @maestroluca</p>
    </section>
</body>
</html>
