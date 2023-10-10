# Telecomunicaciones
Bienvenidos

Este es un proyecto en donde analizamos datos de la Entidad de Comunicacion de la Nacion Argentina para evaluar si conviene invertir, dónde y en qué tecnologias.
Realizamos el Analisis de Datos Exploratorios en un Notebook de Jupyter y los visualizamos en un Dashboard de Power BI
<img src=https://github.com/pablozmr/telecomunicaciones_pillofon/blob/main/image/home.png>
## Requerimientos del proyecto:
Para poder trabajar con los datos de forma deseada, lo primero que debemos hacer es ver la calidad de los datos en los datasets que disponemos, luego manipularlos de tal forma que nos sean utiles. Para la transformacion de los datos utilizamos las librerias Pandas y Numpy de python.
Luego, para su analisis utilizamos las librerias matplotlib y Seaborn para graficar los datos y poder sacar conclusiones. El ultimo paso es la creacion del Dashboard en Power BI

Estructura de contenido

- Dataset:
    - accesos_tecnologia.csv: Este archivo contiene la cantidad de accesos a traves de diferentes tecnologias desde el 2014 al tercer trimestre del 2022.
    - calendario.csv: Este archivo contiene fechas en formato de fecha, año, trimestre y año_trimestre.
    - ingreso.csv: Este archivo contiene los ingresos en miles de pesos, trimestrales desde el 2014 al tercer trimestre del año 2022.
    - listado_localidades.csv: Este archivo contiene la cantidad de accesos a traves de diferentes tecnologias, de cada localidad de las provincias.
    - mbps.csv: En este archivo se encuentran los datos de la media de velocidad de bajada por provincia en el lapso del 2014 al tercer trimestre del 2022.
    - penetracion.csv: En este archivo estan los datos de accesos a internet cada 100 hogares por provincias en el lapso del 2014 al tercer trimestre del 2022.
    - provincia.csv: Este archivo contiene un listado de provincias unicas que aparecen en los demas .csv.
    - tecnologia.csv: Este archivo contiene los accesos por tecnologia de cada provincia en el lapso del 2014 al tercer trimestre del 2022.
    - velocidad.csv: Este archivo contiene los accesos por velocidad de cada provincia en el lapso del 2014 al tercer trimestre del 2022.
- Image:
    - home.png
    - acceso.png
    - tecnologia.png
    - dashboard1.png
    - dashboard2.png
- EDA_telecomunicaciones.ipynb: Este archivo es un Notebook Jupyter que contiene el Analisis Exploratorio de los Datos y sus conclusiones para el desarrollo del Dashboard.
- PilloFon_Dashboard.pbix: Este archivo .pbix contiene el Dashboard de Power BI.
- PilloFon_Dashboard.pdf: Este archivo .pdf contiene capturas de cada pagina del Dashboard de Power BI.
  
## Sobre el Dashboard

  Este tablero de datos interactivo esta creado con datasets del extraidos de la pagina de ENACOM, procesados de manera local. 
  
Tiene una introduccion, donde se analiza en primer lugar el acceso promedio a internet de la poblacion en Argentina para evaluar si es rentable invertir segun la curva de su crecimiento.
<img src=https://github.com/pablozmr/telecomunicaciones_pillofon/blob/main/image/acceso.png>

  Luego analizamos el crecimiento de la demanda de tecnologias aplicadas para llevar el internet al hogar y la cantidad de accesos historico que tiene cada una. Sacamos la conclusion de que es muy favorable invertir en la tecnologia de Fibra Optica, ya que no representa ni siquiera un 25% del total de las tecnologias establecidas y las demas tecnologias estan en caida.

<img src=https://github.com/pablozmr/telecomunicaciones_pillofon/blob/main/image/tecnologia.png>

  Y por ultimo presentamos el Dashboard en dos partes. 
  
En la primera parte podemos analizar mejor la demanda de las tecnologias totales y la diferencia con la demanda de la tecnologia de fibra optica año a año. Tambien podemos analizar en profundidad el crecimiento de las tecnologias. 

Tenemos establecidos dos KPIs como Objetivos de crecimiento anual:
- Media de accesos a internet cada 100 habitantes: 7% por año.
- Demanda de Fibra Optica: 25% por año.

Estos kpis se pueden filtrar por año y por provincia.

<img src=https://github.com/pablozmr/telecomunicaciones_pillofon/blob/main/image/dashboard1.png>

  En la segunda parte apreciamos el crecimiento del total de los ingresos (en miles de pesos) y el crecimiento del promedio de la velocidad media de bajada (mbps) a traves del tiempo (2014 al tercer trimestre del 2022).
  
Ademas podemos analizar la diferencia porcentual anual de los ingresos, el historico de la distribucion de tecnologias por provincia y la distribucion de velocidades por provincia y por año.

Tenemos establecidos tres KPIs como Objetivos de crecimiento anual:
- Total de ingresos: 40% por año.
- Demanda de velocidades mayores a 30 Mbps: 50% por año.
- Media de velocidad de bajada: 12%
    
El primer KPI se puede filtrar solo por año, mientras que los ultimos dos se pueden filtrar por año y por provincia.

<img src=https://github.com/pablozmr/telecomunicaciones_pillofon/blob/main/image/dashboard2.png>

## Conclusiones

Comprobado por el analisis, estos crecimientos son correlativos entre si. La demanda de velocidades mayores a 30mbps estan dadas, en paralelo, con el crecimiento de la demanda de Fibra Optica. Lo que implica que los ingresos, la velocidad media de bajada y la media de accesos a internet cada 100 hogares crezca proporcionadamente.

## Fuente

https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/

## Contacto

pabloszmr@gmail.com

www.linkedin.com/in/pablozmr/


  
