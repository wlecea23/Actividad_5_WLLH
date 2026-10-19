# CHANGELOG  
  
## Versión 1.0  
##   
## Datos  
Dataset creditcardfraud cargado desde Kaggle.  
Verificación de calidad y ausencia de valores nulos. 
## Preparación
Estandarización de las variables Time y Amount.
División de datos en entrenamiento y prueba.
## Modelado
Implementación de Regresión Logística.
Implementación de Random Forest.
## Experimento 1  
Modelo: Regresión Logística  
Resultado: F1 = XX  
##   
## Experimento 2  
Modelo: Random Forest  
Resultado: F1 = XX  
## Evaluación
Incorporación de Accuracy, Precision, Recall, F1-Score y ROC-AUC.
Aplicación de validación cruzada.
## MLOps
Integración de MLflow para el registro de experimentos.
## 
## Mejor modelo  
Random Forest  
##   
##   
## Conclusión  
El modelo Random Forest mostró mejor capacidad para detectar transacciones fraudulentas, reduciendo falsos negativos y mejorando el Recall, métrica prioritaria para sistemas antifraude.  
