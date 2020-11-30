# Employee-Attrition
The aim of this Project is to predict whether an Employee would face Attrition in this Lockdown period.
The model was made as part of a Hackathon Organised by Consulting and Analytics Club, IIT Guwahati.

Competition Link: [https://www.kaggle.com/c/summeranalytics2020](https://www.kaggle.com/c/summeranalytics2020)

## Working
The model used is an ensemble of Random Forest Classifier, XgBoost Classifier and LightGBM Classifier and achieves an AUC score of 0.804 on the test dataset. 
The web application is deployed with Flask as backend and the frontend was built using Bootstrap and some custom CSS.

## Demo
![](https://github.com/DebarshiChanda/Employee-Attrition/blob/master/Employee-Attrition.gif)

Link to Complete Demo: [Drive Link](https://drive.google.com/file/d/1yd-FzRsRnj7BX0ueNQwODuEJaRmUfP-A/view?usp=sharing)

## Usage
1. Create a Virtual Environment preferably with Anaconda
```bash
conda create -n myenv
```
2. Activate the virtual environment
```bash
conda activate myenv
```
2. Install the Requirements file
```bash
pip install -r requirements.txt
```
3. Change directory to the cloned directory

4. Run the app.py file using the following command
```bash
python app.py
```

## References
1. [Deploy Machine Learning Model using Flask by Krish Naik](https://www.youtube.com/watch?v=UbCWoMf80PY)
2. [Flask Tutorials by Corey Schafer](https://www.youtube.com/playlist?list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH)
