# 🚗 Predicción de Precios de Autos Usados  

Este proyecto es un trabajo sencillo realizado como parte de un curso en **Platzi**, utilizando un **dataset de autos usados** para predecir su precio con modelos de Machine Learning.  

---

## 📌 **Descripción del Proyecto**  
El objetivo principal de este proyecto es construir un **modelo de predicción de precios de autos usados** a partir de variables como:  
✅ **Año de producción**  
✅ **Kilometraje**  
✅ **Capacidad del motor**  
✅ **Marca y modelo del auto**  

Utilizamos técnicas de **preprocesamiento de datos**, **selección de características** y modelos como **Random Forest, Gradient Boosting y XGBoost** para optimizar las predicciones.  

---

## 📊 **Resultados del Proyecto**  
Después de entrenar y comparar los modelos, obtuvimos los siguientes resultados:

| **Modelo**          | **MAE**       | **MSE**        | **R² Score**  |
|--------------------|--------------|--------------|--------------|
| **Random Forest**   | 1,149.51     | 3,034,667.39 | 0.8558       |
| **Gradient Boosting** | 1,146.91   | 2,869,511.89 | 0.8637       |
| **XGBoost**         | 1,152.32     | 2,875,367.83 | 0.8634       |

🔍 **Conclusión:** El mejor modelo en términos de precisión y desempeño fue **Gradient Boosting**, seguido de cerca por **XGBoost** y **Random Forest**.

---

## 🗂️ **Estructura del Repositorio**  
El repositorio contiene las siguientes carpetas y archivos:  

📂 **`/notebooks/`** → Contiene el análisis exploratorio y el modelado de datos.  
📂 **`/models/`** → Modelos entrenados y optimizados.  
📂 **`/results/`** → Reportes y visualizaciones de los resultados.  
📄 **`README.md`** → Este archivo con la documentación del proyecto.  
📄 **`Used-Cars-Prediction.ipynb`** → Notebook principal con el desarrollo del modelo.  

---

## 🚀 **Tecnologías Utilizadas**  
- **Python 3.9+**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **Scikit-Learn, XGBoost**  
- **Jupyter Notebook**  

---

## 📌 **Cómo Usar Este Proyecto**  
Para correr este proyecto en tu máquina:  

1️⃣ Clona el repositorio:  
   ```bash```
   git clone https://github.com/NachoRob/Used-Cars-Prediction.git
   cd Used-Cars-Prediction

2️⃣ Instala las dependencias
   ```bash
   pip install -r requirements.txt

3️⃣ Ejecuta el notebook principal
   ```bash
   jupyter notebook Used-Cars-Prediction.ipynb

🤝 Contribuciones
Si quieres mejorar el proyecto, ¡bienvenido! Puedes hacer un fork, trabajar en mejoras y enviar un pull request.
   
📩 Contacto

Si tienes dudas o sugerencias, puedes encontrarme en GitHub.
