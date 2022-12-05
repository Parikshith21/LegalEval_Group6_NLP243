# LegalEval_Group6_NLP243
This repository is for the work of the project on LegalEval of predicting rhetorical roles

#### Here are the steps needed for setting up the file path in respective notebook files:
1. To run the notebook : MLP__Legal_Eval_NLP243_Project_Group6.ipynb
Dataset files for path variables should be replaced are as follows
    * train_data_json = '/Datasets/train.json'
    * dev_data_json = '/Datasets/dev.json'
    * train_data_csv = '/Datasets/train_data_converted_json_to_csv1_0.csv'
    * dev_data_csv = '/Datasets/dev_data_converted_json_to_csv.csv'
    
2. To run the notebook : BERT_and_BERT_LSTM_project_243_Not_Sampled_Group_6.ipynb
Dataset files for path variables should be replaced are as follows
    * train_initial_data = '/Datasets/train_data_converted_json_to_csv1_0.csv'
    * train_data_sampled = '/Datasets/train_data_sampled.csv'
    
3. To run the notebook : BERT_and_BERT_LSTM_project_243_Sampled_Data_Group_6.ipynb
Dataset files for path variables should be replaced are as follows
    * train_initial_data = '/Datasets/train_data_converted_json_to_csv1_0.csv'
    * train_data_sampled = '/Datasets/train_data_sampled.csv'
    
**After changing the paths or downloading the daatsets and changing the paths as per local the notebooks can be executed.**
#### For Accuracy graphs, Loss graphs, Classification Report and Confusion Matrix can refer the folder /Accracy_Loss_Matrix_Report_Images


### Dependencies
   * Python 3.x
   * transformers
   * scikit-learn 
   * scipy 
   * matplotlib
   * pandas
   * seaborn
   * nltk
   * torch
