# <h1 align="center">**`PROYECTO INDIVIDUAL 2 🚀`**</h1>
# <h2 align="center"> **`DATA ANALYST`** </h2>
# <h4 align="center"> **`LEANDRO IBARRA`** </h4>

Hola! Cómo estan? En este repositorio se van a encontrar con el segundo proyecto individual de la carrera Data Science de Soy Henry. Espero que lo disfruten!!!😁

### `INDICE:`

+ *Data PowerBI:* Esta carpeta continen los Dataframes limpios listos para utilizar en PowerBI

+ *Datasets:* Contiene los datos nacionales que utilizamos y analizamos.

+ *EDA y ETL adicional:* En esta carpeta se encuentran los archivos que fueron visualizados y tranformados pero que no fueron tenidos en cuenta por distintos motivos paara el desarrollo del proyecto.

+ *EDA_y_ETL.ipynb:* Este archivo posee los datos que si se van a usar en el proyecto. En el obviamente estan las visualizaciones y el proceso de transformación que le realizamos. Cuenta con muchos graficos explicados para su mejor comprensión.

### `TEMA:`

En esta ocasión nos encontramos con un proyecto sobre `TELECOMUNICACIONES` en la República Argentina. 🌐


<p align="center">
  <img width="300" height="180" src="https://github.com/leaibarra/proyecto_2_lea/assets/126922100/e76f1eea-7af1-4b08-82e5-e6258838c26b">
</p>





Por nuestra parte (hipoteticamente) nos contrato la empresa de:  <img src="https://github.com/leaibarra/proyecto_2_lea/assets/126922100/3ccd8a7b-860c-4259-9636-e1f47f86eef8" width="100"> 

DirecTV es una empresa  proveedora de televisión vía satelital, por otra parte también brinda servicio de internet por medio de fibra óptica.
La razón por la cual fuimos contratados fue la necesidad por parte de la empresa en querer crecer en el interior del país arrancando por Mendoza.

### `¿Por qué mendoza?`

DirecTV cuenta con cobertura de internet en algunas localidades de: 

+ Provincia de Buenos Aires

+ CABA

+ Provincia de Mendoza ( aquÍ desde hace aproximadamente 10 años se incorporó en brindar servicios de internet por fibra óptica) 

Para ser mas exactos las localidades de Mendoza que tienen cobertura son: Godoy Cruz, Guaymallén, Las Heras y Luján de Cuyo.

###### La información sobre la provincia de Mendoza fue sacada directamente hablando con operadores de la empresa de DirecTV.
###### También fue sacada de [Selectra](https://selectra.com.ar/empresas/directv/internet#cobertura-internet-dtv) la información.

Argentina cuenta con cableado de fibra óptica en una gran parte de su terrritorio, obviamente en ciudades con más cantidad de habitantes.

![aaaaa (1)](https://github.com/leaibarra/proyecto_2_lea/assets/126922100/0939f849-956e-4523-b2c4-1c80f791dd69)
###### Grafico sacado de: [Gobierno de Argentina](https://www.argentina.gob.ar/jefatura/innovacion-publica/telecomunicaciones-y-conectividad/conectar/que-es-la-red-federal-de).

Argentina es un pais muy apasionado por el fútbol, por lo tanto, en el año 2022 por causa del Mundial de fútbol, que se realizo en Qatar, la población Argentina hizo inversiones comprando televisores y haciendose del servicio de DirecTV para poder ver los partidos. Pero solo contrataban la parte de televisión via satelite.

La intencion de DirecTV es obtener la mayor cantidad de clientes en Mendoza en donde las localidades que ya cuentan con fibra óptica y el servicio de DirecTV se hagan de los servicios de internet por fibra óptica también. Obviamente también se quiere llegar a la gente que no posee ningun tipo de servicio de DirecTV.

También su idea es empezar a llegar a otras localidades de Mendoza donde todavía no tienen cobertura pero si cuantan con cableado de fibra óptica.

A largo plazo, anhelan con obtener clientes de esa zona; apenas se produzcan nuevos cableados de fibra óptica en localidades donde no cuentan con ella, y así empezar a crecer aún más.

## `¿Cuál es nuestro trabajo?`

Nuestro proyecto se centrara en realizar un trabajo de Data Analyst y mostrarles los datos con los que contamos, para que ellos puedan ver que tan factible es crecer en la ciudad de Mendoza y ayudarles con las visualizaciones así deciden que camino pueden tomar y los posibles resultados con los que se encontraran.

Para poder llevarlo a cabo realizamos la carga de los [datos](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/) sobre internet que sacamos de la página oficial del gobierno.

Luego avanzamos con el EDA y ETL convirtiendo los Datasets en Dataframes y utilizamos notebooks de Python (en Visual Studio Code). Después con la ayuda de librerias como pandas, matplotlib y seaborn lo hicimos posible. 

Luego de eso tranformamos los Dataframes en archivos csv para poder abrirlos en PowerBi asi creamos un Dashboard muy interactivo y con una eleccion de graficos coherentes, que contiene filtros permitiendo explorar detalladamente los datos. Ahi incluimos los Kpis que vamos a utilizar.

## `KPIs que utilizaremos:`


+ **Accesos:** Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia. La fórmula es la siguiente:

    *Kpi acceso*= [( internet cada 100 hogares proximo - internet cada 100 hogares actual ) / internet cada 100 hogares actual ] * 100

+ **Penetración del Mercado:** Calcular la proporción de partidos que ya tienen acceso al servicio de internet de fibra óptica en comparación con el total de partidos que hay. La fórmula sería:
  
  *Kpi Penetración del Mercado* = (partidos con acceso a fibra optica / Total de partidos) * 100

+ **Accesos de Fibra Óptica:** Calcular el porcentaje de Accesos de Fibra Óptica en comparación con el periodo anterior. La fórmula seria:
  *Kpi Accesos de Fibra Óptica* = [(Accesos de Fibra Óptica proximo - Accesos de Fibra Óptica actual) / Accesos de Fibra Óptica actual] * 100







