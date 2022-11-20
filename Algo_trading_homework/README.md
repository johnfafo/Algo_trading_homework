# Algo_trading_homework

I created a baseline performance using SVM and trainning the data over 3 months <br>
Initial accuracy was 0.64 <br>

![Image](Starter_Code/Initial_SVM_Accuracy.png) <br><br>
![Image](Starter_Code/Graph_with_3months_training.png)<br><br>

I altered the training period to 10 months with worsening results <br><br>
Acccuracy decreased to 0.55
        ![Image](Starter_Code/10months_training_period.png) <br><br>
        ![Image](Starter_Code/Graph_with10_months_training.png) <br><br><br><br>

I increased the training period to 30 months with slightly better results <br><br>
Accuracy was 0.57<b>

![Image](Starter_Code/30months_training.png) 
    ![Image](Starter_Code/Graph_with_30months_training.png)<br><br><br><br>

I again changed the moving averages to 10 & 65  periods for long and short SMA<br>
Training period was 3months and accuracy improved to 0.63 <br>

![Image](Starter_Code/SMA_short&long_changed_10&65.png)<br><br>
![Image](Starter_Code/Graph_for_diff_SMA.png)<br><br><br><br>

Finally i added 3 imput parameters<br>
 1. SMA fast minus close shifted by 1 period<br>
 2. Close - SMA Slow shifted by 1 period <br>
 3. Multipied both parameters above shifted by 1 period <br>

Acurracy increased to 0.67 
        ![Image](Starter_Code/New_parameters_Accuracy.png)<br><br>
        ![Image](Starter_Code/New_parameters.png)<br><br><br><br>

Finally i used a new classifier Logistic regression this had an accuracy of 0.52
        ![Image](Starter_Code/New_classifier.png)<br><br><br><br>

## Conclusion 
<br><br>
### The SVM model performed better than Logistic regression 
### The training period was better at 3 months. 
### Adding new parameters provided improved accuracy

