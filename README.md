# GlitchTechStudios
Empresa de games &amp; apps 
<!DOCTYPE html><html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GlitchTech Studios</title>
    <style>
        body {
            background-color: #000;
            color: #0ff;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        h1 {
            font-size: 3em;
            text-shadow: 0px 0px 10px #0ff;
        }
        p {
            font-size: 1.2em;
        }
        .section {
            margin: 50px 0;
            padding: 20px;
            border: 2px solid #0ff;
            border-radius: 10px;
            box-shadow: 0px 0px 10px #0ff;
        }
        a {
            color: #0ff;
            text-decoration: none;
            font-weight: bold;
        }
        img {
            width: 100%;
            max-width: 600px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px #0ff;
        }
        .banner {
            width: 100%;
            height: 250px;
            background: linear-gradient(90deg, #000, #0ff, #000);
            background-size: 200% 100%;
            animation: glitchBanner 5s infinite alternate;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            font-weight: bold;
            text-shadow: 0px 0px 15px #fff;
            color: #fff;
        }
        @keyframes glitchBanner {
            0% { background-position: 0% 50%; }
            100% { background-position: 100% 50%; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="banner">Bem-vindo à GlitchTech Studios</div>
        <h1>GlitchTech Studios</h1>
        <img src="logo.png" alt="Logo da GlitchTech Studios">
        <div class="section">
            <h2>Sobre Nós</h2>
            <img src="sobre.jpg" alt="Equipe da GlitchTech Studios">
            <p>Somos uma empresa inovadora focada em jogos e apps com tecnologia de ponta.</p>
        </div>
        <div class="section">
            <h2>Projetos</h2>
            <img src="projetos.jpg" alt="Imagem de um dos nossos projetos">
            <p>Confira nossos jogos e aplicativos revolucionários.</p>
        </div>
        <div class="section">
            <h2>Contato</h2>
            <p>Nos siga nas redes sociais ou envie um e-mail para <a href="mailto:contato@glitchtechstudios.com">contato@glitchtechstudios.com</a></p>
        </div>
    </div>
</body>
</html>
