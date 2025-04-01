# comp-560-project
### TODO immediately
- **Everyone create their own branch with username**
- **Make sure to pull from main before committing anything to avoid conflicts**
- **Create and activate a virtual environment:**
    `python3 -m venv venv` \
    `source venv/bin/activate`
- **Git pull frequently!**
- **Everyone install the required packes and check out the code**

### Gameplan
- blank

### Questions
- What are we trying to predict?
- How do we keep dependencies consistent across our devices?

### Abstract 
### Predicting Titanic Survival Probability Using TensorFlow
The objective of this project is to apply machine learning to predict the probability of survival for an individual passenger of the Titanic. The model is built and trained on the TensorFlow platform with a specific dataset containing key attributes such as age, gender, ticket class, number of relatives in the ship, and fare paid. Input data is cleaned and transformed using TensorFlow feature columns for both numerical and categorical variables. A sequential neural network model was constructed with two fully connected layers, each with 128 neurons, employing ReLU activation functions. A probability score is assessed with the final output layer using sigmoid function, determining the chances of survival from 0-1. The dataset is split into training and evaluation sets and data is streamed to the model in batches to manage memory more efficiently. The model is trained with Adam optimizer and binary cross-entropy loss function, producing evaluation accuracy of 79.92%.

Following the training, the model is able to determine the likelihood of survival of each individual passenger depending on their personal traits. A sample prediction was conducted where it was estimated the chance of survival probability for a second-class male passenger was 5.56%. This figure was compared to the actual survival data. This project demonstrates the effectiveness of deep learning in classification tasks and highlights the importance of data preprocessing, model architecture, and evaluation metrics in machine learning applications.

