# mini-project-iron-kaggle

## Resumen del Proyecto

Este proyecto tiene como objetivo predecir las ventas de una empresa utilizando técnicas de Machine Learning. A continuación se presentan los aspectos más relevantes:

### Datos
- Se cuenta con información histórica de ventas que incluye variables como:
  - ID de la tienda
  - Día de la semana
  - Fecha
  - Número de clientes
  - Estado de apertura
  - Promociones
  - Días festivos
  - Días de vacaciones escolares

### Modelos Implementados
Se utilizaron dos modelos de Machine Learning:

1. Regresión Lineal
   - R² Entrenamiento: 0.8541
   - R² Prueba: 0.8515

2. XGBoost 
   - R² Entrenamiento: 0.9691
   - R² Prueba: 0.9412

### Resultados
- El modelo XGBoost mostró un mejor rendimiento con un R² de 0.94 en datos de prueba
- Se logró una predicción precisa de las ventas basada en los factores analizados
- Las variables más influyentes fueron el número de clientes y el estado de apertura de las tiendas

### Tecnologías Utilizadas
- Python
- Pandas para manipulación de datos
- Scikit-learn para modelos de Machine Learning
- XGBoost para modelado avanzado
