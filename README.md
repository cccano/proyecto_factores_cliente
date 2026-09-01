# sprint_8_proyecto_final
uso de scatterplots, correalación de pearson, spearman, punto-biserial y v de cramer

## objetivo
Que factores del comportamiento del cliente están mas fuertemente asociados con el ingreso anual generado.

**Datasets Utilizados**

- plans.csv : planes actuales, precios de planes y minutos, GB incluidos y costos extras.
- users_latam.csv : información de los clientes, como edad, ciudad, planes, fechas de registro.
- usage.csv : detalle de uso real en llamadas y mensajes.

**Etapas de Análsis**

- Exploración y estructura de datesets.
- Identificación de problemas de calidad de los datos.
- No se detectan valores nulos ni inconsistentes
- cambio de la variable edad tipo float a int
- Análisis de correlación matriz de correlaciones
- Mapa de calor de correlaciones
- Distribución de variables númericas
- Distribución de variables categoricas
- Correlación de pearson y sperman de variables relevantes
- Correlación de punto-biserial
- Correlación de v de cramer
- Hallazgos
- Limitantes 

**Como ejecutar el notebook**

Desde el siguiente boton dando clic para ir al notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cccano/sprint_8_proyecto_final/blob/main/S8_Student_Version_Project_NovaRetail.ipynb)

**Guia de reproducción**

En el notebook queda guardado el conjunto de archivos csv que son necesarios para realizar el análisis.
solo tienes que direccionarte a colab desde el boton que abre el notebook, importar pandas ejecutar pd.read.csv() para ejecutar el conjunto de datos.


