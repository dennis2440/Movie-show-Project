# MOVIE AND SHOW PROJECT

## A FULLY FUNCTIONAL PROJECT DATASETS MERGED TO CREATE ONE DATASET THAT LATER SHOWS ANALYSIS OF THE DATASETS AND SOME VISUALIZATIONS.

# The project was made using two datasets an imdb dataset and a netflix dataset then merged to create one.
* The 1st and 2nd datasets read
* The two datasets merged tother form a sort of an enriched dataset based on the id_column of the two datasets
* open-ended Exploratory Data Analysis (EDA) performed on the enriched dataset
*  repeative columns dropped on the dataset
*  the genre column moved(rearranged) to the 3rd indedx  from the start
*  Then cleaning explored whereby the Seasons had mutiple NAN values where the movies rows in the season column had NAN values but the shows column had values
*  The NAN values in seasons column replaced with 0
*  The dataset then sorted according to the release year for easier referencing

  # a new fearure is engineered thats is'RATING' column whereby 
  *rating 0-5 is rated as poor
  * rating 5-7 is rated as average
  * rating 7-10 is rated as Best
# The dataset is saved into a new path together with changes
# followed by importation of various libraries
*import matplotlib.pyplot as plt
*import seaborn as sns
*import numpy as np
*%matplotlib inline
# followed by code of the various visualizations 
 *bargraph
 *piechart
* scatterplot
* histogram
* regression plot

  ## conclusion based on the dataset
The key takeaway from this analysis is that while IMDB scores play a crucial role in determining the overall success of a show, content quality, production efficiency,
and marketing strategies are also important factors to consider. To enhance potential returns, 
it is advisable to explore strategies that can capitalize on the relationships between these variables and continuously monitor their impact on the bottom line


  ### recommendations based on the dataset
film industies to create movies/shows genres based on the imdb score 
film industries to develop online platform and make them relative chaeper for views to access and earn contect at the same time

### updates to the readme coming soon..



