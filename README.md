# Reproduçãoo-Pagina-Web
Reprodução Pagina Web, HTML e CSS -  Tempo de excução em 1 hora, requisito foi utilizar Flexbox! 

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>G&P</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Exo+2:wght@100;200;400;500&display=swap" rel="stylesheet">
    
    </head>
    <body>
        <header>
            <h1 class="logopreto">G&<span class="logobranco">P</span></h1>
            <div class="caixasuperior">
                <nav>
                    <ul>
                        <li><a href="">Home</a></li>
                        <li><a href="">Jogos</a></li>
                        <li><a href="">Celular</a></li>
                        <li><a href="">Informática</a></li>
                        <li><a href="">Eletrônicos</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <main class="corpo">
            <div class="container">
                <div class="child">
                    <h2 class="titulocard">Imprensa</h2>
                    <h2 class="subtitulocard">G&P renova parceria com a IBM</h2>
                    <p class="postagem">postado 20 março 2022</p>
                    <img class="imagem" class="margim" src="card1.PNG">
                    <p class="margim">Renovada anualmente, a parceria vai ao mesmo encontro do objetivo de trazer melhorias contínuas e beneficiar cada vez mais os clientes da companhia, dos segmentos públicos e privados."Por mais um ano renovamos a parceria com a IBM, fortalecimendo nosso portofólio e diferenciando nossos negócios. Esta parceria nos beneficia, proporcionando uma grande oportunidade de crescimento intelectual e acesso a soluções tecnológicas mundialmente utilizadas", relata Rodrigo Bicas, Gerente de Aliança da G&P.</p>
                    <a class="leia" href="Leia mais">Leia mais</a>
                </div>
                
                <div class="child2">
                    <h2 class="subtitulocard">Ouvidoria G&P</h2>
                    <P class="margim">Estamos abertos para melhorar sempre os nossos serviços e temos um canal de relacionamento de forma transparente e ágil. O nosso canal de ouvidoria para comunicação para registro de elogios, sugestões, reclamações ou dúvidas de todos os públicos que se relacionam com a G&P Projetos e Sistemas, como colaboradores, clientes e fornecedores. Como acionar a ouvidoria G&P? Você poderá fazer o seu elogio, sugestão ou denúncia através do e-mail ouvidoria@gpnet.com.br ou aqui no nosso formulário clicando aqui.</P>
                    <a class="leia" href="Leia mais">Leia mais</a>
                    <hr class="traco">
                    <p class="margim">Investimos em um completo ecossistema de inovação para atender as principais verticais. oferecendo a tecnologia como solução aos nossos clientes, como oferta alinhadas as principais tendências de tecnologia. W</p>
                    <a class="leia" href="Leia mais">Leia mais</a>
                </div>

                <div class="child">
                    <h2 class="titulocard">Nossos Clientes</h2>
                    <p class="postagem">postado 10 março 2022</p>
                    <img class="imagem" src="card2.jpg">
                    <p class="margim">A G&P atua com foco nas nescessidades de cada cliente, desenvolvendo um trabalho customizado, oferecendo uma solução específica para cada particularidade, sempre com sinergia com todos os profissionais envolvidos em cada etapa do processo. Abaixo alguns de nossos clientes.</p>
                    <a class="leia" href="Leia mais">Leia mais</a>
                </div>
                <div class="child3">
                    <h2 class="subtitulocard">Categorias</h2>
                    <ul class="list">
                        <li>Jogos</li>
                        <li>Celular</li>
                        <li>Informática</li>
                        <li>Eletrônicos</li>
                        <li>Jogos</li>
                    </ul>
                </div>
                <div class="foot">
                    <h2 class="direitos">Todos os direitos reservados</h2>
                </div>
            </div>
        </main>
    </body>
</html>

