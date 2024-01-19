# Estado del Arte

## Contexto Cientifico

### Articulo 1: Implementación de un sistema de apoyo a las decisiones agrícolas inteligentes basado en LoRaWAN para un rendimiento óptimo de los cultivos.

Este artículo destaca la implementación de un sistema de agricultura inteligente que utiliza sensores para recopilar datos cruciales, incluyendo humedad del suelo, pH, ubicación y temperatura del campo. Los datos recopilados se transmiten a la nube y a un servidor web a través de internet utilizando LoRa (largo alcance) y el protocolo de comunicación SPI, donde se analizan y se muestran a través de una aplicación móvil. Asimismo, el prototipo cuenta con un Sistema de Soporte de Decisiones (DSS) basado en redes el cual recomienda precauciones que conduzcan a un rendimiento sostenible óptimo.

![Art. 1.1](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Art_1.1.png?raw=true)

Imágen 1. Descripción general del sistema propuesto desde la recopilación de datos de los sensores hacia la nube

![Art. 1.2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Art_1.2.png?raw=true)

Imágen 2: Despliegue de sensores en los cultivos

### Artículo 2: WB-CPI: Predicción de cultivos basada en el clima en la India mediante análisis de big data

Este estudio se centra en la predicción de cultivos en la India mediante el análisis de datos agrícolas y meteorológicos. Se recopilan datos extensos de cultivos de todos los estados de la India, pero los datos meteorológicos se centran en tres estados y dos territorios de La Unión. El conjunto de datos, que incluye información de precipitaciones desde 1901 y datos de temperatura desde 1995, se consideran una fuente de Big Data. Utilizando el marco MapReduce, el algoritmo de agrupamiento de K-medias y una función de recomendación, el proyecto busca sugerir cultivos para sembrar, explorando así las aplicaciones de big data en la producción agrícola.

![Art. 2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Art_2.png?raw=true)

Imágen 3. WB-CPI: Weather Based Crop Prediction in India Using Big Data Analytics

### Artículo 3: An intelligent agriculture management system for rainfall prediction and fruit health monitoring (Un sistema inteligente de gestión agrícola para la predicción de precipitaciones y el seguimiento de la salud de la fruta)

En este artículo, se describe el uso de un sistema integrado de procesamiento que combina varios sensores como parte de un paquete de IoT, el cual impulsa un sistema de gestión agrícola inteligente diseñado para predecir lluvias y monitorear la salud de la fruta. El sistema emplea un modelo asistido por IA, utilizando una red neuronal convolucional (CNN) con una capa de memoria a corto plazo (LSTM) para predecir lluvias. Se introduce un modelo combinado de predictor de lluvia y reconocedor de la salud de la fruta, utilizando un LSTM CNN+ y un mecanismo de autoatención de múltiples cabezales.

![Art. 3](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Art_3.png?raw=true)

Imágen 4: Configuración experimental del sistema IoT propuesto.

### Artículo 4: Meta-Analysis in Using Satellite Precipitation Products for Drought Monitoring: Lessons Learnt and Way Forward (Metaanálisis sobre el uso de productos de precipitación satelital para el monitoreo de sequías: lecciones aprendidas y camino a seguir)

Este estudio resume experiencias en el uso de sistemas de pronóstico de sequías (SPP) para el monitoreo de sequías y propone avances en esta área de investigación. El metanálisis revela que el rendimiento de los SPP depende del clima y la longitud del registro de datos. La revisión examina el impacto del clima, la duración de los registros y la escalada de tiempo en el rendimiento de los SPP. Se concluye que los SPP tienen un mejor rendimiento en climas templados y tropicales y con registros de datos más extensos. El estudio también analiza la combinación de SPP con datos in situ, lecciones aprendidas y futuras aplicaciones para el monitoreo de sequías.

![Art. 4](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Art_4.png?raw=true)

Imágen 5: Meta-Analys in using Satellite Precupitation Products for Drought Monitoring: Lessons Learnt and Way Forward

## Contexto Comercial

### Dispositivo en el Mercado 1: Sensor de humedad de suelo FC-28

