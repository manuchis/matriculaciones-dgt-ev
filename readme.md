# Procesamiento de datos de matriculaciones DGT

Datos obtenidos de https://sedeapl.dgt.gob.es/WEB_IEST_CONSULTA/microdatos.faces

## Cómo se usa
Dentro del repositorio se encuentran dos ficheros Notebooks:
- **Parser** Permite procesar los ficheros mensuales de la DGT que se descargan del sitio, se deben colocar los ficheros en la carpeta *data* y colocar los nombres de los ficheros que se desean procesar. Este exportará dos JSON, uno para todos los registros `registros.json` y otro solo para coches EV `registros_bev.json`. 
- **EVS** Procesa y permite visualizar los datos de los coches EV.

### Requisitos

Requirements for the software and other tools to build, test and push
- Python 3
- Jupyter Notebook
- Pandas
- MatPlotLib

## Autores

  - **Manuel Portela**
    [@Manuchis](https://manuchis.net)

## Licencia

El proyecto está licenciado bajo la licencia [GNU v3](LICENSE).
