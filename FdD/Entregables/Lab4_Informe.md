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

En este caso necesitamos se implementaron 2 nuevos valores: temperatureF y temperatureK. Estos valores representan la temperatura en grados Farhenheit y Kelvin Respectivamente. Una vez establecidos, se le agregaron en el loop para que el arduino sepa como presentar los valores

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Val.png?raw=true" width="500" height="320" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Void2.png?raw=true" width="500" height="320" />  </p>

Además de ello también se implementaro nuevos valores del Touch para que cada momento se vuelva a tocar este sensor este cambie el valor de la temperatura. Finalmente, se implemento nuevos comandos dentro del comando void para que se puedan generar estos valores dentro de la pantalla del arduino con respecto a ciertos criterios ya establecidos como el tamaño de letra o el color de este.

<p float="left">  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Touch.png?raw=true" width="400" height="220" />  <img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje3_Void.png?raw=true" width="320" height="220" />  </p>

### Actividad #4: Realizar código de sensor de proximidad y que cambie de la pantalla con respecto a la temperatura.

En este caso se modifico codigo voidTemperature para que el color de la pantalla de temperatura vaya a tomar o un color rojo o uno azul respecto a que si el valor de temperatura sobrepasa un rango ya establecido.

![VoidT](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje4_VoidT.png?raw=true)

Para activar el sensor de proximidad PIR, se ingreso codigo dentro del voidloop que cambie el color de la pantalla en caso el sensor PIR detecte movimiento.

![Sens](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab4_Eje4_Sens.png?raw=true)