Este dispositivo es un sensor higrómetro capaz de detectar la humedad relativa del aire y del suelo. Según Naylamp Electronics (2023), este sensor funciona mediante 2 electrodos resistivos, puesto que una vez insertados dentro del suelo, dependiendo de la humedad del suelo, el valor de resistencia será alto o bajo. Se tendrá una humedad relativa alta si la resistencia de los electrodos es muy bajo y una humedad relativa baja si su resistencia es alta.

![Prod. 1](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Prod1.jpg?raw=true)

Imágen 6. Sensor de humedad de suelo FC-28 (Seeed Studio).

### Dispositivo en el Mercado 2: Sensor de Temperatura y humedad (DHT11)

Este dispositivo es un sensor eléctrico que permite medir la humedad de la tierra gracias a la resistencia de la tierra frente al paso de la corriente.

Características:

-   Alta precisión de humedad (Toma rango entre 5% a 95% de la humedad relativa con una desviación de 5%).
-   Permite transmitir datos a largas distancias.
-   Posee una alta estabilidad.

![Prod. 2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Prod2.png?raw=true)

Imágen 7. Sensor de Temperatura y humedad (DHT11) (EIC Group).

### Dispositivo en el Mercado 3: Estación meteorológica WatchDog 2900ET

Este dispositivo permite la medición y la recolección de datos de la evapotranspiración, la radiación solar, la velocidad, dirección y enfriamiento del viento, el punto de rocío, la temperatura, la humedad relativa y las precipitaciones.

Características:

-   Transmite datos de manera inalámbrica a 1 o varias estaciones lejanas de este diapositivo
-   Larga vida del diapositivo de hasta 12 meses con baterías de litio AA
![Prod. 3](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Prod3.png?raw=true)

Imágen 8. Estación meteorológica WatchDog 2900ET (WatchDog).

### Patente 1: Farmland ecological environment meteorological monitoring device

