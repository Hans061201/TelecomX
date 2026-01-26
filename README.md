# TelecomX

# 📊 Análisis de Evasión de Clientes - Telecomunicaciones

## 📝 Descripción del Proyecto
Este proyecto desarrolla un **Análisis Exploratorio de Datos (EDA)** detallado sobre la pérdida de clientes en una empresa de telecomunicaciones. El objetivo es identificar los patrones demográficos, de servicio y financieros que correlacionan con la evasión para orientar acciones estratégicas de retención.



## 🚀 Funcionalidades y Flujo de Trabajo
1. **Limpieza de Datos**: Tratamiento de nulos y estandarización de la variable objetivo `Churn` (0: Continúa, 1: Se retiró).
2. **Análisis Categórico**: Evaluación del impacto de variables como género, tipo de contrato y servicios contratados.
3. **Análisis Numérico**: Estudio de la antigüedad (`tenure`) y cargos financieros mediante histogramas de densidad y boxplots.
4. **Visualización Estética**: Uso de estilos limpios (sin bordes superiores/derechos) y leyendas personalizadas para facilitar la comunicación de resultados.


## 🛠️ Tecnologías Utilizadas
* **Python 3.x**
* **Pandas**: Manipulación de datos.
* **Matplotlib & Seaborn**: Generación de gráficos de alta fidelidad y visualización estadística.



## 📈 Insights Principales (Hallazgos)

### 1. El Factor Contrato
Los clientes con contrato **"Mes a mes"** son los más propensos a retirarse (**1,655 casos**), representando el mayor riesgo operativo.

### 2. Periodo Crítico de Retención
Se identificó una **fuga masiva** durante los primeros **0 a 6 meses** de servicio. Una vez superados los **20 meses**, la lealtad del cliente aumenta exponencialmente.



### 3. Servicio de Internet
Los usuarios de **Fibra Óptica** presentan una tasa de abandono significativamente mayor (**1,297**) que otros segmentos, sugiriendo posibles problemas técnicos o de precio en esta tecnología.



## 📋 Cómo Ejecutar este Proyecto
1. Clona el repositorio.
2. Instala las dependencias necesarias:
   ```bash
   pip install pandas matplotlib seaborn
3. Ejecuta el archivo .ipynb en tu entorno preferido (Jupyter, VS Code, Google Colab).

