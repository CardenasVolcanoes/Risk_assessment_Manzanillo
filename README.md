# Risk_assessment_Manzanillo
Code for Risk Assesment using PMBOK AND FUZZY LOGIC 
# Análisis de Riesgos en Logística con DEMATEL - MATLAB

![MATLAB](https://img.shields.io/badge/MATLAB-R2023a-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Descripción

Este repositorio contiene un código en MATLAB que implementa el método DEMATEL (Decision Making Trial and Evaluation Laboratory) para el análisis de riesgos en logística comercial, diseñado específicamente para el capítulo *"Gestión de Riesgos: PMBOK ante Amenazas Naturales en el Puerto de Manzanillo"*  por **Enrique Cárdenas Sánchez**, Universidad Tecnológica de Manzanillo. El código evalúa cinco riesgos clave en el contexto portuario: Retrasos, Accidentes, Clima, Condiciones de la carretera y Tráfico, proporcionando una priorización basada en su importancia total (`R+J`) e impacto neto (`R-J`).

## Características

- Construcción de la matriz de relaciones directas (`A`) basada en influencias entre riesgos.
- Normalización y cálculo de la matriz total de relaciones (`T`) considerando efectos directos e indirectos.
- Cálculo de métricas DEMATEL:  
  - `R`: Influencia total ejercida.  
  - `J`: Influencia total recibida.  
  - `R+J`: Importancia total (priorización).  
  - `R-J`: Impacto neto (emisores vs. receptores).
- Visualizaciones:  
  - Gráfico de barras para `R+J`.  
  - Gráfico de dispersión para `R+J` vs. `R-J`.
- Ejemplo aplicado al Puerto de Manzanillo, adaptable a otros contextos logísticos.

## Requisitos

- **MATLAB**: Versión R2023a o superior (requiere funciones básicas de álgebra lineal como `inv` y `eye`).
- No se necesitan toolboxes adicionales.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/CardenasVolcanoes/Risk_assessment_Manzanillo
