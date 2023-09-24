<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

# Actividad: Crear una tabla HTML con información sobre productos.
### Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación
  
Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

! [tabla](![Alt text](image.png) )

_____
_____

``````` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="uft-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <h1></h1>
    <table border="10" align="6" cellpadding="20" cellspacing="10" valign="5"></table>
    <thead>
        <tr>
            <th>Codigo</th>
            <th>Nombre</th>
            <th colspan="7">Descripcion</th>
            <th>Stock</th>
            <th>Precio</th>
            <th>Fecha De <br>Creacion</th>
        </tr>
    </thead>
</body>
</html>
