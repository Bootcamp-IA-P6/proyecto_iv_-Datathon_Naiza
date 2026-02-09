
# EDA / TRATADO DE DATOS 
## Análisis de Tendencia de Mortalidad (Alabama) - Regresión Lineal

- Este proyecto realiza un análisis de datos sobre las muertes confirmadas en el estado de Alabama, utilizando técnicas de limpieza de datos y un modelo de aprendizaje automático (Machine Learning) para visualizar la tendencia temporal.

- 🚀 Funcionalidades
Limpieza de Datos: Eliminación automática de registros con valores nulos en columnas críticas.

Procesamiento Temporal: Conversión de fechas de calendario a formato numérico (días transcurridos) para facilitar el modelado matemático.

Modelado Predictivo: Implementación de una Regresión Lineal para identificar la tendencia de crecimiento.

Visualización: Generación de gráficos comparativos entre los datos reales y la predicción del modelo.

🛠️ Tecnologías Utilizadas
Python 3.x

Pandas: Manipulación y limpieza de estructuras de datos.

NumPy: Operaciones numéricas de alto rendimiento.

Scikit-Learn: Implementación del modelo de Regresión Lineal.

Matplotlib: Visualización de datos y gráficos.

📋 Estructura del Código
Filtrado: Se extraen únicamente los datos correspondientes al estado de Alabama (AL).

Normalización: Se establece una fecha base (Día 0) para medir el tiempo de forma relativa.

Entrenamiento: El modelo ajusta una línea recta que minimiza la distancia entre los datos reales de muertes y la predicción.

Gráfica: Se visualiza mediante un scatter plot (puntos azules) y una línea de tendencia (roja).

⚙️ Requisitos
Para ejecutar este proyecto, necesitas instalar las siguientes dependencias:

Bash
pip install pandas numpy matplotlib scikit-learn jupyter