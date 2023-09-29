<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

# Actividad: Aplicando estilos con selectores CSS

### El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado 
  
 ```html
 <header>
  ```

- Tres párrafos 
  
```html
  <p>
```

- Una imagen
   
```html
   <img>
  ```

- Un pie de página
   
```html
<footer>
```

- Aplica los siguientes estilos usando selectores de etiqueta:

Color rojo a los encabezados 

```html
<h1>
```
Color azul a los párrafos 

```html
<p>
```
Borde grueso negro a la imagen 

```html
<img>
```

### Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
  
- Tamaño de fuente grande a los elementos con la clase ".grande"
  
### Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"
- Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un

```html
<div>
```
Centrar el contenido de la sección

```html
 <section>
```
<!-- Su documentación aquí -->

# Solución
__________________________

```html

<!DOCTYPE html>
<html>

<head>
    <title>Creando Estilos Con Css</title>
    <link rel="stylesheet" href="index.css">
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: rgb(245, 248, 231);
            margin: 0;
            padding: 0;
        }
        #e1{color: blue;}
    </style>
</head>

<body>
    <header>
        <h1 style="color: red;">LOBOS</h1>
    </header>
    <div class="container">

        <p id="e1">El lobo, más conocido con el nombre científico de Canis Lupus es un mamífero placentario del orden de los
            carnívoros. Los lobos siempre han sido objeto de la leyenda debido a su aullido, el cual usan para
            comunicarse. Un lobo solitario puede aullar para atraer la atención de su manada del mismo modo que los
            aullidos de una manada pueden actuar como mensajes territoriales entre varias de ellas. </p> <br>

        <p id="e1">Los lobos se agrupan en manadas de entre 6 y 20 animales y generalmente dirigida por una pareja reproductora
            y dominante. Son animales muy inteligentes que viven organizados en manadas, que por lo general no suelen
            superar los quince o veinte miembros como máximo, y cuya estructura jerárquica está muy marcada. </p><br>

        <p id="e1">Viven entre seis y ocho años. Las manadas suelen tener un comportamiento territorial, cubriendo alrededor de
            200 kilómetros cuadrados. Evitan los lindes de su propio territorio para no tener encuentros en ocasiones
            muy agresivos con las demás manadas. </p>
        </div>
        <div>
            <h3>Lobo Blanco</h3>
            <img src="https://firebasestorage.googleapis.com/v0/b/evidencias1-7176a.appspot.com/o/lobo_blanco.jpg?alt=media&token=6bb81c34-0cbb-4ddc-9bd6-e2469fc9e595&_gl=1*aapr4l*_ga*MzUyNzg5MDg5LjE2OTQ3Mzg1Mjk.*_ga_CW55HF8NVT*MTY5NjAxMjYxMi44LjEuMTY5NjAxMjcxNC4xOC4wLjA." alt="lobo_blanco" width="500" style="border: 2px solid black;">
        </div>
        <br>
        <div>
            <h3>Lobo Gris</h3>
            <img src="https://firebasestorage.googleapis.com/v0/b/evidencias1-7176a.appspot.com/o/lobo_gris.jpg?alt=media&token=c52b037a-1b61-4cf8-a7c8-20569527ea62&_gl=1*jysp58*_ga*MzUyNzg5MDg5LjE2OTQ3Mzg1Mjk.*_ga_CW55HF8NVT*MTY5NjAxMjYxMi44LjEuMTY5NjAxMjc1OS42MC4wLjA." alt="lobo_gris" width="400" style="border: 2px solid black;">
        </div>

        <footer>
            <p>Julio Cesar Torres °2023</p>
        </footer>
       

</body>

</html>
```
________________
________________

## css externo

_________________
_________________

```css
footer {background-color: aquamarine;
text-align: center;
padding: 10;}

```



