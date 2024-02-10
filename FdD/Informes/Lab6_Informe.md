# Lab 6. Esquemático del circuito electrónico

## Introducción

## Marco Teórico

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
