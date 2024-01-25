# Informe de Lab #4

## Introducción:

En el marco del taller de laboratorio de electrónica básica, hemos explorado los fundamentos prácticos de la electrónica mediante el uso del Explore Iot Kit (kit de arduino). Este kit, que incluye sensores de humedad, temperatura, proximidad y que viene integrado con luces LED, nos ha permitido fusionar teoría y aplicación de manera tangible.

Este informe documenta nuestras experiencias prácticas, desde la conexión de componentes hasta la programación de microcontroladores, destacando los desafíos enfrentados y los resultados obtenidos. A través de esta experiencia, buscamos resaltar la importancia de la experimentación práctica en la comprensión de la electrónica y fomentar la aplicación directa de conocimientos teóricos en situaciones del mundo real.

### Explore Iot Kit 
Todas las actividades adoptan un enfoque de aprendizaje práctico en el que se adquieren conocimientos paso a paso mediante la construcción de soluciones totalmente funcionales. Este kit proporciona todas las herramientas y tutoriales necesarios para comprender los fundamentos de las cinco áreas distintas: Hardware, Seguridad, Programación, Red y Datos.

- Encapsulado de la Carrier
El conjunto también contiene una cubierta de plástico que puede ser empleada en ciertas actividades, brindando una capa adicional de protección a la MKR IoT Carrier y permitiendo su fijación a diversas superficies. Asimismo, todas las funciones de la MKR IoT Carrier pueden ser utilizadas aun cuando se encuentra dentro de la cubierta

- Batería
La MKR IoT Carrier incluye un soporte para batería 18650 Li-Ion que posibilita la operación autónoma de proyectos portátiles

## Marco Teórico:

Internet de las Cosas: Este concepto se refiere a la red gigante de dispositivos conectados entre sí los cuales recopilan datos y lo comparten a través de todos los dispositivos del mundo. El Internet de las cosas o IoT (por sus siglas en inglés) es una forma de ver cómo nuestro mundo cada día más se está volviendo digital.

Arduino Uno: Es una placa de microcontrolador de código abierto basado, equipada con conjuntos de pines digitales y analógicas que pueden conectarse a varias placas de expansión y otros circuitos. Es una tarjeta de desarrollo ideal para proyectos de hardware y de automatización programable que permite llevar a cabo ideas tanto personales como industriales, haciendo accesible su uso a cualquier persona.

Arduino IDE: Llamado también entorno de desarrollo integrado (IDE), es una aplicación multiplataforma con la que se puede realizar programas con placas compatibles con Arduino.

Arduino MKR WiFi 1010: Es una placa que sirve para diseñar aplicaciones básicas de Internet de las Cosas (IoT). Esta placa es una solución integral para muchos escenarios de aplicaciones de IoT. Además, la placa Arduino MKR WiFi 1010 permite conectarse a Internet y descargar contenido de una página web.


## Procedimiento y Resultados

### Actividad #1:

Primero se debe de desatornillar la tapa y retirarla de la cápsula.

![Pas1](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje1_Pas1.png?raw=true)

Luego insertamos el arduino MKR IoT Carrier y lo ajustamos con tornillas ya brindados por el Kit.

![Pas2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje1_Pas2.png?raw=true)

Finalmente volvemos a tapar la cápsula con el arduino dentro.

![Pas3](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje1_Pas3.png?raw=true)

Adicionalmente, una vez se tiene el código dentro del arduino para que este se opere, se le pone una batería para que este funcione sin necesidad de estar conectado a la computadora.

![Pas4](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje1_Pas4.png?raw=true)

### Actividad #2: Funcionar el codigo de temperatura y humedad en el arduino.

Una vez verificado que funciona arduino, se decidió instalar el código proporcionado por la guía Explore IoT Kit sobre la temperatura y humedad.

![codigo](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Cod.png?raw=true)

Lamentablemente, debido a que a pesar de que se había conecatdo el arduino con la computadora, este no lo podía leer. Así que se tuvo que instalar el Arduino Create Agent para solucionar el problema.

![Arduino Create Agent](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_ACA.png?raw=true)

Una vez solucionado, se verifico el código y se subió en el arduino para que diera los valores de humedad y temperatura en el lugar.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Temp.jpeg?raw=true" width="220" height="220" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Hum.jpeg?raw=true" width="220" height="220" />  </p>

### Actividad #3: Cambiar las temperaturas de Celsius a Fahrenheit y de Fahrenheit a Celsius.

En este caso necesitamos se implementaron 2 nuevos valores: temperatureF y temperatureK. Estos valores representan la temperatura en grados Farhenheit y Kelvin Respectivamente. Una vez establecidos, se le agregaron en el loop para que el arduino sepa como presentar los valores

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Val.png?raw=true" width="500" height="320" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Void2.png?raw=true" width="500" height="320" />  </p>

Además de ello también se implementaro nuevos valores del Touch para que cada momento se vuelva a tocar este sensor este cambie el valor de la temperatura. Finalmente, se implemento nuevos comandos dentro del comando void para que se puedan generar estos valores dentro de la pantalla del arduino con respecto a ciertos criterios ya establecidos como el tamaño de letra o el color de este.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Touch.png?raw=true" width="400" height="220" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Void.png?raw=true" width="320" height="220" />  </p>

### Actividad #4: Realizar código de sensor de proximidad y que cambie de la pantalla con respecto a la temperatura.

En este caso se modifico codigo voidTemperature para que el color de la pantalla de temperatura vaya a tomar o un color rojo o uno azul respecto a que si el valor de temperatura sobrepasa un rango ya establecido.

![VoidT](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje4_VoidT.png?raw=true)

Para activar el sensor de proximidad PIR, se ingreso codigo dentro del voidloop que cambie el color de la pantalla en caso el sensor PIR detecte movimiento.

![Sens](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje4_Sens.png?raw=true)

## Discusión:

A pesar de no tener problemas durante el primer ejercicio en el desamblaje del kit, durante el segundo ejercicio se tuvieron problemas respecto a la conexión directa entre la computadora y el arduino por lo que tuvimos que recurrir a un programa externo, Arduino Create Agent, para solucionar el problema. Además de ello, durante los ejercicios 3 y 4, se nos presentaron varios problemas a la hora de editar el codigo ya existente proporcionado por el sitio web debido a nuestra falta de conocimiento de este nuevo sistema ya que varios integrantes del grupo no estaban familiarizados con el arduino. Para enfrentar este problema, utilizamos el sitio guía del kit y una vez entendido el programa, se llego a editar correctamente el código.

## Conclusiones:

- A pesar de enfrentar desafíos en el taller de laboratorio, logramos superar obstáculos clave. La programación del Arduino desde la computadora nos obligó a ajustar el código según las indicaciones del docente, destacando la necesidad de adaptabilidad en entornos prácticos.

- Destacamos nuestro éxito en el desarrollo del sensor de temperatura y humedad, evidenciando la aplicación efectiva de conocimientos teóricos. Asimismo, exploramos y sincronizamos los LEDs del kit con el sensor de proximidad, demostrando nuestra capacidad para integrar componentes de manera efectiva.

- Se cumplió el objetivo de la sesión el cual fue familiarizarnos con el lenguaje de programación arduino y con el dispositivo MRK IoT Carrier

