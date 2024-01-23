# Informe de Lab #3 "FUNDAMENTOS DE ELECTRÓNICA I"
 
Integrantes:
- Carpio Peralta Joaquín Felipe
- Franco Alegría Sebastián Stephano
- Orosco Taype Mayerly Nicole
- Pacheco Vidalon Sebastián Marcelo
- Rioja Cruz Vanesa Doris

## Marco teórico:

El presente  informe de laboratorio titulado “Fundamentos de Electrónica I” tiene como objetivo adentrarnos al uso de protoboard, circuitos básicos y demás componentes electrónicos. La electrónica es la rama de la física y la ingeniería que se encarga del estudio y aplicación de los circuitos, dispositivos y sistemas que utilizan corrientes de electrones para el procesamiento y transmisión de información. Comprende un conjunto de fundamentos teóricos y conceptos clave que son esenciales para comprender el funcionamiento de los componentes electrónicos y los circuitos.

**Componentes activos:** Hace referencia a los dispositivos que son capaces de proporcionar energía eléctrica al circuito (Diodos, transistores, circuitos integrados)

**Protoboard:** Es una herramienta fundamental en electrónica que se utiliza para construir y probar circuitos electrónicos Consiste en una placa con orificios conectados eléctricamente en los que se pueden insertar y conectar componentes electrónicos, como resistencias, condensadores, transistores, entre otros, mediante cables de conexión.

**Componentes pasivos:** Son aquellos elementos que no requieren fuente de alimentación externa y que pueden almacenar energía en forma de corriente (Amperaje) o voltaje (Voltios), como ejemplo se tiene a resistor, condensador e inductor.

**Ley de Ohm:** La ley de Ohm establece la relación fundamental entre el voltaje (V), la corriente (I) y la resistencia (R) en un circuito eléctrico. Esta ley establece que el voltaje en un circuito es igual al producto de la corriente y la resistencia, expresado por la fórmula V=I*R. 

**Cálculo de la resistencia:** Para saber el valor de una resistencia tenemos que fijarnos que tiene 3 bandas de colores seguidas y una cuarta más separada. Leyendo las bandas de colores de izquierda a derecha, las 3 primeras bandas nos determinarán su valor, la cuarta banda nos indica su tolerancia.

![Resistencias](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Resis.jpg?raw=true)

## Procedimiento:

### **Ejercicio1**: Determinar las resistencia total del siguiente circuito.

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje1_Ini.png?raw=true)

Como los colores de la resistencia 1 (R1) son  cafe - negro - rojo se tendrá una resistencia de 1x10^3 Ω. Así con el resto de resistencias, siendo los colores de la resistencia 2 (R2) (rojo - rojo - café) equivalentes a 220 Ω y los colores de la resistencia 3 (R3) café - negro - amarillo equivalente a 1x10^5 Ω.

Para llegar el resultado de la Resistencia total primero sumamos las resistencias que están en serie (R1 y R2):

R1 + R2 = 1x10^3 Ω + 220 Ω = 1220 Ω

Con la suma de R1 y R2 la resistencia resultante la sumamos con la R3 que está en paralelo.

1/Rt = 1/(1220 Ω) + 1/(1x10^5 Ω)

R total = 1205.3 Ω = 1.21 KΩ

![Evidencia](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje1_Evidencia.jpg?raw=true)

Para comprobar el resultado, se realizo una simulación en tinkecard cumpliendo las mismas condiciones que en el ejercicio. 

![Evidencia](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje1_Sim.png?raw=true)

### **Ejercicio2**: Determinar las resistencia total del siguiente circuito.

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje2_Ini.png?raw=true)

Como los colores de la resistencia 1 (R1) son  cafe - negro - rojo se tendrá una resistencia de 1x10^3 Ω. Así con el resto de resistencias, siendo los colores de la resistencia 2 (R2) (rojo - rojo - café) equivalentes a 220 Ω, los colores de la resistencia 3 (R3) café - negro - amarillo equivalente a 1x10^5 Ω, los colores de la resistencia 4 (R4) café - negro - amarillo equivalente a 1x10^5 Ω y los colores de la resistencia 5 (R5) café - negro - rojo equivalente a 1x10^3 Ω

Para llegar el resultado de la Resistencia total primero sumamos las resistencias que están en serie (R1 y R2):

R1 + R2 = 1x10^3 Ω + 220 Ω = 1220 Ω

