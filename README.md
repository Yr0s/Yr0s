<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html> <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simulador de Aplicativo de Segurança</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2e;
            color: #e0e0ff;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            background-color: #2a2a40;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            margin: 0;
            color: #9c88ff;
        }

        nav {
            margin-top: 20px;
            width: 100%;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #9c88ff;
            text-decoration: none;
            margin: 0 15px;
            padding: 10px 20px;
            border-radius: 25px;
            background-color: #2f2f4f;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #9c88ff;
            color: #1e1e2e;
        }

        section {
            margin-top: 30px;
            width: 90%;
            max-width: 1200px;
            display: none;
        }

        .active {
            display: block;
        }

        footer {
            margin-top: auto;
            width: 100%;
            padding: 20px;
            background-color: #2a2a40;
            text-align: center;
            color: #9c88ff;
        }
    </style>
</head>
<body>

    <header>
        <h1>Simulador de Segurança</h1>
    </header>

    <nav>
        <a href="#procurar" onclick="showSection('procurar')">Procurar Equipamentos</a>
        <a href="#servicos" onclick="showSection('servicos')">Área de Serviço</a>
        <a href="#chat" onclick="showSection('chat')">Chat</a>
        <a href="#perfil" onclick="showSection('perfil')">Perfil</a>
    </nav>

    <section id="procurar" class="active">
        <h2>Procurar Equipamentos</h2>
        <p>Aqui você pode procurar por equipamentos de segurança para comprar.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="servicos">
        <h2>Área de Serviço</h2>
        <p>Aqui você pode encontrar trabalhadores da área de segurança.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="chat">
        <h2>Chat</h2>
        <p>Aqui você pode conversar com os trabalhadores disponíveis.</p>
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <section id="perfil">
        <h2>Perfil</h2>
        <p>Aqui você pode visualizar suas compras e informações pessoais.</p> 
        <!-- Conteúdo adicional pode ser adicionado aqui -->
    </section>

    <footer>
        <p>&copy; 2024 Simulador de Segurança. Todos os direitos reservados.</p>
    </footer>

    <script>
        function showSection(sectionId) {
            const sections = document.querySelectorAll('section');
            sections.forEach(section => {
                section.classList.remove('active');
            });

            const selectedSection = document.getElementById(sectionId);
            selectedSection.classList.add('active');
        }
    </script>

</body>
</html> 

<!---
Yr0s/Yr0s is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
