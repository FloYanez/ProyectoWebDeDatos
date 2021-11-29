# ProyectoWebDeDatos
Proyecto del curso CC7220 La Web de Datos, toma un dataset de MyAnimeList y lo transforma a RDF.

# Dataset
El dataset utilizado se descargó de kaggle:
https://www.kaggle.com/azathoth42/myanimelist

# Correr el codigo

Ejecutar
`bash run.sh`

A continuación, se explica lo que hace run.sh:
## Crear un ambiente virtual

Para instalar _pip_ (si es que no está instalado) y _venv_, correr:

`sudo apt install python3-pip python3-venv`

Para crear un ambiente virtual, correr:

`python3 -m venv .venv`

Para activar el _venv_ correr:

`source .venv/bin/activate`

## Instalar los paquetes

Correr:

`python3 -m pip install -r requirements`
