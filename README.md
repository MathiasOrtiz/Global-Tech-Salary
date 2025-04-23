# 💼 GLOBAL TECH SALARY

Este proyecto tiene como objetivo **analizar cómo varía el salario en USD de los trabajadores del sector tecnológico** en función de diversas características como su experiencia, rol, tamaño de la empresa, localización, entre otros.

🔍 A lo largo del análisis se filtraron los datos, se eliminaron outliers y se generaron visualizaciones relevantes utilizando Power BI. Finalmente, se incluyó una **predicción de salario como valor agregado** mediante modelos de machine learning y deep learning.

---

## 👨‍💻 Colaboradores

- [Mathias Damian Ortiz Sanabria](https://www.linkedin.com/in/mathiasortiz/)  
- [Lucas Lopez](https://www.linkedin.com/in/lucaslopezcoluchi/)  

---

## 📊 Herramientas utilizadas

- **Python** (pandas, numpy, scikit-learn, tensorflow, xgboost)
- **Power BI** (para la presentación del dashboard)
- **Google Colab** (entrenamiento del modelo predictivo)
- **Jupyter Notebook** (`Proyecto_GlobalSalary.ipynb`)

---

## 📈 Visualización

El dashboard final de Power BI incluye:

- Mapa de países con mayor representación
- Gráficos de distribución de salario por rol, experiencia y año
- Segmentación por tamaño de empresa
- Insights clave presentados en tarjetas visuales

---

## 🧠 Modelos Predictivos

Aunque el enfoque principal es exploratorio, se realizó una predicción de salario en USD utilizando los siguientes modelos:

| Modelo              | MAE     | MSE         | R²     |
|---------------------|---------|-------------|--------|
| XGBoost             | 34,011  | 1.78e+09    | 0.25   |
| Random Forest       | 34,711  | 1.87e+09    | 0.21   |
| Linear Regression   | 34,220  | 1.79e+09    | 0.24   |
| KNN                 | 35,057  | 1.93e+09    | 0.18   |
| Decision Tree       | 35,020  | 1.95e+09    | 0.17   |
| **Red Neuronal (Keras)** | **33,894**  | **2e+009**         | **0.22**  |

> ⚙️ El modelo en Keras fue construido con 3 capas ocultas, Dropout del 30%, función de activación `ReLU` y pérdida `MAE`.


---

## 📁 Archivos del repositorio

- `Proyecto_GlobalSalary.ipynb` → análisis completo en Python
- `Prototipo.pdf` → presentación en Power BI
- `dashboard_visual.png` → imagen del dashboard
- `README.md` → este archivo

---

## 🧠 Conclusión

Este proyecto permite comprender de forma clara **cómo influyen el rol, la experiencia y la ubicación en el salario USD de los profesionales del sector tech**. 

Además, se construyó un modelo que, aunque no perfecto, logra acercarse a una estimación del salario real, demostrando cómo los modelos de regresión pueden complementar un análisis exploratorio tradicional.

---

✅ Si te interesa este tipo de análisis, no dudes en **darle estrella ⭐ al repositorio** y seguirnos en LinkedIn.
