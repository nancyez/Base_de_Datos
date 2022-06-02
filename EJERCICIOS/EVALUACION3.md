
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)

Es un almacen de datos único y centralizado que agrega y combina información de diferentes fuentes.  


2. Realiza un diseño del modelo en estrella (valor 2)

![image](https://user-images.githubusercontent.com/101658619/171660538-7442d2dd-2514-4b47-aba7-e6d5823a9d49.png)


3. Realiza un diseño del modelo copo de nieve (valor 2)
![image](https://user-images.githubusercontent.com/101658619/171662021-17990d75-8f41-45c0-afaf-957c83201188.png)



## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

https://www.db-fiddle.com/f/r1PHXXpzUwunenY8wmZdGD/3

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)
![image](https://user-images.githubusercontent.com/101658619/171664040-ee98f4d9-aa2a-4286-bffb-ae3aa92052cf.png)



2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)
![image](https://user-images.githubusercontent.com/101658619/171673986-accf4a79-06f7-4743-9efa-184e1b4d243f.png)

![image](https://user-images.githubusercontent.com/101658619/171673914-64780335-10fc-4d56-bb22-9f3b57a9c8f8.png)


3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)
![image](https://user-images.githubusercontent.com/101658619/171674309-f42e79ba-3294-424a-a3fb-0875dfb0a022.png)
![image](https://user-images.githubusercontent.com/101658619/171674366-f1a4f386-30e3-461f-9a10-06972138f247.png)






4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)
![image](https://user-images.githubusercontent.com/101658619/171675835-4d8a705f-c2ef-40af-8285-ddd6bb7d9e1a.png)
![image](https://user-images.githubusercontent.com/101658619/171675882-539dec0b-33c6-4a20-97c6-83490943bf12.png)


## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.
