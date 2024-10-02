<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>
# <h1 align=center> *Telecomunicaciones* </h1>

## 1. Introducion
    Este proyecto individual tiene como fin informar los hallazagos obtenidos a traves de un Analisis Exploratorio de Datos, a un Data Sets con informacion sobre conexiones a internet de la Republica Argentina, por periodos 2014 - 2024.
    La informacion fue descargarda de la pagina web del ENACOM.

## 2. Instalación y Requisitos
  <h3>Requisitos:</h3>
  <ul>
    <li>Python 3.10 o superior</li>
    <li>pandas</li>
    <li>numpy</li>
    <li>matplotlib.pyplot</li>
    <li>seaborn</li>
    <li>matplotlib.pyplot</li>
    <li>itertools</li>
    <li>sklearn.preprocessing</li>

  </ul>
   <h3>Pasos de instalación:</h3>
    <ol>
    <li>Clonar el repositorio: <code>git clone https://github.com/moralespbl/MoralesPI_01.git</code></li>
  

## 3. Estructura del Proyecto
- `DataSets/`: Contiene los archivos de datos utilizados en el EDA.
- `DataSets/EDA_Internet.ipynb`: Contiene el EDA.
- `README.md`: Archivo de documentación del proyecto.

## 4. Uso y Ejecución
1. Para ejecutar el EDA, abrir el notebook `EDA_Internet.ipynb`. El notebook guiará a través de las diferentes etapas cumpliendo lo solicitado por las consignas.
2. En notebook encontrara el analisis de datos realizado y obtendra como resultado varios Data Frames que son los utilizados en Power BI. Se trabajo solamente con la informacion de Internet.

## 5. Datos y Fuentes
Para ingresar a los [Datos](https://indicadores.enacom.gob.ar/datos-abiertos) crudos.

## 6. Metodología
Una vez descargados los datos nos encontramos con el DataSets de Internet, se descargan cada hoha en DataFrames distintos.
Se crean Funciones que reemplazan los nombres de las columnas y otra para informar sobre valores faltantes.

A medida que se avanza con el analisis data frame por data frame se van renombrando las columnas y se verifican los valores faltantes y nulos.

Las concluciones extraidas de cada uno se encuentran plasmada en el mismo orden.

Se crea una Data frame conbinando data de varios para realizar una matriz de correlaciones y encontrar asociaciones, no sin antes escalar los datos, normalizando los mismos.

Para finalizar se exportan los data frames resultantes como archivos csv para que sean consumidos por Power BI.

## 7. Resultados y Conclusiones
Se cumplieron con las consignas solicitadas.
Existe un crecimiento desigual entre las provincias, los usuarios prefieren tecnologias modernas.

## 8. Autor:
Este proyecto fue realizado por Pablo Alberto Morales Valeriano

## 9. Links Entregables:
- [Repo de github](https://github.com/moralespbl/MoralesPI_02.git)
