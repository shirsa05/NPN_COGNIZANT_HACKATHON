# NPN_COGNIZANT_HACKATHON
A review sentiment analyzer solution for hotel owners.
 
```
NPN_COGNIZANT_HACKATHON 
|
├── src -- Prediction endpoint
│ ├── nltk_data/ -- Contains the nltk downloads
│ ├── .gitignore
│ ├── Contractions.py -- The file containing the mapping of contractions 
│ ├── __init__.py 
│ ├── app.py -- The app.py  
│ ├── feature_extractor.py -- Feature Extractor  
│ ├── model_evaluation.py -- Model Evaluator 
│ ├── model_trainer.py -- Model Trainer 
│ ├── preprocessor.py -- Precprocessor 
│ ├── requirements.txt 
│ └── sentiment_pipeline.pkl -- The full pipline 
|
├── NPN_COG_APP -- streamlit app 
│ ├── .gitignore 
│ ├── api_client.py -- api integration with database, and gensim endpoint 
│ ├── app.py -- main app.py 
│ ├── dashboard.py -- dashboard code 
│ ├── database.py -- database insert, fetch code 
│ ├── nltk.txt -- nltk downloads required for app 
│ └── requirements.txt 
|
├── others -- streamlit app 
│ ├── data_cleaning_ver1.ipynb -- an eda files 
│ ├── new_data.csv -- data used for training  
```



