# Estudio de Costo de Vivienda

## Objetivo
Analizar los factores que influyen en el precio de venta de las viviendas a través de técnicas de análisis exploratorio de datos (EDA) y modelos de regresión, con el fin de identificar las variables más relevantes para la valoración inmobiliaria.

---

## Tabla de Contenidos
- [Introducción](#introducción)  
- [Fuente de Datos](#fuente-de-datos)  
- [Análisis Exploratorio (EDA)](#análisis-exploratorio-eda)  
- [Modelado Predictivo](#modelado-predictivo)  
- [Conclusiones](#conclusiones)  
- [Requisitos](#requisitos)  
- [Uso](#uso)  
- [Contribuciones](#contribuciones)  
- [Autor](#autor)

---

## Introducción
El análisis de precios de vivienda permite entender cómo distintas características estructurales y del entorno afectan el valor de mercado de las propiedades. Este proyecto incluye:
- Limpieza y transformación de datos.
- Visualizaciones interactivas.
- Modelos de regresión lineal para estimación de precios.

---

## Fuente de Datos
- **Archivo esperado:** `housing_data.csv` (u otro formato descrito en el notebook).
- Atributos comunes analizados: superficie habitable, número de habitaciones, antigüedad, ubicación, calidad de construcción, etc.

---

## Análisis Exploratorio (EDA)
Se realiza un análisis exhaustivo para detectar:
- Distribuciones de variables numéricas y categóricas.
- Correlaciones entre variables.
- Valores atípicos (outliers).
- Impacto de variables clave en el precio de venta.

---

## Modelado Predictivo
Se implementan modelos de regresión para predecir el precio de la vivienda:
- Regresión Lineal Simple y Múltiple.
- Métricas de evaluación como RMSE y R².
- Evaluación de normalidad y multicolinealidad.

---

## Conclusiones
- **Factores Relevantes:** El área habitable, el número de baños y la calidad de construcción son algunas de las variables más influyentes.
- **Outliers:** Se identificaron valores atípicos que pueden distorsionar el modelo.
- **Mejoras Futuras:** Se recomienda incorporar variables categóricas codificadas y aplicar transformaciones para mejorar la precisión.

---

## Requisitos
Asegúrate de tener instalados los siguientes paquetes:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Uso
1. Clona el repositorio:
```bash
git clone https://github.com/tu_usuario/estudio-costo-vivienda.git
```
2. Abre el notebook:
```bash
jupyter notebook "Estudio de Costo de vivienda.ipynb"
```
3. Ejecuta las celdas en orden para realizar el análisis completo.

---

## Contribuciones
¿Tienes ideas para extender el modelo o usar otras técnicas como árboles o redes neuronales?  
¡Siéntete libre de abrir un issue o enviar un pull request!

---

## Autor
**José Eduardo Saucedo Martínez**  
