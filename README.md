# taller-analisis-datos-101
Una introducción al análisis de datos con Python - PyconAR 2016.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Setting up!](#setting-up)
- [Temas del taller](#temas-del-taller)
- [Otros recursos](#otros-recursos)
  - [APIs](#apis)
  - [Portales de Datos](#portales-de-datos)
  - [Librerías](#librer%C3%ADas)
- [Herramientas usadas en el taller](#herramientas-usadas-en-el-taller)
- [Duración recomendada](#duraci%C3%B3n-recomendada)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

Para seguir el taller te recomendamos que sigas las instrucciones de instalación, clones el repositorio y sigas los jupyters de ejemplo, ejecutando celda por celda.

## Setting up!

Si estás dispuesto a cambiar tu instalación de python (o todavía no tenés una!) te recomendamos que instales el paquete [Anaconda](https://www.continuum.io/downloads). Ofrece un entorno preparado para hacer análisis de datos con python y ya viene con **dependencias pre-instaladas** para la mayoría de los paquetes que se usan.

Si no tenés Anaconda y usás Ubuntu:

`sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran`

Después clonate el repo e instalá las dependencias:

```
git clone https://github.com/datosgobar/taller-analisis-datos-101.git
pip install -r requirements.txt
```

## Temas del taller

1. Instalación de recursos (10')
2. Presentación (20/30')
3. Introducción a Jupyter ("hola mundo") (20')
4. Introducción a pandas + numpy + matplotlib (10')
5. Ejemplo: Análisis de datos agrícolas (50')

## Otros recursos

### APIs

* [COMTRADE](https://comtrade.un.org/data/doc/api/bulk/): API con datos de comercio exterior de Naciones Unidas.
* [Banco Mundial](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-api-documentation): API con indicadores de desarrollo de todo el mundo mantenida por el Banco Mundial.
* [FRED](https://research.stlouisfed.org/docs/api/): API con datos estadísticos y económicos principalmente de Estados Unidos pero también del mundo, mantenida por la Reserva Federal de Estados Unidos.

### Portales de Datos

#### Argentina: nivel nacional

* Portal Nacional: http://datos.gob.ar/
* Ministerio de Agroindustria: https://datos.magyp.gob.ar/
* Ministerio de Justicia: http://datos.jus.gob.ar/
* PAMI: http://datos.pami.org.ar:5000/dataset
* Ministerio de Energía: http://datos.minem.gob.ar/

#### Argentina: nivel provincial

* Ciudad de Buenos Aires: http://data.buenosaires.gob.ar/
* Jujuy: http://datos.gajujuy.gob.ar/
* Misiones: http://www.datos.misiones.gov.ar/

#### Argentina: nivel municipal

* Mar del Plata: http://www.mardelplata.gob.ar/opendata
* Bahia Blanca: http://gabierto.bahiablanca.gob.ar/datos-abiertos/
* Mercedes: http://datos.mercedes.gob.ar/home
* Pilar: http://datosabiertos.pilar.gov.ar/home
* Gualeguachú: http://data.gualeguaychu.gov.ar/
* Junín: http://www.junin.gov.ar/ga/
* Córdoba (ciudad): http://cdcordoba.opendata.junar.com/home/
* Mendoza (ciudad): http://datos.ciudaddemendoza.gov.ar/

#### Resto del mundo

* Unión Europea: https://www.europeandataportal.eu/
* Estados Unidos: https://www.data.gov/
* Reino Unido: https://www.data.gov.uk/

### Librerías

* [`pandas`](http://pandas.pydata.org/): Estructuras y herramientas para análisis de datos en Python.
* [`geopandas`](http://geopandas.org/): Extiende `pandas` con funcionalidades geoespaciales.
* [`numpy`](http://www.numpy.org/): Objetos y estructuras para computación científica en Python.
* [`matplotlib`](http://matplotlib.org/): Gráficos en Python.
* [`scikit-learn`](http://scikit-learn.org/): Machine learning en Python.

## Herramientas usadas en el taller

* [Anaconda](https://www.continuum.io/downloads) - Nuestra distro de python para análisis de datos.
* [Jupyter](http://jupyter.org/) - El notebook para ejecutar código dinámicamente.
* [API de COMTRADE](https://comtrade.un.org/data/doc/api/bulk/)
* [API del Banco Mundial](https://datahelpdesk.worldbank.org/knowledgebase/articles/889392-api-documentation)
* [DocToc](https://github.com/thlorenz/doctoc) - Para la tabla de contenidos

## Duración recomendada

2 horas
