# Disaster Response Pipeline Project
![Header](../screenshots/header.png)
### Table of content

1. [Description](#description)
2. [Dependencies](#dependencies)
3. [Instructions](#instructions)
4. [Authors](#authors)
5. [License](#license)
6. [Acknowledgement](#acknowledgement)
7. [Screenshots](#screenshots)

### Description




### Dependencies
- Python 3.5+
- Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
- Natural Language Process Libraries: NLTK
- SQLlite Database Libraqries: SQLalchemy
- Model Loading and Saving Library: Pickle
- Web App and Data Visualization: Flask, Plotly

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Go to `app` directory: `cd app`

3. Run your web app: `python run.py`

4. Click the `PREVIEW` button to open the homepage

### Authors
- Cheruiyot Emmanuel

### License
- None

### Acknowledgements
- Udacity
- Landlord, MultiLingual disaster Response Messages https://www.kaggle.com/datasets/landlord/multilingual-disaster-response-messages

### Screenshots
![Ditribution-of-messages](../screenshots/distribution.png)
![Ditribution-of-disasters](../screenshots/distribution_of_disaster.png)



