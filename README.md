<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinho | Agro Forte e Futuro Sustentável</title>
    <style>
        :root {
            --primary: #2e7d32;
            --primary-dark: #1b5e20;
            --accent: #f9a825;
            --bg-light: #f1f8e9;
            --text-dark: #263238;
            --white: #ffffff;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* Cabeçalho */
        header {
            background: linear-gradient(rgba(27, 94, 32, 0.85), rgba(27, 94, 32, 0.95)), 
                        url('https://images.unsplash.com/photo-1500937386664-56d1dfef3854?q=80&w=1200') no-repeat center/cover;
            color: var(--white);
            text-align: center;
            padding: 4rem 1rem;
        }

        header h1 {
            font-size: 2.8rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        header p {
            font-size: 1.3rem;
            max-width: 700px;
            margin: 0 auto;
            font-weight: 300;
        }

        /* Navegação */
        nav {
            background-color: var(--primary-dark);
            position: sticky;
            top: 0;
            z-index: 1000;
            text-align: center;
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            padding: 1rem 1.5rem;
            display: inline-block;
            font-weight: 600;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: var(--primary);
        }

        /* Conteúdo Principal */
        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 1.5rem;
        }

        .section-card {
            background: var(--white);
            padding: 2.5rem;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            margin-bottom: 2.5rem;
        }

        h2 {
            color: var(--primary-dark);
            font-size: 2rem;
            margin-bottom: 1.2rem;
            border-bottom: 4px solid var(--accent);
            display: inline-block;
            padding-bottom: 0.3rem;
        }

        p {
            font-size: 1.1rem;
            margin-bottom: 1.2rem;
            text-align: justify;
        }

        /* Grid de Destaques */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .grid-item {
            background-color: #fafafa;
            padding: 1.8rem;
            border-top: 4px solid var(--primary);
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.02);
        }

        .grid-item h3 {
            color: var(--primary);
            margin-bottom: 0.8rem;
            font-size: 1.3rem;
        }

        /* Rodapé */
        footer {
            background-color: var(--primary-dark);
            color: var(--white);
            text-align: center;
            padding: 1.5rem;
            margin-top: 4rem;
            font-size: 1rem;
        }

        /* Responsividade para Celular */
        @media (max-width: 600px) {
            header h1 { font-size: 2rem; }
            header p { font-size: 1rem; }
            nav a { padding: 0.8rem 0.8rem; font-size: 0.9rem; }
            .section-card { padding: 1.5rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Projeto Agrinho</h1>
        <p>Agro Forte e Futuro Sustentável: Equilibrando produção, tecnologia e respeito à nossa terra.</p>
    </header>

    <nav>
        <a href="#tema">O Tema</a>
        <a href="#pilares">Pilares Sustentáveis</a>
        <a href="#projeto">Nosso Projeto</a>
    </nav>

    <div class="container">
        
        <section id="tema" class="section-card">
            <h2>Agro Forte e Futuro Sustentável</h2>
            <p>O grande propósito do campo hoje é alimentar o mundo com eficiência enquanto protege o meio ambiente. Um <strong>Agro Forte</strong> utiliza o conhecimento técnico, a inovação e o trabalho dedicado do produtor rural para alcançar safras recordes. Um <strong>Futuro Sustentável</strong> garante que essa força não esgote os recursos naturais, cuidando da água, do solo e das florestas.</p>
            <p>O Programa Agrinho nos incentiva a pensar em soluções onde a produtividade e a ecologia andam de mãos dadas, mostrando que a tecnologia pode ser a maior aliada da natureza.</p>
        </section>

        <section id="pilares" class="section-card">
            <h2>Práticas do Campo do Futuro</h2>
            <p>A união entre a força agrícola e a conservação ambiental acontece na prática através de três pilares principais:</p>
            
            <div class="grid">
                <div class="grid-item">
                    <h3>Tecnologia de Precisão</h3>
                    <p>O uso de drones, sensores climáticos e maquinários inteligentes ajuda a aplicar água, fertilizantes e insumos na quantidade exata, evitando o desperdício e protegendo o ecossistema.</p>
                </div>
                <div class="grid-item">
                    <h3>Conservação do Solo</h3>
                    <p>Técnicas essenciais como o plantio direto, rotação de culturas e a integração lavoura-pecuária-floresta mantêm a terra rica em nutrientes e evitam a erosão do
