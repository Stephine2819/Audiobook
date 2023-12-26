# Audiobook
The project involves developing a machine learning algorithm for an Audiobook App with a focus on predicting whether a customer will make a repeat purchase. The primary challenge addressed is the efficient allocation of marketing resources by identifying customers likely to convert again, thereby optimizing advertising expenses. The model also aims to pinpoint key metrics influencing customer retention, offering growth opportunities by targeting valuable customer behaviors.

The dataset comprises customer purchase records, with each entry representing a customer who has made at least one purchase. It is a binary classification problem, categorizing customers into two classes: those who will buy again (1) and those who won't (0). The project workflow includes data extraction from a CSV file, preprocessing steps such as balancing the dataset and standardization of inputs, shuffling the data, and splitting it into training, validation, and test sets. The balanced datasets are saved in *.npz format for future use.

The machine learning model is a neural network with two hidden layers and a softmax output layer for classification. The model is trained using the Adam optimizer and sparse categorical cross-entropy loss function. Early stopping is implemented to prevent overfitting. The achieved accuracy on the test set is evaluated to assess the model's performance which in this case came out to be 92.13%.







