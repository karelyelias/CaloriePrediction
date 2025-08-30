#### Project Overview
To achieve the goal of this project, a log was created containing over 300 entries detailing all foods consumed daily. Each entry includes calories, protein, carbohydrates, fats (lipids), and sodium, sourced from MyFitnessPal.

The most influential attributes in the dataset appear to be fats, carbohydrates, and proteins. Previous regression analyses demonstrated that these three variables are strongly correlated with total calorie intake.

#### Technologies and Libraries
- Python (pandas, numpy, matplotlib, sklearn, scipy)
- Models: LinearRegression, GradientBoostingRegressor, KNeighborsRegressor
- 3D Visualization using mpl_toolkits.mplot3d

#### Key Findings
- The models confirm that proteins and carbohydrates contribute approximately 4 kcal/g, while fats contribute around 8–9 kcal/g.
- The best-performing model was KNeighborsRegressor, with an R² ≈ 0.99.
- Sodium was excluded due to its lack of caloric impact.
