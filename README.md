# 🚕 Proyecto Automatidata – NYC TLC

Análisis Exploratorio de Datos (EDA) y visualización de tarifas de taxi para la **Comisión de Taxis y Limusinas de Nueva York (TLC)**.  
Este proyecto forma parte del curso *Go Beyond the Numbers: Translate Data into Insights* y demuestra cómo aplicar técnicas de limpieza, análisis y visualización de datos en Python y Tableau.

---

## 📂 Contenido del repositorio

- **Automatidata_EDA.ipynb** → Notebook técnico en Google Colab con:
  - Limpieza y estructuración del dataset.
  - Exploración de outliers y valores nulos.
  - Visualizaciones en Python (boxplots, histogramas, barplots).
  - Insights sobre patrones temporales, propinas y ubicaciones.

- **Resumen_ejecutivo_Automatidata.pptx** → Presentación profesional con:
  - Contexto y objetivos del proyecto.
  - Capturas de Tableau (7 visualizaciones).
  - Conclusiones y próximos pasos para el modelado predictivo.

- **screenshots/** → Carpeta con las 7 capturas de Tableau:
  - Captura 1: estructura de campos del dataset.  
  - Captura 2: dispersión inicial distancia vs importe.  
  - Captura 3: detalle de registros nulos/outliers.  
  - Captura 4: visualización comparativa tras limpieza.  
  - Captura 5: distribución de tarifas.  
  - Captura 6: mapa de ubicaciones.  
  - Captura 7: relación final importe vs distancia.

---

## 🛠️ Herramientas utilizadas

- **Python**: pandas, numpy, matplotlib, seaborn.  
- **Tableau Public**: dashboards y visualizaciones interactivas.  
- **GitHub**: control de versiones y portafolio.  
- **Google Colab**: entorno de ejecución del notebook.

---

## 📊 Principales hallazgos

- La mayoría de viajes duran menos de **5 millas** y cuestan entre **5–15 USD**.  
- Existen outliers: distancias = 0 y tarifas negativas, que deben excluirse.  
- Patrones temporales: más viajes miércoles–sábado y en primavera; menos en verano y domingos.  
- Propinas consistentes entre vendors, con ligeras variaciones por número de pasajeros.  
- Drop-off locations distribuidos de forma amplia, con algunos puntos de alta concentración.

---

## 🚀 Próximos pasos

- Documentar criterios de limpieza y depuración.  
- Desarrollar y validar el modelo de regresión para predicción de tarifas.  
- Generar visualizaciones finales y recomendaciones estratégicas para la TLC.  

---

👩‍💻 Proyecto realizado por **Selene** como parte del portafolio de análisis de datos.
