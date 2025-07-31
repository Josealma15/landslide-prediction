# landslide-prediction
📊 Proyecto de Machine Learning en Python para predecir la probabilidad de deslizamientos en Colombia (1998-2024) 
⚠️🏞️. Analiza datos históricos y genera un ranking de departamentos más vulnerables con el objetivo de crear un sistema de alerta pública. 🌍

## Descripción

Este proyecto implementa un sistema de alerta temprana para deslizamientos de tierra en Colombia. A partir de más de 50 000 registros históricos (1998–2024) de emergencias geológicas, procesa y limpia datos de fecha, departamento, municipio y tipo de evento, unifica categorías (“Deslizamiento”, “Incendio”, etc.) y extrae el año como variable clave. Luego entrena y compara tres modelos de clasificación:

- **Decision Tree Classifier**  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**

Los modelos alcanzan más del 85 % de exactitud en la detección de deslizamientos históricos, identifican los departamentos más vulnerables y permiten calcular la probabilidad de riesgo por región.

- **Consolidación y limpieza** de datasets anuales en un solo DataFrame.  

<img width="524" height="513" alt="image" src="https://github.com/user-attachments/assets/b39be871-5d58-4a56-b4b1-ca5688fed78a" />

- **Análisis exploratorio** con conteos por departamento y por año.  

<img width="629" height="619" alt="image" src="https://github.com/user-attachments/assets/9f77e485-9dc1-4d65-97d5-9a4e7f63ea91" />

<img width="695" height="591" alt="image" src="https://github.com/user-attachments/assets/d48a72db-a944-41a6-a24d-1fded5f64d7b" />


- **Modelos de ML**: Árbol de decisión, KNN y regresión logística.

<img width="400" height="205" alt="image" src="https://github.com/user-attachments/assets/ec28aa68-c470-4b4f-af69-cf18f6094168" />

- **Ranking** de departamentos ordenados por probabilidad promedio de deslizamiento.

- **Mockups** de prototipo de app (móvil y escritorio) para sistema de alerta en el futuro.
<img width="1024" height="1536" alt="ChatGPT Image Jul 30, 2025, 07_12_10 PM" src="https://github.com/user-attachments/assets/4325ca5f-5af7-4411-bfeb-cdca23918013" />
<img width="1024" height="1024" alt="ChatGPT Image Jul 30, 2025, 07_15_16 PM" src="https://github.com/user-attachments/assets/2bad0bdc-a4b6-406a-804b-6e435a7dfb13" />

  