Con la suma de R1 y R2 la resistencia resultante la sumamos con la R3, R4 y R5 que está en paralelo.

1/Rt = 1/(1220 Ω) + 1/(1x10^5 Ω) + 1/(1x10^5 Ω)

Rt = 1190.94 Ω = 1.19 KΩ

Sin embargo, puesto que la resistencia 5 está una misma columna, el resultado de la resistencia del cortocircuito es 0 Ω puesto que ocurre un cortocircuito.

![Evidencia](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje2_Eidencia.jpeg?raw=true)

Para comprobar la resistencia se realizo una simulación en tinkecard cumpliendo las mismas condiciones que en el ejercicio.

![Simulación](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje2_Sim.png?raw=true)

### **Ejercicio3**: Determinar las resistencia total del siguiente circuito.

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje3_Ini.png)

Para encontrar la resistencia final se utilizaron resistencias equivalentes a 1x10^5 V y la imágen presentada en el ejercicio se puede representar de la siguiente manera para que sea más sencillo entender lo que se debe de hacer

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje3_Plant.jpeg?raw=true)

Para llegar al resultado se sumaron los 3 pares de resistencias en serie:

R3 + R1 = R6 + R5 = R4 + R2 = 1x10^5 Ω + 1x10^5 Ω = 2x10^5 Ω

Y se sumaron las resistencias en serie

1/Rt = 1/(2x10^5 Ω) + 1/(2x10^5 Ω) + 1/(2x10^5 Ω)

1/Rt = 3/(2x10^5 Ω)

Rt = 2x10^5/3 = 66666.67 Ω = 66.67 KΩ

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje_3_Eidencia.jpeg)

<img src="https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje4_Indicadorjpg.jpg?raw=true" width="380" height="430">

Para comprobar la resistencia se realizo una simulación en tinkecard cumpliendo las mismas condiciones que en el ejercicio.

![Simulación](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje3_Sim.png?raw=true)

### **Ejercicio4**: Que el voltaje liberado sea equivalente a 1.1V si se tiene como voltaje inicial 5V.

En el ejercicio 4, se utilizo esta secuencia de resistencias en el protoboard para conseguir una **V** out equivalente a 1.1 V.

![Inicio](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje4_Ini.png?raw=true)

Para llegar al resultado primero se tuvo que encontrar la relación entre la resistencia 1 (R1) y la resistencia 2 (R2):

**V** in = 5V	= (R1 + R2) x I

I =  **V** in/(R1 + R2)

**V** out = 1.1V =  R2 x [**V** in/(R1 + R2)]

1.1V / 5 V = R2 / (R1 + R2)

1.1V x (R1 + R2) = 5V x (R2)

1.1V x R1 = 3.9V x R2

(1.1V x R1 = 3.9V x R2) x 0.909

R1 = 3.54 Ω

R2 = 1 Ω

Para tener 3.54 Ω en una resistencia se tuvieron que usar 3 resistencias en serie y 2 en una secuencia en paralelo, todas con una resistencia de 1 KΩ

R1* = 1 KΩ + 1 KΩ + 1 KΩ = 3 KΩ 

1/R1** = (1 / 1 KΩ) + (1 /1 KΩ)

1 / R1** = (2 / 1 KΩ)

R1** = 500 Ω

R1 = R1* + R2** = 3 KΩ + 500 Ω = 3500 Ω

En el caso de la resistencia 2, solo se uso una resistencia equivalente a 1 KΩ.

![Evidencia](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje4_Evidencia.jpg?raw=true)

Para comprobar el resultado, se realizo una simulación en tinkecard cumpliendo las mismas condiciones que en el ejercicio.

![Sim](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje4_Sim.png?raw=true)

## Discusión:

Para realizar los ejercicios se emplearon las formulas para encontrar las resistencias totales de circuitos en serie (Rt = R1 + R2 + R3), así como circuitos en pararlelos (1/Rt = 1/R1 + 1/R2 + 1/R3). Además de ello, para el ejercicio #4 se empleo la ley de Ohm que establece que el voltaje es equivalente a la Intensidad multiplicado por la resistencia total presente en el circuito (V = IxR). Además de ello, cuando se simulo el ejercicio #2, la resistencia seguía siendo equivalente a 1.19 KΩ. Esto se debe a que la simulación utilizada presenta limitaciones para todos los casos que este puede simular siendo un caso de cortocircuito fuera de los limites de este simulador. 
