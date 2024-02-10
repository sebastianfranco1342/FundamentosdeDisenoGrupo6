# _INFORME DE LABORATORIO 06: ESQUEMÁTICO DEL CIRCUITO ELECTRÓNICO📑_
## Docentes:👨‍🏫
- Mg Umbert Lewis De La Cruz
- Mg. Paulo Camilo Vela Antón
- Mg. Moises Stevend Meza Rodriguez
- Dr. Harry Anderson Rivera Tito
- Ing. Juan Manuel Zuñiga Mamani
- Ing. Renzo José Chan Ríos
## Integrantes📊
- Carpio Peralta Joaquín Felipe
- Franco Alegría Sebastián Stephano
- Orosco Taype Mayerly Nicole
- Pacheco Vidalón Sebastián Marcelo
- Rioja Cruz Vanesa Doris
  
### INTRODUCCIÓN:

El presente trabajo tiene como objetivo retratar de manera detallada todo lo abordado durante el taller sobre la utilización de Flux AI para el modelado de circuitos. Durante la sesión, se exploraron diversas funcionalidades de esta herramienta, con el propósito de familiarizarnos con su uso y modelar el circuito que utilizaremos en nuestro proyecto.
A lo largo del taller, se llevaron a cabo una serie de ejercicios prácticos diseñados para poner en práctica conceptos teóricos de la herramienta Flux AI. En este informe, se detallarán los pasos seguidos en cada uno de los ejercicios desarrollados, así como las observaciones y conclusiones obtenidas a partir de esta experiencia.

### MARCO TEÓRICO
A continuación realizamos las revisiones literarias, con el fin de conocer los términos que se usan en esta rama de nuestra investigación.

- Flux.AI: Es un programa el cual tiene como objetivo crear modelos de circuitos electrónicos. Incorporando múltiples herramientas como una inteligencia artificial para optimizar los diseños, una gran variedad de componentes para modelar un diagrama y la capacidad de trabajar colaborativamente.

- User Flow: Similar a un diagrama de flujo, tiene el propósito de graficar la ruta que se toma en un programa interactivo, tales como una página web o una aplicación para completar una tarea.

- Prototipado de Software: Es el proceso en el que se crea una versión preliminar y simplificada de una aplicación o sistema que se está desarrollando. Existen diversos programas que ayudan a moldear y crear uno, tales como Figma, Appinventor, Scratch, entre otros.

- Por último cabe aclarar que también pudimos observar los conceptos ligados al diagrama de flujo el cual es un modelo gráfico que representa el proceso, sistema, algoritmo o funcionamiento sistemático para facilitar la comprensión de esta misma. 

### EJERCICIOS

Todos los ejercicios realizados en el lab se realizaron con el programa

### Ejercicio N°1: Crear un circuito que pueda encender un LED

En este caso se han utilizado 3 componentes, las cuales detallaremos a continuación:
- Resistencia genérica: Es un componente electrónico que se utiliza para limitar el flujo de corriente en un circuito eléctrico. Las resistencias se utilizan para controlar la corriente, reducir la tensión, dividir el voltaje y polarizar transistores
Se utilizan para ajustar la corriente que fluye a través de un circuito y proteger los componentes sensibles al exceso de corriente.
- Una luz led (WP7113SRD/D): Es un diodo emisor de luz que emite luz cuando se le aplica corriente eléctrica. En el caso específico del LED WP7113SRD/D, es un LED rojo de alta intensidad. Los LEDs son componentes electrónicos que se utilizan comúnmente en circuitos electrónicos, indicadores luminosos, pantallas, iluminación, entre otros.
> - Una batería: Este es un componente fundamental que proporciona la energía necesaria para alimentar los dispositivos electrónicos.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa.png?raw=true" width="180" height="300" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_LED.png?raw=true" width="180" height="300" /> 
<img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia.png?raw=true" width="250" height="300" />  </p>

Primero se puso el resistor dentro del circuito eléctrico y se le modificó para que tuviera una resistencia de 330 ohm y cambiara su tipo de paquete.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia_C.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Resistencia_P.png?raw=true" width="180" height="350" />  </p>

Después, se coloca la batería y se conecta con el resistor. También se cambia el tipo de parte en la sección de propiedades a fuente de energía. 

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa_C.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bater%C3%ADa_Ppng.png?raw=true" width="250" height="350" />  </p>

Finalmente, se coloca el LED, se une con el resistor y con la batería.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_LED_C.png?raw=true" width="500" height="350" /> </p>

En las siguientes imágenes se evidencia la visión 2D y 3D en la sección de PCB.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.1_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.1_PCB3D.png?raw=true" width="500" height="350" />  </p>

En caso utilizar un bloque terminal (2-Position Screw Terminal) como una fuente de energía, se siguen los mismos pasos anteriores en la sección esquemática solo que se cambió el bloque terminal con la batería.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Bloque_C.png?raw=true" width="500" height="350" /> </p>

