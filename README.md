<h1 align='center'>
 <b>Proyecto Individual de Analisis de Datos</b>
</h1>

***
# <h1 align="center">**`Informe de Siniestros Viales`**</h1> 

<p align="center">
  <img src="https://www.infobae.com/new-resizer/rFmz0ihvY-P7qckmvMuvx8hyhlk=/992x558/filters:format(webp):quality(85)/cloudfront-us-east-1.images.arcpublishing.com/infobae/BGRNAAETQ5GIZNMVE24ZOSFZFU.jpg" alt="Imagen de portada siniestros viales. Fuente: Infobae">
</p>

## Contenido
1. [Información General](#información-gral)
2. [Contexto](#contexto)
3. [Datos](#datos)
4. [Tecnologías](#tecnologías)
5. [Ejecución](#ejecución)
6. [Primer KPI](#kpi1)
7. [Segundo KPI](#kpi2)
8. [Conclusión/es](#conclusión)
9. [Autor](#autor)

### Información General
***
Este proyecto tiene como objetivo abordar la problemática de los siniestros viales en la Ciudad de Buenos Aires mediante un análisis exhaustivo de datos proporcionados por el Observatorio de Movilidad y Seguridad Vial (OMSV). La iniciativa busca generar información valiosa que permita a las autoridades locales implementar medidas efectivas para reducir la cantidad de víctimas fatales en accidentes de tránsito. 

### Screenshot
![Image text](https://github.com/Guido097/DA_ProyectoInd_2/blob/main/src/Screenshot.jpg?raw=true)

## Contexto
***
En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país. Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.

Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.

## Datos
***
Para llevar a cabo este proyecto la identidad correspondiendte, en este caso el Observatorio de Movilidad y Seguridad Vial, que es un organismo que trabaja en la órbita del "Secretaría de Transporte del Gobierno de la Ciudad autónoma de Buenos Aires" brindó un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad de Buenos Aires durante el periodo 2016-2021. En este se encontraba datos de las víctimas tales como sexo, edad, rol en el siniestro, vehículo damnificado(en caso de haberlo) y vehículo acusado de propiciar el siniestro, entre otros.

Lo que se realizó fue un análisis de estos datos, una transformación de los mismos para poder dejar una base datos más aprovechable y una exposición de estos datos conjuntamente con la creación de dos medidores de desempeño(KPI) para evaluar el rendimiento del trabajo que se realiza en materia de seguridad vial.


## Tecnologías
***
Una lista de las tecnologías aplicadas en este proyecto:
* [Python](https://www.python.org/downloads/): Version 3.11.4
* [Power BI](https://apps.microsoft.com/detail/9NTXR16HNW1T?hl=es-ar&gl=AR)
* [Pandas](https://pandas.pydata.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)

## Ejecución
***
1. Clone este repositorio en su máquina local.
2. Asegúrese de tener todas las dependencias instaladas (pandas, matplotlib, seaborn, etc.).
3. Ejecute el notebook de análisis exploratorio (EDA.ipynb) para obtener información detallada sobre los datos.
4. Explore el dashboard interactivo (VisualizacionKPI's.pbix) para visualizar patrones y tendencias.

## Primer KPI
***
![Image text](https://github.com/Guido097/DA_ProyectoInd_2/blob/main/src/kpi1.jpg?raw=true)

El primer KPI se ve cumplido solo en algunos casos, como se ve en la captura, no en todos los semestres se logró una disminución del 10% de las víctimas fatales en siniestros, pero se puede apreciar que mientras más pasa el tiempo se ve una tendencia de baja en estos casos.


## Segundo KPI
***
![Image text](https://github.com/Guido097/DA_ProyectoInd_2/blob/main/src/kpi2.jpg?raw=true)

El segundo KPI que busca la disminución de un 7% los siniestros mortales para motocicletas se vio en menor medida cumplido ya que como se ve en la captura, en 2019 y 2020 cayó la cantidad de víctimas pero para 2021 se vió un fuerte incremento de estos casos.


## Conclusión/es
***
Luego de haber estado trabajando en este informe se llega a la conclusión de que las medidas que se llevan a cabo por el gobierno en materia de seguridad vial están llevando a una pequeña disminución paulatina a través de los años, viendo como en el 2016 las víctimas fatales fueron 131 y para el 2021, en cambio se alcanzó la cifra de 95 víctimas fatales. Sin embargo, esas cifras siguen siendo muy altas y no lineales, por lo que en algunas situaciones se ven apercibidos los medidores de rendimiento planteados para este informe. Decimos que estas cifras son altas porque de acuerdo con informes de la "Municipalidad de Córdoba"([Link](https://drive.google.com/file/d/1TlbDwwNGV_s7Ddw8BcQsEvr9NlmsCatN/view)) para el mismo período(2021) se registraron 66 víctimas fatales siendo en territorio(576km2 contra 203km2) un %288 más grande.

Este proyecto busca no solo abordar los requisitos mínimos sino también desafiarse a sí mismo para ofrecer un análisis completo y competente en la temática de seguridad vial en Buenos Aires.

## Autor
***
Link de Github: https://github.com/Guido097

Link de Linkedin: https://www.linkedin.com/in/guido-lujan/
