# Análisis de Movilidad Urbana y Productividad Económica – Sprint 5

Este repositorio contiene el análisis realizado durante el Sprint 5 del programa de Data Analyst, enfocado en la relación entre movilidad urbana y productividad económica en ciudades latinoamericanas.

📊 Contexto del proyecto
Como analista de datos del Latin American Development Bank, el objetivo fue construir una tabla unificada que combine variables de movilidad urbana (TomTom) con variables económicas (OECD) para ciudades de América Latina en 2024.

El propósito es generar una base limpia, estandarizada y lista para futuros análisis sobre cómo la movilidad urbana puede influir en la productividad económica.

📂 Datasets utilizados
tomtom_traffic.csv: Datos de congestión vehicular y condiciones de tráfico en tiempo real
Niveles de tráfico y congestión por ciudad
Retrasos, índices de tráfico, longitud de embotellamientos
Tiempos de viaje actuales vs. históricos
oecd_city_economy.csv: Indicadores económicos y urbanos anuales
PIB per cápita por ciudad
Porcentaje de desempleo
Concentración de PM2.5 (contaminación del aire)
Población total
🎯 Objetivo del análisis
Generar insights sobre cómo la movilidad urbana puede influir en la productividad económica para identificar ciudades donde invertir en infraestructura de transporte.

📂 Contenido del repositorio
S5_ladb_mobility_economy_project_student.ipynb → Notebook principal con todo el proceso de análisis
ladb_mobility_economy_2024_clean.csv → Dataset unificado y depurado (resultado final)

▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

[https://colab.research.google.com/github/quintanamarquezraudel-cloud/Movilidadurbanaanalisis/blob/main/S5_ladb_mobility_economy_project_student.ipynb]

## 📘 Cómo reproducir el análisis

1. Abre `S5_ladb_mobility_economy_project_student.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente los datasets

## 🛠️ Herramientas utilizadas

- **Python**: pandas, numpy, seaborn, matplotlib
- **Jupyter Notebook**
- **Datasets**: TomTom Traffic Index y OECD Cities

## 🧠 Metodología

1. Limpieza y estandarización de datos
2. Unión de datasets por ciudad
3. Filtrado para el año 2024
4. Cálculo de indicadores agregados
5. Análisis exploratorio y visualizaciones
6. Identificación de patrones y correlaciones

## 📈 Principales hallazgos

El análisis de 15 ciudades latinoamericanas en 2024 muestra que no existe una relación directa entre el PIB per cápita y los niveles de congestión vehicular. 

## 🎯 Objetivo del banco

Identificar ciudades donde invertir en infraestructura de transporte para aumentar la productividad y el bienestar de la población.
