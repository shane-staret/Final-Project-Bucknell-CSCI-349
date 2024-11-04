# Final Project | Shane Staret  

### [Link to final project video](https://mediaspace.bucknell.edu/media/FinalProjectVideo.mov/1_lj3dctqq)  

## Project Overview  
#### The primary problem presented through this dataset is one involving the prediction of student performance in secondary school based on data gathered on several hundred students. With 32 input variables, this is a high-dimensional dataset. The idea is to predict which of these variables, if any, can help us predict how well a student may perform academically. This is arguably a very important problem to look into, as determining variables that contribute to student achievement or failure can influence methods currently used within schooling to help students succeed. It can also help to identify variables that may irrelevant, allowing those focused on increasing student achievement to ignore these variables and focus on the impactful ones.  
  
#### This dataset displays student achievement in secondary education of two Portuguese schools. The data was collected using school reports and questionnaires. There are 33 total data characteristics (1 being the target value, which is the final grade of each student). The data attributes include student grades, demographic, social and school related features. Two datasets are provided regarding the performance in two distinct subjects: Mathematics and Portuguese language. The two datasets were modeled under binary/five-level classification and regression tasks. The idea is to predict student performance based on the values of 32 attributes. This data is directly from the University of Minho and is hosted by the ICS School in the University of California, Irvine (UCI).  
  
## Challenges  
#### Problems presented themselves when attempting to model the data, specifically when trying to use a Keras NN method. No matter the activation function, the optimizer, the number of hidden nodes, the batch size, batch size, or number of folds, the Keras NN model *never* performed better than the multiple linear regression model. Perhaps there are issues with how the Keras NN model was set up, however, I have exhaustedly experimented with this model with minimal improvement.

## Conclusions  
#### Overall, it appears that the conclusions in the research paper that evaluated this dataset are very similar to the conclusions of this project. Unless the first and second period grades are included, it is difficult to generate any meaningful predictions or a list of variables that are relevant/irrelevant to a student's final scores. In other words, previous student performance is the best predictor of future student importance. Of course, there are other variables that contribute negatively (previous failures, high weekday drinking, etc) and positively (good family relationship, school support, etc) but their influence appears to not be as great as the previous performance variables (G1 & G2).  
  
#### While not many strong relationships could be generated between the input variables and student performance, many irrelevant variables were found. These results could be used to focus on specific variables that have appear to have relevant influence on student performance, while putting less emphasis on attributes that appear to not have much effect.  
  
## Important Resources  
##### [Link to dataset](http://archive.ics.uci.edu/ml/datasets/Student+Performance)
##### [Link to research paper using this dataset](http://www3.dsi.uminho.pt/pcortez/student.pdf)