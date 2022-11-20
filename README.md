# Projeto---Dubairro2022---TCC
Baixe o código por aqui ->

<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="./img/logo_alternativa.jpg" type="image/x-icon">

    <!-- Importação Swiper - Slides -->

    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">

    <!-- Importação Style -->

    <link rel="stylesheet" href="./css/style.css">

    <title>Dubairro</title>

    <!-- Descrição da Página -->

    <meta name="description"
        content="Dubairro - O Website que usa a geolocalização, onde moradores e pequenos comércios locais podem se cadastrar, permitindo maior interação entre moradores do bairro.">

</head>

<body>

    <!-- Início Preloader -->

    <div id="preloader">
    </div>

    <!-- Fim Preloader -->

    <!-- Início Cabeçalho -->

    <header>
        <figure>
            <a href="./index.html" class="logo"><img src="./img/logo 3000x2000.png" alt="Logotipo"></a>
        </figure>

        <nav class="menu_navegacao">
            <ul>
                <li><a href="#home">Início<span class="icone-lado"><i class="fa fa-home"></i></span></a></li>
                <li><a href="./comercios.html">Comércios<span class="icone-lado"><i class="fa fa-shop"></i></span></a>
                </li>
                <li><a href="./bate_papo.html">Chat<span class="icone-lado"><i class="fa fa-message"></i></span></a>
                </li>
                <li><a href="#sobre">Sobre<span class="icone-lado"><i class="fa fa-table"></i></span></a>
                </li>
                <li><a href="#equipe">Equipe<span class="icone-lado"><i class="fa fa-group"></i></span></a></li>
            </ul>
            <label id="icon">
                <i class="fas fa-bars"></i>
            </label>
        </nav>
        <div class="conta">
            <a href="./login.php" class="conta"><span></span><span></span><span></span><span></span>Entrar<span><i
                        class="fa fa-user"></i></span></a>
        </div>
    </header>

    <!-- Fim Cabeçalho -->

    <main>

        <!-- Início Seção Home -->

        <section id="home" class="home">
            <div class="home-text">
                <h4>Desenvolvimento Sustentável</h4>
                <h1>Cadastre-se e Interaja com<br>
                    os moradores do seu
                    <br><span>Bairro!</span>
                </h1>
                <a href="#">Ler mais<span><i class="fa fa-angle-right"></i></span></a>
            </div>
        </section>

        <!-- Seta Baixo -->

        <div class="seta-baixo"></div>

        <!-- Fim Seção Home -->


        <!-- Início Seção Contexto -->

        <section id="sobre" class="contexto">

            <figure class="imagem-esquerdo"><img src="./img/agrupa.png" alt=""></figure>
            <div class="texto1">
                <h2>Sustentabilidade</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Obcaecati tempora tenetur laudantium earum
                    enim, aperiam amet beatae placeat delectus nemo iure a adipisci illo quas distinctio eligendi.
                    Possimus, reiciendis? Unde similique, modi nemo placeat soluta amet reprehenderit. Neque dolores
                    iusto deserunt aliquid voluptatibus blanditiis, earum autem ab fugiat, itaque perferendis optio
                    tempore omnis eius iste, temporibus aliquam nam voluptates nulla!</p>
            </div>
        </section>

        <section class="ods">
            <div class="texto">
                <h2>Relação com ODS</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Obcaecati tempora tenetur laudantium earum
                    enim, aperiam amet beatae placeat delectus nemo iure a adipisci illo quas distinctio eligendi.
                    Possimus, reiciendis? Unde similique, modi nemo placeat soluta amet reprehenderit. Neque dolores
                    iusto deserunt aliquid voluptatibus blanditiis, earum autem ab fugiat, itaque perferendis optio
                    tempore omnis eius iste, temporibus aliquam nam voluptates nulla!</p>
            </div>
            <figure class="imagem-direito"><img src="./img/ods11.jpg" alt=""></figure>
        </section>
        <section class="contexto2">
            <div class="container">
                <div class="card">
                    <h2>Objetivos <i class="fas fa-arrow-right" style="color: #c70535;"></i></h2>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel.</p>
                    <img class="image-card" src="./img/objetivos.png" alt="ícone representando os objetivos">
                </div>
                <div class="card">
                    <h2>Projeto <i class="fas fa-arrow-right" style="color: #c70535;"></i></h2>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel.</p>
                    <img class="image-card" src="./img/projeto.png" alt="ícone representando o projeto">
                </div>
                <div class="card">
                    <h2>Contribua <i class="fas fa-arrow-right" style="color: #c70535;"></i></h2>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vel.</p>
                    <img class="image-card" src="./img/contribua.png" alt="ícone representando a contruibuição">
                </div>
            </div>
        </section>

        <!-- Fim Seção Contexto -->

        <!-- Início Seção Sobre o site -->

        <section class="cell-dubairro">
            <figure class="cell">
                <img src="./img/celular_notebook.png" alt="Imagem representando uma Cidade/bairro">
            </figure>
            <div class="texto">
                <div class="texto_geo">
                    <h2>Geolocalização</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quisquam quam veniam temporibus
                        cupiditate ex quae. Vel eius eveniet molestias labore animi.</p>
                </div>
                <div class="texto_acess">
                    <h2>Acessibilidade</h2>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat quisquam quam veniam temporibus
                        cupiditate ex quae. Vel eius eveniet molestias labore animi.</p>
                </div>
            </div>
        </section>

        <!-- Fim Seção Sobre o site -->

        <!-- Início Seção Equipe -->

        <section id="equipe" class="equipe">
            <div class="swiper mySwiper container">
                <div class="swiper-wrapper content">
                    <div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Samuel.jpg" alt="Foto do integrante da equipe: Samuel.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Samuel H. Souza</span>
                                <span class="funcao">Programador</span>
                            </div>
                        </div>
                    </div><div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Murilo.jpg" alt="Foto do integrante da equipe: Murilo.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Murilo M. Alves</span>
                                <span class="funcao">Programador</span>
                            </div>
                        </div>
                    </div><div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Rodrigo.jpg" alt="Foto do integrante da equipe: Rodrigo.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Rodrigo R. Rocha</span>
                                <span class="funcao">Pesquisador</span>
                            </div>
                        </div>
                    </div><div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Mateus.jpg" alt="Foto do integrante da equipe: Mateus.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Mateus H. Souza</span>
                                <span class="funcao">Designer</span>
                            </div>
                        </div>
                    </div><div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Kevin.jpg" alt="Foto do integrante da equipe: Kevin.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Kevin R. Gomes</span>
                                <span class="funcao">Pesquisador</span>
                            </div>
                        </div>
                    </div><div class="swiper-slide card">
                        <div class="card-content">
                            <div class="image">
                                <img src="./img/Vinicius.jpg" alt="Foto do integrante da equipe: Vinicius.">
                            </div>
                            <div class="media-icons">
                                <i class="fab fa-facebook"></i>
                                <i class="fab fa-instagram"></i>
                                <i class="fab fa-twitter"></i>
                            </div>
                            <div class="names">
                                <span class="name">Vinicius G. Bezerra</span>
                                <span class="funcao">Designer</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Fim Seção Equipe -->


        <!-- Início Seção Sugestões -->

        <section id="sugestoes" class="sugestoes">
            <div class="wrapper">
                <div class="wrapper-title">
                    <h2>Deixe sua sugestão aqui <i class="fas fa-angle-down" style="color: #c70535;"></i></h2>
                </div>
                <form action="./php/sugestoes.php" class="contato" method="POST">
                    <div class="dbl-field">
                        <div class="field">
                            <input type="text" placeholder="Nome" name="name" required>
                            <i class="fas fa-user"></i>
                        </div>
                        <div class="field">
                            <input type="email" placeholder="E-mail" name="email" required>
                            <i class="fas fa-envelope"></i>
                        </div>
                    </div>
                    <div class="message">
                        <textarea name="message" placeholder="Digite algo..." required></textarea>
                        <i class="fas fa-message"></i>
                        <div class="caracteres">
                            <span class="min-num">0</span>
                            <span class="limit-num">/500</span>
                        </div>
                    </div>
                    <div class="button-area">
                        <button type="submit">Enviar</button>
                    </div>
                </form>
            </div>
        </section>

        <!-- Fim Seção Sugestões -->

    </main>

    <!-- Início Rodapé -->

    <footer>
        <div class="container_info">
            <figure>
                <a href="./index.html" class="rodape"><img src="./img/logo 3000x2000.png" alt="Logotipo"></a>
            </figure>

            <div class="contato">
                <h3>Contato</h3>
                <ul>
                    <li><a href="#">dubairro22projeto@gmail.com</a></li>
                    <li><a href="#">+55(11)4002-8922</a></li>
                </ul>
            </div>
            <div class="sobre">
                <h3>Sobre</h3>
                <ul>
                    <li><a href="#">Equipe</a></li>
                    <li><a href="#">Direitos</a></li>
                    <li><a href="#">Termos</a></li>
                    <li><a href="#">Privacidade</a></li>
                </ul>
            </div>
            <div class="duvida">
                <h3>Dúvidas</h3>
                <ul>
                    <li><a href="#">Comunidade</a></li>
                    <li><a href="#">Ajuda</a></li>
                </ul>
            </div>
        </div>
        <div class="container">
            <div class="social">
                <a href="https://www.instagram.com/dubairro22/" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://twitter.com/DubairroOFC" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://github.com/DUbairro" target="_blank"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin" target="_blank"></i></a>
            </div>
        </div>

        <p class="copyright">
            Projeto com fins acadêmicos | ETEC de Carapicuíba | 2022
        </p>
    </footer>

    <!-- Fim Rodapé -->


    <!-- JS & Font Awesome -->

    <script src="https://kit.fontawesome.com/8588795106.js" crossorigin="anonymous"></script>
    <script src="./js/scripts.js">
    </script>
    <!-- Swiper -->
    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

    <script>

        var swiper = new Swiper(".mySwiper", {
            slidesPerView: 3,
            scapeBetween: 30,
            slidesPerGroup: 3,
            loop: true,
            loopFillGroupWithBlank: true,
            pagination: {
                el: ".swiper-pagination",
                clickable: true,
            },
        });

    </script>

    <div vw class="enabled">
        <div vw-access-button class="active"></div>
        <div vw-plugin-wrapper>
            <div class="vw-plugin-top-wrapper"></div>
        </div>
    </div>
    <script src="https://vlibras.gov.br/app/vlibras-plugin.js"></script>
    <script>
        new window.VLibras.Widget('https://vlibras.gov.br/app');
    </script>
</body>

</html>
