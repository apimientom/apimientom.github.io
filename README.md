<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Leonidas Esteban</title>
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
	<link rel="icon" type="image/png" href="./images/logo.png"/>
	<link rel="stylesheet" href="./css/index.css">
</head>
<body>
	<!-- Barra de navegacion -->
	<header class="navbar container">
		<figure class="navbar-logo">
			<img class="navbar-logo-imagen" src="./images/logo.png" alt="Logo de Leonidas Esteban">
			<p class="navbar-logo-nombre">Leonidas Esteban</p>
		</figure>
		<nav class="navbar-menu">
			<a href="#portafolio" class="navbar-menu-link">Portafolio</a>
			<a href="#experiencias" class="navbar-menu-link">Experiencia</a>
			<a href="#contactos" class="navbar-menu-link">Trabajemos juntos</a>
		</nav>
	</header>

	<!-- Seccion de Portada -->
	<section class="hero container">
		<h1 class="hero-titulo">
			Hola! Soy <span>Leonidas Esteban</span><br>
			Desarrollador <span>Javascript</span> con<br>
			Pasión por la <span>Enseñanza</span>
		</h1>
		<figure class="hero-imagen-container">
			<div class="hero-border-imagen"></div>
			<img class="hero-imagen" src="./images/hero.png" alt="Imagen de Leonidas Esteban">
		</figure>
	</section>
	
	<!-- Seccion de Portafolio -->
	<section id="portafolio" class="portafolio container">
		<div class="container-adorno"></div>
		<div class="container-titulo">
			<div class="titulo-adorno"></div>
			<p class="titulo-texto">Portafolio ( Proyectos Destacados )</p>
		</div>
		<article class="portafolio-proyecto">
			<div class="proyecto-informacion">
				<h2 class="informacion-titulo">Platzi Video</h2>
				<p class="informacion-subtitulo">React Native / React</p>
				<p class="informacion-fecha">Fecha: <span>01/07/2018</span></p>
				<p class="informacion-link">Puedes verlo en: <a href="www.platzi.com/native" target="_blank">www.platzi.com/native</a></p>
				<p class="informacion-descripcion">Platzi Video fue el resultado de 3 meses de trabajo para crear la mejor app para enseñar el funcionamiento de React y React Native. Desde crear un vista detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
			</div>
			<figure class="proyecto-imagen-container">
				<img class="proyecto-imagen" src="./images/platzi-video.png" alt="Imagen del Proyecto">
			</figure>
		</article>
		<!-- <article class="portafolio-proyecto">
			<div class="proyecto-informacion">
				<h2 class="informacion-titulo">Platzi Video</h2>
				<p class="informacion-subtitulo">React Native / React</p>
				<p class="informacion-fecha">Fecha: <span>01/07/2018</span></p>
				<p class="informacion-link">Puedes verlo en: <a href="www.platzi.com/native" target="_blank">www.platzi.com/native</a></p>
				<p class="informacion-descripcion">Platzi Video fue el resultado de 3 meses de trabajo para crear la mejor app para enseñar el funcionamiento de React y React Native. Desde crear un vista detalle, hasta patrones avanzados de nevegación, este proyecto ha sido el ejemplo de futuros creadores de aplicaciones multiplataforma</p>
			</div>
			<figure class="proyecto-imagen-container">
				<img class="proyecto-imagen" src="./images/platzi-video.png" alt="Imagen del Proyecto">
			</figure>
		</article> -->
	</section>

	<!-- Seccion de Experiencias -->
	<section id="experiencias" class="experiencias container">
		<div class="container-adorno"></div>
		<div class="container-titulo">
			<div class="titulo-adorno"></div>
			<p class="titulo-texto">Mas sobre mi experiencia</p>
		</div>
		<div class="experiencias-galeria">
			<article class="galeria-experiencia">
				<figure class="experiencia-multimedia-container">
					<img class="experiencia-multimedia" src="./images/platzi-conf.png" alt="Imagen de PlatziConf">
				</figure>
				<div class="experiencia-contenido">
					<h2 class="contenido-titulo">PlatziConf México 2018</h2>
					<p class="contenido-descripcion">Un evento para gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="contenido-link">Ver Plática</a>
				</div>
			</article>

			<article class="galeria-experiencia">
				<figure class="experiencia-multimedia-container">
					<img class="experiencia-multimedia" src="./images/frontend.png" alt="Imagen de PlatziConf">
				</figure>
				<div class="experiencia-contenido">
					<h2 class="contenido-titulo">2do Lugar Master Frontend</h2>
					<p class="contenido-descripcion">Un evento donde pruebas ser el mejor frontend solo usando tus reflejos y memoria. Sin internet, sin stackoverflow, adrenalina pura.</p>
					<a class="contenido-link">Ver Plática</a>
				</div>
			</article>

			<!-- <article class="galeria-experiencia">
				<figure class="experiencia-multimedia-container">
					<img class="experiencia-multimedia" src="./images/frontend.png" alt="Imagen de PlatziConf">
				</figure>
				<div class="experiencia-contenido">
					<h2 class="contenido-titulo">2do Lugar Master Frontend</h2>
					<p class="contenido-descripcion">Un evento donde pruebas ser el mejor frontend solo usando tus reflejos y memoria. Sin internet, sin stackoverflow, adrenalina pura.</p>
					<a class="contenido-link">Ver Plática</a>
				</div>
			</article>
			<article class="galeria-experiencia">
				<figure class="experiencia-multimedia-container">
					<img class="experiencia-multimedia" src="./images/platzi-conf.png" alt="Imagen de PlatziConf">
				</figure>
				<div class="experiencia-contenido">
					<h2 class="contenido-titulo">PlatziConf México 2018</h2>
					<p class="contenido-descripcion">Un evento para gente que quiere aprender más de internet. En esté evento te comparto como tener una vida de constante aprendizaje.</p>
					<a class="contenido-link">Ver Plática</a>
				</div>
			</article> -->
		</div>
	</section>

	<!-- Seccion de Conocimientos -->
	<section class="conocimientos container">
		<div class="container-adorno"></div>
		<div class="conocimientos-grilla">
			<div class="conocimientos-columna">
				<div class="conocimientos-elemento"><p>NodeJS</p><p>React Native</p></div>
				<div class="conocimientos-elemento"><p>React</p></div>
				<div class="conocimientos-elemento"><p>Project Manager</p><p>Stylus</p></div>
				<div class="conocimientos-elemento"><p>JavaScript</p></div>
				<div class="conocimientos-elemento"><p>Project Manager</p><p>Stylus</p></div>
				<div class="conocimientos-elemento"><p>JavaScript</p></div>
			</div>
			<figure class="conocimientos-leonidas-container">
				<img class="conocimientos-leonidas" src="./images/leonidas.png" alt="Imagen de Leonidas Esteban">
			</figure>
			<div class="conocimientos-columna">
				<div class="conocimientos-elemento"><p>Profesor</p><p>Conferencista</p></div>
				<div class="conocimientos-elemento"><p>Bilingue</p></div>
				<div class="conocimientos-elemento"><p>Maestro Pokemon</p><p>Escritor</p></div>
				<div class="conocimientos-elemento"><p>React Native</p></div>
				<div class="conocimientos-elemento"><p>React</p><p>Maestro Pokemon</p></div>
				<div class="conocimientos-elemento"><p>React</p></div>
			</div>
		</div>
	</section>

	<!-- Seccion de Contacto -->
	<section id="contactos" class="contactos container">
		<div class="container-adorno"></div>
		<div class="contactos-grilla">
			<form class="contactos-formulario">
				<div class="container-titulo">
					<div class="titulo-adorno"></div>
					<p class="titulo-texto">¿Creamos algo juntos?</p>
				</div>
				<input class="formulario-input" type="text" placeholder="Dejame tu email">
				<button class="formulario-boton">Enviar</button>
			</form>
			<div class="contactos-redes">
				<a href="https://twitter.com/leonidasesteban" target="_blank"><i class="icono fab fa-twitter"></i></a>
				<a href="https://www.facebook.com/LeonidasEsteban" target="_blank"><i class="icono fab fa-facebook"></i></a>
				<a href="https://github.com/LeonidasEsteban" target="_blank"><i class="icono fab fa-github"></i></a>
				<a href="https://www.instagram.com/leonidasesteban/" target="_blank"><i class="icono fab fa-instagram"></i></a>
			</div>
		</div>
	</section>

	<!-- Pie de Pagina -->
	<footer class="footer container">
		<p class="footer-agradecimientos">
			Curso de Desarrollo Web Online 2018 &nbsp;&nbsp;• 
			<img src="./images/platzi.png" alt="Logo Platzi">
		</p>
		<p class="footer-dedicatoria">
			Designed with ❤ by 
			<a href="https://twitter.com/thespianartist?lang=es" target="_blank">@thespianartist</a>
		</p>
	</footer>
</body>
</html>

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
