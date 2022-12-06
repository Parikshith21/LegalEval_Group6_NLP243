# LegalEval_Group6_NLP243
This repository is for the work of the project on LegalEval of predicting rhetorical roles

### **GPU is needed to run the models of BERT and BERT+LSTM -- So need to change the Runtype for this select Change Runtime Type option in the Runtime dropdown in colab to GPU and save**

#### Here are the steps needed for setting up the file path in respective notebook files:

#### For running the files in Colab for these three files of three models these are the following steps needs to be followed:

Files:
1. MLP__Legal_Eval_NLP243_Project_Group6.ipynb
2. Colab_BERT_and_BERT_LSTM_project_243_Sampled_Data_Group_6.ipynb
3. Colab_BERT_and_BERT_LSTM_project_243_Not_Sampled_Group_6.ipynb

Before running the files first need to create shortcut of the Datasets folder in the Drive:
- Right click on the Datasets Folder and select Add shotcut to drive
- Then click on My Drive
- Then click on ADD SHORTCUT

Now we can execute the files in colab, when we run the first cell we will be prompted to mount drive as 
"Permit this notebook to access your Google Drive files" so we need to follow the prompts so the drive with the Datasets Folder is mounted.

Next we can run the following cells.

**-------------------------------------------------------------------------------------------------------**
### The following steps are to run the notebooks in local jupyter 

Files:
1. MLP__Legal_Eval_NLP243_Project_Group6.ipynb
2. BERT_and_BERT_LSTM_project_243_Sampled_Data_Group_6.ipynb
3. BERT_and_BERT_LSTM_project_243_Not_Sampled_Group_6.ipynb
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

Install the following dependencies if not installed in the environment before using, **!pip install**
   * Python 3.x
   * transformers
   * scikit-learn 
   * scipy 
   * matplotlib
   * pandas
   * seaborn
   * nltk
   * numpy
   * torch

