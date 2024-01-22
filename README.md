# EstacionamientoUnahur
Programa que simula el sistema de ingreso/salida de vehículos en el estacionamiento de una universidad.

## Enunciado:

Dada la creciente demanda de autos en el estacionamiento de UNAHUR por el regreso a las clases presenciales, la universidad nos solicitó ayuda para comenzar a tarifar el estacionamiento.

El estacionamiento tiene una capacidad máxima en general, y a su vez tiene sectores que tienen su propia capacidad.


● El sector docente tiene 50 lugares y cuesta $10 la hora.


● El sector de alumnos tiene 50 lugares y cuesta $5 la hora.


● Y el sector general, que tiene 100 lugares, cuesta $20 la hora.

### Tener en cuenta las siguientes especificaciones:

### a) Cada vez que ingresa un auto al estacionamiento, se registra la matrícula, la hora
de ingreso y el sector en donde se estaciona.

### b) No se puede exceder la capacidad y se debe arrojar una excepción si esto ocurre.

### c) Cuando un auto sale, se registra su hora de salida.

### d) No se debe ingresar un auto que esté actualmente en el estacionamiento. Se debe
lanzar una excepción.

### e) El estacionamiento, en algún momento, deberá poder responder cuánto dinero recaudó.

### Ejemplo:

★ Ingresa el auto docente AAA111 a las 11 y sale a las 13

★ Ingresa el auto alumno BBB111 a las 12 y sale a las 15

★ Ingresa el auto general CCC111 a las 10 y sale a las 13

El total a recaudar es: 2 * $ 10 + 3 * $ 5 + 3 * $ 20

Se pide Modelar el TDA Estacionamiento, escribiendo la interfaz pública de todos los TDAs involucrados. En la interfaz se deben indicar de manera prolija los atributos y las operaciones, usando nombres declarativos e incluyendo una breve explicación de cada una. Se puede entregar un txt/pdf adicional al código con esta información.

### Tener en cuenta que se debe poder:

I. Registrar el ingreso de un auto con los datos indicados previamente.

II. Consultar si un auto está en el estacionamiento para una hora determinada.

III. Registrar la salida de un auto con los datos indicados.

IV. Calcular el dinero recaudado. Esta operación se debe resolver lo más
rápido posible

Para lo anterior, se pide:
1. Escribir la interfaz pública de los TDAs involucrados (nombre, atributos y operaciones principales de cada uno).
2. Implementar los métodos para poder responder las operaciones I...IV indicadas en
el enunciado.
