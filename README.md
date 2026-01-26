# TelecomX

📊 Proyecto: Análisis de Evasión de Clientes (Churn)
📝 Descripción del Proyecto
Este proyecto consiste en un Análisis Exploratorio de Datos (EDA) enfocado en identificar los factores que influyen en la pérdida de clientes de una compañía de servicios. El objetivo es transformar datos brutos en insights estratégicos para reducir la tasa de abandono y mejorar la retención.

🚀 Funcionalidades Principales
Limpieza de Datos: Procesamiento de variables y normalización de la columna objetivo churn.

Análisis de Variables Categóricas: Identificación de patrones en tipos de contrato, servicios de internet y métodos de pago.

Análisis de Variables Numéricas: Estudio de la antigüedad del cliente (tenure) y cargos financieros.

Visualizaciones Avanzadas: Uso de subplots, histogramas con tendencia (KDE) y gráficos de caja (Boxplots) para una comunicación clara.

🛠️ Tecnologías y Dependencias
El proyecto está desarrollado en Python utilizando las siguientes librerías:

Pandas: Para la manipulación y limpieza de estructuras de datos.

Matplotlib: Para la generación de la estructura base de los gráficos.

Seaborn: Para visualizaciones estadísticas avanzadas y estilizadas.

📈 Hallazgos Clave (Insights)
Punto de Riesgo Crítico: La mayor tasa de abandono ocurre entre los 0 y 6 meses de antigüedad.

Impacto del Contrato: Los contratos "Mes a mes" presentan 1,655 retiros, siendo el mayor foco de fuga.

Efecto de la Tecnología: Los usuarios con Fibra Óptica tienen una mayor tendencia al retiro (1,297 casos).

📋 Cómo Ejecutar el Proyecto
Clona este repositorio.

Asegúrate de tener instalado Python 3.x.

Instala las dependencias necesarias:

Bash
pip install pandas matplotlib seaborn
Abre el archivo .ipynb en Jupyter Notebook o VS Code para visualizar el flujo del análisis.
