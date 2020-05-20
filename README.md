# Data_Science_Portfolio
20-30 second overview of each project. Use this to navigate through my portfolio. :)


## Using Reisistance Training Data to Facilitate Strength Progression.
#### Read the project report [here](https://matthewnaples.github.io/Individual_Strength_Analysis/)
#### View the repository with code  [here](https://github.com/matthewnaples/Individual_Strength_Analysis)
* As a result of the analysis, I put 30 pounds on my bench press (310-340 lbs) , 50 pounds on my squat (405-455) , and about 65 pounds on my deadlift (430-495)  after nearly a year of stagnation.
* Before the analysis, I gathered my resistance training data for approximately one year. 
* I used an iterative approach. I followed an 8-10 week program, performed an analysis, updated the program, then followed the updated version. There were a total of four programs performed.
* No formal statistical modeling was used for the following reasons: (1) I'm not estimating population parameters; (2) time series forecast is useless, as I am knowingly going to manipulate causal factors that will change the process governing that forecast; (3) formal experimental design is untennable.



[example_image] (image alt-text)

## Predicting strength changes in the powerlifting population over time using ARIMA models
#### Read the report [here](https://matthewnaples.github.io/powerlifting_TSA/)
#### View code at the original repo [here](https://github.com/matthewnaples/powerlifting_TSA/) 
* Using arima forecasting, I predict change in the powerlifting population over time with a Mean Absolute Error of ~ 5 IPF-points, which can be interpreted as around 80 pounds (for a 185 pound male).
* This data uses the powerlifting competition scores from hundreds of thousands of powerlifters.


## Identifying lawns from Satellite Images of Properties Using Mask R-CNN
#### Read the report [here](https://github.com/matthewnaples/Lawn_maskRCNN/blob/master/Final%20Report%20-%20Geospatial%20Object%20Detection.pdf)
#### View the python notebook and instructions for running the model [here](https://github.com/matthewnaples/Lawn_maskRCNN)
* Identified lawns with a mean Average Arecision (mAP) of 86.02%.
* Adopted [Matterport Inc's implementation](https://github.com/matterport/Mask_RCNN) of Mask R-CNN for the challenge.
* used image augmentation to overcome sample size barriers (only 85 original images).



