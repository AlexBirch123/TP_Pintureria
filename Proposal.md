<h1><strong>Propuesta TP DSW </strong></h1>


<br>

<h3>Grupo</h3>

Integrantes

49847 - Birchmeyer, Alex

47286 - Battista, Jonatan

<br>



<h3>Repositorios</h3>


* [frontend app](https://github.com/AlexBirch123/Rio-Color-Pintureria---Frontend-/tree/master)


* [backend app](https://github.com/jonibattista/Pintureria-Back-main/tree/master)


<hr>

<h3>Tema:  “Sistema para pinturería” </h3>

<strong>Descripción </strong>

El sistema se encargará de proveer servicios para una pinturería familiar con múltiples sucursales. Servirá como un sistema de gestión interno para realizar el control de stock, actualización de precios y administración de los productos que se encuentren a la venta. También, le otorgará al cliente la posibilidad de acceder a un listado de los productos que se encuentran disponibles.


<br>
<bold>
 Modelo


Alcance Funcional
</bold>



[Pintureria DC.drawio.pdf](https://github.com/AlexBirch123/TP_Pintureria/blob/main/Pintureria%20DC.drawio.pdf)







<table>
    <tbody>
        <tr>
            <th rowspan="7">CRUD SIMPLE</th>
            <td>CRUD Sucursal</td>
        </tr>
        <tr>
            <td>CRUD Usuario</td>
        </tr>
        <tr>
            <td>CRUD Cliente</td>
        </tr>
        <tr>
            <td>CRUD Producto</td>
        </tr>
         <tr>
            <td>CRUD Empleado</td>
        </tr>
         <tr>
            <td>CRUD Proveedor</td>
        </tr>
     <tr>
            <td>CRUD Categoria</td>
        </tr>
        <tr>
            <th rowspan="2">CRUD DEPENDIENTE</th>
            <td>CRUD Venta {depende de} CRUD Producto , CRUD usuario , CRUD Cliente, CRUD Empleado</td>
        </tr>
        <tr>
            <td>CRUD Renglon {depende de} CRUD Venta</td>
        </tr>
        <tr>
        <tr>
            <th rowspan="7">LISTADO + DETALLE</th>
            <td>Listado de productos filtrado por titulo de producto,codigo SKU, proveedor o categoria , muestra producto, precio y una previsualizacion para muestra al publico => detalle CRUD Producto</td>
        </tr>
        <tr>
            <td>Listado de ventas filtrado por rango de fecha, muestra venta, cliente, id de venta y total => detalle muestra datos completos de la venta, cliente, renglones .</td>
        </tr>
        <tr>
            <td>Listado de clientes, muestra datos cliente, filtrado por nombre o dni=> CRUD Cliente</td>
        </tr>
      <tr>
            <td>Listado de sucursales, muestra datos sucursales, filtrado por direccion y telefono => CRUD Sucursal</td>
        </tr>
     <tr>
            <td>Listado de empleado, muestra datos empleado, filtrado por direccion, telefono y nombre => CRUD Empleado</td>
        </tr>
     <tr>
            <td>Listado de proveedores, muestra datos proveedor, filtrado por cuit, telefono y nombre => CRUD Proveedor</td>
        </tr>
     <tr>
            <td>Listado de usuarios, muestra datos usuario, filtrado por email, username y role => CRUD Usuario</td>
        </tr>
        <tr>
            <th rowspan="7">CUU/EPIC</th>
            <td>Realizar la compra de un producto.</td>
        </tr>
        <tr>
            <td>Realizar una venta.</td>
        </tr>
        <tr>
            <td>Actualización de stock de un producto.</td>
        </tr>
       <tr>
            <td>Ingresar un producto.</td>
        </tr>
      <tr>
            <td>Ingresar un cliente</td>
        </tr>
      <tr>
            <td>Ingresar un proveedor</td>
        </tr>
      <tr>
            <td>crear usuario.</td>
        </tr>
     <tr>
            <td>Usuario realiza compra por carrito</td>
        </tr>
        <tr>
            <th>OTROS</th>
            <td>Enviar mail de recuperacion de cuenta al usuario</td>
        </tr>
    </tbody>
</table>

 
<strong>Primer CRUD a presentar:</strong>
CRUD Sucursal
