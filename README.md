# Analisis de datos Siniestros Viales 

<div style="display: flex; align-items: center;">
    <img src="https://img.shields.io/badge/STATUS-EN%20DESAROLLO-green" />
    <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/bkmay1417/Analisis_de_datos_Siniestros_Viales" />
</div>
<p id="readme-top"></p>

[Introducion](#Introducion) | [Datos](#Datos) | [Dashboard](#Dashboard) | [KPI](#KPI) | [Conclusiones](#Conclusiones) | 

![Descripción de la imagen](https://4.bp.blogspot.com/-7wb49nj_4ok/VPQesmuzrnI/AAAAAAAABH8/Q3wevmpdn7o/s1600/Imagen22.png)

## Introducion

En el contexto de una ciudad dinámica como Buenos Aires, los siniestros viales representan un desafío constante que impacta tanto en la seguridad pública como en la calidad de vida de sus habitantes. Estos eventos, que abarcan desde colisiones entre vehículos hasta atropellos de peatones, tienen repercusiones que van desde daños materiales hasta pérdidas humanas irreparables. Este proyecto se centra en el análisis de datos relacionados con siniestros viales en Buenos Aires, con el objetivo de proporcionar información detallada y perspicaz para informar políticas públicas y medidas de seguridad que contribuyan a reducir la incidencia y las consecuencias de estos incidentes. Utilizando un conjunto de datos específico que abarca los años 2016-2021, se busca profundizar en la comprensión de estos eventos y así promover un entorno vial más seguro y protegido para todos los ciudadanos.

## Tecnologías utilizadas


![Python](https://img.shields.io/badge/-Python-333333?style=flat&logo=python) ![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas) ![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy) ![Matplotlib](https://img.shields.io/badge/Matplotlib-333333?style=flat&logo=WordCloud) ![Seaborn](https://img.shields.io/badge/Seaborn-333333?style=flat&logo=Seaborn) ![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-333333?style=flat&logo=visual-studio-code&logoColor=007ACC) ![Jupyter Notebooks](https://img.shields.io/badge/-Jupyter_Notebook-333333?style=flat&logo=jupyter)  ![Power BI](https://img.shields.io/badge/PowerBI-333333?style=flat&logo=powerbi) ![DAX](https://img.shields.io/badge/-DAX-333333?style=flat&logo=powerbi)


## Datos

Los datos brindados fueron una hechos.csv con los datos de los acidentes desde 2016 a 2021 y lesiones.xlsx con los datos de 2019 a 2021 estos datos fueron pasados por un proceso de ETL ( extracción, transformación y carga ) y EDA ( análisis exploratorio de datos ) en  este proceso se revisaron valores nulos, outliers, duplicados se normalizaron los datos y se inputaron datos dependiendo del caso ya sea con la media o moda una vez hecho eso se procedio analizar los datos por medio de graficos para poder llegar un comprecion mas profunda   

## Dashboard

Este dashboard se compone de 6 pagina siendo la primera la portada y la ultima las conclusiones una con una analisis por ubicaciones en caba y otra enfocada en el analisis de la victimas luegos dos hojas para los kpi corespondientes 

<p align="center"><img src="img/dash.gif" alt="dash"  height="100%" width="100%" /></p>

## KPI 

Se realizaron los siguientes KPI

- *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*.
  
  Definimos a la **tasa de homicidios en siniestros viales** como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.
  Su fórmula es: <center>
$\frac{\text{Número de homicidios en siniestros viales}}{\text{Población total}} * 100000$<br><br>
</center >
  
- *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*.
  
  Definimos a la **cantidad de accidentes mortales de motociclistas en siniestros viales** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal.
  Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: <center>
$\frac{\text{Víctimas en moto del año anterior - Víctimas en moto del año actual}}{\text{Víctimas en moto del año anterior}}*100$<br>
<br></center>



## Conclusiones

- Los siniestros viales con patrones destacados son la hora de la mañana, la edad de 20 a 35 años y el trimestre más crítico siendo el cuarto por las fiestas.

- Los motociclistas son las principales víctimas, con la comuna 1 y la zona sur de Buenos Aires registrando la mayor cantidad de accidentes.

- La General Paz es la calle con más accidentes, y las avenidas son las más peligrosas, representando el 61.64% de los siniestros.

- La disminución de los siniestros a partir de 2019, con un mínimo en 2020, esta relacionada con la pandemia de COVID-19.







## Gracias por llegar hasta aqui

![gracias](img/Animation-gracias.gif?raw=true)

## Desarrolladores

| [<img src="https://avatars.githubusercontent.com/u/163685041?v=4" width=115><br><sub>Michael Martinez</sub>](https://github.com/bkmay1417) |
| :---: |

Copyright (c) 2024 [Michael Martinez] yam8991@gmail.com
