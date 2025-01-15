# FloralFor - Flower Detection

## Project Description
FloralFor is a machine learning project that detects and classifies flowers using advanced algorithms. The project leverages Python-based machine learning models, deployed through the Django framework to offer a user-friendly web interface. It incorporates Jupyter notebooks for training models, supports a pre-trained model for rapid deployment, and features an interactive front-end for user engagement.

---

## Features
- **Flower Detection**: Predicts flower species with high accuracy.
- **Django Integration**: Provides a seamless web interface for interactions.
- **Pre-trained Models**: Includes serialized models for quick deployment.
- **Customizable**: Designed for easy retraining with new datasets.
- **Interactive Frontend**: Responsive web UI for users.

---

## Folder Structure

```
FloralFor---Flower-Detection/
|
|-- FlowerDetection/         # Scripts and core machine learning logic
|-- Notebooks/               # Jupyter notebooks for training and analysis
|-- djangoMLDeployment/      # Django app for deploying the model
|-- static/images/           # Static assets for the web application
|-- templates/               # HTML templates for the web interface
|-- trainedModel/            # Pre-trained serialized model files
|-- db.sqlite3               # SQLite database for Django
|-- manage.py                # Django's management script
```

---

## Getting Started

### Prerequisites
- Python 3.8+
- Django 3.2+
- Required Python packages (listed in `requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/suyash0131/FloralFor---Flower-Detection.git
   cd FloralFor---Flower-Detection
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use `env\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```
6. Access the application at `http://127.0.0.1:8000/`.

---


