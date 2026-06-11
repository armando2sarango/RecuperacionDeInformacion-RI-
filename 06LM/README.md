# Sistema de Recuperación de Información - Examen 1Bim

Este repositorio contiene la solución del Examen del Primer Bimestre para la materia de Recuperación de Información (2026-A).

## Integrante
* **Nombre:** José Armando Sarango Cuenca

## Requisitos Previos y Estructura de Datos
Para ejecutar el notebook de manera reproducible, asegúrese de contar con la siguiente estructura de archivos dentro del directorio del proyecto:

```text
├── [SarangoJose]_ex1bim_ir26a.ipynb   # Notebook Principal Ejecutado
├── requirements.txt                   # Dependencias del Sistema
├── README.md                          # Instrucciones de Ejecución
└── Data/                              # Carpeta de Datos (Omitida en Git)
    ├── rotten_tomatoes_movies.csv
    └── rotten_tomatoes_critic_reviews.csv


## Instrucciones de Ejecución

### Clonar el repositorio

```bash
git clone <URL_DE_TU_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>
```

### Instalar las dependencias obligatorias

Se recomienda utilizar un entorno virtual limpio (`venv`).  
Instale los paquetes requeridos ejecutando:

```bash
pip install -r requirements.txt
```

### Ejecutar el Notebook

Inicie el servidor de Jupyter o abra el entorno en su IDE de preferencia (VS Code, Jupyter Lab, etc.):

```bash
jupyter notebook [SarangoJose]_ex1bim_ir26a.ipynb
```

Asegúrese de ejecutar las celdas de forma secuencial de inicio a fin.  
La primera ejecución descargará automáticamente el modelo `word2vec-google-news-300` de las APIs oficiales de Gensim y los tokenizadores de NLTK.
