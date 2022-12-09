<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Needis Teste</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <section>
        <div class="circle"></div>
        <header>
            <nav>
                <a href="#"><img src="img/Needis1.png" class="logo"></a>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Menu</a></li>
                    <li><a href="#">Sobre</a></li>
                    <li><a href="#">Contato</a></li>
                </ul>
            </nav>
        </header>
        <div class="content">
            <div class="BoxTexto">
                <h2>Gente que cuida de gente.<br>É <span>Needis</span></h2>
                <p>Saúde das Pessoas, do Negócio e do nosso Planeta.<br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum architecto corrupti voluptatum placeat officia reiciendis aut. Similique asperiores possimus enim ullam quibusdam fuga ad eos reprehenderit soluta, officiis quaerat dolor!

                </p>
                <a href="#">Saiba Mais</a>
            </div>
            <div class="imgBox">
                <img src="img/img1.png" class="starbucks">
            </div>
        </div>
            <nav>
                <figure>
                        <ul class="thumb">
                            <li><img src="img/thumb1.png" onclick="imgSlider('img/img1.png');changeCircleColor('#017143')"></li>
                            <figcaption>Nutrilite</figcaption>
                            <li><img src="img/thumb2.png" onclick="imgSlider('img/img2.png');changeCircleColor('#eb7495')"></li>
                            <figcaption>Covid</figcaption>
                            <li><img src="img/thumb3.png" onclick="imgSlider('img/img3.png');changeCircleColor('#8fd6ff')"></li>
                            <figcaption>Burnout</figcaption>
                        </ul>
                    </figcaption>
                </figure>
                <ul class="social">
                    <li><a href="https://www.instagram.com/_rnn.oliveira/" target="_blank" rel="noopener noreferrer"><img src="img/instagram.png"></a></li>
                    <li><a href="https://twitter.com/RNanWP" target="_blank" rel="noopener noreferrer"><img src="img/twitter.png"></a></li>
                    <li><a href="https://www.facebook.com/Desenhos.ProArt" target="_blank" rel="noopener noreferrer"><img src="img/facebook.png"></a></li>
                </ul>
            </nav>
        </section>
        <footer>
            <div class="container-footer">
                <div class="linha-footer">
                    <!--footer coluna-->
                    <div class="footer-col">
                        <h4>Empresa</h4>
                        <ul>
                            <li> <a href="#"> Quem somos</a> </li>
                            <li> <a href="#"> Nossos serviços</a> </li>
                            <li> <a href="#"> Política de privacidade</a> </li>
                            <li> <a href="#"> Programa de afilidados</a> </li>
                        </ul>
                    </div>
                    <!--Fim footer coluna-->
                    <!--footer coluna-->
                    <div class="footer-col">
                        <h4>Obter ajuda</h4>
                        <ul>
                            <li> <a href="#"> FAQ</a> </li>
                            <li> <a href="#"> Transporte</a> </li>
                            <li> <a href="#"> Devoluções</a> </li>
                            <li> <a href="#"> Status de pedido</a> </li>
                            <li> <a href="#"> Opções de pagamento</a> </li>
                        </ul>
                    </div>
                    <!--Fim footer coluna-->
                    <!--footer coluna-->
                    <div class="footer-col">
                        <h4>Loja online</h4>
                        <ul>
                            <li> <a href="#"> Remédios</a> </li>
                            <li> <a href="#"> Endereço</a> </li>
                        </ul>
                    </div>
                    <!--Fim footer coluna-->
                    <!--footer coluna-->
                    <div class="footer-col">
                        <h4>Email</h4>
                        <!--Email sub-->
                        <div class="email-sub">
                            <form>
                                <input type="email" placeholder="Digite o seu e-mail" required>
                                <button>Inscrever-se</button>
                            </form>
                            Aluno: Renan Santos de Oliveira<br>RA: 2222200490
                        </div>
                        <!--Fim email sub-->
                    </div>
                    <!--Fim footer coluna-->
                </div>
            </div>
        </footer>
</body>
</html>
