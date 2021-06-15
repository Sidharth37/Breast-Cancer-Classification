# Breast-Cancer-Classification
Classified medical records into benign and malignant breast cancer cases, based on 30 features.
<b>Business Case?</b><br>
Mamography is one of the most prevalent way for detecting breast cancer. The sensitivity of for this technique is 87%. This literally means that 13% of the cases go undected.
Breast cancer is vry treatable if you spot it early, the main objective behind this project is improving the detection percentage of 87% which we achieve through mamography.<br>

<b>The project is divided into 5 main parts:</b><br>
1. Importing, exploring and visualizing the features in the dataset.<br>
2. Creating a baseline model, for classifying medical records into benign and malignant<br>
3. Evaluation of the baseline model<br>
4. Improving the classification model using techniques such as Grid Search<br>
5. Evaluation of the improved model<br>
<br>
<b>Importing, exploring and visualizing the features in the dataset -</b><br>
The dataset is based on 30 features pertaining to the physical attributes of the breast like - mean radius, mean texture, mean perimeter, mean area ...
Based on the sample we have 37% of the cases are malignant and the rest 63% cases are benign.
Based on the heatmap inclusive of all the features and the reuslt, the 5 most influential features correlating with the record being malignant are largest concave points, largest perimeter, largest radius, mean concave points and mean perimeter<br><br>
<b>Creating a baseline model, for classifying medical records into benign and malignant -</b><br>
The machine learning model we have built is based on Support Vector Machines.
We start by pre-processing all the 30 features to get everything on the same scale. This would get rid of biases caused to inconsistent scales and measurements.
We then proceed to forming a 80-20 train-test split.<br>
After this we move to fitting the support vector classification model and start predicting.<br><br>
<b>Evaluation of the baseline model</b><br>
Even with the baseline model, we have been able to achieve an accuracy score of 87%.
But we are falling behing on identifying the malignant cases. We have been able to able to identify the malign cases with a score of mere 65%. 
The cost of detecting a malignant record is much more than the cost of misidentifying a benign case as malignant. <br><br>
<b>Improving the classification model using techniques such as Grid Search</b><br>