Y su visión 2D y 3D en la sección PCB es la siguiente.

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2.1_PCB3D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej1.2.2_PCB3D.png?raw=true" width="500" height="350" />  </p>

### Ejercicio N° 2: Realizar un circuito eléctrico en base a nuestro proyecto
Para la construcción de este circuito, se seleccionó  los componentes que se asemejen a nuestr proyecto de solución, los cuáles fueron:
- Panel solar (P123 Surface Mount):  Es un componente utilizado para convertir la energía solar en electricidad, al instalar y conectar correctamente en un sistema eléctrico, se puede aprovechar la energía solar para alimentar dispositivos, cargar baterías o incluso suministrar energía a redes eléctricas.
- Regulador de voltaje de 5V (L7805CV): Es un regulador de voltaje lineal positivo con voltaje de salida de 5V DC y corriente de salida máxima 1.5A. Tiene un encapsulado de TO-220 de tres pines. El L7805CV es un regulador de voltaje lineal, que se utiliza para proporcionar una salida de voltaje constante a partir de una entrada de voltaje variable. Es un componente electrónico comúnmente utilizado en proyectos de electrónica
- Un diodo (1N4007W) es un componente electrónico que se utiliza para mantener una salida de voltaje constante de 5 voltios, independientemente de las variaciones en el voltaje de entrada. Este regulador de voltaje es muy común y se emplea en una variedad de aplicaciones para garantizar un suministro de energía estable y fiable. Se utilizan regularmente como rectificadores de señales, aplicándolo en fuentes de CA a CD.
- Módulo recargador de baterías (TP4056): El TP4056 es un chip de carga lineal con protección de sobrecarga y sobre descarga. Se puede utilizar para cargar baterías de litio de una celda con una corriente de carga ajustable, lo que lo hace ideal para cargar baterías utilizadas en proyectos electrónicos como Arduino, Raspberry Pi, dispositivos portátiles, entre otros.
- Portador de baterías (BK-18650-PC2) es un dispositivo que se utiliza para sostener y conectar baterías de litio tipo 18650 en un circuito. Este portador de baterías suele tener contactos metálicos para conectar las baterías de forma segura y permitir su uso en proyectos electrónicos.
- Amplificador de voltaje (LM2596 DC-DC buck converter) es un dispositivo que se utiliza para convertir un voltaje de entrada más alto a un voltaje de salida más bajo de manera eficiente. Este tipo de dispositivo es comúnmente utilizado en aplicaciones donde se requiere una fuente de alimentación con un voltaje específico y estable, como en circuitos electrónicos, proyectos de electrónica, sistemas de energía solar, entre otros


<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Panel.png?raw=true" width="250" height="300" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Regulador.png?raw=true" width="250" height="300" /> 
<img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Diodo.png?raw=true" width="250" height="300" />  </p>

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_TP4056.png?raw=true" width="250" height="300" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_CargadorB.png?raw=true" width="250" height="300" /> 
<img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Booster.png?raw=true" width="250" height="300" />  </p>

Nosotros queríamos usar otro versión del panel solar y amplificador de voltaje pero tuvimos que utilizar estos debido a que los que buscamos no están presentes en la base de datos de flux.

- Primero, unimos el panel solar con el regulador de voltaje.

<p align="center" float="left"> <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.1.png?raw=true" width="500" height="500" />  </p>

- Después de ello, unimos el sistema con el diodo y el módulo recargador de baterías YP4056.

<p align="center" float="left"> <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.2.png?raw=true" width="500" height="500" />  </p>

- Finalmente, el sistema lo unimos con el cargador de baterías y el amplificador de voltaje.

<p align="center" float="left"> <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Eje.2.3.png?raw=true" width="700" height="350" />  </p>

- A continuación se observa la visión 2D y 3D en la sección PCB:

<p align="center" float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej2_PCB2D.png?raw=true" width="500" height="350" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab6_Ej2_PCB3D.png?raw=true" width="500" height="350" />  </p>

### _Discusión🥇_

Debido a que la creación de esquemas de circuitos eléctricos es nuevo conocimiento para los integrantes del grupo, se nos dificultó su creación. Además de ello, los materiales que queremos utilizar no están disopnibles en "flux.ai" debido a que no están los modelos en su librería de componentes. A pesar de estos problemos, llegamos afrontar cada uno de ellos, leyendo la documentación disponible en el sitio web para aprender el programa y utilizando otros materiales para elaborar el circuito eléctrico. 

### _Conclusión☑️_

En conclusión, este laboratorio nos permitió realizar diversos circuitos eléctricos que nos van a apoyar cuando realizemos el circuito eléctrico de nuestro prototipo. Además de ello, nos permitió a aprender los diferentes símbolos que simbolizan globalmente los componentes del esquemático de un circuito eléctrico, mejorando nuestra comprensión de estos.
