# CS4248Proj

## Sections 3 of the report (Corpus Analysis/Preprocessing/Feature Engineering)
Requirements: To run the notebook on Google Colab, connect Google Drive and place the raw_data into the your root directory
- Corpus Analysis: The results of corpus analysis can be directly observed from the outputs
- Preprocessing: Under the section "Preprocessor Class" in "CorpusExploration_Preprocessing_FeatureEngineering.ipynb" we provide instructions on how to preprocess and vectorize data
- Feature Engineering: Parts of feature engineering can be found under the "Preprocessor Class" from the previous point. Analysis and generation of preprocessed topic modelling features can be found in "FeatureEngineering_TopicModelling.ipynb"

## Sections 4.1 - 4.4 of the report (Statistical Methods)

There are 2 types of data collection "scripts" here, which are further annotated in markdown cells in the notebook:
- "One-off": Runs one combination of parameters. Good for quick testing.
- "Combination": Runs multiple combinations of parameters. Good for overnight testing.

Other than that, simply make sure that `fulltrain.csv` and `balancedtest.csv` files from the dataset are in the same folder as this notebook. (or, you can edit the variables `FULL_TRAIN/TEST_PATH` down below)

## Sections 4.5 - 4.7 of the report (Logistic regression & LSTM)

There are two python notebooks that are uploaded, which have our pre-processing functions as well as the model set up prepared. 

Logistic_regression.ipynb (Logistic regression implementation)
LSTM.ipynb (LSTM implementation)

These notebooks should be run on google colab as we have tested it on.

Ensure that `fulltrain.csv` and `balancedtest.csv` files are in the user's google drive, and reference the file path in the top few cells in the notebook.




