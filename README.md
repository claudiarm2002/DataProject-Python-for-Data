# Data Project: Bank Marketing Analysis 

---

## 📊🧩 Project Description
Este proyecto contiene un análisis integral de campañas de marketing directo de una institución bancaria, orientado a la predicción de suscripciones de depósitos. 
El objetivo principal es identificar el perfil de cliente ideal y entender cómo los factores macroeconómicos influyen en la toma de decisiones.
El flujo de trabajo incluye:
- Transformación y Limpieza: Tratamiento de nulos mediante imputación por mediana y descarte de variables no fiables.
- Análisis Univariante: Caracterización demográfica de la cartera de clientes (edad, ocupación, educación).
- Análisis Bivariante: Identificación de determinantes de éxito mediante el cruce de variables de campaña y perfil.
- Definición de Perfiles de Éxito: Intersección de múltiples variables para maximizar la tasa de conversión.

---

## 📂 Project Structure
El proyecto está organizado de la siguiente manera:
- DataProject_PythonForData.ipynb: 
- Informe.pdf: Documento principal con el análisis detallado y conclusiones.
- Carpeta DatosProyecto
  - Dataset Principal (bank-additional.cvs): Información de llamadas y contexto socioeconómico.
  - Dataset Principal limpio (bank-additional-clean.cvs).
  - Dataset Complementario (costumer-details.xlsx): Datos demográficos y comportamiento web organizado por hojas anuales.
  - Dataset Complementario limpio (costumer-details-clean.xlsx)

---

## ⚙️ Technical Details
Herramientas: Python
Fuentes de datos: CSV (Llamadas) y Excel (Demografía).
Variables Clave: 
- Campaña: last_outcome_success, last_call_duration, campaign_contacts.
- Económicas: emp.var.rate, cons.price.idx, euribor3m.
- Cliente: age, job, marital, education.

---

## ✅ Results and Conclusions
A través de este análisis, se ha determinado que el éxito no depende de un único factor, sino de una combinación estratégica de variables:
- Efecto Anticíclico: El producto tiene mayor aceptación cuando el empleo flaquea o el Euribor es bajo.F
- idelización: Un resultado positivo previo es el indicador más fiable, elevando la probabilidad de éxito al 34,57%.
- Optimización de Recursos: Se identificó un punto de saturación a partir de la 7ª llamada, donde la rentabilidad cae drásticamente.
- Canal Crítico: El uso de telefonía móvil (cellular) triplica la tasa de éxito en perfiles jóvenes y solteros en comparación con el teléfono fijo.

Este proyecto permite consolidar una estrategia de marketing basada en datos, permitiendo a la entidad bancaria dirigir sus esfuerzos hacia los segmentos de mayor conversión de manera eficiente.

---

**Author:** Clàudia Rafart Medina
