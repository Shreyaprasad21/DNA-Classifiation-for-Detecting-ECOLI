# DNA Classification for E.Coli Detection
![image-1](https://github.com/Shreyaprasad21/Feynn-AI-Product-Service-Prototype-Development-DNA-classification-app/assets/142075353/56dae95e-6464-411b-b522-47f957fc8045)
This project involves the classification of DNA sequences to detect the presence of E.Coli. It employs a machine learning model, specifically an MLPClassifier, trained on a dataset of promoter gene sequences. The web application, built with Django, allows users to input DNA sequences and view classification results. The project encompasses data preprocessing, model training, and prediction functionalities. The machine learning model is serialized and saved to disk, and a one-hot encoder used in preprocessing is also saved for future use. The project is structured for reproducibility and deployment.
                        
## Usage

1. Create a Django project: `django-admin startproject <project_name>`
2. Create a Django app: `python manage.py startapp <app_name>`
3. Set up `settings.py` in the project directory.       
4. Initialize tables: `python manage.py migrate`
5. Run the server: `python manage.py runserver`

## Project Structure                                          

- The main project folder contains Django settings and configurations.
- The app folder (`mysite/polls`) includes views, models, and templates for the web application.
- The `Code files` directory holds the DNA classification script and saved model files.

## Libraries and Commands

```bash
pip install asgiref==3.4.1
pip install Django==3.2
pip install joblib==1.1.0
pip install numpy==1.19.5
pip install pandas==1.1.5
pip install python-dateutil==2.8.2
pip install python-dotenv==0.19.2
pip install pytz==2021.3
pip install scikit-learn==0.22
pip install scipy==1.5.4
pip install six==1.16.0
pip install sqlparse==0.4.2
pip install threadpoolctl==3.0.0
pip install typing_extensions==4.0.1
