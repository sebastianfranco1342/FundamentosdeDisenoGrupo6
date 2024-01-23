Marco teorico: (Tabla de colores, ley de ohm, protoboard, etc....)

Materiales:

Procedimiento:

**Ejercicio1**

**Ejercicio2**

**Ejercicio3**: Determinar las resistencia total del siguiente circuito.

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje_3_Ini.jpeg)

Para encontrar la resistencia final se utilizaron resistencias equivalentes a 1x10^5 V. La imágen presentada en el ejercicio se puede representar de la siguiente manera para que sea más sencillo entender lo que se debe de hacer

![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje_3_Plant.jpeg)


![Ini](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje_3_Ini.jpeg)

**Ejercicio4**: Que el voltaje liberado sea equivalente a 1.1V si se tiene como voltaje inicial 5V.

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

Para comprobar el resultado, se realizo una simulación en tinkecard. Las resistencias dentro de la simulación son equivalentes a 1KΩ. 

![Sim](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Lab3_Eje4_Sim.png?raw=true)

Discusión:
