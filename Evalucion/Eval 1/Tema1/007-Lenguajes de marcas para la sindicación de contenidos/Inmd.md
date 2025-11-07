# Indroduccion brece y contexalizacion




# Desarrollo técnico correcto y preciso
## HTML
### Despues de crear una gile `index.html` voy a hacer una pagina
### Código básico para una estructura de do
```
<!doctype html>
<html lang="es">
  <head>
    <!-- Añade tu contenido aquí -->
  </head>
  <body>
    <!-- Añade tu contenido aquí -->
  </body>
</html>
```
### Esribo `head` en que guardo configuraciones y enlaces necesarios para que la página funcione y se vea bien, pero no muestra contenido en la pantalla.
```
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portafolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
```
### Esribo `<body>` que es contiene todo lo que se muestra en la pantalla: encabezado, menú, contenido principal y pie de página
```
<body>
    <header>Encabezado</header>
    <nav>Menú Navegación</nav>
    <main>
        <section class="item">Sección 1</section>
        <section class="item">Sección 2</section>
        <section class="item">Sección 3</section>
    </main>
    <footer>Pie de página</footer>
</body>
```

# Codigo completa
## HTML

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Curriculum</title>
    <style>
        html{background-color: grey;font-family: sans-serif;font-size: 11px;}
        body{
            width: 700px;background: white;margin: auto;
            display: flex;
        }
        #izquierda_botom {flex:1;background-color:#333a49;padding: 20px; color: white;}
        #izquierda_botom img{width: 120px;border-radius: 10px;}
        #izquierda_botom ul {list-style-type: none;padding-left: 5px;}
        #izquierda_botom a{color:white; text-decoration:none;}

        #derecha{flex:3;padding: 20px;background-color: rgb(97, 157, 212);}
        #derecha h1{margin-bottom: 5px;}
        #derecha p{padding-left: 5px;}
        #derecha hr{border: 1px solid black;}
    </style>
</head>

<body>

<section id="izquierda_botom">
    <img src="descarga.jfif" alt="Foto">

    <h3>Contacto</h3>
    <hr>
    <ul>
        <li>Número de teléfono</li>
        <p>645573661</p>
        <li>Email</li>
        <p>Sidorenko.bohdan.05@gmail.com</p>
        <li>Dirección</li>
        <p>Valencia Malvarrosa</p>
        <li><a href="https://github.com/Sagmanua">Github</a></li>
        <p>Repositorio con proyectos</p>
    </ul>

    <h3>Idiomas</h3>
    <hr>
    <ul>
        <li>Ucraniano (Nativo)</li>
        <li>Ruso (Nativo)</li>
        <li>Español (Medio)</li>
        <li>Inglés (Medio)</li>
    </ul>
</section>

<section id="derecha">
    <h1>Bohdan Sydorenko</h1>
    <h2>Full Stack Developer</h2>
    <p>Soy estudiante de DAW. Me considero una persona responsable,
       organizada y con ganas de aprender. Busco mi primera experiencia laboral.</p>

    <h3>Educación</h3>
    <hr>
    <ul>
        <li>2025 - Actualidad</li>
        <p>Desarrollo de Aplicaciones Multiplataforma</p>
    </ul>

    <h3>Experiencia</h3>
    <hr>
    <ul>
        <li>Voluntario en Educación Infantil</li>
        <p>Organización y apoyo en actividades para niños.</p>
    </ul>

    <h3>Habilidades</h3>
    <hr>
    <ul>
        <li>Python</li>
        <li>Java</li>
        <li>MySQL</li>
        <li>HTML</li>
        <li>CSS</li>
    </ul>
</section>

</body>
</html>

```

# 4.-Cierre/Conclusión enlazando con la unidad

