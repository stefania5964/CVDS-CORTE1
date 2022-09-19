# *PARCIAL Daniel Builes- Stefania Giraldo*

## Paso a paso  
1. **se realizo el repositorio en nuestro github**

![1](./1.png)

2. **clonar repositorio a refactorizar**

![2](./2.png)

3.**Identificar malas practicas**
> hacer una clase maestra donde contiene todos los metodos
![3](./foto1.png)
![6](./documentacion.png)

> hace en una sola clase la parte de presentacion y la parte de dominio
![4](./foto4.png)

> no tiene documentacion
![5](./documentacion.png)


4. **soluciones para malas practicas**
> separar los metodos en diferentes clases y diferenciar funcionalidades de los metodos
> hacer paquete de capa de presentacion y de dominio
> realizar la documentacion correspondiente pero no extensa
> realizar cambio de nombres a los metodos para evitar tanta documentacion

5.**UT**
> una mala practica en las pruebas de unidad  es que falta especificar el patron AAA (Arrange,Act,Assert)
![7](./tests.png)

> En los test no se prueba en su totalidad lo que deberia realizar el programa(Mock)
![8](./tests.png)


> Las pruebas no se pueden realizar todas en un solo test,esto es una muy mala practica
![9](./tests.png)


6. **Soluciones UT**
> se realiza el patron AAA a todas las pruebas
> se realizan test que utilicen operaciones mas complejas
> se realizan pruebas en metodos por separado

7. **Patterns**
> se encontro que el patron que aplica en este proyecto es el patron estructurales
 ya que estos se encargan de realizar la estructara de las cosas

8. **add,commit, push**

![3](./3.png)