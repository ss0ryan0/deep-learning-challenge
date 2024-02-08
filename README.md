# Report
## Overview
* The purpose of this analysis is to determine what models most accurately predict the data based on the targets, features, neurons, layers, and activation functions.
## Results
![Epoch Model Fit Results](deep-learning-challenge/epochs.png)
### Data Processing:
* What variable(s) are the target(s) for your model?
  * _**The Application Type, the Class, and the Name**_
* What variable(s) are the features for your model?
  * _**'IS_SUCCESSFUL': the success status**_
* What variable(s) should be removed from the input data because they are neither targets nor features?
  * **_Except for attempt 2, the EIN and NAME were removed. In attempt 2, with the help and suggestion of a tutor, the Name was put back in._**

### Compiling, Training, and Evaluating the Model
[Model Parameters] (deep-learning-challenge/params.png)
* How many neurons, layers, and activation functions did you select for your neural network model, and why?
 * I did 3 layers with all 3 activation functions so that the best of all 3 functions can work together.
Were you able to achieve the target model performance?
 * In the second attempt, when I didn't drop the 'NAME' column, I was able to acheive my target performance of over 75%.
What steps did you take in your attempts to increase model performance?
 * With the help of a tutor, I kept the name value and used all 3 functions: relu, sigmoid, and tanh, and they all worked in increasing model performance.

## Summary
* To summarize, when the 'NAME' column was kept and when I used 3 layers: Relu, TanH, and Sigmoid, in that order, I acheived my target performance of over 75%.
* A different model I would use would be to add more hidden layers to further increase the accuracy. I would play around with the combinations of Relu, TanH, and Sigmoid to test for better performance. I would also modify the units to change the output shape to test for higher performance and greater levels of accuracy.
