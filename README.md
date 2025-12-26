# Customer Churn Prediction

Proyecto de Data Science que predice qué clientes de una empresa de telecomunicaciones tienen mayor probabilidad de cancelar el servicio.

## Objetivo

Desarrollar un modelo de Machine Learning que identifique clientes en riesgo de abandono, permitiendo a la empresa tomar acciones preventivas de retención.

## Dataset

- **Fuente:** Telco Customer Churn (Kaggle)
- **Registros:** 7,043 clientes
- **Variables:** 21 características (demografía, servicios, facturación)
- **Variable objetivo:** Churn (Yes/No)

## Metodología

1. Análisis Exploratorio de Datos (EDA)
2. Limpieza y preparación de datos
3. Feature Engineering con One-Hot Encoding
4. División train/test (80/20)
5. Modelado con Regresión Logística
6. Evaluación con matriz de confusión

## Resultados

- **Precisión:** 82.3%
- **Recall:** 60.3%
- **Clientes en riesgo detectados:** 225
- **Impacto estimado:** Retención de ~$270,000 anuales

## Tecnologías

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Kagglehub

## Cómo ejecutar

1. Clona este repositorio
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta el notebook: `jupyter notebook churn_analysis.ipynb`

## Estructura del Proyecto
```
├── churn_analysis.ipynb    # Notebook principal con análisis completo
├── README.md               # Documentación del proyecto
└── requirements.txt        # Dependencias necesarias
```

## Conclusiones

El modelo identifica correctamente el 82% de los casos, detectando 225 clientes en riesgo de abandono. Los principales predictores de churn son: antigüedad baja (tenure < 12 meses), contratos mensuales, y cargos mensuales elevados.

## Próximos Pasos

- Implementare algoritmos más avanzados (Random Forest, XGBoost)
- Optimizare threshold para mejorar recall
- Realizare feature engineering avanzado
- Desplegare modelo en producción

## Autor

HILDEBRANDO PEÑA QUEZADA 

## Licencia

Este proyecto está bajo licencia MIT.

