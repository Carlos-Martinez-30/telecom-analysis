# telecom-analysis
sprint7-final-project

## 🧠 Objetivo del análisis
El propósito de este proyecto es analizar patrones de uso y segmentar clientes de la empresa ConnectaTel, con el fin de identificar oportunidades comerciales, optimizar la oferta de planes y mejorar la retención de usuarios.

## Los datasets utilizados
plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)
usage_join → Dataset resultante de la unión y limpieza de los anteriores, utilizado para el análisis final.

##  Etapas del análisis
Limpieza de datos → 
Detección y corrección de valores nulos o sentinelas (-999).
Normalización de columnas como age y city.
Exploración inicial (EDA) → 
Distribución de variables numéricas (edad, llamadas, mensajes, minutos).
Identificación de outliers mediante boxplots e IQR.
Segmentación de clientes → 
Creación de la columna grupo_uso (Bajo uso, Uso medio, Alto uso).
Creación de la columna grupo_edad (Joven, Adulto, Adulto Mayor).
Visualización con countplot y tablas de frecuencia.
Hallazgos clave → 
Segmentos dominantes: Adultos con uso medio.
Outliers: heavy users con consumo extremo.
Oportunidades: planes premium y paquetes digitales para jóvenes.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Carlos-Martinez-30/Analysis-everpeak/blob/main/notebook.ipynb](https://colab.research.google.com/drive/1_8z_XWxvYQb3KDGj6i26AhkfAn7J_3hA?usp=sharing))

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**
