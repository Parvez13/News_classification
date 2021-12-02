# News Classification

## 🎯Problem Statement

In today’s world, data is power. With News companies having terabytes of data stored in
servers, everyone is in the quest to discover insights that add value to the organization.
With various examples to quote in which analytics is being used to drive actions, one that
stands out is news article classification.

Nowadays on the Internet there are a lot of sources that generate immense amounts of
daily news. In addition, the demand for information by users has been growing
continuously, so it is crucial that the news is classified to allow users to access the
information of interest quickly and effectively. This way, the machine learning model for
automated news classification could be used to identify topics of untracked news and/or
make individual suggestions based on the user’s prior interests.

## 📝Data Description

The dataset is downloaded from [Kaggle](https://www.kaggle.com/c/learn-ai-bbc/data). 

## 🌳Project Tree
```
Folder PATH listing for volume OS
Volume serial number is D68C-5DC3
C:.
|   requirements.txt
|   tree.txt
|   
|       
+---Dataset
|   |   BBC News Sample Solution.csv
|   |   BBC_ News_Test.csv
|   |   BBC_News_Train.csv
|   |   __init__.py
|   |   
|   \---.ipynb_checkpoints
|                   
+---reports
|   |   __init__.py
|   |   
|   +---logs
|   |       logs.txt
|   |       
|   +---Model_Logs
|   |   +---model_2_Conv1d
|   |   |   \---20211129-014706
|   |   |       +---train
|   |   |       |       events.out.tfevents.1638150426.825470378f70.74.2.v2
|   |   |       |       
|   |   |       \---validation
|   |   |               events.out.tfevents.1638150435.825470378f70.74.3.v2
|   |   |               
|   |   +---Model_3_LSTM
|   |   |   \---20211129-014722
|   |   |       +---train
|   |   |       |       events.out.tfevents.1638150442.825470378f70.74.4.v2
|   |   |       |       
|   |   |       \---validation
|   |   |               events.out.tfevents.1638150449.825470378f70.74.5.v2
|   |   |               
|   |   +---Model_4_GRU
|   |   |   \---20211129-014756
|   |   |       +---train
|   |   |       |       events.out.tfevents.1638150476.825470378f70.74.6.v2
|   |   |       |       
|   |   |       \---validation
|   |   |               events.out.tfevents.1638150483.825470378f70.74.7.v2
|   |   |               
|   |   +---Model_5_Bidirectional(LSTM)
|   |   |   \---20211129-014826
|   |   |       +---train
|   |   |       |       events.out.tfevents.1638150506.825470378f70.74.8.v2
|   |   |       |       
|   |   |       \---validation
|   |   |               events.out.tfevents.1638150529.825470378f70.74.9.v2
|   |   |               
|   |   +---Model_6_Bert
|   |   |   \---20211129-015051
|   |   |       +---train
|   |   |       |       events.out.tfevents.1638150651.825470378f70.74.10.v2
|   |   |       |       
|   |   |       \---validation
|   |   |               events.out.tfevents.1638150686.825470378f70.74.11.v2
|   |   |               
|   |   \---simple_dense_model
|   |       \---20211129-014659
|   |           +---train
|   |           |       events.out.tfevents.1638150420.825470378f70.74.0.v2
|   |           |       
|   |           \---validation
|   |                   events.out.tfevents.1638150422.825470378f70.74.1.v2
|   |                   
|   +---notebook
|   |       news_classification.ipynb
|   |       
|   \---saved_model
|       |   bidirectional.pkl
|       |   
|       \---bidirectional_lstm
|           |   keras_metadata.pb
|           |   saved_model.pb
|           |   
|           +---assets
|           \---variables
|                   variables.data-00000-of-00001
|                   variables.index
|                   
```

## ⚒️ Tools Used
![tools](https://user-images.githubusercontent.com/66157611/144349534-16132f61-7f06-4990-b91f-ad8e13776b5d.png)

## 👦Contributor
[Mohammad Sohail Parvez](https://github.com/Parvez13/)
