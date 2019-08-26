#Site
Em html5 + css3
<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Mr. DOCTOR - Seu espaço de saúde</title>
		<link rel="icon" href="img/doctor classic update 2019.jpg">        
        <!-- GOOGLE ICONS -->
		<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
        <!-- FONT AWESOME -->
        <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
		<!-- MATERIALIZE CSS -->		
		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.100.2/css/materialize.min.css">
		<!-- CUSTOM CSS -->
		<link rel="stylesheet" href="css/custom.css">
	</head>
	<body>
    
    <!-- HEADER -->
	<header>
	    <!-- MENU MOBILE -->
		<ul class="side-nav" id="menu-mobile">
			<li><a class="hide-menu" href="#home">Home</a></li>
			<li><a class="hide-menu" href="#sobre">Sobre o Mr. DOCTOR</a></li>
			<li><a class="hide-menu" href="#servicos">Serviços</a></li>
			<li><a class="hide-menu" href="#contato">Contato</a></li>
		</ul>

	    <div class="navbar-fixed">
		<nav class="navbar z-depth-0">
			<div class="nav-wrapper container">
				<h1 class="logo_text">Mr. DOCTOR - Seu espaço de saúde </h1>
				<a href=""><img class="logo_img"  src="img/doctor classic update 2019.jpg" class="circle responsive-img" alt="Centro Boa Forma"></a>

				<ul class="right light hide-on-med-and-down">
					<li><a href="#home">Home</a></li>
					<li><a href="#sobre">Sobre o Mr. DOCTOR</a></li>
					<li><a href="#servicos">Serviços</a></li>
					<li><a href="#contato">Contato</a></li>
				</ul>			

				<a href="#" data-activates="menu-mobile" class="button-collapse right"><i class="material-icons">menu</i></a>
			</div>
		</nav>
		</div>
	</header>
    
    <!-- HOME -->
    <section class="home bloco scrollspy" id="home">
    	<div class="row container">
    		<div class="col s12 center">
    			<h2 class="">O melhor espaço para cuidar da sua saúde!</h2>
    			<p class="light">Um novo conceito em prevenção, promoção e valorização da saúde para quem 
                    busca o melhor. Quer experimentar?</p>
    			<div class="row">
    				<a href="#sobre" class="btn btn-large blue-logo"> Sobre nós </a>
    				<a href="#contato" class="btn btn-large white black-text"> Contato </a>
    			</div>
    		</div>
    	</div>
    </section>

    <!-- SOBRE -->
    <section class="sobre bloco scrollspy" id="sobre">
    	<div class="row container">
    		<div class="col s12 center">
    			<h2 class="light titulo">Sobre nós</h2>
    		</div>

    		<div class="col s12 l6">
    			<p class="light">
    		     A Mr. DOCTOR chegou a Monte Mor e região trazendo um novo conceito
			     em prevenção, promoção e valorização da saúde. Localizada no centro da cidade, 
			     conta com fácil estacionamento, salas amplas e climatizadas, ambiente confortável 
			     e seguro aos seus usuários. Suas instalações foram projetadas e equipadas sob medida,
			     dentro dos padrões de acessibilidade, para acolher principalmente pessoas com limitações funcionais.   
			     O centro dispõe de uma equipe profissional qualificada e com experiência no mercado, prezando sempre por
			     tratamentos individualizados e baseados em evidências científicas.
    			</p>
    		</div>

    		<div class="col s12 l6">
    			<div class="carousel carousel-slider" data-indicators="true">
    				<a href="#" class="carousel-item">
    					<img alt="Imagem institucional" src="img/parceirosmedicos.jpeg">
    				</a>

    				<a href="#" class="carousel-item">
    					<img alt="Imagem institucional" src="img/parceiros (1).jpeg">
    				</a>

    				<a href="#" class="carousel-item">
    					<img alt="Imagem institucional" src="img/quemsomos.jpeg">
    				</a>
    			</div>
    		</div>

    	</div>

    	<div class="row blue-logo missao-visao-valores">
    		<div class="container">
    			<article class="item col s12 m4 center">
    				<span class="icon"><i class="material-icons medium">directions_run</i></span>
    				<h3 class="light">Missão</h3>
    				<p class="light">Promover a saúde e bem-estar dos clientes com ações de prevenção, promoção e reabilitação,através de tratamentos eficazes e humanizados em Fisioterapia e suas vertentes.</p>    				
    			</article>

    			<article class="item col s12 m4 center">
    				<span class="icon"><i class="material-icons medium">visibility</i></span>
    				<h3 class="light">Visão</h3>
    				<p class="light">Tornar-se referência no cenário estadual, buscando a excelência dos serviços prestados, além de promover o desenvolvimento técnico-científico de sua equipe e da sociedade.</p>   				
    			</article>

    			<article class="item col s12 m4 center">
    				<span class="icon"><i class="material-icons medium">grade</i></span>
    				<h3 class="light">Valores</h3>
    				<p class="light">
    					 • Agir com ética frente aos clientes e colaboradores.<br>
    					 • Tornar o ambiente de trabalho o mais familiar possível.<br>
    					 • Priorizar a qualidade e excelência do atendimento, valorizando e qualificando a equipe. 
    				</p>    				
    			</article>
    		</div>
    	</div>
    </section>

    <!-- SERVIÇOS -->
    <section class="servicos bloco scrollspy" id="servicos">
    	<div class="row container">
    		<div class="col s12 center">
    			<h2 class="light titulo white-text"> Serviços </h2>
    			<p class="light paragrafo white-text">  Suas instalações foram projetadas e equipadas sob medida, 
                    dentro dos padrões de acessibilidade, para acolher principalmente pessoas com limitações funcionais. 
                    A clínica dispõe de uma equipe profissional qualificada e com experiência no mercado,
                     prezando sempre por tratamentos individualizados e baseados em evidências científicas.</p>
    		</div>
    	</div> 

    	<div class="row container">    	
    	    <!-- PILATES -->
    		<article class="col s12 m6 l3">
    			<div class="card">
    				<div class="card-image">
    					<img src="img/serviços.jpeg" alt="clinicoGeral" class="materialboxed">
    					<a href="#clinico-modal" class="btn btn-floating halfway-fab blue-logo modal-trigger">
    						<i class="material-icons">more_horiz</i>
    					</a>    				
    				</div>
    				<div class="card-content">
    					<h3 class="card-title"> Clínico Geral </h3>
    					<p class="light"> O Clínico Geral por ser o profissional responsável por servir à comunidade... </p>
    				</div>
    			</div>    			
    		</article>

    		<!-- MODAL CLINICO -->
    		<div class="modal" id="clinico-modal">
    			<div class="modal-content">
    				<h5 class="light"> O que é um clinico geral? </h5>
    				<p class="light black-text"> O Clínico Geral por ser o profissional responsável por servir à comunidade, auxiliando na prevenção e cura de doenças se relaciona com toda área da saúde. </p>
    				<h5 class="light"> O que faz uma Clínico Geral? </h5>
    				<ul class="collection">
    					<li class="collection-item">Tem conhecimento aprofundado de todos os orgãos e aparelhos do corpo humano;</li>
    					<li class="collection-item">Faz diagnósticos;</li>
    					<li class="collection-item">Pede exames;</li>
    					<li class="collection-item">Prescreve medicamentos; </li>
                        <li class="collection-item">Realiza cirurgias;</li>
    				</ul>
    			</div>

    			<div class="modal-footer">
    				<a class="btn blue-logo modal-action modal-close"> Sair </a>
    			</div>
    		</div>
            
            <!-- NUTRIÇÃO -->
    		<article class="col s12 m6 l3">
    			<div class="card">
    				<div class="card-image">
    					<img src="img/nutricao.jpg" alt="Nutrição" class="materialboxed">
    					<a href="#nutricao-modal" class="btn btn-floating halfway-fab blue-logo modal-trigger">
    						<i class="material-icons">more_horiz</i>
    					</a>    				
    				</div>
    				<div class="card-content">
    					<h3 class="card-title"> Nutrição </h3>
    					<p class="light"> Ele planeja, administra e coordena programas de alimentação e nutrição em empresas, escolas... </p>
    				</div>
    			</div>    			
    		</article>

    		<!-- MODAL NUTRIÇÃO -->
    		<div class="modal" id="nutricao-modal">
    			<div class="modal-content">
                    <h5 class="light"> Qual a importância da nutrição? </h5>
                    <p class="light black-text"> Seja por um estilo de vida saudável ou para eliminar peso, a preocupação com os alimentos é constante na rotina das pessoas. Por isso é importante saber comer e dar relevância ao que se come. Uma nutrição adequada pode prevenir doenças e tornar a vida mais saudável. </p>
    			</div>

    			<div class="modal-footer">
                    <a class="btn blue-logo modal-action modal-close"> Sair </a>
    			</div>
    		</div>

            
            <!-- FISIOTERAPIA -->
    		<article class="col s12 m6 l3">
    			<div class="card">
    				<div class="card-image">
    					<img src="img/fisioterapia.jpg" alt="Fisioterapia" class="materialboxed">
    					<a class="btn btn-floating halfway-fab blue-logo">
    						<i class="material-icons">more_horiz</i>
    					</a>    				
    				</div>
    				<div class="card-content">
    					<h3 class="card-title"> Fisioterapia </h3>
    					<p class="light">O fisioterapeuta trata e previne doenças e lesões, empregando técnicas... </p>
    				</div>
    			</div>    			
    		</article>
            
            <!-- GINECOLOGIA E OBSTETRÍCIA -->
    		<article class="col s12 m6 l3">
    			<div class="card">
    				<div class="card-image">
    					<img src="img/Gineco.jpg" alt="Gineco" class="materialboxed">
    					<a class="btn btn-floating halfway-fab blue-logo">
    						<i class="material-icons">more_horiz</i>
    					</a>    				
    				</div>
    				<div class="card-content">
    					<h3 class="card-title"> Ginecologia e  Obstetrícia </h3>
    					<p class="light"> O atendimento Ginecológico e Obstétrico especializado... </p>
    				</div>
    			</div>    			
    		</article>

            <!-- BOTÃO QUADRO DE HORÁRIOS -->
            <div class="row center btn-horario">
                <a href="#horarios-modal" class="btn btn-large blue-logo modal-trigger"><i class="material-icons left">timer</i> Quadro de horários </a>
            </div>

            <!-- MODAL QUADRO DE HORÁRIOS -->
            <div class="modal" id="horarios-modal">
                <div class="modal-content">
                    <h5 class="light">Quadro de horários</h5>

                    <ul class="tabs">
                        <li class="tab col s3"><a class="active" href="#tabela-clinico">Clínico Geral</a></li>
                        <li class="tab col s3"><a href="#tabela-fisio">Fisioterapia</a></li>
                        <li class="tab col s3"><a href="#tabela-nutricao">Nutrição</a></li>
                        <li class="tab col s3"><a href="#tabela-gineco">Ginecologia e Obstetrícia</a></li>
                    </ul>

                    <!-- TABELA CLINICO GERAL -->
                    <table class="striped responsive-table" id="tabela-clinico">
                        <thead>
                            <tr>
                                <th></th>
                                <th>Segunda</th>
                                <th>Terça</th>
                                <th>Quarta</th>
                                <th>Quinta</th>
                                <th>Sexta</th>
                                <th>Sábado</th>
                                <th>Domingo</th>
                            </tr>                            
                        </thead>

                        <tbody>
                            <tr>
                                <td>6:00 às 12:00</td> 
                                <td>Clinico</td>
                                <td></td>
                                <td>Clinico</td>
                                <td></td>
                                <td>Clinico</td>
                                <td>Clinico</td>
                                <td></td>                               
                            </tr> 

                            <tr>
                                <td>12:00 às 22:00</td> 
                                <td></td>
                                <td>Clinico</td>
                                <td></td>
                                <td>Clinico</td>
                                <td></td>
                                <td></td>
                                <td></td>                               
                            </tr>                           
                        </tbody>                        
                    </table>

                    <!-- TABELA FISIOTERAPIA -->
                    <table class="striped responsive-table" id="tabela-fisio">
                            <thead>
                                <tr>
                                    <th></th>
                                    <th>Segunda</th>
                                    <th>Terça</th>
                                    <th>Quarta</th>
                                    <th>Quinta</th>
                                    <th>Sexta</th>
                                    <th>Sábado</th>
                                    <th>Domingo</th>
                                </tr>                            
                            </thead>
    
                            <tbody>
                                <tr>
                                    <td>8:00 às 10:00</td> 
                                    <td>Fisioterapia</td>
                                    <td>Fisioterapia</td>
                                    <td></td>
                                    <td></td>
                                    <td>Fisioterapia</td>
                                    <td>Fisioterapia</td>
                                    <td></td>                               
                                </tr> 
    
                                <tr>
                                    <td>10:00 às 19:00</td> 
                                    <td></td>
                                    <td></td>
                                    <td>Fisioterapia</td>
                                    <td>Fisioterapia</td>
                                    <td></td>
                                    <td></td>
                                    <td></td>                               
                                </tr>                           
                            </tbody>                        
                        </table>                    
                        
                    <!-- TABELA NUTRIÇÃO -->
                        <table class="striped responsive-table" id="tabela-nutricao">
                                <thead>
                                    <tr>
                                        <th></th>
                                        <th>Segunda</th>
                                        <th>Terça</th>
                                        <th>Quarta</th>
                                        <th>Quinta</th>
                                        <th>Sexta</th>
                                        <th>Sábado</th>
                                        <th>Domingo</th>
                                    </tr>                            
                                </thead>
        
                                <tbody>
                                    <tr>
                                        <td>8:00 às 11:00</td> 
                                        <td>Nutrição</td>
                                        <td></td>
                                        <td>Nutrição</td>
                                        <td></td>
                                        <td>Nutrição</td>
                                        <td></td>
                                        <td></td>                               
                                    </tr> 
        
                                    <tr>
                                        <td>12:00 às 22:00</td> 
                                        <td></td>
                                        <td>Nutrição</td>
                                        <td></td>
                                        <td>Nutrição</td>
                                        <td></td>
                                        <td></td>
                                        <td></td>                               
                                    </tr>                           
                                </tbody>                        
                            </table>


                    <!-- TABELA GINECO -->
                    <table class="striped responsive-table" id="tabela-gineco">
                        <thead>
                            <tr>
                                <th></th>
                                <th>Segunda</th>
                                <th>Terça</th>
                                <th>Quarta</th>
                                <th>Quinta</th>
                                <th>Sexta</th>
                                <th>Sábado</th>
                                <th>Domingo</th>
                            </tr>                            
                        </thead>

                        <tbody>
                            <tr>
                                <td>6:00 às 13:00</td> 
                                <td>Ginecologia e Obstetrícia</td>
                                <td></td>
                                <td>Ginecologia e Obstetrícia</td>
                                <td></td>
                                <td>Ginecologia e Obstetrícia</td>
                                <td>Ginecologia e Obstetrícia</td>
                                <td></td>                               
                            </tr> 

                            <tr>
                                <td>12:00 às 22:00</td> 
                                <td></td>
                                <td>Ginecologia e Obstetrícia</td>
                                <td></td>
                                <td>Ginecologia e Obstetrícia</td>
                                <td></td>
                                <td></td>
                                <td></td>                               
                            </tr>                           
                        </tbody>                        
                    </table>


                </div>
                <div class="modal-footer">
                </div>
            </div>

    	</div>   	
    </section>

    <!-- CONTATO -->
    <section class="contato bloco scrollspy" id="contato">
        <div class="row container">
            <div class="col s12 center">
                <h2 class="titulo light black-text"> Contato </h2>
            </div>

           <div class="col s12 m6 l4 hide-on-med-only ">
                <div class="mapa transparent">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5195.859054685209!2d-47.31261102893339!3d-22.949226410414582!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94c8a5478e43da95%3A0x1c29757df0969e13!2sMonte%20Mor%20-%20SP%2C%2013190-000!5e0!3m2!1spt-BR!2sbr!4v1566790695040!5m2!1spt-BR!2sbr" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen=""></iframe>
                </div>
           </div>

           <div class="col s12 m6 l4">
                <div class="informacoes white-text">
                    <h4> Redes sociais </h4>
                    <p class="light"> Fique por dentro das novidades, receba dicas, ou simplesmente mostre ao mundo que você faz parte desse projeto sensacional! </p>
                    <a href="#" class="btn-floating blue-logo"><i class="fa fa-facebook"></i></a>
                    <a href="#" class="btn-floating blue-logo"><i class="fa fa-google"></i></a>
                    <a href="#" class="btn-floating blue-logo"><i class="fa fa-twitter"></i></a>

                    <h4> Endereço </h4>
                    <p class="light"> Rua Eduardo Scaranello Filho, 29 <br>
                    Centro, Monte Mor - SP</p>

                    <h4> Contatos </h4>
                    <p class="light">
                        (73) 123456987 <br>
                        (45) 123456789 <br>
                        (56) 234567678 
                    </p>

                </div>
           </div>

           <div class="col s12 m6 l4">
                <div class="formulario white black-text">
                    <h4> Fale conosco </h4>
                    <p class="light">  Dúvidas, criticas ou sujestões? Entre em contato conosco, seu feedback é muito importante. </p>

                    <form action="enviar-email.php" method="post">

                        <div class="input-field">
                            <input type="text" name="name" id="name">
                            <label for="name">Seu nome</label>
                        </div>

                        <div class="input-field">
                            <input type="email" name="email" id="email">
                            <label for="email">Seu email</label>
                        </div>

                        <div class="input-field">
                            <input type="text" name="subject" id="subject">
                            <label for="subject">Assunto</label>
                        </div>

                        <div class="input-field">
                            <textarea id="message" name="message" class="materialize-textarea"></textarea>
                            <label for="message">Mensagem</label>
                        </div>

                        <button class="btn blue-logo" type="submit"> Enviar </button>

                    </form>
                </div>
           </div>

        </div>
    </section>

    <!-- DEPOIMENTOS -->
    <div class="depoimentos blue-logo">
        <div class="row container">
            <div class="col s12 center">
                <h2 class="titulo white-text light">Depoimentos</h2>
            </div>

            <div class="col s12 m4 center">
                <img src="img/depo1.jpg" class="circle responsive-img" alt="Depoimento um">
                <p class="light white-text"> "Conheci o atendimento nutricional da Mr. DOCTOR por indicação de um amigo. Execelentes profissionais e super atenciosos!"</p>
                <h4 class="light white-text">Felipe Brito</h4>
                <p class="white-text">
                    <i class="material-icons">star</i>
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i>  
                </p>
            </div>

            <div class="col s12 m4 center">
                <img src="img/depo2.jpg" class="circle responsive-img" alt="Depoimento de Bruno">
                <p class="light white-text"> "Gostei muito da Fisioterapia, superou minhas expectativas. A empresa e os profissionais foram ótimos!"</p>
                <h4 class="light white-text">Marcos Valério</h4>
                <p class="white-text">
                    <i class="material-icons">star</i>
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i>  
                </p>
            </div>

            <div class="col s12 m4 center">
                <img src="img/depo3.jpg" class="circle responsive-img" alt="Depoimento um">
                <p class="light white-text"> "Amei o atendimento personalizado e humanizado obtidos são esses os motivos que me conquistaram e me mantém no Mr. DOCTOR."</p>
                <h4 class="light white-text">Maria Joaquina</h4>
                <p class="white-text">
                    <i class="material-icons">star</i>
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i> 
                    <i class="material-icons">star</i>  
                </p>
            </div>

        </div>
    </div>

    <!-- RODAPÉ -->
    <footer class="rodape">
        <div class="row container center">
            <img src="img/doctor classic update 2019.jpg" class="logo_img">
            <p class="light dark-text">© Mr. DOCTOR 2019 - Todos os direitos reservados </p>
        </div>        
    </footer>
	
    
    <!-- JQUERY -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>

	<!-- MATERIALIZE JS -->
	<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.100.2/js/materialize.min.js"></script>

	<!-- JAVASCRIPT -->
	<script>
	    // INICIALIZAÇÃO 
		$(document).ready(function(){
        	// MENU MOBILE
        	$(".button-collapse").sideNav();
        	// LINK INTERNO
        	$(".scrollspy").scrollSpy({
        		scrollOffset: 0
        	});
        	// CAROUSEL
        	$(".carousel.carousel-slider").carousel({
        		fullWidth:true
        	});
        	// MODAL
        	$(".modal").modal();
            // TABS
            $("ul.tabs").tabs();
            // ESCONDER MENU AO CLICAR
            $(".hide-menu").click(function(){
                $(".button-collapse").sideNav("hide");
            });
            // AUTOPLAY
            function autoplay() {
                $(".carousel").carousel("next");
                setTimeout(autoplay, 4500);
            }

            autoplay();

		});        
        // ADICIONANDO NAVCOLOR
		$(window).on("scroll", function(){
			if($(window).scrollTop() > 100) {
				$(".navbar").addClass("nav-color");
			} else {
				$(".navbar").removeClass("nav-color");
			}
		});
    </script>
        <?php
            if(isset($_GET['status']));
                if(isset($_GET['status']=="sucesso"):
                    echo "<script>Materialize.toast('Enviado com sucesso!',4000);</script>";
                else;
                    echo"<script>Materialize.toast('Erro ao enviar', 4000);</script>";
                endif;
            endif;
        ?>
	</body>
</html>
