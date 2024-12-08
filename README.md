Hey there, this is my code for Task 5, Sentiment Analysis using BERT:

Here, I have used the BERT-small model due to limitations on my laptop and kaggle. The dataset that I trained on is the Sentiment140 Dataset. The model was only trained on a part of it( about a fifth) due to computation limitations.

The pipeline I followed was :

1) Data Exploration: Went through different datasets available and their properties, used the Sentiment140 Twitter dataset.
2) Tokenization of the given dataset (There was no need of cleaning the dataset as it was already done.) and one hot encoding of the target to make it a classification problem
3) Defining the model - Used BERT Small due to limitations and added a fine tuned it
4) Training and Validation
5) Deployment using Gradio

Please find the training results of the model below:
![image](https://github.com/user-attachments/assets/502ac963-8a1d-4898-afe8-dedb3930ffd6)
![image](https://github.com/user-attachments/assets/3db9a125-6fae-4d4c-9973-52f6ad991226)
I have deployed the model using Gradio, here's how it looks:
![image](https://github.com/user-attachments/assets/8d97fad3-f0d2-4d11-9fc3-d5c0bac34189)
![image](https://github.com/user-attachments/assets/1b178adf-13ce-4992-b5c8-158c818db410)
The gradio can be made public by using ngrok.

Feel free to run the code and check it out
