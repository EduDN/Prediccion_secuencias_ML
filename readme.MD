# Predicción de Demanda de Secuencias - Ingeniería en Informática

## Descripción

Este repositorio contiene una aplicación web interactiva creada con Streamlit y potenciada con Inteligencia Artificial (IA), Machine Learning (ML) para predecir la demanda de secuencias de clases para el plan 2010 y 2021 de la carrera de Ingeniería en Informática. La aplicación utiliza archivos de datos históricos, preprocesa estos datos y aplica un modelo de regresión lineal, un método de aprendizaje automático, para realizar las predicciones.

## Funcionamiento

1. El usuario debe cargar tres archivos de Excel que contienen los datos históricos. Estos archivos deben incluir detalles como el número de alumnos que ingresaron, el número de bajas temporales y definitivas, el número de reprobados y la información del semestre.

2. La aplicación preprocesa estos datos y realiza una codificación OneHotEncoder para convertir la variable categórica "Semestre" en una serie de variables binarias.

3. El programa divide el dataset por semestre y utiliza un modelo de Regresión Lineal, una técnica de Inteligencia Artificial, para predecir la demanda de secuencias para cada materia en cada semestre.

4. La aplicación también proporciona una interfaz de usuario interactiva que permite al usuario seleccionar un semestre específico para visualizar la demanda de secuencias para todas las materias en ese semestre.

5. Finalmente, la aplicación muestra un resumen en el panel lateral que incluye el total de secuencias requeridas por semestre y la suma total de secuencias para todos los semestres.

## Instalación

Para ejecutar este código, necesita tener instalados Python, Streamlit y los paquetes necesarios. Puedes instalar las dependencias necesarias con pip:

```shell
pip install -r requirements.txt
```

Si necesitas instalar Streamlit, puedes hacerlo con el siguiente comando:

```shell
pip install streamlit
```

## Uso

Para iniciar la aplicación, navegue hasta el directorio que contiene el archivo del código en la línea de comandos y escriba:

```shell
streamlit run nombre_del_archivo.py
```

La aplicación se iniciará en su navegador web.

## Contribuir

Las contribuciones a este repositorio son bienvenidas. Por favor, antes de realizar cualquier cambio, abra un issue para discutir lo que le gustaría cambiar.