# Analysis Overview

1. What variable(s) are the target(s) for your model?

    *The IS_SUCCESSFUL field from application_df*

2. What variable(s) are the features for your model?

    *Dropped the target variable from the dataframe and the remaining variables were the model featrures*

3. What variable(s) should be removed from the input data because they are neither targets nor features?

    *Remove 'EIN' and 'NAME' variables as they did not fit either of the above categories.*

# Training the Model

4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
    *Initially (and it was a stab in the dark), my model had eight hidden layers and five hidden nodes.*

5. Were you able to achieve the target model performance?

    *I came close with a 73% accuracy; my model did not achieve the 75% target*

6. What steps did you take in your attempts to increase model performance?

    *I removed columns, added additional layers and hidden nodes, and modified the activation types.*

# Summary

This deep learning was only 73% accurate. To increase accuracy I would:
* go back cleanup the data even further
* if that did not work, I could use a model that has a tighter correlation
* if that still did not work, I could choose a model with different activation type. 

*I would do a combination of all three until the score increases.*