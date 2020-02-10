# Wine-evaluation-white-vs-red
This is the project from Udacity to hone my skills in data visualization and analysis.

Two data are given, winequality-red.csv and winequality-white.csv, consited of columns that are :

[fixed_acidity, volatile_acidity, citric_acid, residual_sugar, chlorides, free_sulfur_dioxide, total_sulfur-dioxide, density, pH, sulphates, alcohol, quality]

The primary purpose of this project is to answer 3 questions :

1.  Q: Do wines with higher alcoholic content receive better ratings? 

2.  Q: Do sweeter wines receive higher ratings?

3.  Q: What level of acidity receives the highest average rating?

Thank you so much for reading this.

# Contents
appending - Appended two data (red wine data, white wine data) to facilitate analysis later

conclusions_groupby - Classified data by "acidity level", which is categorized by interquartile range of pH, and grouped this by quqality and color.

conclusions_query - Divided data into two parts (lower than the median sugar level, higher than the median sugar level). Used query to find average of qualities on each part.

eda_visuals - Applied histogram to visually see the correlation of quality to other variables.

plotting_type_quality - Plotted proportions of red wine and white wine to their quality.

wine_visualizations - Creating visualizations that can support to answer the questions listed.
