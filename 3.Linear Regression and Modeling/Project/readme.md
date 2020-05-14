This is the Project about this course.  
***
Congratulations on getting a job as a data scientist at Paramount Pictures! Please see the Data Analysis Project for your assignment. Below you will find the files that you will need.

Your boss has just acquired data about how much audiences and critics like movies as well as numerous other variables about the movies. This dataset is provided below, and it includes information from Rotten Tomatoes and IMDB for a random sample of movies.

She is interested in learning what attributes make a movie popular. She is also interested in learning something new about movies. She wants you team to figure it all out.

As part of this project you will complete exploratory data analysis (EDA), modeling, and prediction.

All analysis must be completed using the R programming language via RStudio, and your write up must be an R Markdown document. To help you get started we provide a template Rmd file below (see Rmd template in the Required files section below). Download this file, and fill in each section.

***IMPORTANT***: Analyses completed using software other than R, or not written up using R Markdown, will receive a 0 on the project regardless of their content.

***

***More information on the data***
The data set is comprised of 651 randomly sampled movies produced and released before 2016.

Some of these variables are only there for informational purposes and do not make any sense to include in a statistical analysis. It is up to you to decide which variables are meaningful and which should be omitted. For example information in the the `actor1` through `actor5` variables was used to determine whether the movie casts an actor or actress who won a best actor or actress Oscar.

You might also choose to omit certain observations or restructure some of the variables to make them suitable for answering your research questions.

When you are fitting a model you should also be careful about collinearity, as some of these variables may be dependent on each other.   

***   

***More information on model selection***
You may choose to use any of the model selection techniques presented in this course, however you should justify your choice. Note that there are many other model selection techniques that are beyond the scope of this course, and those should not be used in this project.

Regardless of whether you are doing forward selection or backward elimination, you should decide on a set of variables that will be considered for the model. These do not have to include all of the variables in the dataset. In fact, some variables might be completely inappropriate to consider (such as URL of the movie) or clearly not informative (such as the actor variables with so many levels). You should first go through the dataset and identify the variable you want to consider, and provide a justification for including those (or excluding the others).
