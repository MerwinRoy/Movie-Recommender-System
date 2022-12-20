# INFO 7390 : Advances in Data Sciences and Architecture
# Final Project: Movie Recommender System

![Home cinema-amico](https://user-images.githubusercontent.com/46862684/208759762-b8049ff7-1a00-4aa0-ae79-654d65d8dbf4.svg)

## Description

Implemented content-based and collaborative filtering recommender systems approach to apply an algorithm that provides relevant movie recommendations to users with the help of Netflix and Movie lens datasets from Kaggle, as well as sentiment analysis on reviews of movies recommended by the system.

 - For the content-based recommendation, the system makes use of cosine similarity metric to measure the similarity between movies from datasets based on different features such as movie genre, actors, and director names.

 - For collaborative filtering recommender system, the system makes use of Pearson’s correlation to measure similarity between users.
 
 - The system also makes use of sentiment analysis, a natural language processing technique (NLP) technique, on comments and reviews scraped from IMDB website to analyze and identify states and subjective information of reviews associated with movies recommended to users by the recommender system. 
 
 - The sentiment analysis has been implemented using CountVectorizer, CNN (Convolutional Neural Network) Model and LSTM-CNN model which combines the traditional neural networks CNN and LSTM (Long Short-Term Memory) model.
 
 The goal of the project is to study and compare different recommender systems (collaborative and content based) as well as different sentiment analysis models (CountVectorizer, CNN, LSTM-CNN) through metrics obtained and eventually provide near perfect movie recommendation results to users with reviews obtained through the process of sentiment analysis.


## Team
| **Team Members**|
| ------------- |
| Merwin Roy      |
| Abhijit Kunjiraman |

## System Architecture

![image](https://user-images.githubusercontent.com/46862684/208759977-3f051935-5f6a-49dd-a09d-e58fdfe957c6.png)

## Packages

<img width="434" alt="Screenshot 2022-12-20 at 3 27 10 PM" src="https://user-images.githubusercontent.com/46862684/208760084-6b4af422-fee1-4b05-8213-f66bb35a2833.png">

## Conclusion

### Model Evalutation

**Multinomial Naive Bayes Model**
   - ROC CURVE
   <img width="457" alt="image" src="https://user-images.githubusercontent.com/46862684/208762998-74928e65-1da8-43a4-a0df-bb18979c9529.png">

   - Precision-Recall Curve
   <img width="450" alt="image" src="https://user-images.githubusercontent.com/46862684/208763316-ac407c85-fd3c-4b61-86e9-ee4fd29d2460.png">

**CNN(Convolutional Neural Network) Model**

 - Training and Validation Accuracy
 <img width="510" alt="image" src="https://user-images.githubusercontent.com/46862684/208763414-075b9b7a-f0bc-4514-9bb4-768cde60d663.png">

 - Training and Validation Loss
 <img width="526" alt="image" src="https://user-images.githubusercontent.com/46862684/208763470-73344274-90de-4118-99e0-e535bbbe5999.png">

**CNN-LSTM(Long Short-Term Memory) Model**

 - Training and Validation Accuracy
 <img width="431" alt="image" src="https://user-images.githubusercontent.com/46862684/208763613-8ca2e5f5-d903-4f34-a1b8-cf135b60317a.png">

 
  - Training and Validation Loss
  <img width="439" alt="image" src="https://user-images.githubusercontent.com/46862684/208763642-d859bc81-2aaf-4117-9f83-3e976491aeca.png">


### Result
<img width="735" alt="Screenshot 2022-12-20 at 3 27 58 PM" src="https://user-images.githubusercontent.com/46862684/208760200-d3c3c0d6-9798-485c-924a-58148c021845.png">

After a comparative study on the models above, we conclude that the classification model using the Convolutional Neural Network (CNN) is model that yielded the best results with an approx. accuracy score of 99.13 %.

