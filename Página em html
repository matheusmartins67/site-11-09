<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0"
    >

    <meta
        name="description"
        content="Como os acontecimentos de 11 de setembro aceleraram o desenvolvimento e a adoção de tecnologias de segurança, dados e comunicação."
    >

    <title>O Ponto de Virada da Tecnologia Pós-11 de Setembro</title>

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

    <link
        href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700;800&display=swap"
        rel="stylesheet"
    >

    <style>

        /* =========================================================
           RESET
        ========================================================= */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            background: #f2f0eb;
            color: #171717;
            font-family: "DM Sans", sans-serif;
            line-height: 1.7;
        }

        img {
            max-width: 100%;
        }

        a {
            color: inherit;
            text-decoration: none;
        }

        /* =========================================================
           HEADER
        ========================================================= */

        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 74px;
            background: rgba(242, 240, 235, 0.94);
            backdrop-filter: blur(12px);
            border-bottom: 1px solid rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        .header-container {
            width: min(1200px, 92%);
            height: 100%;
            margin: auto;

            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .logo {
            font-size: 17px;
            font-weight: 700;
            letter-spacing: -0.4px;
        }

        .logo span {
            color: #087f5b;
        }

        nav {
            display: flex;
            gap: 28px;
        }

        nav a {
            font-size: 13px;
            font-weight: 600;
            color: #555;
            transition: 0.2s;
        }

        nav a:hover {
            color: #087f5b;
        }

        /* =========================================================
           GLOBAL
        ========================================================= */

        .container {
            width: min(1200px, 92%);
            margin: auto;
        }

        section {
            padding: 110px 0;
        }

        .section-label {
            display: inline-block;

            font-size: 11px;
            font-weight: 700;
            letter-spacing: 2px;
            text-transform: uppercase;

            color: #087f5b;

            margin-bottom: 18px;
        }

        h1,
        h2,
        h3 {
            font-family: "Playfair Display", serif;
            font-weight: 700;
            line-height: 1.1;
        }

        h2 {
            font-size: clamp(36px, 5vw, 62px);
            letter-spacing: -1.5px;
        }

        p {
            color: #575757;
        }

        /* =========================================================
           IMAGE SYSTEM
        ========================================================= */

        .image-box {
            width: 100%;
            min-height: 380px;

            background: #dedbd4;

            border: 1px solid rgba(0, 0, 0, 0.12);

            overflow: hidden;

            position: relative;
        }

        .image-box img {
            width: 100%;
            height: 100%;
            min-height: inherit;

            display: block;

            object-fit: cover;
        }

        .hero-image {
            min-height: 620px;
        }

        .context-image {
            min-height: 480px;
        }

        .tech-image {
            min-height: 430px;
        }

        /* =========================================================
           HERO
        ========================================================= */

        .hero {
            min-height: 100vh;
            padding-top: 150px;
            padding-bottom: 80px;

            display: flex;
            align-items: center;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 70px;

            align-items: center;
        }

        .hero-content h1 {
            font-size: clamp(55px, 7vw, 100px);
            letter-spacing: -4px;
            max-width: 850px;
        }

        .hero-content h1 span {
            color: #087f5b;
        }

        .hero-description {
            margin-top: 30px;
            max-width: 620px;

            font-size: 18px;
            line-height: 1.8;
        }

        .hero-meta {
            margin-top: 40px;

            display: flex;
            gap: 35px;

            font-size: 12px;
            color: #777;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* =========================================================
           INTRO DARK
        ========================================================= */

        .intro {
            background: #171a1b;
            color: white;
        }

        .intro-grid {
            display: grid;
            grid-template-columns: 1fr 1.5fr;
            gap: 80px;
        }

        .intro h2 {
            color: white;
        }

        .intro p {
            color: #c5c8c7;
            font-size: 20px;
            line-height: 1.9;
        }

        .intro strong {
            color: #53d69c;
        }

        /* =========================================================
           CONTEXTO
        ========================================================= */

        .context-grid {
            display: grid;
            grid-template-columns: 1.1fr 1fr;
            gap: 80px;

            align-items: center;
        }

        .context-text p {
            margin-top: 25px;
            font-size: 18px;
        }

        .context-text .highlight {
            margin-top: 35px;
            padding-left: 25px;

            border-left: 3px solid #087f5b;

            font-family: "Playfair Display", serif;
            font-size: 25px;
            line-height: 1.5;

            color: #242424;
        }

        /* =========================================================
           TIMELINE
        ========================================================= */

        .timeline-section {
            background: #e8e5df;
        }

        .timeline-intro {
            max-width: 760px;
            margin-bottom: 80px;
        }

        .timeline-intro p {
            margin-top: 25px;
            font-size: 18px;
        }

        .timeline {
            border-top: 1px solid rgba(0, 0, 0, 0.2);
        }

        .timeline-item {
            display: grid;
            grid-template-columns: 180px 1fr;

            padding: 45px 0;

            border-bottom: 1px solid rgba(0, 0, 0, 0.2);
        }

        .timeline-year {
            font-family: "Playfair Display", serif;
            font-size: 42px;
            color: #087f5b;
        }

        .timeline-content h3 {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .timeline-content p {
            max-width: 800px;
        }

        /* =========================================================
           TECNOLOGIAS
        ========================================================= */

        .technologies-header {
            max-width: 800px;
            margin-bottom: 90px;
        }

        .technologies-header p {
            margin-top: 25px;
            font-size: 18px;
        }

        .technology {
            padding: 100px 0;

            border-top: 1px solid rgba(0, 0, 0, 0.15);
        }

        .technology-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;

            gap: 80px;

            align-items: center;
        }

        .technology:nth-child(even) .technology-grid {
            direction: rtl;
        }

        .technology:nth-child(even) .technology-text {
            direction: ltr;
        }

        .technology:nth-child(even) .image-box {
            direction: ltr;
        }

        .technology-number {
            color: #087f5b;

            font-size: 12px;
            font-weight: 700;

            letter-spacing: 2px;

            margin-bottom: 15px;
        }

        .technology h3 {
            font-size: clamp(38px, 5vw, 62px);

            margin-bottom: 25px;
        }

        .technology-text p {
            font-size: 17px;
            margin-bottom: 20px;
        }

        .technology-list {
            margin-top: 30px;

            list-style: none;
        }

        .technology-list li {
            position: relative;

            padding-left: 20px;
            margin-bottom: 12px;

            color: #555;
        }

        .technology-list li::before {
            content: "";

            width: 6px;
            height: 6px;

            background: #087f5b;

            position: absolute;
            left: 0;
            top: 11px;

            border-radius: 50%;
        }

        /* =========================================================
           DEBATE
        ========================================================= */

        .debate {
            background: #171a1b;
            color: white;
        }

        .debate-header {
            max-width: 800px;
            margin-bottom: 70px;
        }

        .debate h2 {
            color: white;
        }

        .debate-header p {
            margin-top: 25px;

            color: #bfc4c2;

            font-size: 18px;
        }

        .debate-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 1px;

            background: #3b3e3d;
        }

        .debate-card {
            padding: 55px;
            background: #171a1b;
        }

        .debate-card h3 {
            font-size: 34px;
            margin-bottom: 20px;
        }

        .debate-card p {
            color: #c5c8c7;
        }

        .debate-card .line {
            width: 45px;
            height: 3px;

            background: #53d69c;

            margin-bottom: 30px;
        }

        /* =========================================================
           CONCLUSÃO
        ========================================================= */

        .conclusion {
            text-align: center;
        }

        .conclusion-content {
            max-width: 900px;
            margin: auto;
        }

        .conclusion h2 {
            font-size: clamp(42px, 6vw, 75px);
        }

        .conclusion p {
            margin: 30px auto 0;

            max-width: 750px;

            font-size: 20px;
        }

        .conclusion .final-note {
            margin-top: 50px;

            color: #087f5b;

            font-size: 13px;
            font-weight: 700;

            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* =========================================================
           FOOTER
        ========================================================= */

        footer {
            background: #111313;
            color: #aaa;

            padding: 45px 0;
        }

        .footer-container {
            width: min(1200px, 92%);
            margin: auto;

            display: flex;
            justify-content: space-between;
            gap: 30px;

            font-size: 12px;
        }

        .footer-logo {
            color: white;
            font-weight: 700;
        }

        .footer-logo span {
            color: #53d69c;
        }

        /* =========================================================
           RESPONSIVE
        ========================================================= */

        @media (max-width: 900px) {

            header {
                height: 65px;
            }

            nav {
                display: none;
            }

            section {
                padding: 80px 0;
            }

            .hero {
                padding-top: 120px;
            }

            .hero-grid,
            .context-grid,
            .technology-grid,
            .intro-grid {
                grid-template-columns: 1fr;
            }

            .hero-image {
                min-height: 450px;
            }

            .context-image,
            .tech-image {
                min-height: 350px;
            }

            .technology:nth-child(even) .technology-grid {
                direction: ltr;
            }

            .technology {
                padding: 75px 0;
            }

            .technology-grid {
                gap: 45px;
            }

            .debate-grid {
                grid-template-columns: 1fr;
            }

            .intro-grid {
                gap: 40px;
            }
        }

        @media (max-width: 600px) {

            .container {
                width: 90%;
            }

            .hero-content h1 {
                font-size: 52px;
                letter-spacing: -2px;
            }

            .hero-description {
                font-size: 16px;
            }

            .hero-meta {
                flex-direction: column;
                gap: 10px;
            }

            .hero-image {
                min-height: 330px;
            }

            .context-image,
            .tech-image {
                min-height: 280px;
            }

            .timeline-item {
                grid-template-columns: 1fr;
                gap: 12px;
            }

            .timeline-year {
                font-size: 34px;
            }

            .debate-card {
                padding: 35px 25px;
            }

            .footer-container {
                flex-direction: column;
            }
        }

    </style>
</head>

<body>

    <!-- =========================================================
         HEADER
    ========================================================= -->

    <header>

        <div class="header-container">

            <a href="#inicio" class="logo">
                TECNOLOGIA<span>.</span>2001
            </a>

            <nav>

                <a href="#contexto">
                    Contexto
                </a>

                <a href="#linha-do-tempo">
                    Linha do tempo
                </a>

                <a href="#tecnologias">
                    Tecnologias
                </a>

                <a href="#debate">
                    Debate
                </a>

            </nav>

        </div>

    </header>


    <main>

        <!-- =====================================================
             HERO
        ====================================================== -->

        <section class="hero" id="inicio">

            <div class="container">

                <div class="hero-grid">

                    <div class="hero-content">

                        <span class="section-label">
                            Tecnologia • História • Sociedade
                        </span>

                        <h1>
                            O ponto de virada da
                            <span>tecnologia</span>
                            pós-11 de setembro
                        </h1>

                        <p class="hero-description">
                            Os ataques de 11 de setembro de 2001 não
                            criaram sozinhos as tecnologias que usamos
                            atualmente. Porém, mudaram prioridades,
                            investimentos e políticas, acelerando a
                            adoção de diversas soluções tecnológicas.
                        </p>

                        <div class="hero-meta">

                            <span>
                                2001 — Presente
                            </span>

                            <span>
                                Segurança & Dados
                            </span>

                            <span>
                                Transformação Digital
                            </span>

                        </div>

                    </div>


                    <!-- =================================================
                         IMAGEM PRINCIPAL
                         TROQUE APENAS O NOME DO ARQUIVO
                    ================================================== -->

                    <div class="image-box hero-image">

                        <img
                            src="predio.webp"
                            alt="Imagem relacionada aos acontecimentos de 11 de setembro de 2001"
                        >

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================================================
             INTRODUÇÃO
        ========================================================= -->

        <section class="intro">

            <div class="container">

                <div class="intro-grid">

                    <div>

                        <span class="section-label">
                            O contexto
                        </span>

                        <h2>
                            Um acontecimento que mudou as prioridades tecnológicas.
                        </h2>

                    </div>

                    <div>

                        <p>
                            Depois dos ataques de 11 de setembro,
                            governos e empresas passaram a dar muito
                            mais atenção à <strong>segurança digital,
                            identificação de pessoas, análise de dados,
                            comunicação segura e monitoramento.</strong>
                        </p>

                        <br>

                        <p>
                            Muitas dessas tecnologias já existiam ou
                            estavam sendo desenvolvidas. O que mudou
                            foi a escala de investimento, pesquisa,
                            integração e utilização.
                        </p>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================================================
             CONTEXTO
        ========================================================= -->

        <section id="contexto">

            <div class="container">

                <div class="context-grid">

                    <div class="context-text">

                        <span class="section-label">
                            Antes e depois
                        </span>

                        <h2>
                            A tecnologia passou a ser vista também como infraestrutura de segurança.
                        </h2>

                        <p>
                            A necessidade de identificar ameaças,
                            compartilhar informações rapidamente e
                            proteger sistemas críticos ganhou uma
                            importância muito maior após 2001.
                        </p>

                        <p>
                            Esse cenário contribuiu para acelerar
                            pesquisas e aplicações em áreas que hoje
                            fazem parte do nosso cotidiano.
                        </p>

                        <div class="highlight">

                            "O 11 de setembro não inventou a tecnologia
                            moderna. Ele ajudou a mudar a velocidade e
                            a direção de sua adoção."

                        </div>

                    </div>


                    <!-- =================================================
                         IMAGEM DE CONTEXTO
                         TROQUE APENAS O NOME DO ARQUIVO
                    ================================================== -->

                    <div class="image-box context-image">

                        <img
                            src="tecnologia.jpeg"
                            alt="Contexto histórico e tecnológico após os ataques de 2001"
                        >

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================================================
             LINHA DO TEMPO
        ========================================================= -->

        <section class="timeline-section" id="linha-do-tempo">

            <div class="container">

                <div class="timeline-intro">

                    <span class="section-label">
                        Linha do tempo
                    </span>

                    <h2>
                        De 2001 até a era digital.
                    </h2>

                    <p>
                        A transformação aconteceu de forma gradual.
                        O impacto pode ser observado em diferentes
                        momentos da evolução tecnológica.
                    </p>

                </div>


                <div class="timeline">

                    <div class="timeline-item">

                        <div class="timeline-year">
                            2001
                        </div>

                        <div class="timeline-content">

                            <h3>
                                O choque inicial
                            </h3>

                            <p>
                                Segurança, inteligência e monitoramento
                                passam a receber atenção e investimentos
                                muito maiores.
                            </p>

                        </div>

                    </div>


                    <div class="timeline-item">

                        <div class="timeline-year">
                            2000s
                        </div>

                        <div class="timeline-content">

                            <h3>
                                Expansão da infraestrutura
                            </h3>

                            <p>
                                Sistemas de identificação, bancos de
                                dados, redes seguras e tecnologias de
                                monitoramento ganham escala.
                            </p>

                        </div>

                    </div>


                    <div class="timeline-item">

                        <div class="timeline-year">
                            2010s
                        </div>

                        <div class="timeline-content">

                            <h3>
                                Dados em grande escala
                            </h3>

                            <p>
                                Computação em nuvem, Big Data,
                                inteligência artificial e análise
                                automatizada tornam-se cada vez mais
                                importantes.
                            </p>

                        </div>

                    </div>


                    <div class="timeline-item">

                        <div class="timeline-year">
                            Hoje
                        </div>

                        <div class="timeline-content">

                            <h3>
                                Segurança integrada ao cotidiano
                            </h3>

                            <p>
                                Biometria, criptografia, reconhecimento
                                facial, computação em nuvem e análise
                                de dados fazem parte de serviços usados
                                diariamente.
                            </p>

                        </div>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================================================
             TECNOLOGIAS
        ========================================================= -->

        <section id="tecnologias">

            <div class="container">

                <div class="technologies-header">

                    <span class="section-label">
                        Tecnologias
                    </span>

                    <h2>
                        Seis áreas que ganharam força.
                    </h2>

                    <p>
                        Algumas tecnologias já estavam em desenvolvimento
                        antes de 2001. O contexto posterior aos ataques
                        contribuiu para acelerar sua pesquisa, financiamento,
                        adoção ou utilização em larga escala.
                    </p>

                </div>


                <!-- =================================================
                     01 CLOUD
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                01 / CLOUD COMPUTING
                            </div>

                            <h3>
                                Computação em nuvem
                            </h3>

                            <p>
                                Organizações passaram a dar maior
                                importância à continuidade de operações
                                e à capacidade de recuperar sistemas
                                depois de grandes interrupções.
                            </p>

                            <p>
                                A computação em nuvem tornou possível
                                distribuir dados e serviços entre
                                diferentes infraestruturas, reduzindo
                                a dependência de um único local físico.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Backup e recuperação de dados
                                </li>

                                <li>
                                    Disaster Recovery
                                </li>

                                <li>
                                    Infraestrutura distribuída
                                </li>

                                <li>
                                    Alta disponibilidade
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM CLOUD -->

                        <div class="image-box tech-image">

                            <img
                                src="banco.png"
                                alt="Computação em nuvem e infraestrutura de servidores"
                            >

                        </div>

                    </div>

                </article>


                <!-- =================================================
                     02 BIOMETRIA
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                02 / BIOMETRIA
                            </div>

                            <h3>
                                Biometria e reconhecimento facial
                            </h3>

                            <p>
                                A identificação por características
                                físicas ganhou espaço em aeroportos,
                                fronteiras, sistemas governamentais
                                e outros ambientes de segurança.
                            </p>

                            <p>
                                Impressões digitais, reconhecimento
                                facial e outras formas de identificação
                                passaram a ser integradas a sistemas
                                digitais.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Impressão digital
                                </li>

                                <li>
                                    Reconhecimento facial
                                </li>

                                <li>
                                    Identificação automatizada
                                </li>

                                <li>
                                    Controle de acesso
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM BIOMETRIA -->

                        <div class="image-box tech-image">

                            <img
                                src="biometria.jpg"
                                alt="Tecnologia de biometria e reconhecimento facial"
                            >

                        </div>

                    </div>

                </article>


                <!-- =================================================
                     03 BIG DATA
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                03 / BIG DATA
                            </div>

                            <h3>
                                Big Data e mineração de dados
                            </h3>

                            <p>
                                A necessidade de cruzar informações
                                provenientes de diferentes fontes
                                impulsionou sistemas capazes de
                                armazenar e analisar enormes volumes
                                de dados.
                            </p>

                            <p>
                                Técnicas de data mining passaram a ser
                                utilizadas para encontrar padrões,
                                relações e possíveis sinais de risco.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Grandes bancos de dados
                                </li>

                                <li>
                                    Data mining
                                </li>

                                <li>
                                    Análise de padrões
                                </li>

                                <li>
                                    Inteligência analítica
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM BIG DATA -->

                        <div class="image-box tech-image">

                            <img
                                src="Big-Data.jpeg"
                                alt="Visualização de grandes volumes de dados"
                            >

                        </div>

                    </div>

                </article>


                <!-- =================================================
                     04 CIBERSEGURANÇA
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                04 / CYBERSECURITY
                            </div>

                            <h3>
                                Cibersegurança
                            </h3>

                            <p>
                                A proteção de redes, sistemas e
                                informações tornou-se uma prioridade
                                cada vez maior.
                            </p>

                            <p>
                                A expansão da internet e a digitalização
                                de serviços fizeram com que ataques
                                digitais passassem a representar riscos
                                estratégicos para organizações.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Firewalls
                                </li>

                                <li>
                                    Detecção de ameaças
                                </li>

                                <li>
                                    Monitoramento de redes
                                </li>

                                <li>
                                    Proteção de infraestrutura crítica
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM CIBERSEGURANÇA -->

                        <div class="image-box tech-image">

                            <img
                                src="segurança.jpg"
                                alt="Cibersegurança e proteção de redes"
                            >

                        </div>

                    </div>

                </article>


                <!-- =================================================
                     05 DRONES
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                05 / UAV
                            </div>

                            <h3>
                                Drones e veículos não tripulados
                            </h3>

                            <p>
                                Veículos aéreos não tripulados já
                                existiam antes de 2001, mas os conflitos
                                das décadas seguintes contribuíram
                                fortemente para sua evolução e utilização.
                            </p>

                            <p>
                                A tecnologia passou a ser usada para
                                reconhecimento, monitoramento e operações
                                em áreas consideradas perigosas.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Vigilância aérea
                                </li>

                                <li>
                                    Reconhecimento
                                </li>

                                <li>
                                    Monitoramento remoto
                                </li>

                                <li>
                                    Operações sem piloto a bordo
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM DRONES -->

                        <div class="image-box tech-image">

                            <img
                                src="drone.jpg"
                                alt="Drone ou veículo aéreo não tripulado"
                            >

                        </div>

                    </div>

                </article>


                <!-- =================================================
                     06 CRIPTOGRAFIA
                ================================================== -->

                <article class="technology">

                    <div class="technology-grid">

                        <div class="technology-text">

                            <div class="technology-number">
                                06 / CRYPTOGRAPHY
                            </div>

                            <h3>
                                Criptografia e comunicação segura
                            </h3>

                            <p>
                                A proteção das comunicações digitais
                                ganhou ainda mais importância conforme
                                governos, empresas e cidadãos passaram
                                a depender cada vez mais da internet.
                            </p>

                            <p>
                                A criptografia permite proteger
                                informações durante seu armazenamento
                                e transmissão.
                            </p>

                            <ul class="technology-list">

                                <li>
                                    Criptografia de dados
                                </li>

                                <li>
                                    Comunicação segura
                                </li>

                                <li>
                                    HTTPS
                                </li>

                                <li>
                                    Criptografia ponta a ponta
                                </li>

                            </ul>

                        </div>


                        <!-- IMAGEM CRIPTOGRAFIA -->

                        <div class="image-box tech-image">

                            <img
                                src="criptografia.jpg"
                                alt="Criptografia e comunicação digital segura"
                            >

                        </div>

                    </div>

                </article>

            </div>

        </section>


        <!-- =========================================================
             DEBATE
        ========================================================= -->

        <section class="debate" id="debate">

            <div class="container">

                <div class="debate-header">

                    <span class="section-label">
                        O outro lado
                    </span>

                    <h2>
                        Segurança versus privacidade.
                    </h2>

                    <p>
                        O avanço das tecnologias de segurança também
                        trouxe discussões sobre vigilância, liberdade,
                        privacidade e uso responsável dos dados.
                    </p>

                </div>


                <div class="debate-grid">

                    <div class="debate-card">

                        <div class="line"></div>

                        <h3>
                            Segurança
                        </h3>

                        <p>
                            Tecnologias de identificação, análise de
                            dados e monitoramento podem ajudar governos
                            e organizações a identificar ameaças e
                            proteger pessoas e infraestrutura.
                        </p>

                    </div>


                    <div class="debate-card">

                        <div class="line"></div>

                        <h3>
                            Privacidade
                        </h3>

                        <p>
                            As mesmas ferramentas podem levantar questões
                            sobre coleta excessiva de informações,
                            vigilância, armazenamento de dados pessoais
                            e limites do monitoramento.
                        </p>

                    </div>

                </div>

            </div>

        </section>


        <!-- =========================================================
             CONCLUSÃO
        ========================================================= -->

        <section class="conclusion">

            <div class="container">

                <div class="conclusion-content">

                    <span class="section-label">
                        Conclusão
                    </span>

                    <h2>
                        O 11 de setembro não criou o futuro.
                        Ele ajudou a acelerar sua chegada.
                    </h2>

                    <p>
                        A transformação tecnológica que ocorreu nas
                        décadas seguintes foi resultado de diversos
                        fatores. Entretanto, o cenário criado após
                        2001 teve um papel importante ao aumentar a
                        prioridade dada à segurança, aos dados,
                        à comunicação e à capacidade de monitoramento.
                    </p>

                    <div class="final-note">
                        Tecnologia • Segurança • Sociedade
                    </div>

                </div>

            </div>

        </section>

    </main>


    <!-- =========================================================
         FOOTER
    ========================================================= -->

    <footer>

        <div class="footer-container">

            <div class="footer-logo">
                TECNOLOGIA<span>.</span>2001
            </div>

            <div>
                Projeto educacional sobre tecnologia e história
            </div>

            <div>
                2001 — Presente
            </div>

        </div>

    </footer>


</body>
</html>
