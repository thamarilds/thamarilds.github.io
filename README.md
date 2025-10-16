<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Bem-vindos ao meu site - teste1">
    <meta name="keywords" content="site, profissional, apresentação, serviços">
    <title>Meu Primeiro Sitinho - Página Inicial </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #610C04;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, #E3242B 0%, #541E1B 100%);
            color: white;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        nav {
            background-color: #fff;
            padding: 1rem 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        nav li {
            margin: 0 1rem;
        }

        nav a {
            text-decoration: none;
            color: #333;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #E6DBAC;
            color: white;
        }

        main {
            background-color: white;
            margin: 2rem 0;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .section {
            margin-bottom: 2rem;
        }

        .section h2 {
            color: #667eea;
            margin-bottom: 1rem;
            border-bottom: 2px solid #E6DBAC;
            padding-bottom: 0.5rem;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .card {
            background: light green;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            border-left: 4px solid#E6DBAC;
        }

        .card h3 {
            color: #333;
            margin-bottom: 1rem;
        }

        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
            transition: transform 0.3s;
        }

        .btn:hover {
            transform: translateY(-2px);
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
        }

        .contact-info {
            background-color: #f8f9fa;
            padding: 1.5rem;
            border-radius: 8px;
            margin-top: 1rem;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav li {
                margin: 0.25rem 0;
            }

            main {
                margin: 1rem 0;
                padding: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Bem-vindo ao Meu Site</h1>
            <p>Sua presença digital profissional</p>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#portfolio">Portfólio</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section id="home" class="section">
            <h2>Página Inicial</h2>
            <p>Ei! Este é o seu novo site hospedado gratuitamente.</p>
            <p>Este site foi criado usando HTML e CSS puros, com hospedagem no Github Pages e tentando fazer com o Vercel tb.</p>
        </section>

        <section id="sobre" class="section">
            <h2>Sobre</h2>
            <p> João menino</p>

            <div class="cards">
                <div class="card">
                    <h3>🎯 Missão</h3>
                    <p>Money money money money</p>
                </div>
                <div class="card">
                    <h3>👁️ Visão</h3>
                    <p>Brinks é servir ao capitalismo </p>
                </div>
                <div class="card">
                    <h3>⭐ Valores</h3>
                    <p>Liste os valores que guiam seu trabalho e relacionamentos.</p>
                </div>
            </div>
        </section>

        <section id="servicos" class="section">
            <h2>Serviços</h2>
            <p>Aqui você pode listar os serviços que oferece, produtos que vende ou áreas de especialização.</p>

            <div class="cards">
                <div class="card">
                    <h3>Serviço 1</h3>
                    <p>Descrição detalhada do primeiro serviço oferecido.</p>
                    <a href="#" class="btn">Saiba Mais</a>
                </div>
                <div class="card">
                    <h3>Serviço 2</h3>
                    <p>Descrição detalhada do segundo serviço oferecido.</p>
                    <a href="#" class="btn">Saiba Mais</a>
                </div>
                <div class="card">
                    <h3>Serviço 3</h3>
                    <p>Descrição detalhada do terceiro serviço oferecido.</p>
                    <a href="#" class="btn">Saiba Mais</a>
                </div>
            </div>
        </section>

        <section id="portfolio" class="section">
            <h2>Portfólio</h2>
            <p>Mostre seus trabalhos anteriores, projetos realizados ou conquistas profissionais.</p>
            <p>Você pode adicionar imagens, links para outros projetos ou descrições detalhadas de suas realizações.</p>
        </section>

        <section id="contato" class="section">
            <h2>Entre em Contato</h2>
            <p>Gostaria de conversar? Entre em contato através dos canais abaixo:</p>

            <div class="contact-info">
                <p><strong>📧 Email:</strong> tatarvargas@gmail.com</p>
                <p><strong>📱 Telefone:</strong> (11) 99999-9999</p>
                <p><strong>📍 Localização:</strong> Bahia, Brasil</p>
                <p><strong>💼 LinkedIn:</strong> <a href="#">https://www.linkedin.com/in/thamaravargas</a></p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
            <p>Site hospedado gratuitamente - Criado com HTML e CSS</p>
        </div>
    </footer>

    <script>
        // Navegação suave entre seções
        document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Animação simples ao carregar a página
        window.addEventListener('load', function() {
            document.body.style.opacity = '0';
            document.body.style.transition = 'opacity 0.5s';
            setTimeout(() => {
                document.body.style.opacity = '1';
            }, 100);
        });
    </script>
</body>
</html>
