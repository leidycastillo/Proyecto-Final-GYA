# Proyecto-Final-GYA
Proyecto final de Almacenamiento y Gestión de datos de la Universidad Autónoma de Occidente.

# Proyecto de Análisis de Datos de Transporte de Carga

## Tabla de Contenidos
1. [Descripción del Problema](#descripción-del-problema)
2. [Contenido del Repositorio](#contenido-del-repositorio)
3. [Descripción de los Datos](#descripción-de-los-datos)
4. [Análisis de los Datos](#análisis-de-los-datos)
5. [Impacto Empresarial](#impacto-empresarial)

---

## Descripción del Problema
En este proyecto, abordamos la problemática relacionada con la optimización del tiempo de viaje de camiones que transportan productos diversos. Los tiempos de entrega pueden verse afectados por una amplia variedad de factores, como el tipo de producto, la configuración del vehículo y el tiempo de espera en los puntos de carga y descarga. La finalidad es predecir con precisión estos tiempos y mejorar la eficiencia logística.

---

## Contenido del Repositorio
Este repositorio contiene los archivos necesarios para reproducir el análisis de datos y la modelización predictiva de los tiempos de viaje de camiones. Los elementos principales que encontrarás son:

- **Dataset original**: Archivo de datos en formato `.csv` que incluye toda la información relevante sobre el transporte de carga.
- **Notebook de Jupyter**: Un archivo `.ipynb` con el código de preprocesamiento, análisis exploratorio y modelado.
- **Modelo entrenado**: Archivos relacionados con el modelo predictivo, entrenado en los datos.
- **Visualizaciones**: Gráficas y resultados obtenidos durante el análisis de los datos.
- **Script de conexión SQL**: Código para la conexión y manipulación de la base de datos con SQLite3.

---

## Descripción de los Datos
El dataset utilizado consta de **562,090 entradas** relacionadas con viajes de camiones. Cada entrada corresponde a un viaje individual con las siguientes **24 características**:

- **Ejemplos de características**:
  - `NATURALEZA`: Tipo de carga (normal, peligrosa, refrigerada, etc.).
  - `COD_PRODUCTO` y `PRODUCTO`: Código y descripción del producto transportado.
  - `HORAS_VIAJE`: Duración del viaje en horas.
  - `HORAS_ESPERA_CARGUE` y `HORAS_ESPERA_DESCARGUE`: Tiempos de espera en los puntos de carga y descarga.
  - **Otras características** incluyen información sobre el transporte, como la empresa, la configuración del camión, si se utilizó GPS, entre otros.

---

## Análisis de los Datos
Durante el análisis, se detectaron varias tendencias clave:

1. **Impacto del Tipo de Producto**: Los productos más pesados o peligrosos tienden a aumentar el tiempo de viaje y los tiempos de espera en carga y descarga.
2. **Configuración del Vehículo**: Camiones con configuraciones más complejas (por ejemplo, de mayor capacidad) experimentan tiempos de viaje más largos.
3. **Factores Externos**: El tiempo de espera en los puntos de carga y descarga varía significativamente entre empresas, lo que indica posibles ineficiencias en ciertos operadores logísticos.

---

## Impacto Empresarial
El descubrimiento clave de este proyecto es que los tiempos de viaje y de espera pueden ser optimizados ajustando la logística en función del tipo de producto y la empresa de transporte. Estos hallazgos podrían aportar un valor significativo a una empresa de las siguientes maneras:

1. **Optimización de rutas y tiempos**: Conociendo de antemano qué productos o configuraciones afectan más los tiempos, una empresa puede optimizar las rutas y asignar los vehículos más adecuados para cada tipo de carga.
2. **Mejora en la eficiencia operativa**: Identificar qué empresas y cargas generan mayores tiempos de espera puede ayudar a mejorar la negociación con proveedores y mejorar la cadena de suministro.
3. **Reducción de costos**: Una predicción precisa de los tiempos de viaje permite reducir costos al minimizar el tiempo ocioso de los vehículos y personal de transporte.

---

¡Gracias por revisar este repositorio! Si tienes alguna pregunta o sugerencia, no dudes en contactarme.
