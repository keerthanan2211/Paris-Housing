# Paris-Housing
Abstract:

This project focuses on the classification of Paris housing using machine learning techniques. The dataset used consists of a variety of features such as housing size, location, age, and price. The goal of this project is to develop a model that can accurately classify Paris housing based on these features. The model will use supervised learning algorithms such as Decision Tree(DT) and NaiveBayes to classify the data into categories such as high-end, mid-range, and low-end housing to improve the accuracy of the model. The results of this project will provide insight into the housing market in Paris, as well as a model that can be used to accurately classify the city's housing.

Procedure :

To load the "ParisHousingClass.csv" dataset into Weka and apply the Decision Tree and Naive Bayes algorithms, follow these steps:

Step 1: Launch Weka Tool Open the Weka tool on your computer. Ensure that you have the latest version of Weka installed.

Step 2: Load the Dataset

Click on the "Explorer" tab in Weka. Click on the "Open file" button, or go to "File" > "Open" and navigate to the directory where "ParisHousingClass.csv" is located. Select the "ParisHousingClass.csv" file and click "Open." Weka will automatically detect the file format and load the dataset. Step 3: Preprocess the Dataset (if necessary) If your dataset requires preprocessing, you can use the various preprocessing options available in Weka. These include handling missing values, attribute selection, normalization, etc. Perform the necessary preprocessing steps according to your dataset requirements.

Step 4: Select the Algorithm

Click on the "Classify" tab in Weka. In the "Classifier" section, click on the dropdown arrow to see the list of available classifiers. Select "trees" and choose "J48" as the Decision Tree algorithm. Alternatively, select "bayes" and choose "NaiveBayes" for the Naive Bayes algorithm. Step 5: Set Evaluation Options (optional) You can configure the evaluation options to control how the algorithms are evaluated and to obtain performance metrics.

Click on the "More options" button under the "Test options" section. Set the desired evaluation options such as cross-validation, percentage split, etc. Step 6: Run the Algorithm

Click on the "Start" button to initiate the classification process. Weka will train the selected classifier on the loaded dataset and display the results in the output area. Step 7: Analyze the Results You can analyze the results provided by Weka, such as accuracy, precision, recall, F-measure, etc., to evaluate the performance of the algorithms.

That's it! You have successfully loaded the "ParisHousingClass.csv" dataset into Weka and applied the Decision Tree and Naive Bayes algorithms. Remember to interpret the results and adjust the algorithm or evaluation options as needed for further analysis.
