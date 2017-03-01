# CV-2017
Html Curriculum Vitae
<!DOCTYPE html>
<html>
	<head>
		<title>CV 2017</title>
		<link rel="stylesheet" type="text/css" href="style.css">
		<link href="https://fonts.googleapis.com/css?family=Arsenal" rel="stylesheet">
		<style>
			*{
				box-sizing: border-box;
			}

			body{
				margin:0;
				padding:0;
			}

			h1, h2, h3, h4, h5, h6, p, ul, li{
				margin:0;
				padding:0;
				color:blue;
				font-family: 'Arsenal', sans-serif;
			}

			hr{
				border:1px dashed blue;
			}

			ul li{
				list-style-type:none;
				margin-left:60px;
				margin-right:40px;
				margin-top:20px;
			}

			img{
				float:right;
				width:30%;	
			}

			.img_desc{
				background-color:white;
				color:blue;
				height:260px;
				padding-left:40px;
				padding-top:20px;
				padding-bottom:20px;
				padding-right:20px;
				
			}

			/*
			.img_desc p, .img_desc h1, .img_desc h4{
				position:absolute;
				float:left;
			} 

			.img_desc h1{
				/*margin-top:300px;
				margin-left:40px;
			}

			.img_desc h4{
				margin-left:40px;
				
			}	*/

			.title{
					position:relative;
					width:100%;
					height:100px;
					background-color:#eee;
					/*border:1px solid blue;*/
			}

			.container{
				margin:0;
				padding:0;
				width:100%;
				background-color: #eee;
			}

			.personal_info, .education, .work_experience, .footer, .img_desc, .text_intro{
				max-width:600px;
				margin:0px auto;
				background-color:white;
				/*border-bottom:5px solid #737373;*/
			}

			.education, .work_experience, .footer, .skills, .personal_info, .text_intro{
				margin-top:20px;
			}

			.personal_info{
				max-height:2000px;
				background-color:blue;
			}

			.personal_info hr{
				border:1px dashed white;
			}

			.skills p, .skills h1, .skills h3{
				color:white;
			}

			.personal_info p{
				font-size:20px;
			}

			.feed{
				font-size:1px;
				color:transparent;
			}

			.text_intro{
				background-color:#eee;
			}

			.text_intro p{
				padding:40px;
				font-size:30px;
			}

			.skills{
				position:relative;
				top:0px;
				clear:left;
				color:white;
			}

			.skills p, .skills h1, .skills h3{
				padding:0 40px;
			}

			.bar{
				height:20px; 
				width:80%; 
				border-radius:10px; 
				background-color:white;
				text-align:center;
				margin-left:40px;
			}

			.bar2{
				position:relative;
				height:20px; 
				border-radius:10px; 
				background-color:#a6a6a6;
				
			}

			.bar p {
				font-size:12px;
				font-weight:bold;
				padding-top:2px; 
				color:white;
			}

			.education{
				max-height:800px;
			}

			.education h1, .education h3, .education p{
				margin: 0 40px;
			}

			.work_experience{
				max-height:5000px;
			}

			.work_experience h1, .work_experience h2, .work_experience h3, .work_experience p{
				margin: 0 40px;
			}

			.footer{
				text-align:center;
				background-color:blue;
				max-height:500px;
			}

			.footer hr{
				border:1px dashed white;
			}

			.footer p{
				margin-bottom:20px;
			}

			.footer a{
				text-decoration:none;
				color:white;
				font-weight:bold;
			}
			.footer a:hover{
				color:black;
			}
		</style>	
	</head>
	<body>
	<p class="feed">Gostaria de me apresentar.</p>
		<div class="container">
			<div class="img_desc">
					<img src="me_cv_blue.svg"/>
					
					<h1>Cláudia <br> Loureiro</h1>
					<br>
					<br>
					<!--<h4>Ilustradora</h4>
					<h4>Web-designer</h4>-->
					
					
					<h4>Lisboa, Portugal</h4>
					
					<h4>966544070</h4>
					<br>
					<br>
					<br>
					<br>
			</div>
			<div class="text_intro">
				<p>Sou <b>Ilustradora</b> ultimamente dedicada ao <b>desenho vectorial</b> e recentemente à área do <b>web-design</b>. </p>
			</div>
			<div class="personal_info">
				
				
				<div class="skills">
					<br>
					<h1>Capacidades</h1>
					<br>
					<h3>Photoshop</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:60%;"><p>60%</p></div>
					</div>
					<br>
					<h3>Illustrator</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:80%;"><p>80%</p></div>
					</div>
					<br>
					<h3>Html</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:60%;"><p>60%</p></div>
					</div>
					<br>
					<h3>Css</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:50%;"><p>50%</p></div>
					</div>
					<br>
					<br>
					<hr>
					<br>
					<br>
					<h1>Idiomas</h1>
					<br>
					<h3>Português</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:90%;"><p>90%</p></div>
					</div>
					<br>
					<h3>Inglês</h3>
					<br>
					<div class="bar">
						<div class="bar2" style="width:60%;"><p>60%</p></div>
					</div>					
				</div>
				<br>
				<br>
				<br>
			</div>
			<div class="text_intro">
				<p>Tenho a ambição de ser cada vez melhor enquanto <b>Ilustradora</b> e <b>Designer</b>, por isso estou sempre disponível para aprender. </p>
			</div>
			
			<div class="education">
				<div class="title">
					<br>
					<br>
					<h1>Educação</h1>
				</div>
				<br>
				<h3>Artes da BD e Ilustração - ESAP Guimarães</h3>
				<br>
				<p>SET 2008</p>
				<br>
				<p>Licenciatura</p>
				
				<br>
				<hr/>
				<br>
				<h3>Workshop de Vector, Illustrator and Inkscape - Mother Volcano</h3>
				<br>
				<p>OUT 2013</p>
				<br>
				<p>Grau de Especialização</p>
				<br>
				<hr/>
				<br>
				<h3>Programação - Citeforma, Lda.</h3>
				<br>
				<p>SET 2015 - JUN 2016</p>
				<br>
				<p>Formação nível 4(CQEP)</p>
				<br>
				<hr/>
				<br>
				<h3>Programação - W3schools</h3>
				<br>
				<p>SET 2016</p>
				<br>
				<p>Especialização</p>
				<br>
				<br>
				<br>
			</div>
			<div class="text_intro">
				<p>Estas são a experiências que tenho adquirido. Quero arrecadar muitas mais e gostava que a <b>WORKMI Studio Design</b> podesse vir a ser uma delas.</p>
			</div>
			<div class="work_experience">
				<div class="title">
				<br>
				<br>
				<h1>Work Experience</h1>
				</div>
				<br>
				<br>
				<h2>Illustradora & Designer Freelancer<h1>
				
				<h3>2011</h3>
				<br>
				<ul>
					<li><b>Ilustradora</b>, Exposição colectiva de ilustração "Não Tenho ideias amanhã mando mais...", Estaleiro Cultural Velha-a-Branca, Braga.</li>
					<li><b>Designer</b> do cartaz e <b>Ilustradora</b> convidada na Exposição colectiva de ilustração "Crash sem Cash", Casa da Animação, Porto.</li>
				</ul>
				<br>
				<br>
				<hr>
				<br>
				<h3>2012 - 2013</h3>
				<br>
				<ul>
					<li><b>Designer Gráfica</b>, cartazes e flyers, Fleemarket, Aveiro.</li>
					<li><b>Formadora</b> no workshop de desenho de observação, Loja Canto Do Baú, Aveiro.</li>
					<li><b>Formadora</b> workshop de Serigrafia, UA-DECA, Aveiro.</li>
					<li><b>Assistente</b> de organização de feira de ilustração "Alôine", Preparação do Espaço, Loja Canto do Baú, Aveiro.</li>
					<li><b>Assistente</b> de organização de feira de ilustração "Alôine", Preparação do Espaço, Loja Canto do Baú, Aveiro.</li>
					<li><b>Assistente de vendas</b> de feira de ilustração itenerante "Farrapeira", venda da ilustrações, Mercado Negro, Aveiro.</li>
				</ul>
				<br>
				<br>
				<hr/>
				<br/>
				<h3>2014</h3>
				<br>
				<ul>
					<li><b>Design e Ilustradora</b>, banner, cartazes e montras. Campanha do dia dos namorais, CMStore24, Lisboa.</li>
					<li><b>Ilustradora</b> ilustração editorial, Afonso Henriques de bicicleta, Revista Gerador nº4, Lisboa.</li>
				</ul>
				<br>
				<br>
				<hr/>
				<br/>
				<h3>2015</h3>
				<br>
				<ul>
					<li><b>Design e Programação</b>, E-book "Livros digitais em bibliotecas públicas", Vera Maria da Silva, Lisboa.</li>
					<li><b>Ilustradora</b>, projecto "Paragens que o tempo habita", Câmara Municipal Guimarães.</li>
				</ul>
				<br>
				<br>
				<hr>
				<br>
				<h3>2016</h3>
				<br>
				<ul>
					<li><b>Ilustradora</b>, capa da revista "Quireward" nº2, Lisboa.</li>
					<li><b>Designer</b>, Material de marketing digital, designbinário, Lisboa.</li>
				</ul>
				<br>
				<br>
				<br>
				
			</div>
			<div class="text_intro">
				<p>Estou convicta que terei o empenho, a creatividade, o profissionalismo, e a capacidade de desenvolver soluções que procuram.</p>
			</div>
			<div class="footer">
				<br>
				<br>
				<p style="color:white;">O meu trabalho online:</p>
				<p style="color:white;"><a href="http://www.workofclaudia.tumblr.com" target="_blank">Tumblr</a> & <a href="http://www.behance.com/claudialoureiro" target="_blank">Behance</a></p>
				<br>
				<hr>
				<br>
				<p style="color:white;">Obrigada pela a vossa atenção! :)</p>
				<p style="color:white;">O Meu Contacto: <a href="mailto:claudiarsloureiro.il@gmail.com">claudiarsloureiro.il@gmail.com</a></p>
				<br>
				<br>
			</div>
		</div>
	</body>
</html>
