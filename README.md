# HV_M2
This repository is for the training of week 1 module 2
# CSS
```css
.shadowbox {
  width: 17em;
  border: 0px solid #333;
  box-shadow: px 8px 5px #444;
  padding: 8px 12px;
  background-image: linear-gradient(180deg, #b4b4b4, #b4b4b4, #b4b4b4);
}
.box{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    width: 17em;
    border-radius: 10px;
    box-shadow: 0px -1px 0px -3px rgba(0,0,0,0.75);
    -webkit-box-shadow: 0px -1px 0px -3px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px -1px 0px -3px rgba(0,0,0,0.75);
    background-image: linear-gradient(180deg, #9f78e6, #ad6464, #b4b4b4);
    
}
.img{
  width: 200px;
  border-radius: 50%;
  aspect-ratio: 1;
  object-fit: cover;
}
```
#HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=
    , initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="prueba.css">
</head>
<body>
    <div style="display: flex;">
        <div style="justify-content: start; width:     300px ;">
            <div class="box"style ="height:2000px" >
                    <img src="./images/raf,360x360,075,t,fafafa_ca443f4786.jpg" alt="" style="width:180 px; height : 180px;"class="img";>
                    <div>   
                        <div>
                            <h3>Contacto</h3>
                                <p>
                                    Telefono : 3012562331
                                    <br>
                                        Email: andrescovaleda07@hotmail.com
                                        </p>
                        </div>   
                        <div>
                            <h3>Estudios</h3>
                                <b>Bachillerato Académico 
                                </b>
                                    <br>
                                    <small>
                                        IEM Santiago Perez <br>
                                        17 de Febrero de 2014 a 06 de Diciembre 2019           
                                    </small> <br>
                                    <b>
                                    Ingenieria mecatronica </b><br>
                                    <small>
                                    Escuela de Ingenieria de Antioquia  <br>
                                    20 de junio de 2020, presente.
                                 </small>
                        </div>
                        <div>
                            <h3>
                                Logros
                            </h3>
                            <ul>
                                <li>
                                    Nominación para lider de la comunidad
                                </li>
                                <li>
                                    Rol de contralor en el bachillerato
                                </li>
                            </ul>
                        </div>
                    </div>
                    
            </div>
        </div>
        <div style="justify-content:end; width: 550px">
            <h1>Andrés David Covaleda Vargas</h1>
            <div>
                <h3>
                    Asesor de servicio al cliente
                </h3>
                    <p>Estudiante de séptimo semestre de ingenieria mecatronica en la universidad EIA, con habilidades en matemáticas, física, programación y resolución de problemas técnicos. Apasionado por la inteligencia artifical y el desarrollo de tecnologías emergentes, con experiencia en análisis de datos, automatización y aprendizaje de máquina. Busco aplicar mis conocimientos en un entorno desafiante que me permita contribuir al desarrollo y correción de modelos IA.</p>
                </div>
                <div>
                    <h2>
                    Experiencia y Habilidades
                    <h3>
                        Universidad
                    </h3>
                        <ul>
                        <li>Matemáticas y Física: Modelado matemático, análisis numérico, dinámica y sistemas de control.
                        </li>
                        <li>Programación: Python, MATLAB, C++, JavaScript. Experiencia en desarrollo de algoritmos y optimización de código.
                        </li>    
                        <li>Inteligencia Artificial: Conceptos de machine learning, redes neuronales, procesamiento de datos y optimización de modelos.
                        </li>
                        <li>Automatización y Control: Sensores, actuadores, robótica y electrónica aplicada.
                        </li>
                        <li>    
                        Análisis de Datos: Manejo de bases de datos, visualización y técnicas de minería de datos.
                        </li>
                            
                        <li>Idiomas: Español (nativo), Inglés (intermedio-avanzado).
                        </li>
                        </ul>

                    <h3>
                        Proyectos  
                    </h3>
                        <p><ul>
                            <li>Analista y Validador de Datos: Experiencia en revisión y corrección de datos utilizados para entrenar modelos de inteligencia artificial.</li>
                            <li>Desarrollo de Algoritmos de IA: Implementación de redes neuronales para clasificación de imágenes y análisis de patrones en datos.</li>
                            <li>Automatización de Sistemas Mecatrónicos: Diseño e integración de sensores en proyectos de control y automatización.</li>
                            <li>
                            Simulación de Sistemas Dinámicos: Modelado y análisis de sistemas robóticos en MATLAB y Simulink.
                        </li>
                        </ul>
                        </p>
                    <div>
                        <h2> Referencias
                            
                        </h2>
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
