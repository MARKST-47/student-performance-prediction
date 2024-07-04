# Student Exam Performance Prediction

This repository contains a machine learning project that predicts student exam performance using MLOps pipelines and a web interface built with Flask. The project includes exploratory data analysis (EDA), model training, and deployment processes, all documented in Jupyter notebooks.

## Table of Contents

- [Project Overview](#project-overview)
- [Setup and Installation](#setup-and-installation)
- [Data Exploration and Preprocessing](#data-exploration-and-preprocessing)
- [MLOps Pipeline](#mlops-pipeline)
- [Web Interface](#web-interface)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to predict students' performance in exams based on various features such as gender, ethnicity, parental level of education, lunch type, test preparation course, and scores in reading and writing. The project leverages MLOps practices to streamline the workflow and ensure reproducibility and scalability.


## Setup and Installation

1. **Clone the repository:**
   
   git clone https://github.com/MARKST-47/student-performance-prediction.git

   cd student-performance-prediction

2. **Create and activate a virtual environment:**

python -m venv venv

source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. **Install the required packages:**

pip install -r requirements.txt

4. **Run the Flask web application:**

python app.py

## Data Exploration and Preprocessing:

The exploratory data analysis (EDA) and data preprocessing steps are documented in the Jupyter notebooks:

1. EDA STUDENT PERFORMANCE.ipynb: Initial data exploration, visualization, and insights.

2. MODEL TRAINING.ipynb: Data cleaning, feature engineering, preparation for modeling then find the best perorming model.


## MLOps Pipeline:

The MLOps pipeline, which includes steps for data versioning, model training, evaluation, and deployment, is documented in the src/pipeline folder. The pipeline ensures that the entire workflow is automated and reproducible.

## Web Interface:

The web interface is built using Flask and allows users to input features and get predictions for their exam performance. 

The web application files are located in the app directory:

**app.py: The main Flask application.**

templates/index.html: Just a Welcome page.
templates/home.html: The predict page, where user input is taken.

## Usage:

Start the Flask web application:

cd app

python app.py

Open a web browser and go to:

http://127.0.0.1:5000/

Use the web interface to input the required features and get predictions for student exam performance.

## Contributing:

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License:

This project is licensed under the MIT License. See the LICENSE file for more details.
