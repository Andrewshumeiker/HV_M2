# HV_M2
This repository is for the training of week 1 module 2
# CSS
```css
./* === RESET GENERAL === */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* === CUERPO Y FUENTE === */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f3e5f5; /* lavanda suave */
  color: #3e1f47;
  line-height: 1.6;
}

/* === BARRA DE NAVEGACIÓN === */
.navbar {
  background-color: #6a1b9a; /* morado oscuro */
  padding: 1em 2em;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
}

.navbar ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 3em;
}

.navbar a {
  color: #ffffff;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s ease;
}

.navbar a:hover {
  color: #d1c4e9; /* lavanda claro */
}

/* === ENCABEZADO PRINCIPAL === */
.main-header {
  background-color: #7b1fa2; /* púrpura intermedio */
  color: white;
  text-align: center;
  padding: 2.5em 1em;
}

.main-img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #f3e5f5;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
  margin-bottom: 1em;
}

.main-info h1 {
  font-size: 2em;
}

.main-info p {
  font-style: italic;
  font-size: 1.1em;
}

/* === CONTENEDOR PRINCIPAL === */
.container {
  max-width: 1100px;
  margin: auto;
  padding: 2em;
  display: flex;
  flex-wrap: wrap;
  gap: 2em;
}

/* === SECCIÓN LATERAL (INFORMACIÓN PERSONAL) === */
.sidebar {
  flex: 1;
  min-width: 300px;
}

/* === SECCIÓN PRINCIPAL (DESCRIPCIÓN, PROYECTOS...) === */
.main-content {
  flex: 2;
  min-width: 500px;
}

/* === CAJAS DE CONTENIDO === */
.box {
  background: linear-gradient(to bottom, #ce93d8, #e1bee7, #f3e5f5); /* degradado morado claro */
  border-radius: 12px;
  padding: 1.5em;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
  margin-bottom: 2em;
}

/* === TÍTULOS Y SUBTÍTULOS === */
h2 {
  border-bottom: 2px solid #6a1b9a;
  padding-bottom: 0.4em;
  margin-bottom: 1em;
  color: #4a148c;
}

h3 {
  color: #6a1b9a;
  margin-top: 1.5em;
}

/* === LISTAS Y TEXTOS === */
ul {
  padding-left: 1.5em;
}

li {
  margin-bottom: 0.5em;
}

```
#HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio Andrés Covaleda</title>
  <link rel="stylesheet" href="prueba.css" />
</head>
<body>

  <!-- Barra de navegación superior -->
  <nav class="navbar">
    <ul>
      <li><a href="#info-personal">Información Personal</a></li>
      <li><a href="#proyectos">Proyectos</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- Sección principal del perfil -->
  <header class="main-header">
    <img src="./images/raf,360x360,075,t,fafafa_ca443f4786.jpg" alt="Foto de perfil" class="main-img" />
    <div class="main-info">
      <h1>Andrés David Covaleda Vargas</h1>
      <p>Desarrollador de Software</p>
    </div>
  </header>

  <!-- Contenido principal en 2 columnas -->
  <div class="container" style="display: flex; flex-wrap: wrap; gap: 20px;">

    <!-- Columna lateral con datos personales -->
    <div style="flex: 1 1 300px;" id="info-personal">
      <div class="box">
        <h2>Sobre mí</h2>

        <!-- Información académica -->
        <div>
          <h3>Estudios</h3>
          <b>Bachillerato Académico</b><br>
          <small>IEM Santiago Pérez<br>17 de Febrero de 2014 - 06 de Diciembre 2019</small><br><br>
          <b>Ingeniería Mecatrónica</b><br>
          <small>Escuela de Ingeniería de Antioquia<br>Desde el 20 de junio de 2020</small>
        </div>

        <!-- Logros -->
        <div>
          <h3>Logros</h3>
          <ul>
            <li>Nominación a líder de la comunidad</li>
            <li>Rol de contralor en el bachillerato</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Columna principal con experiencia y proyectos -->
    <div style="flex: 2 1 600px;">
      <div class="box">
        <!-- Descripción -->
        <h2>Perfil Profesional</h2>
        <p>
          Estudiante de séptimo semestre de Ingeniería Mecatrónica en la Universidad EIA. Apasionado por la inteligencia artificial y el desarrollo de tecnologías emergentes. Experiencia en análisis de datos, automatización y aprendizaje de máquina. Busco aplicar mis conocimientos en un entorno desafiante que me permita contribuir al desarrollo y mejora de modelos IA.
        </p>

        <!-- Habilidades -->
        <h2>Experiencia y Habilidades</h2>
        <ul>
          <li>Modelado matemático, análisis numérico y sistemas de control.</li>
          <li>Python, MATLAB, C++, JavaScript.</li>
          <li>Machine Learning, redes neuronales, procesamiento de datos.</li>
          <li>Sensores, actuadores, robótica y electrónica aplicada.</li>
          <li>Bases de datos, visualización y minería de datos.</li>
          <li>Español (nativo), Inglés (intermedio-avanzado).</li>
        </ul>

        <!-- Proyectos -->
        <h2 id="proyectos">Proyectos</h2>
        <ul>
          <li>Analista de datos para entrenamiento de IA.</li>
          <li>Redes neuronales para clasificación de imágenes.</li>
          <li>Automatización de sistemas mecatrónicos.</li>
          <li>Simulación de sistemas robóticos en MATLAB/Simulink.</li>
        </ul>

        <!-- Contacto -->
        <h2 id="contacto">Contacto</h2>
        <p>
          Teléfono: 3012562331<br>
          Email: andrescovaleda07@hotmail.com
        </p>

        <!-- Referencias -->
        <h2>Referencias</h2>
        <p>Disponibles a solicitud.</p>
      </div>
    </div>
  </div>

