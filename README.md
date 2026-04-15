# 📊 Análisis y Predicción de Fallas Industriales

## 🚀 Descripción

En este proyecto trabajé con datos históricos de mantenimiento industrial para entender cómo se comportan las fallas a lo largo del tiempo.

La idea fue ir más allá de solo ver los datos: analizar patrones, clasificar los tipos de fallas y tratar de proyectar qué podría pasar en el corto plazo.

---

## 🎯 Objetivo

- Entender cómo se comportan las fallas  
- Clasificar los diferentes tipos  
- Encontrar patrones en los datos  
- Tener una idea de cómo podrían comportarse en el futuro  

---

## 📂 Dataset

El dataset proviene de un entorno real de mantenimiento industrial.

Por temas de confidencialidad, no se incluye en el repositorio, pero el análisis se puede seguir completamente desde el notebook.

---

## 🔍 Análisis Exploratorio (EDA)

Antes de modelar, me enfoqué en entender bien los datos:

- revisé valores nulos  
- analicé la distribución de las fallas  
- exploré cómo cambian en el tiempo  

### Algunas cosas interesantes:

- hay un desbalance claro entre tipos de falla  
- algunas categorías aparecen mucho más que otras  
- el comportamiento en el tiempo es bastante estable  

---

## 🤖 Modelo de Clasificación

Para clasificar las fallas utilicé un modelo de **Random Forest**.

Lo elegí porque funciona bien con datos de este tipo y no requiere demasiados supuestos.

El modelo logró una exactitud cercana al **60%**, lo cual es razonable teniendo en cuenta que es un problema multiclase (varios tipos de falla).

---

## 🔮 Predicción

Después de clasificar, trabajé en proyectar el comportamiento de las fallas en el tiempo.

El resultado es un archivo con:

- una predicción principal  
- un límite inferior (escenario más bajo)  
- un límite superior (escenario más alto)  

Más que un número exacto, esto sirve como una guía de cómo podrían comportarse las fallas en los próximos días.

---

## 🏢 ¿Qué aporta esto?

Este tipo de análisis puede ayudar a:

- entender mejor qué está pasando con los equipos  
- anticiparse a ciertos comportamientos  
- apoyar decisiones de mantenimiento  
- pasar de reaccionar a planear  

---

## 🛠 Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Jupyter / Google Colab  

---

## 📌 Archivos del proyecto

- `analisis_prediccion_fallas_industriales.ipynb` → todo el análisis paso a paso  
- `predicciones_30_dias_todos_los_modos_fallo.xlsx` → resultados de la predicción  

---

## ⭐ Conclusión

Este proyecto fue un primer acercamiento práctico a trabajar con datos reales, entenderlos y sacar conclusiones útiles.

Más allá del modelo, lo importante fue el proceso: explorar, cuestionar los datos y tratar de traducirlos en algo que tenga sentido para negocio.
