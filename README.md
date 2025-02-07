# Parcial 2 POO

## Punto 1 Patrón de arquitectura.

La aplicación fue ordenada segun lo explicado en clase en diferentes paquetes, uno dedicado a la logica del programa, otro para la conexion con la DB de firebase, otra para la view (GUI) y por ultimo uno para la clase main que es la que sera ejecutada.

 ![image](https://github.com/user-attachments/assets/cafbea5d-1b80-471b-81f2-8243c8fc222d)

## Punto 1 "La implementación de las clases para la autenticación como administrativo"

Se agrega la clase "Autenticacion" en el paquete de "Logic" para guardar los datos de autenticacion.

![image](https://github.com/user-attachments/assets/41bf801d-5f33-4740-926c-18e0f1db91f9)

Y en la clase "InterfazGrafica" se agrega un "JOptionPane" para que se realize la autenticación antes de ejecutar.

![image](https://github.com/user-attachments/assets/bbfaad66-6e3e-4b04-a1a3-2b5aa5ffaf69)

Pantallas de Log In

![image](https://github.com/user-attachments/assets/72aa99d2-ccbc-4c46-b375-af9b682bbf0e) // ![image](https://github.com/user-attachments/assets/5a3a497f-01d6-449c-90ab-f90ec4c4d065)




Si esta falla, por usuario o clave incorrecta se mostrara el siguiente pop up y terminara el programa.

![image](https://github.com/user-attachments/assets/20b759d0-5a01-44f2-9982-44a5a2c8aec7)

## Punto 2 Un menú de opciones por ventana que permita verificar los siguientes procesos: 1. Listar las unidades en bodega. 2. Ingreso y modificación de productos.

Despues de haber autenticado se despliega el siguiente menu;

![image](https://github.com/user-attachments/assets/c5c60329-8a18-4cb7-8ff8-036ba6194401)

### Listar unidades en la bodega (desde la DB)

![image](https://github.com/user-attachments/assets/ddf7cc94-7c5c-4156-a893-fb58c02e97b2)

### Modificacion e Ingreso de productos

Al seleccionar editar un producto se despliega este menu, se tiene que ingresar un producto existente

![image](https://github.com/user-attachments/assets/fdb20adb-d9be-4564-bd6c-ce3e54ca1a17)

Se pide su precio si quiere ser modificado

![image](https://github.com/user-attachments/assets/cef354f5-b667-4cbc-ac7c-d86bbe7514cb)

Y su cantidad si quiere ser editada

![image](https://github.com/user-attachments/assets/81255e9f-f31b-4fa2-9cbc-74a2d4a6a534)

Si se desea borrar un producto aparecera un pop up preguntando el nombre del producto

![image](https://github.com/user-attachments/assets/4bf2c7a1-86b1-4d2d-bf70-e8640bc64168) // ![image](https://github.com/user-attachments/assets/004f69c5-0845-4607-96c7-3949bdbe1246)



Esta informacion se vera reflejada en la DB y en el boton de Listar productos.

![image](https://github.com/user-attachments/assets/6f98961a-26bb-4c08-bb24-bf2991bbfd46) // ![image](https://github.com/user-attachments/assets/c1a9c802-72a0-48b1-8a7d-6f4c2a258222)

![image](https://github.com/user-attachments/assets/73593439-6ccf-4c37-8595-08ef941cffd2) // ![image](https://github.com/user-attachments/assets/55dc365b-9698-49d2-bd80-724cd4abe7d0)



## Punto 3 Implementación de una colección que permita visualizar los productos en orden ascendente.

Se implemento una coleccion que permita este orden, dependiendo pe precio, nombre (alfabetico) y cantidad. Esto por medio del uso de ´Lists´ y ´ArrayList´

![image](https://github.com/user-attachments/assets/ac46ed81-3d37-4604-9dbb-cb55906f4c78)

Al ser ejecutados se obtienen las siguientes ventanas

### Por nombre

![image](https://github.com/user-attachments/assets/c7f5c35b-d724-4f93-b032-bce19fd33ccf)

### Por precio

![image](https://github.com/user-attachments/assets/2e1e845c-1729-4afa-ac7a-08805029082a)

### Por cantidad

![image](https://github.com/user-attachments/assets/3c1f5b67-f68e-4c36-8a5a-4f75d7bd05ba)

## Punto 4 La información debe persistir en el tiempo (DB)

Utilice la BD vista en clase (Firebase) la cual es inicializada en la clase ´DatabaseManger´

![image](https://github.com/user-attachments/assets/8897fb98-67c1-45d9-baf6-a14577a93f29)

Los datos son guardados en la database

![image](https://github.com/user-attachments/assets/782155f2-ed7d-4423-a909-37b9ada5112f)

































