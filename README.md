
# EDA / TRATADO DE DATOS 
## Análisis de Tendencia de Mortalidad (Alabama) - Regresión Lineal

- Este proyecto realiza un análisis de datos sobre las muertes confirmadas en el estado de Alabama, utilizando técnicas de limpieza de datos y un modelo de aprendizaje automático (Machine Learning) para visualizar la tendencia temporal.

- 🚀 Funcionalidades
Limpieza de Datos: Eliminación automática de registros con valores nulos en columnas críticas.

- Procesamiento Temporal: Conversión de fechas de calendario a formato numérico (días transcurridos) para facilitar el modelado matemático.

### Modelado Predictivo: Implementación de una Regresión Lineal para identificar la tendencia de crecimiento.

- Visualización: Generación de gráficos comparativos entre los datos reales y la predicción del modelo.

- 🛠️ Tecnologías Utilizadas
Python 3.12, numpy, pandas, scikit learn, matplotlit

Pandas: Manipulación y limpieza de estructuras de datos.

NumPy: Operaciones numéricas de alto rendimiento.

Scikit-Learn: Implementación del modelo de Regresión Lineal.

Matplotlib: Visualización de datos y gráficos.

📋 Estructura del Código
Filtrado: Se extraen únicamente los datos correspondientes al estado de Alabama (AL) para la regresión líneal, utilizando la tecnología de scikit learn.

- Es importante que ubiques un dataset para tu tratado de datos ¿Cómo lo vas hacer? Descargar el archivo en tu proyecto 
## Recomendación 
- Aplicar las siguientes extensiones:
- jupyter, python extension pack, coolab
  
### Step 1 ) Tu entorno virtual tiene que estar activado 
- python -m venv .ven --> para instalar el entorno 
- source .venv/Script/activate --> para activar entorno en Window 
  ### Step 2 ) Crea tu archivo gitignore
  - En el archivo coloca tu entorno virtual, y tus librerias que puedan afectar el rendimiento de tu repo 
  - for example __pycache__/
*.py[cod]
*$py.class

  ### step 3 ) En la carpeta local coloca el archivo csv 
  ### step 4 ) creamos un archivo con la extencion ipynnb

  ### En el notebook (analisis.ypynb) Visualizaras el formato Markdow con la explicación del código 

⚙️ Requisitos
Para ejecutar este proyecto, necesitas instalar las siguientes dependencias:

pip isnstall

Bash
pip install pandas numpy matplotlib scikit-learn jupyter