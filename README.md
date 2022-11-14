# beFit
## Repositorio para el proyecto de IV UGR 2023

###Descripción del problema
Según el PGC (Plan General de Contabilidad), las empresas pueden optar por hacer la contabilidad de las existencias en su inventario siguiendo tres métodos el FIFO (First In First Out), LIFO (Last In First OUT) y PMP (Precio Medio Ponderado), dependiendo de las decisiones que tomen las empresas las distintas formas de contabilizar dichas existencias pueden llevar a resultados del ejercicio distintos, pudiendo no ser del todo cierta la imagen fiel de la empresa y dificultando la comparabilidad con el resto de empresas que sigan otro sistema. Además dependiendo del momento económico en el que nos encontremos usar un tipo de algoritmo u otro puede beneficiar a las empresas aumentando su resultado del ejecicio o reduciendolo, por ejemplo si la empresa decide utilizar el sistema FIFO cuando exista inflación con el objetivo de dar salida a los productos que se fabricaron a precios más bajos y conservando guardados aquellos que ha costado más producir. La imagen de la compañía mejoraría a simple vista trabajando de esta manera, a priori.

###Propuesta
Por lo cual, proponemos implementar una herramienta web para poder alternar de manera rapida entre las tres formas de contabilización de existencias que existen según el PGC. Esto facilitará la tarea de los propios contables de la empresa para determinar que modelo les conviene más en ese momento, sin la necesidad de hacer otra vez todas las cuentas y pudiendo cambiar de método fácilmente.

###Logica de Negocio
Implementaremos los tres algoritmos FIFO, LIFO y PMP para la contabilización de existencias e indicaremos cual es el más indicado usar a las empresas en función de que objetivos persigan (aumentar beneficios en los resultados de ese año o disminuir beneficios) en función de cuál es la situación del mercado (inflación, deflación...)

###Usuarios
Los usuarios son las empresas que desen ahorrar tiempo en el proceso de contabilidad y que quieran cambiar rapidamente entre los distintos tipos existentes de contabilización de existencias para mejorar sus resultados y sacar el mayor provecho posible a cada uno de estos métodos.

###La nube
Nos permitirá alojar la app web y que todos los encargados del departamento y directivos puedan acceder a esta información, además servira para que puedan tener un buen recuento del inventario existente.

