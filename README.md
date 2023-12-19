The aim of this project is to conduct a comparative study on Sentiment Analysis of Arabic Reviews and translated reviews into English using a Deep Learning LSTM model.
The Arabic dataset has been downloaded from "https://www.kaggle.com/datasets/abanoubsamir004/arabic-reviews-sentiment-analysis?resource=download".
The file "ArabicToEnglishDatasetGenerator.ipynb" will translate the reviews from "original_dataset.xlsx" into English and generate a translated dataset named "ArabicToEnglishDatasetTwoClass.xlsx." This dataset will contain two columns, one for Arabic and the other for English.
"ArabicSentimentAnalysisUsingLSTM.ipynb" will utilize Arabic reviews from "ArabicToEnglishDatasetTwoClass.xlsx" to train the model and produce results.
"ArabicEnglishSentimentAnalysisUsingLSTM.ipynb" will use English reviews from "ArabicToEnglishDatasetTwoClass.xlsx" to train the model and produce results.
The remaining 'xlsx' files have been generated from the proposed model.