-   Número de Publicación: [CN217766885U](https://worldwide.espacenet.com/patent/search?q=pn%3DCN217766885U)
-   Fecha de Publicación: 08/11/2022
-   Autores: Wei Qingwei, Wang Min, Zhang Qing, Zhang Minqzhu.

Este dispositivo se utiliza para la monitorización meteorológica del entorno ecológico en los cultivos. Posee un sensor de índice de vegetación en su parte superior para que pueda medir la vegetación y la altura de los cultivos. También posee un sensor de temperatura y humedad del suelo y un sensor de precipitaciones con el fin de monitorear los parámetros meteorológicos del área en los que se encuentran los cultivos.

![Pat. 1](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Pate1.png?raw=true)

Imágen 9.Farmland ecological environment meteorological monitoring device (Wang, Wei, Zhang & Zhang)

### Patente 2: Sistema para sincronizar las mediciones de una red de sensores climáticos con un servidor central en tiempo real

-   Número de Publicación: [WO2020263069](https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2020263069&_cid=P10-LRJTOS-18100-1)
-   Fecha de Publicación: 30/12/2020
-   Autores: Astiazarán Aguirre, José Carlos

Este es un sistema de monitoreo climático que utiliza sensores y un Raspberry Pi para recoger datos del clima, los cuales son procesados por un algoritmo en la nube para predecir temperaturas extremas en áreas agrícolas. Los usuarios pueden acceder a estas predicciones a través de una aplicación, basada en el modelo meteorológico del Centro Europeo para las Previsiones Meteorológicas a Medio Plazo (ECMWF).

![Pat. 2](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Pate2.png?raw=true)

Imágen 9. Sistema para sincronizar las mediciones de una red de sensores climáticos con un servidor central en tiempo real (Astiazarán Aguirre, José Carlos)

### Patente 3: Temperature and humidity measurement instrument

-   Número de Publicación: WO201410286770.7A
-   Fecha de Publicación: 2014-06-25
-   Autores: Xu Lianggui, Lu Zhenglian

Esta invención es un instrumento de medición de temperatura y humedad. El Instrumento de medición constituye un la adquisición de los datos de temperatura y humedad un módulo de control maestro, un módulos de visualización y un módulo de alarma. El módulo de control maestro se utiliza como núcleo, se adopta una microcomputadora de un solo chip STC89C52 y se adopta un sensor digital de temperatura y humedad DHT11.

![Pat. 3](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Pate3.png?raw=true)

Imágen 10. Temperature and humidity measurement instrument (Xu Lianggui, Lu Zhenglian)

# Lista de Requerimientos

![Req. F](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Req_F.png?raw=true)

![Req. NF](https://github.com/sebastianfranco1342/FundamentosdeDisenoGrupo6/blob/main/Carpetas%20del%20Proyecto/Im%C3%A1genes/Entr4_Req_NF.png?raw=true)

##  Bibliografía

- Aguirre, A. & Carlos, J. (2020). WO2020263069 - SYSTEM FOR THE REAL-TIME SYNCHRONISATION OF THE MEASUREMENTS OF A NETWORK OF WEATHER SENSORS WITH A CENTRAL SERVER. [https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2020263069&_cid=P10-LRJTOS-18100-1](https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2020263069&_cid=P10-LRJTOS-18100-1)

- Arshad, J.; Aziz, M.; Al-Huqail, A.A.; Zaman, M.H.u.; Husnain, M.; Rehman, A.U.; Shafiq, M. Implementation of a LoRaWAN Based Smart Agriculture Decision Support System for Optimum Crop Yield. Sustainability 2022, 14, 827. [https://doi.org/10.3390/su14020827](https://doi.org/10.3390/su14020827)

- EIC Group. (s.f.). Estación meteorológica WatchDog 2900ET.  [https://eiccontrols.com/es/inicio/395-estacion-meteorologica-watchdog-2900et.html](https://eiccontrols.com/es/inicio/395-estacion-meteorologica-watchdog-2900et.html)

- Gupta, R. et al., "WB-CPI: Predicción de cultivos basada en el clima en la India mediante análisis de big data", en IEEE Access, vol. 9, pp. 137869-137885, 2021. WB-CPI: Predicción de cultivos basada en el clima en India mediante análisis de big data | Diarios y revistas del IEEE | IEEE Xplore. [https://ieeexplore.ieee.org/document/9557312](https://ieeexplore.ieee.org/document/9557312)

- Hinge, G.; Mohamed, M.M.; Long, D.; Hamouda, M.A. Meta-Analysis in Using Satellite Precipitation Products for Drought Monitoring: Lessons Learnt and Way Forward. Remote Sens. 2021, 13, 4353. [https://doi.org/10.3390/rs13214353](https://doi.org/10.3390/rs13214353)

- Kaplun, D., Deka, S., Bora, A., Choudhury, N., Basistha, J., Purkayastha, B., Mazumder, I.Z., Gulvanskii, V., Sarma, K.K., Misra, D.D. An intelligent agriculture management system for rainfall prediction and fruit health monitoring (2024) Scientific Reports, 14 (1), art. no. 512,[https://www.scopus.com/inward/record.uri?eid=2-s2.0-85181464149&doi=10.1038%2fs41598-023-49186-y&partnerID=40&md5DOI: 10.1038/s41598-023-49186-y ](https://pubmed.ncbi.nlm.nih.gov/38177254/#:~:text=The%20proposed%20system%20based%20on,models%20for%20fruit%20health%20monitoring.)

- Liangui, X. & Zhenglian, L. Temperature and humidity measurement instrument. [https://patents.google.com/patent/CN104048700A/en](https://patents.google.com/patent/CN104048700A/en)

- Seeed Studio. (2023). Grove - Temperature & Humidity Sensor (DHT11). [https://www.seeedstudio.com/Grove-Temperature-Humidity-Sensor-DHT11.html](https://www.seeedstudio.com/Grove-Temperature-Humidity-Sensor-DHT11.html)

- Naylamp Mechatronics (s.f.). Sensor de Humedad del Suelo FC-28. [https://naylampmechatronics.com/sensores-temperatura-y-humedad/47-sensor-de-humedad-de-suelo-fc-28.html](https://naylampmechatronics.com/sensores-temperatura-y-humedad/47-sensor-de-humedad-de-suelo-fc-28.html)

- Wang, M., Wei, W., Zhang, M. & Zhang, Q. (2022). Farmland ecological environment meteorological monitoring device. [https://worldwide.espacenet.com/patent/search/family/083889349/publication/CN217766885U?q=pn%3DCN217766885U](https://worldwide.espacenet.com/patent/search/family/083889349/publication/CN217766885U?q=pn%3DCN217766885U)

- 
