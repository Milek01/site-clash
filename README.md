<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Educação no Campo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #c3dcdf;
            color: #191f04;
        }
        header {
            background-color: #2c9fa3f;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #4e5861;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #4e5861;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .section-title {
            font-size: 2em;
            margin-bottom: 10px;
            color: #4e5861;
        }
        .content {
            margin-bottom: 20px;
        }
        footer {
            background-color: #4e5861;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .form-container {
            background-color: #4e5861;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-top: 20px;
        }
        .form-container input, .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #4e5861;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Educação no Campo</h1>
        <p>Promovendo o acesso à educação de qualidade para as comunidades rurais</p>
    </header>

    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#programas">Programas Educacionais</a>
        <a href="#beneficios">Benefícios</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <section id="sobre">
            <h2 class="section-title">Sobre a Educação no Campo</h2>
            <p class="content">
                A educação do campo busca garantir o direito à educação para as pessoas que vivem em áreas rurais, considerando suas especificidades culturais, sociais e econômicas. Seu foco está em oferecer um currículo contextualizado que valorize o saber local, como práticas agrícolas e culturais tradicionais, além de abordar questões como sustentabilidade e identidade regional. A educação do campo também enfrenta desafios como a falta de infraestrutura escolar, dificuldades de acesso e escassez de professores qualificados. Ela visa não só a formação acadêmica, mas também a inclusão de saberes locais e a preparação dos jovens para o mercado de trabalho, com ênfase em cursos profissionalizantes. Movimentos sociais e políticas públicas, como o Pronera, têm trabalhado para superar as desigualdades educacionais nas zonas rurais.
            </p>
        </section>

        <section id="programas">
            <h2 class="section-title">Programas Educacionais</h2>
            <p class="content">
               Programas educacionais são iniciativas voltadas para melhorar a qualidade e o acesso à educação. Eles incluem ações como bolsas de estudo (ex: Prouni), programas de alfabetização (ex: Brasil Alfabetizado), formação de professores, educação inclusiva para alunos com deficiência e educação profissionalizante (ex: PRONATEC). O objetivo desses programas é reduzir desigualdades educacionais, garantir o direito à educação e preparar os estudantes para o mercado de trabalho, promovendo o desenvolvimento social e econômico, como:
            </p>
            <ul class="content">
                <li>Educação do Campo no Ensino Fundamental e Médio</li>
                <li>Formação de Educadores Rurais</li>
                <li>Projetos de Inclusão Digital e Capacitação Profissional</li>
                <li>Educação Ambiental e Sustentabilidade</li>
            </ul>
        </section>

        <section id="beneficios">
            <h2 class="section-title">Benefícios da Educação no Campo</h2>
            <p class="content">
                A educação no campo traz diversos benefícios tanto para os indivíduos quanto para as comunidades, tais como:
            </p>
            <ul class="content">
                <li>Promoção da igualdade de oportunidades para jovens e adultos rurais</li>
                <li>Fortalecimento das economias locais</li>
                <li>Desenvolvimento de habilidades essenciais para a agricultura sustentável</li>
                <li>Redução da migração para as grandes cidades</li>
            </ul>
        </section>

        <section id="contato">
            <h2 class="section-title">Entre em Contato</h2>
            <div class="form-container">
                <p class="content">Se você deseja saber mais sobre nossos programas ou colaborar de alguma forma, entre em contato conosco:</p>
                <form>
                    <input type="text" id="nome" name="nome" placeholder="Seu Nome" required>
                    <input type="email" id="email" name="email" placeholder="Seu Email" required>
                    <textarea id="mensagem" name="mensagem" placeholder="Sua Mensagem" rows="5" required></textarea>
                    <button type="submit">Enviar</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2025 Educação no Campo. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

