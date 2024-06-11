# Student Performance Analysis and Prediction

## Project Description

This project analyzes student performance data and predicts their final grades using various machine learning models. It includes:
- Exploratory Data Analysis (EDA) to understand data patterns and relationships.
- Model training using different algorithms to find the best predictor.
- A Flask app to deploy and run the model.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RohanTalaviya10/Student-Performance-Prediction
   cd student-performance-prediction
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the EDA notebook:**
   Open `1. EDA STUDENT PERFORMANCE.ipynb` in Jupyter Notebook or Jupyter Lab to explore the dataset and visualize insights.

2. **Train the model:**
   Open `2. MODEL TRAINING.ipynb` in Jupyter Notebook or Jupyter Lab to preprocess data, train various models, and evaluate their performance.

3. **Run the Flask app:**
   ```bash
   flask run
   ```
   The Flask app will be available at `http://127.0.0.1:5000/`. Use it to input student data and get predictions.

## Project Structure

- `1. EDA STUDENT PERFORMANCE.ipynb`: Notebook for exploratory data analysis.
- `2. MODEL TRAINING.ipynb`: Notebook for data preprocessing, model training, and evaluation.
- `application.py`: Flask application to deploy the trained model.
- `requirements.txt`: List of dependencies required to run the project.
- `templates/`: Directory containing HTML templates for the Flask app.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- Dataset: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
