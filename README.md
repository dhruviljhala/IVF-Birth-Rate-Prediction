# IVF-Birth-Rate-Prediction

<!--- 
Comment Starts here

For the analysis of the patient characteristics with respect to live birth outcome, we used a database created by Human Fertilisation and Embryology Authority which contained data from 2015-2016. This database included 158,519 different records and 95 different features from the IVF procedures conducted. Only a few of the 95 predictors were chosen, based on previous research and NICE (National Institute for Health and Care Excellence) clinical recommendations. Female age, previous IVF procedures count, pregnancy history, Body Mass Index, number of embryos transferred, and lifestyle variables, according to NICE clinical guidelines, can be used to predict success rate.

The embryo analysis was conducted by using a dataset consisting of 443 grayscale day 3 embryo images of  128x128 pixel size. We evaluate and score certain aspects of the structure of embryos from in vitro fertilisation to determine their quality. Below are the different grades of embryos.


<img src="https://github.com/dhruviljhala/IVF-Prediction-using-Patient-Characteristics/blob/main/Grades.PNG" width=70% height=70%>


An embryo with 8-cells and <5% fragmentation promises to be perfect. There is no embryo division, and the cells are all of the same size and shape, followed by the 8-cell and >5% fragmentation embryo. The 6-cell embryo is moderately divided, with irregularly sized cells and irregular fragmentation and the 2-cell embryo is severely fractured and of low quality. Ideally we see at least 6 cells by 72 hours, with some at about 8 cells. But as it depends on patient characteristics as well, babies were also born from four-cell embryos on day three, but the chances of pregnancy rise dramatically as the number of cells increases.


![Interface](https://github.com/dhruviljhala/IVF-Prediction-using-Patient-Characteristics/blob/main/Table.PNG)


As shown in the above table, two test cases [25,1,0,3] and [50,3,0,2] are considered where each value refers to Age, embryos transferred, the total number of previous IVF cycles, and the total number of previous pregnancies respectively. Hence among the five algorithms, the best model was selected on the basis of its predictive value for a specific case where the outcome for live birth was positive and negative. As seen from the predicted values, Multiple Linear Regression was able to differentiate between two outcomes with more differences compared to others. 


 --->
