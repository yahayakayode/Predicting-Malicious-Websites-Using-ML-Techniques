## Predicting Malicious Websites Using Machine Learning Techniques
> The objective this project is to use supervise or classifier algorithms to classify website into either Malicious (Type=1) or Benign (Type=0) using the various features given in the dataset
> The data revealed that the target label (type) has data imbalance as 12.1% of the dataset is Malicious Websites, while 87.9% is Benign Websites, this data imbalance was solved using Synthetic Minority Oversampling Technique (SMOTE) for data augmentations.<br>
> Positive strong correlations was observed among some of the features such as; number_special_characters and url_length,  tcp_conversation_exchange and `remote_app_packets, app_bytes and remote_app_bytes among others.<br>
> Decision Tree and XGBoost algorithms were used, and XGBoost performed better with accuracy of 96%, while Decision Tree have an accuracy of 94%.
