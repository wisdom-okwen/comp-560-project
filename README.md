> Collaborators/group: Paul Signorelli, Christopher Sáez, Wisdom Okwen, Austin Campbell, Ethan Byrd, Will Scuria

# Abstract: Predicting Bank Customer Churn Using Machine Learning and Deep Learning  

Customer churn refers to the process of customers leaving a service or discontinuing their relationship with a business. This study develops both a traditional machine learning classifier and a deep learning model to predict customer churn based on past customer data, including demographic details, insurance history, and engagement metrics.  

Prior to model training, the dataset is preprocessed using one-hot encoding for categorical features. Our machine learning classifier, implemented with Scikit-learn, achieves a mean cross-validation accuracy of 90.17% on test data. For our deep learning approach, we employ PyTorch and structure the data into tensors for efficient computation.  

The neural network consists of seven layers, including three trainable layers using `torch.nn.Linear()`. The first hidden layer has 64 neurons, followed by a ReLU activation function (`torch.nn.ReLU()`) to capture non-linear patterns. A dropout layer (`torch.nn.Dropout(0.3)`) mitigates overfitting by randomly deactivating 30% of neurons. Subsequent layers reduce the neuron count from 64 to 32 before outputting a final prediction layer with two neurons.  

The model is optimized using the Adam optimizer and trained with binary cross-entropy loss. After 50 epochs with a batch size of 32, our deep learning model achieves an average predictive accuracy of approximately 91%. These results highlight the effectiveness of both machine learning and deep learning approaches in predicting customer churn, providing valuable insights for financial institutions aiming to improve customer retention strategies.  