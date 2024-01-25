# Informe de Lab #4

## Introducción:

## Marco Teórico:

## Procedimiento y Resultados

### Actividad #1:

### Actividad #2: Funcionar el codigo de temperatura y humedad en el arduino.

Una vez verificado que funciona arduino, se decidio instalar el codigo proporcionado por la guía Explore IoT Kit sobre la temperatura y humedad.

![codigo](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Cod.png?raw=true)

Lamentablemente, debido a que a pesar de que se había conecatdo el arduino con la computadora, este no lo podía leer. Así que se tuvo que instalar el Arduino Create Agent para solucionar el problema.

![Arduino Create Agent](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_ACA.png?raw=true)

Una vez solucionado, se verifico el codigo y se subió en el arduino para que diera los valores de humedad y temperatura en el lugar.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Temp.jpeg?raw=true" width="220" height="220" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje2_Hum.jpeg?raw=true" width="220" height="220" />  </p>

### Actividad #3: Cambiar las temperaturas de Celsius a Fahrenheit y de Fahrenheit a Celsius.

En este caso necesitamos se implementaron 2 nuevos valores: temperatureF y temperatureK. Estos valores representan la temperatura en grados Farhenheit y Kelvin Respectivamente.

![F y C](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Val.png?raw=true)

Además de ello también se implemento nuevos valores del Touch para que cada momento se vuelva a tocar este sensor este cambie el valor de la temperatura. Finalmente, se implemento nuevos comandos void para que se puedan generar estos valores dentro de la pantalla del arduino.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Touch.png?raw=true" width="400" height="220" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Void.png?raw=true" width="320" height="220" />  </p>

### Actividad #4: Realizar código de sensor de proximidad y que cambie de la pantalla con respecto a la temperatura.

