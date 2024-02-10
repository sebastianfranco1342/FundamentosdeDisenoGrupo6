# Lab 6. Esquemático del circuito electrónico

## Introducción

El presente trabajo tiene como objetivo retratar de manera detallada todo lo abordado durante el taller sobre la utilización de Flux AI para el modelado de circuitos. Durante la sesión, se exploraron diversas funcionalidades de esta herramienta, con el propósito de familiarizarnos con su uso y modelar el circuito que utilizaremos en nuestro proyecto.
A lo largo del taller, se llevaron a cabo una serie de ejercicios prácticos diseñados para poner en práctica conceptos teóricos de la herramienta Flux AI. En este informe, se detallarán los pasos seguidos en cada uno de los ejercicios desarrollados, así como las observaciones y conclusiones obtenidas a partir de esta experiencia.

## Marco Teórico

- Flux.AI: Es un programa el cual tiene como objetivo crear modelos de circuitos electrónicos. Incorporando múltiples herramientas como una inteligencia artificial para optimizar los diseños, una gran variedad de componentes para modelar un diagrama y la capacidad de trabajar colaborativamente.

- Diagrama de flujo: Es un modelo gráfico que representa el proceso, sistema, algoritmo o funcionamiento sistemático para facilitar la comprensión de esta misma. 

- User Flow: Similar a un diagrama de flujo, tiene el propósito de graficar la ruta que se toma en un programa interactivo, tales como una página web o una aplicación para completar una tarea.

- Prototipado de Software: Es el proceso en el que se crea una versión preliminar y simplificada de una aplicación o sistema que se está desarrollando. Existen diversos programas que ayudan a moldear y crear uno, tales como Figma, Appinventor, Scratch, entre otros.

## Ejercicios

Todos los ejercicios realizados en el lab se realizaron con el programa

### Ejercicio #1: Realiza un circuito eléctrico para un led

En este caso se han utilizado 3 componentes, una resistencia generica, una luz led (WP7113SRD/D) y una batería.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa.png?raw=true" width="180" height="300" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_LED.png?raw=true" width="180" height="300" /> 
<img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia.png?raw=true" width="220" height="280" />  </p>

Primero se puso el resister dentro del circuito eléctrico y se le modifico para que tuviera una resistencia de 330 ohm y cambiara su tipo de paquete.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia_C.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia_P.png?raw=true" width="180" height="350" />  </p>

Despues se coloca la batería y se conecta con el resistor. También se cambia el tipo de parte en la sección de propiedades a fuente de energía. 

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa_C.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa_Ppng.png?raw=true" width="250" height="350" />  </p>

Finalmente se coloca el LED y se une con el resistor y con la batería.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_LED_C.png?raw=true" width="500" height="350" /> </p>

Las siguientes imagenes serían su visión 2D y 3D en la sección de PCB.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.1_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.1_PCB3D.png?raw=true" width="500" height="350" />  </p>

En caso utilizar un bloque terminal (2-Position Screw Terminal) como una fuente de energía, se siguen los mismos pasos anterior en la sección esquemática solo que se cambio el bloque terminal con la batería.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bloque_C.png?raw=true" width="500" height="350" /> </p>

Y su visión 2D y 3D en la sección PCB es la siguiente.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2.1_PCB3D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2.2_PCB3D.png?raw=true" width="500" height="350" />  </p>

### Ejercicio #2: Realizar un circuito eléctrico de mínimo 6 componentes

Para este ejercicio se utilizarán un panel solar (P123 Surface Mount), un regulador de voltaje de 5V (L7805CV), un diodo, (1N4007W), un módulo recargador de baterías TP4056, un portador de baterías (BK-18650-PC2) y un amplificador de voltaje (LM2596 DC-DC buck converter).

Nosotros queríamos usar otro versión del panel solar y amplificador de voltaje pero tuvimos que utilizar estos debido a que los que buscamos no están presentes en la base de datos de flux.

Primero unimos el panel solar con el regulador de voltaje.

![1](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.1.png?raw=true)

Despues de ello unimos el sistema con el diodo y el módulo recargador de baterías YP4056.

![2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.2.png?raw=true)

Finalmente el sistema lo unimos con el cargador de baterías y el amplificador de voltaje.

![3](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.3.png?raw=true)

Y su visión 2D y 3D en la sección PCB es la siguiente.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej2_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej2_PCB3D.png?raw=true" width="500" height="350" />  </p>

## Discusión

Debido a que la creación de esquemas de circuitos eléctricos es nuevo conocimiento para los integrantes del grupo, se nos dificulto su creación. Además de ello, los materiales que queremos utilizar no están disopnibles en flux.ai debido a que no están los modelos en su libreria de componentes. A pesar de estos problemos, llegamos afrontar cada uno de ellos, leyendo la documentación disponible en el sitio web para aprender el programa y utilizando otros materiales para elaborar el circuito eléctrico. 

## Conclusión

En conclusión, este laboratorio nos permitió realizar diversos circuitos eléctricos que nos van a apoyar cuando realizemos el circuito eléctrico de nuestro prototipo. Además de ello, nos permitió a aprender los diferentes simbolos que se simbolizan globalmente los componentes del esquematico de un circuito electrico, mejorando nuestra comprensión de estos.