**
CSS
body{
    background-color:rgb(242, 243, 243);
}
header {
	text-align: center;
	background: rgb(244,180,4);
	padding: 5px 0;
    font-family: 'Exo 2', sans-serif;
}
.logopreto{
    font-size: 100px;
    font-weight: bold;
    padding-top: 10px;
    font-family: 'Exo 2', sans-serif;
}
.logobranco{
    font-size: 100px;
    font-weight: bold;
    padding-top: 16px;
    color: #ffffff;
}
.caixasuperior nav{
	margin: 20px;
	padding: 5px;
	text-align: center;
}
nav {
    margin: 1em;
	padding: 20px 20px;
	top: 110px;
	right: 0;
}
nav li {
	display: inline;
	margin: 0 15px 0 15px;
}
nav a {
	color: #ffffff;
	font-size: 16px;
	text-decoration: none;
}
nav a:hover {
	color: rgb(244,180,4);
	text-decoration: none;
    padding: 10px;
    background-color: rgb(252, 252, 250);
}
 /*Card*/   
.corpo{
    display: block;
    margin-left: auto;
    margin-right: auto;
    max-width: 924px;
}
.container{
    flex-wrap: wrap;
    width:1060px;
    padding:10px;
    display:flex;
}
.child{
    max-width: 645px;
    background-color: rgb(255, 254, 254);
	margin-top: 1em;
	padding:15px;
}
.child2{
    height: 70%;
    width: 300px;
    background-color: rgb(255, 254, 254);
    margin: 1em;
    padding:15px;
}
.child3{
    height: 70%;
    width: 300px;
    background-color: rgb(255, 254, 254);
    margin: 1em;
    padding:15px;
    margin-top: -205px;
}
.subtitulocard {
    font-family: 'Exo 2', sans-serif;
	margin: 3px 1px 1px 1px;
	padding: 5px;
	background: #cacece;
	color:rgb(83, 85, 85);
}
.titulocard {
	font-weight: bold;
	font-size: 24px;
	margin-left: 3px 0 0 0; 
	padding-bottom: 2px;
	color:rgb(244,180,4)
}
.postagem{
    font-family: 'Exo 2', sans-serif;
	font-size: 15px;
	margin-left: 5px 2px 0 15px;
    padding: 0 0 1em 0;
}
.margim{
    padding: 1px 0 5px;
    font-family: 'Exo 2', sans-serif;
}
.list, .leia{
    font-family: 'Exo 2', sans-serif;
	background: #ffffff;
	color:rgb(244,180,4);
	padding: 1px;
	list-style: none;
    text-decoration: none;
}
.traco{
	border: 1px dashed #000;
    color:rgb(145, 148, 148);
}
.imagem{
    max-width: 645px;
}
.foot{
    font-family: 'Exo 2', sans-serif;
    margin: 1em 0;
    width:1005px;
	height: 20px;
	Background: #cacece;
	text-align: center;
	padding: 10px;
}
/*media query*/
@media (min-width:440px) and (max-width: 900px){
    .container{
        flex-direction: column;
    }
    .logopreto{
        font-size: 70px;
        font-weight: bold;
        padding-top: 10px;
        font-family: 'Exo 2', sans-serif;
    }
    .logobranco{
        font-size: 70px;
        font-weight: bold;
        padding-top: 13px;
        color: #ffffff;
    }
      nav a {
        color: #ffffff;
        font-size: 13px;
        text-decoration: none;
    }
    nav a:hover {
        color: rgb(244,180,4);
        text-decoration: none;
        padding: 8px;
        background-color: rgb(252, 252, 250);
    }
    .child2, .child3 {
        width: 645px;
        background-color: rgb(255, 254, 254);
        padding:15px;
        margin-left: -2px;
    }
    .child2 {
        margin-top: 30px;
    }
    .child3 {
        margin-top: 30px;
    }
    .foot{
        font-family: 'Exo 2', sans-serif;
        margin: 1em 0;
        width:653px;
        height: 20px;
        Background: #cacece;
        text-align: center;
        padding: 10px;
    }
}
