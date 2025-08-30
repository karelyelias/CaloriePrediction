# Proyecto de Ciencia de Datos: Predicción de Calorías
Para lograr el objetivo del presente proyecto se creó una bitácora con más de 300 datos con todos los alimentos consumidos día con día, con sus respectivas calorías, proteínas, carbohidratos, lípidos (grasas), y sodio obtenidas de MyFitnessPal.

Los atributos de la base de datos que parecen más comprometedores son los lípidos, los carbohidratos, y las proteínas, debido a que después de haber realizado anteriormente varios análisis regresivos se demostraron que estos tres atributos están relacionados a la cantidad de calorías consumidas.

### Tecnologías y librerías
- Python (pandas, numpy, matplotlib, sklearn, scipy)
- Modelos: LinearRegression, GradientBoostingRegressor, KNeighborsRegressor
- Visualización 3D con mpl_toolkits.mplot3d

### Hallazgos clave
- Los modelos confirman que proteínas y carbohidratos aportan ~4 kcal/g, mientras que lípidos ~8–9 kcal/g.
- El modelo con mejor desempeño fue KNeighborsRegressor con un R² ≈ 0.99.
- El sodio fue descartado por no tener impacto calórico.
