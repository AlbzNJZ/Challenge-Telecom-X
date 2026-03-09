# Challenge-Telecom-X
Autor: Eduardo Albizo 

💡 Descripción del Proyecto

Este proyecto analiza los factores que provocan la evasión de clientes en Telecom X. Se trabajó con un dataset de más de 7,000 registros aplicando un completo proceso de ETL (Extracción, Transformación y Limpieza) y un Análisis Exploratorio de Datos (EDA) para descubrir patrones de abandono y generar recomendaciones estratégicas que ayuden a mejorar la retención de clientes.

🛠️ Tecnologías y Herramientas

Lenguaje: Python 3

Manipulación de datos: pandas, numpy

Visualización de datos: matplotlib, seaborn

Entorno: Jupyter Notebook / Google Colab

🚀 Cómo Ejecutar el Proyecto

Clonar el repositorio y descargar el archivo TelecomX_Data.json al mismo directorio que el notebook principal.

Abrir el notebook Analisis_Evasion_TelecomX.ipynb.

Ejecutar las celdas secuencialmente, desde la carga de datos hasta las visualizaciones y análisis de correlación.

El notebook está preparado para ejecutarse de manera interactiva, permitiendo explorar los datos y generar gráficos claros paso a paso.

📈 Estructura del Análisis

Carga de Datos: Lectura del JSON y verificación de la estructura.

Transformación: Desanidamiento de columnas, limpieza de registros incompletos y estandarización de variables.

Análisis Exploratorio:

Estadísticas descriptivas de variables numéricas.

Distribución de la variable objetivo Evasion.

Relación de variables categóricas y numéricas con la evasión.

Mapa de correlación para identificar relaciones significativas.

Resultados y Recomendaciones: Insights clave y estrategias para reducir la tasa de churn.

🔹 Hallazgos Más Relevantes

Tasa de abandono: 26.6% de los clientes actuales han cancelado su servicio.

Contratos cortos = mayor riesgo: Clientes con contratos mensuales representan ~70% de las cancelaciones; la retención mejora en contratos de 1–2 años.

Fibra óptica: Usuarios con internet de fibra óptica presentan mayor churn que los de ADSL.

Vulnerabilidad temprana: Mediana de antigüedad de clientes que abandonan: 10 meses. Si un cliente supera el primer año, es muy probable que permanezca.

Sensibilidad al precio y métodos de pago: Facturación alta y pagos por cheque electrónico muestran ligera asociación con mayor probabilidad de abandono.

🎯 Recomendaciones Estratégicas

Prioridad Alta: Incentivar contratos a largo plazo y auditar el servicio de fibra óptica.

Prioridad Media: Implementar programas de fidelización temprana durante los primeros 10 meses del cliente.

Prioridad Baja: Revisar precios y métodos de pago para mejorar la retención y satisfacción del cliente.

📊 Visualizaciones Clave

Mapa de calor de correlaciones entre variables numéricas y evasión.

Distribución de churn por tipo de contrato y servicio de internet.

Comparación de facturación y gasto diario entre clientes que permanecen y los que abandonan.

Estas visualizaciones facilitan la toma de decisiones basada en datos claros y medibles.

✅ Conclusión

El análisis demuestra que la retención temprana y los contratos a largo plazo son los factores más críticos para reducir la evasión de clientes. Aplicando campañas estratégicas, auditorías técnicas y programas de fidelización, Telecom X puede disminuir la tasa de churn y mejorar la satisfacción y fidelidad del cliente.
