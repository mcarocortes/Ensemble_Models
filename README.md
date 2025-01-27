# Ensemble Models - Modelos en Conjunto

## Descripción
Este proyecto implementa y compara diferentes modelos de aprendizaje automático basados en Ensemble Methods para predecir `Item_Outlet_Sales`. Se analizan técnicas de Bagging y Boosting, utilizando el Error Cuadrático Medio (MSE) para evaluar el rendimiento.

## Contenido del Proyecto
- `Train.csv` - Dataset con información sobre ventas.
- `ensemble_models_analysis.ipynb` - Notebook con el código y análisis.
- `README.md` - Descripción del proyecto.

## Modelos Evaluados
### Bagging Methods
1. Decision Tree (Base Model)
2. Random Forest
3. Extra Trees

### Boosting Methods
4. AdaBoost
5. XGBoost
6. LightGBM

## Evaluación de Modelos
Se comparan modelos usando MSE y se visualizan los resultados en gráficos.

## Resultados
| Modelo | MSE |
|--------|------------|
| LightGBM | Menor MSE |
| XGBoost | Buen desempeño |
| Random Forest | Precisión aceptable |
| Extra Trees | Similar a Random Forest |
| AdaBoost | Mayor error que XGBoost |
| Decision Tree | Peor rendimiento |

## Conclusiones
- LightGBM y XGBoost son los más precisos.
- Bagging mejora la precisión respecto a un solo árbol de decisión.
- AdaBoost mejora sobre un árbol de decisión, pero es inferior a XGBoost y LightGBM.

