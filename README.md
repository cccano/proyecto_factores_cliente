# Correlación de factores del cliente con ingresos anuales
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

Descarga el achivo csv "novaretail_comportamiento_clientes_2024.csv" y cargarlo a colab. 

Dirígete al menú lateral izquierdo de tu Google Colab y haz clic en el ícono de Carpeta (Archivos).

Haz clic en el primer ícono de arriba que dice "Subir al almacenamiento de sesiones" (representado con una pequeña carpeta y una flecha hacia arriba).

Selecciona tu archivo desde tu PC.

Una vez cargado en la lista, haz clic derecho sobre el nombre del archivo, selecciona "Copiar ruta" (Copy path) y pégala dentro de tu función de Pandas


