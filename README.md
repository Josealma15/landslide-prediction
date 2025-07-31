# Modelo Predictivo de Vulnerabilidad de Deslizamientos en Colombia
📊 Proyecto de Machine Learning en Python para predecir la probabilidad de deslizamientos en Colombia (1998-2024) 
⚠️🏞️. Analiza datos históricos y genera un ranking de departamentos más vulnerables con el objetivo de crear un sistema de alerta pública. 🌍

## Descripción

Este proyecto implementa un sistema de alerta temprana para deslizamientos de tierra en Colombia. A partir de más de 50 000 registros históricos (1998–2024) de emergencias geológicas, procesa y limpia datos de fecha, departamento, municipio y tipo de evento, unifica categorías (“Deslizamiento”, “Incendio”, etc.) y extrae el año como variable clave. Luego entrena y compara tres modelos de clasificación:

- **Decision Tree Classifier**  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**

Los modelos alcanzan más del 85 % de exactitud en la detección de deslizamientos históricos, identifican los departamentos más vulnerables y permiten calcular la probabilidad de riesgo por región.

- **Consolidación y limpieza** de datasets anuales en un solo DataFrame.  

<img width="200" height="196" alt="limpieza" src="https://github.com/user-attachments/assets/a0dbc6d0-cb2c-4a88-9ae0-c273212cd951" />

- **Análisis exploratorio** con conteos por departamento y por año.  

<img width="695" height="684" alt="ana1" src="https://github.com/user-attachments/assets/2aa61cdd-55bb-4953-950b-ceb7dc768a6e" />

<img width="695" height="591" alt="ana2" src="https://github.com/user-attachments/assets/f312ad7d-39dc-43bd-9897-667b918650ee" />


- **Modelos de ML**: Árbol de decisión, KNN y regresión logística.

<img width="695" height="356" alt="compara" src="https://github.com/user-attachments/assets/75d92f14-31d9-40c2-8f4e-debf6c88ed4e" />

- **Ranking** de departamentos ordenados por probabilidad promedio de deslizamiento.

- **Mockups** de prototipo de app (móvil y escritorio) para sistema de alerta en el futuro.
<img width="695" height="1043" alt="ChatGPT Image Jul 30, 2025, 07_27_54 PM (1) (1)" src="https://github.com/user-attachments/assets/5fb4a35a-3c41-45b4-80da-2f4a7b4697ca" />
<img width="695" height="695" alt="mock2" src="https://github.com/user-attachments/assets/ca558200-95c4-48ea-8ba7-5b4e5839b210" />

  
