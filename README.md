# EMNIST-Hand-Written-Recognition-AI
Create a MLP neural network model using SKlearn. This model is trained using EMNIST Dataset's 120,000 images of a-z letters and the remains are used as testing set. It can take in images from the internet or from your local drive, and predict what letter it is. 

The validation accuracy after  50 epochs and 5 hidden layers is ~92%.

Unfortunately, micmicking EMNIST's preprocessing method still does not yield good accuracy when using an image outside of the dataset. 
The main reason is the noise (colors, lighting, letter thickness, ...) from taking picture on your phone or online alters the model decision dramatically.

Google Colab link: https://colab.research.google.com/drive/10P6_9vcsKmjGZfCnyDRhdACINPH9wgjD?usp=sharing