</body>
</html>


```
# Version 2
```css
/* General: Establece fuente base y color de fondo para toda la página */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f5f5f5;
  margin: 0;
  padding: 0;
  color: #333;
}

/* Contenedor general para centrar el contenido */
.container {
  max-width: 960px;
  margin: 0 auto;
  padding: 20px;
}

/* Estilo para títulos principales */
h1, h2 {
  color: #4a4a4a;
  text-align: center;
  margin-bottom: 1em;
}

/* Imagen redonda (usualmente para foto de perfil) */
.img {
  width: 200px;
  border-radius: 50%;
  aspect-ratio: 1;
  object-fit: cover;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.25);
  display: block;
  margin: 0 auto 1em auto;
}

/* Caja estética para secciones individuales */
.box {
  background: linear-gradient(180deg, #ffffff, #f0f0f0);
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  padding: 20px;
  margin: 20px 0;
}

/* Alternativa con color más llamativo para destacar */
.shadowbox {
  background: linear-gradient(180deg, #7f5af0, #f2545b, #f4f4f4);
  border-radius: 12px;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  padding: 20px;
  color: #fff;
}

/* Sección de contacto con inputs */
.contact-form {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.contact-form input,
.contact-form textarea {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 8px;
  font-size: 1em;
  resize: vertical;
}

.contact-form button {
  padding: 10px;
  border: none;
  border-radius: 8px;
  background-color: #7f5af0;
  color: #fff;
  cursor: pointer;
  transition: background 0.3s ease;
}

.contact-form button:hover {
  background-color: #693ee5;
}

/* Estilo para lista de proyectos */
.projects ul {
  list-style: none;
  padding: 0;
}

.projects li {
  background-color: #fff;
  margin: 10px 0;
  padding: 12px 16px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

```
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio Andrés Covaleda</title>
  <link rel="stylesheet" href="prueba.css">
</head>
<body>

  <!-- Contenedor principal -->
  <div class="container" style="display: flex; flex-wrap: wrap; gap: 20px;">

    <!-- Columna lateral con datos personales -->
    <div style="flex: 1 1 300px;">
      <div class="box">

        <!-- Foto de perfil -->
        <img src="./images/raf,360x360,075,t,fafafa_ca443f4786.jpg" alt="Foto de perfil" class="img">

        <!-- Información de contacto -->
        <div>
          <h3>Contacto</h3>
          <p>
            Teléfono: 3012562331<br>
            Email: andrescovaleda07@hotmail.com
          </p>
        </div>

        <!-- Información académica -->
        <div>
          <h3>Estudios</h3>
          <b>Bachillerato Académico</b><br>
          <small>IEM Santiago Pérez<br>17 de Febrero de 2014 - 06 de Diciembre 2019</small><br><br>
          <b>Ingeniería Mecatrónica</b><br>
          <small>Escuela de Ingeniería de Antioquia<br>Desde el 20 de junio de 2020</small>
        </div>

        <!-- Logros -->
        <div>
          <h3>Logros</h3>
          <ul>
            <li>Nominación a líder de la comunidad</li>
            <li>Rol de contralor en el bachillerato</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Columna principal con descripción profesional -->
    <div style="flex: 2 1 600px;">
      <div class="box">
        <!-- Nombre principal -->
        <h1>Andrés David Covaleda Vargas</h1>

        <!-- Título profesional -->
        <h3>Asesor de servicio al cliente</h3>
        <p>
          Estudiante de séptimo semestre de Ingeniería Mecatrónica en la Universidad EIA, con habilidades en matemáticas, física, programación y resolución de problemas técnicos. Apasionado por la inteligencia artificial y el desarrollo de tecnologías emergentes, con experiencia en análisis de datos, automatización y aprendizaje de máquina. Busco aplicar mis conocimientos en un entorno desafiante que me permita contribuir al desarrollo y corrección de modelos IA.
        </p>

        <!-- Experiencia y habilidades -->
        <h2>Experiencia y Habilidades</h2>
        <h3>Universidad</h3>
        <ul>
          <li>Matemáticas y Física: Modelado matemático, análisis numérico, dinámica y sistemas de control.</li>
          <li>Programación: Python, MATLAB, C++, JavaScript. Experiencia en desarrollo de algoritmos y optimización de código.</li>
          <li>Inteligencia Artificial: Machine Learning, redes neuronales, procesamiento de datos y optimización de modelos.</li>
          <li>Automatización y Control: Sensores, actuadores, robótica y electrónica aplicada.</li>
          <li>Análisis de Datos: Bases de datos, visualización y minería de datos.</li>
          <li>Idiomas: Español (nativo), Inglés (intermedio-avanzado).</li>
        </ul>

        <!-- Proyectos -->
        <h3>Proyectos</h3>
        <ul>
          <li>Analista y validador de datos para entrenar modelos de inteligencia artificial.</li>
          <li>Implementación de redes neuronales para clasificación de imágenes y análisis de patrones.</li>
          <li>Diseño e integración de sensores para sistemas de automatización.</li>
          <li>Simulación de sistemas robóticos en MATLAB y Simulink.</li>
        </ul>

        <!-- Referencias (puedes agregar nombres y contactos si lo deseas) -->
        <h2>Referencias</h2>
        <p>Disponibles a solicitud.</p>
      </div>
    </div>
  </div>

</body>
</html>
```
