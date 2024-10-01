# Heart-Failure-Prediction

Proyecto para crear un modelo de ML que ayude con la detección temprana de enfermedades cardiovasculares.

## Contexto

La **enfermedad arterial coronaria** (Coronary Artery Disease) es una enfermedad en la que se produce un estrechamiento u obstrucción de las arterias coronarias (vasos sanguineos que llevan sangre y oxígeno al corazón).

![Enfermedad Arterial Coronaria](https://continentalhospitals.com/uploads/Coronary%20Artery%20Diseases.jpg)

**Causa típica de la enfermedad**: La causa de esta enfermedad por lo general es la acumulación de grasa y formación de placas dentro de las arterias coronarias.

**Síntomas típicos**: Esta enfermedad normalmente causa dolor de pecho, dificultad para respirar durante el ejercicio físico e infartos de miocardio.

**Factores de riesgo**: El riesgo de esta enfermedad aumenta cuando:
- Hay antecedentes familiares en menores de 50 años de edad
- Edad avanzada
- Tabaquismo
- Hipertensión
- Colesterol alto
- Diabetes
- Falta de ejercicio
- Obesidad

## Conjunto de datos

El conjunto de datos está compuesto por 12 columnas / features:

| Feature         | Descipción                                    |
| --------------- | --------------------------------------------- |
| Age             | Edad del paciente en años                     |
| Sex             | Sexo del paciente (M: masculino, F: femenino) |
| ChestPainType   | Angina = dolor de pecho. TA: Typical angina, ATA: Atypical angina, NAP: Non-Anginal Pain, ASY: Asintomático |
| RestingBP       | Presión sanguínea en reposo                   |
| Cholesterol     | Nivel de colesterol sérico / total (lipoproteínas de alta y baja densidad, triglicéridos) en mg/dl (no puede ser 0) |
| FastingBS       | Un tipo de test de diabetes (1: si el test dio $x>120$ mg/dl, 0: en otro caso) |
| RestingECG      | Resultados de electrocardiograma en reposo (Normal: Normal, ST: tiene anormalidades ST o T, LVH: signos de hipertrofia ventricular izquierda) |
| MaxHR           | Ritmo cardiaco máximo alcanzado (60-202) |
| ExcerciseAngina | El paciente tuvo dolor de pecho a causa de ejercicio (Y: sí, N: no) |
| Oldpeak         | Depresión ST (en ECG) inducida por el ejercicio comparado con el reposo |
| ST_Slope        | La pendiente del segmento ST máximo al hacer ejercicio (Up: pendiente positiva, Flat: constante, Down: pendiente negativa) |
| HeartDisease    | El paciente tiene enfermedad arterial coronaria (1: sí, 0: no) |

## Referencias

**Enfermedad Arterial Coronaria (NIH):** https://www.cancer.gov/espanol/publicaciones/diccionarios/diccionario-cancer/def/enfermedad-arterial-coronaria

**Conjunto de datos obtenido de:**

fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [Date Retrieved] from https://www.kaggle.com/fedesoriano/heart-failure-prediction.

**Fuentes de datos originales recopiladas y preprocesadas por FedeSoriano:**

- Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). Heart Disease [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X.
- Statlog (Heart) [Dataset].  UCI Machine Learning Repository. https://doi.org/10.24432/C57303.

