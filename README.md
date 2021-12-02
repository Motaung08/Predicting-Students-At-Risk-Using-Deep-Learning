# Predicting-Students-At-Risk-Using-Deep-Learning
Machine learning algorithms have lately gained popularity for analyzing educational data and uncovering hidden meaningful patterns for predicting student grades. This research compares the best probabilistic machine learning models from other researchers and the ones implemented to the implemented deep learning neural network and analyses the students’ accomplishments in the context of learning students’ behavioral attributes. Students academic performance classification is tackled by first identifying and extracting aspects of students' behaviour. Subsequently students features were tested for their significance in the task of classification using mutual information gain in order to make the feature vector compact, comprehensive and efficient. After several off-the-shelve classifiers were used, Support Vector Machines with a radial basis function kernel turned out to be the best performing model achieving an accuracy of 77.51% in classifying students into 3 label classes,labeled L: low-level (0-69), M: Middle-level (70-89) and H: High level (90-100). A detailed write up can be found in the Research report pdf.

## Models and Accuracy
- Support Vector Machine (77.51%)
- Random Forest (77.36)
- k Nearest Neighbor (75.74%)
- Multilayer Perceptron (73.73%)
- Convolutional Neural Network (72.58%)

## Feature Selection
With a varied number of relevant characteristics, there is a cut off point represented by a red vertical line where a number of features can be omitted without affecting classification accuracy significantly. Support vector machines were used to create the graph.

![Alt txt](https://github.com/Motaung08/Predicting-Students-At-Risk-Using-Deep-Learning/blob/main/images/SVCConfMtr.png)
<!-- ![Alt text](https://github.com/Motaung08/Predicting-Students-At-Risk-Using-Deep-Learning/main/images/graph.png) -->
<!-- ![Alt text](https://raw.githubusercontent.com/Motaung08/Brain-Tumor-Segmentation/main/results/LR_cm.png) -->
