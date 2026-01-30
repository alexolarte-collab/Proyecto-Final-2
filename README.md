Proyecto-Final-2
Modelo de Machine Learning para la predicción de la Esperanza de Vida.
Autor: Alex Olarte

## 🏢 Contexto Comercial
Este proyecto se desarrolla para una **Agencia Internacional de Consultoría en Salud Pública**. El objetivo estratégico es proporcionar a gobiernos y ONGs una herramienta predictiva que identifique los factores clave (sanitarios y económicos) que impactan en la longevidad. Esto permite pasar de una gestión reactiva a una **proactiva**, optimizando la inversión de recursos para maximizar los años de vida de la población.

## 🎯 Objetivos y Preguntas de Investigación
El estudio busca resolver:
1. ¿Cuáles son los factores con mayor peso en la predicción de la esperanza de vida?
2. ¿Cómo influyen variables estructurales como la escolaridad y el PIB frente a crisis sanitarias (HIV/AIDS)?
3. ¿Es posible predecir con alta precisión la longevidad basándose en indicadores socioeconómicos?

## 🛠️ Metodología (Data Wrangling & EDA)
- **Limpieza de Datos:** Estandarización de nombres de columnas, tratamiento de valores nulos (imputación por media) y manejo de outliers.
- **EDA:** Análisis profundo mediante 6 visualizaciones clave, incluyendo histogramas de distribución, boxplots de escolaridad y una **Matriz de Correlación (Heatmap)**.
- **Feature Engineering:** Codificación de variables categóricas (Status) y selección de atributos mediante SelectKBest.

## 🤖 Modelado y Optimización
Se compararon dos algoritmos de regresión:
1. **Linear Regression:** (Línea base).
2. **Random Forest Regressor:** Optimizado mediante **GridSearchCV** para encontrar los mejores hiperparámetros.

### Resultados Finales:
- **R² Score:** 0.9681 (El modelo explica el 97% de la variabilidad).
- **MAE:** 1.07 años (Error promedio de predicción).

## 📊 Insights Clave
El análisis de **Feature Importance** reveló que el factor más determinante es el impacto del **HIV/AIDS**, seguido de la composición del ingreso de recursos y la escolaridad. Esto valida la hipótesis de que las políticas de salud pública estructurales y el desarrollo económico son los pilares de la longevidad moderna.
