## Adoption of Cats from Animal Shelters

### Goal
To build a classification model to predict whether a cat would be adopted or not within 4 weeks of their intake into a shelter give certain features of the cat.

### Motivation 
The Austin Animal Center is the largest no-kill animal shelter in the United States that provides care and shelter to over 18,000 animals each year and is involved in a range of county, city, and state-wide initiatives for the protection and care of abandoned, at-risk, and surrendered animals. Every year, approximately 7.6 million companion animals end up in US shelters. Many animals are given up as unwanted by their owners, while others are picked up after getting lost or taken out of cruelty situations. Many of these animals find forever families to take them home, but just as many are not so lucky. 

Running a no kill shelter is no mean feat and for such a facility, management of resources is very important. Knowing what kind of animals are more likely to be adopted would certainly be of help to such a facility as it would help them to better manage thier resources and combat overcrowding of the shelters.

Austin shelters takes in a number of kinds of animals like cats, dogs, livestock and birds. I chose to do my analysis only of cats because each type of animal has a unique set of charateristics like breed, color, average age etc. Building a generalised model for all thses kinds of animals wouldn't be right.

### Data Sources
https://data.austintexas.gov/ 

The figure below shows how the diiferent models performed on the classification task after optimizing for parameters and hyper-parameters for each model.

<img src='images/ROC curves.png' width=70%>

### Files included

01 - Data Cleaning and EDA.ipynb - Jupyter notebook consisting of the data cleaning, feature engineering and EDA.

02 - Classification.ipynb - Jupyter notebook where different classification models are built and their performances are compared.

index.html - d3 bubble graph that shows the variable importance of the features.
- Run your local server to see how things look! 
```
# for Python 2
python -m SimpleHTTPServer 8000

# for Python 3
python -m http.server 8000
```

Also, you can click here to find my blog post on this project.
