# News-detection
This repository contains the code and notebook for the news detection project. Below are the details of each file included:

## Files
### 1. `news_detection.ipynb`
- **Description**: This Jupyter notebook contains the implementation of the emotion detection model. It includes data preprocessing, feature extraction, model training, and evaluation steps.
- **Usage**: Open the notebook in JupyterLab or Jupyter Notebook to execute the cells and follow the step-by-step process to understand how the news detection model is built and evaluated.

### 2. `web.py`
- **Description**: This Python script contains the code for deploying the emotion detection model as a web application. It includes endpoints for predicting news credibilty from text inputs and handling web requests.
- **Usage**: Run this script to start the web application. Ensure you have all the necessary dependencies installed. You can then send text inputs to the application to get emotion predictions.

## Getting Started
1. **Environment Setup**:
   - Ensure you have Python installed (version 3.6 or higher).
   - Install the necessary dependencies by running:
     ```bash
     pip install -r requirements.txt
     ```

2. **Running the Notebook**:
   - Open `news_detection.ipynb` in JupyterLab or Jupyter Notebook.
   - Follow the instructions and execute the cells sequentially to understand and replicate the news detection process.

3. **Running the Web Application**:
   - Ensure the dependencies are installed.
   - Run the `web.py` script:
     ```bash
     python web.py
     ```
   - Access the web application via the provided local server address.

## Dependencies
- Python 3.6 or higher
- JupyterLab or Jupyter Notebook
- Flask (for the web application)
- scikit-learn
- LightGBM
- pandas
- numpy
