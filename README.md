# Interactive demographic forecasting tool for different religious communities in Israel under various scenarios.

The population of Israel is characterized by strong religious cleavages (Muslim and Jews, Orthodox and Liberals), which heavily impact the political landscape of the country. 
There is no doubt that the demographic composition of the country will play a decisive role in the future of the country, which results in a frequent instrumentalization of this issue in the political discourse.
However, demographic forecasting, especially in this case, implies many parameters (fertility trajectories, migration pattern and defection across religious groups), which must be regarded as endogeneous to the model. 
This project aims at allowing political scientists, demographers or journalists to form a reasoned opinion on the matter by providing an interactive, visual forecasting tool, written in Python, under different scenarios.
The projections are calculated using enhanced Leslie Matrices accounting for dynamic, endogenous changes in demographic variables upon time. 

Although the subject is not addressed here, projections are presented by age groups, in order to easily model shifts in fertility tempi (mothering age), which might be of significant consequences on the population trajectories.

## Contents
The **.csv files** are the raw data obtained from the statistical reports of the Central Bureau of Statistics. The **Jupyter Notebook presentation.ipynb** presents the scientific reasoning behind the calculations and provides the Python code for the projections as well as an interactive visualization tool. 

## Requirements
The Jupyter Notebook is written in Python 3. The following libraries are used:
Numpy, Pandas, Matplotlib, Bokeh.

