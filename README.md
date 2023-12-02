# Algae Population Prediction

Algae population prediction uses https://www.kaggle.com/datasets/rukenmissonnier/research-on-algae-growth-in-the-laboratory dataset to make predictions on the population of algae

It features 7 columns and one target

Light (μmol photons/m²/s): This particular column quantifies the luminous intensity in micromoles of photons per square meter per second. The availability of light, as elucidated herein, emerges as a pivotal determinant profoundly shaping the growth patterns and spatial distribution of algae within aquatic realms.

Nitrate (mg/L): The concentration of nitrate, meticulously gauged in milligrams per liter (mg/L), stands as a cardinal parameter instrumental in assessing the nutritional landscape of water bodies. Its eminent role in modulating algal proliferation casts it in the role of a linchpin variable in the exploration of algal populations.

Phosphate (mg/L): Echoing the significance of nutrient dynamics, the column denoting phosphate concentration, similarly quantified in milligrams per liter (mg/L), assumes a prominent stance. This parameter's sway over algal growth underscores its relevance in comprehending the nutrient intricacies inherent in the ecosystem.

Iron (mg/L): The presence of iron, quantified in milligrams per liter (mg/L), exerts a pronounced influence on the flourishing of algae. Algae, in their quest for photosynthetic sustenance, demand iron—a fact that elevates the status of this column to one of paramount importance in the evaluation of micronutrient availability.

Temperature (°C): Temperature, meticulously documented in degrees Celsius (°C), stands as a foundational environmental factor. It exerts a profound sway over the metabolic rates and seasonal ebb and flow characterizing algae populations.

pH: The pH level, acting as a sentinel of acidity or alkalinity, wields considerable power over algae populations. The susceptibility of these organisms to fluctuations in pH amplifies the relevance of this parameter in the quest to fathom their well-being and distribution.

Carbon Dioxide (CO2) (mg/L): The concentration of carbon dioxide, quantified in milligrams per liter (mg/L), occupies a crucial niche in the carbon cycle and exerts an indelible imprint on the rates of algal photosynthesis.

Population (Algae Population): Last but by no means least, this column has its gaze squarely fixed on the population of algae inhabiting the studied milieu. It is the encapsulation of density or abundance, offering insights into the intricate interplay between algae and the array of environmental factors meticulously chronicled in this dataset.

## Jupyter Notebook
The headings in the notebook are as follows:
* Set-Up
* Data Exploration
* Early Visualtions
* Correlation Matrix
* Linear Regression Processing
* Ensemble 
* Conclusion

### Set Up
Involves the import of data and making the df

### Data Exploration 
Involves the gathering of statistics such as the mean etc

### Early Visualtions
Shows a pairplot and pairgrid for the data

### Correlation Matrix
Shows and explains a correlation matrix

### Linear Reegression
1. PCA
2. Linear Regression
3. Lasso Linear Regression
4. Ridge Linear Regression
5. Elastic Net Linear Regression
6. Polynomial Regression

### Ensemble
1. Random Forest
2. Extra Trees
3. KNN
4. Gradient Boosting
5. Voting Regressor
6. Model Creation
7. Model Training
8. Model Testing
9. Model Comparion

### Conclusion
Linear Regression poor model as no correlation in data
Polynomial Reegresison 96% r2 score as increases to a point then decreases
Ensemble methods approx 96% r2 score slight variations 
Success in creating a model

More explanations in MD sections of notebook.

