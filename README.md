# Titanic Survival Prediction Web App

This is a simple machine learning web application built with Flask that predicts whether a passenger would have survived the Titanic disaster. It uses a trained classification model and offers a web interface for users to input features and get predictions.

## 🔧 Project Structure
├── static/                  # Static files (e.g., CSS, images)
├── templates/               # HTML templates for the web app
├── app.py                   # Flask application script
├── train\_model.py           # Script to train and save the model
├── titanic\_model.pkl        # Trained model file
├── requirements.txt         # Dependencies
├── render.yaml              # Deployment config (e.g., for Render.com)
└── README.md                # Project documentation

## 🚀 Getting Started

### Clone the Repository
git clone https://github.com/fortunemaviya/<your-repo-name>.git
cd <your-repo-name>


### Create a Virtual Environment (Optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

### Install Dependencies
pip install -r requirements.txt

### Run the App Locally

python app.py
Visit `http://127.0.0.1:5000/` in your browser to test the app.

## 🧠 Model Info

The model is trained on the [Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic) using features such as:

* Passenger class
* Age
* Sex
* Fare
* Embarked location
* Number of siblings/spouses or parents/children aboard

You can retrain the model using the `train_model.py` script.

## ☁️ Deployment

This project includes a `render.yaml` file for easy deployment on [Render.com](https://render.com/). After pushing your repo:

1. Create a new web service on Render.
2. Use Python as the environment.
3. Point to `app.py` as the start command.

## 🤝 Contributions

Pull requests and issues are welcome. Feel free to fork and enhance the project.

## 📄 License

This project is licensed under the MIT License.
