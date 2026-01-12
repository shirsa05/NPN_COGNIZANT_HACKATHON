# NPN_COGNIZANT_HACKATHON
A review sentiment analyzer solution for hotel owners.
<br>
```
NPN_COGNIZANT_HACKATHON <br>
|<br>
├── **src** -- Prediction endpoint<br>
│ ├── nltk_data/ -- Contains the nltk downloads<br>
│ ├── .gitignore<br>
│ ├── Contractions.py -- The file containing the mapping of contractions<br>
│ ├── __init__.py<br>
│ ├── app.py -- The app.py <br>
│ ├── feature_extractor.py -- Feature Extractor <br>
│ ├── model_evaluation.py -- Model Evaluator<br>
│ ├── model_trainer.py -- Model Trainer<br>
│ ├── preprocessor.py -- Precprocessor<br>
│ ├── requirements.txt<br>
│ └── sentiment_pipeline.pkl -- The full pipline<br>
|<br>
├── **NPN_COG_APP**   -- streamlit app<br>
│ ├── .gitignore<br>
│ ├── api_client.py -- api integration with database, and gensin endpoint<br>
│ ├── app.py -- main app.py<br>
│ ├── dashboard.py -- dashboard code<br>
│ ├── database.py -- database insert, fetch code<br>
│ ├── nltk.txt -- nltk downloads required for app<br>
│ └── requirements.txt<br>
|<br>
├── **others**   -- streamlit app<br>
│ ├── data_cleaning_ver1.ipynb -- an eda files<br>
│ ├── new_data.csv -- data used for training <br>
```



