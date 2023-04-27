# MenuPHP

Menu con php, formulario de usuario y una operacion a eleccion del usuario

1.En el primer arcivo Programa1, tenemos un archivo php con codigo html en el que usamos un formulario y adentro una tabla donde le preguntamos  al usuario sus datos y usamos el atributo "name" para guardar los datos y el action del form lo enviamos hacia Operaciones.php

2.En este archivo traemos los datos que guardaron los formularios de la pagina de Programa1, usamos la funcion echo para imprimir los datos ingresados, creamos las variables que van a almacenar los datos traidos con $_REQUEST y entre corchetes ponemos el nombre que tenia el imput en la pagina principal

3.creamos la funcion calcular donde retornaremos el resultado de la operacion que el usuario escogio, con un condicional switch, que evalua la variable operacion que pide la funcion para poder retornar, dependiendo del resultado, el condicional buscara la opcion que elegio el usuario,  y retornara la operacion

4.luego de la funcion declaramos las variables que necestamos para la operacion y usamos $_REQUEST y entre corchetes el nombre del campo del que queremos traer los datos

5.usamos la funcion echo para imprimir en pantalla la funcion calcular, pasandonle como parametro las variables que declaramos de numero, operacion y numero2

6. por ultimo un boton para regresar a la pagina anterior

![imagen](https://user-images.githubusercontent.com/104031898/234883957-3a7b4dcc-2b0e-4441-a494-4e021855710b.png)
