<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 1 


# Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

## Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto
  
  ___
  ___
  # Solución

  ## Acerca 

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Sobre nosotros</title>
</head>

<body>

    <header>
        <h1>Sobre nosotros</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="contact.html">Contacto</a>
    </nav>

    <section>
        <h2>Historia</h2>
        <p>Fundada en 2010...</p>

        <article>
            <h3>Misión y visión</h3>
            <p>Nuestra misión es...</p>
        </article>

    </section>

    <footer>
        <p>copyright 2023 - Juan Perez</p>
    </footer>

</body>
</html>
```
___

## Contacto

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>contacto</title>
</head>

<body>

    <header>
        <h1>contacto</h1>
    </header>

    <nav>
        <a href="index.html">inicio</a>
        <a href="about.html">acerca</a>
    </nav>

    <main>

<form>
    <label for="nombre">nombre:</label>
    <input type="text" id="nombre"><br>

    <label for="email">email:</label>
    <input type="imail" id="email"><br>

    <label for="mensaje">mensaje:</label><br>
    <textarea id="mensaje"></textarea><br>

    <input type="submit" value="enviar">
</form>

<aside>
    <h3>ubicacion</h3>
    <p>calle falsa 123</p>
</aside>

    </main>
    
    <footer>
        <p>Copiright 2023 - juan perez</p>
    </footer>

</body>

</html>
```
___

## Index

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>mi primer sitio web</title>
</head>
<body>
 <header>
    <h1>mi sitio web</h1>
 </header> 
 <nav>
    <a href="about.html">acerca</a>
    <a href="contact.html">contacto</a>
 </nav> 
 <main>
    <p>bienvenidos a mi sitio sobre empresas xyz</p>
    <p>aqui encontraran informacion sobre nuestros productos y servicios</p>
 </main>
 <footer>
    <p>copyright 2023 - juan perez</p>
    <p>juanperez@gmail.com</p>
 </footer>
</body>
</html>
```





