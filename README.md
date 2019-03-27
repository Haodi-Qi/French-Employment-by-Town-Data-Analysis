# Kaggle_French_employment_by_town_Analysis
The dataset is about French employment, salaries, populationby town from Kaggle: https://www.kaggle.com/etiennelq/french-employment-by-town

I firstly did EDA on salary data and firm/industry data, identifying trends across firms of varying sizes and across genders and ages.
Then I created a correlation matrix among gender, position and salary, followed by building a Decision Tree Regressor model to predict salary. I repeated the process for gender, age and salary. The model built from gender, position and salary is useful but that from gender, age and salary is not.

Next, I used Random Forest Regressor to build a better model. The improvement is rather small.

Lastly, I plotted distributions of mean salary, male-to-female ratio, and total population across departments on the map, with some bar charts for further elaboration.

The technology used includes:
Numpy, Pandas, Sklearn, Matplotlib, Geopandas


