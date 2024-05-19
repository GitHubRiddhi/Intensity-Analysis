# Intensity-Analysis #

## Sentiment Analysis Model Deployment ##

This project aims to deploy a sentiment analysis model using Amazon SageMaker. The model predicts the sentiment (happiness, sadness, or angriness) of textual data. The project demonstrates the end-to-end process of building, training, and deploying a machine learning model for sentiment analysis.

## Dependencies
Python 3
pandas
scikit-learn
sagemaker
Amazon SageMaker account with appropriate IAM roles
To install the required Python libraries, run:

## Copy code
pip install pandas scikit-learn sagemaker

## Usage
 Data Preparation: Preprocess the textual data by removing special characters, converting text to lowercase, and handling missing values.
 
Feature Engineering: Use TF-IDF Vectorization to convert text into numerical features and select the top features using SelectKBest with a chi-square test.

Model Training: Split the data into training and testing sets, initialize a Multinomial Naive Bayes classifier, and train the model on the training data.

Model Evaluation: Evaluate the trained model using accuracy score, classification report, and confusion matrix.

Hyperparameter Tuning: Fine-tune the model hyperparameters using GridSearchCV or RandomizedSearchCV for improved performance.

Model Deployment: Deploy the best performing model to Amazon SageMaker as an endpoint for real-time predictions.

## Contribution Guidelines
Contributions to this project are welcome. To report bugs, suggest improvements, or submit pull requests, please follow the guidelines outlined in CONTRIBUTING.md.

## Data Science Community:

Continuous learning and inspiration from the vibrant data science and machine learning communities.

## Online Resources:

AWS Documentation, Blogs, articles and tutorials that provided valuable insights and knowledge. I appreciate the collective efforts of the open-source community and the wealth of knowledge shared by individuals and organizations.

If you find any resource missing or would like to be credited, please let us know, and I'll make sure to acknowledge your contributions.

Thank you for being part of this journey!

Riddhi Sharma - Data Scientist
