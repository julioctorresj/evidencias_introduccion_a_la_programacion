<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
# Actividad: Diseñar un formulario de pedido de un producto

#### Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1.  Crear un nuevo documento HTML.

2. Crear un formulario con los siguientes campos:
   
   - Nombre del producto
   - Cantidad
   - Precio unitario
   - Precio total
   - Dirección de envío
   - Información de contacto (nombre, correo electrónico, número de teléfono)
  
3. Agregar los siguientes campos relacionados al formulario:

   - Método de pago
   - Fecha de entrega
   - Comentarios
  4. Utilizar las etiquetas HTML apropiados para cada campo.
   _____
   # Solución
   _____
   ``````html
   <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form action="">
        <h1>Formulario</h1>

        <div>
            <label for="iddeproducto">Nombre Del Producto</label>
            <input type="text" id="iddeproducto">
        </div>
        <br>
        <div>
            <label for="idcantidad">Cantidad</label>
            <input type="number" id="idcantidad">
        </div>
        <br>
        <div>
            <label for="idpreciounitario">Precio Unitario</label>
            <input type="number" id="idpreciounitario">
        </div>
        <br>
        <div>
            <label for="idpreciototal">Precio Total</label>
            <input type="number" id="idpreciototal">
        </div>
        <br>
        <div>
            <label for="iddirecciondeenvio">Direccion De Envio</label>
            <input type="text" id="iddirecciondeenvio">
        </div>
        <br>
        <h1> <b>Informacion De Contacto</b></h1>

        <div>
            <label for="idnombre">Nombre</label>
            <input type="text" id="idnombre">
        </div>
        <br>
        <div>
            <label for="idcorreoelectronico">Correo Electronico</label>
            <input type="email" id="idcoreoelectronico">
            <input type="submit" value="Enviar">
        </div>
        <br>
        <div>
            <label for="idnumerodetelefono">Numero De Telefono</label>
            <input type="tel" id="idnumerodetelefono" placeholder="Numero de Telefono">
        </div>
        <br>
        <h1><b>Metodos De Pago</b></h1>
        <div>
            <label for="idtarjetadecredito">Tarjeta De Credito</label>
            <input type="radio" id="idtarjetadecredito" name="Pagos">
            <br>
            <label for="idtarjetadecredito">Tarjeta Debito</label>
            <input type="radio" id="idtarjetadebito" name="Pagos">
        </div>
        <br>
        <div>
            <label for="fecha">Fecha De Entrega</label>
            <input type="date" id="fecha"> 
        </div>
        <br>
        <h1> <b>Comentarios</b></h1>
        <div>
            <textarea name="Comentarios" id="Comentarios" maxlength="260" placeholder="Ingrese Aqui Sus Comentarios" cols="30" rows="10"></textarea>
        </div>
</body>

</html>
``````





