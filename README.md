# Multiple Disease Prediction System

This is a web-based Multiple Disease Prediction System built using Machine Learning models and Streamlit. The system predicts the likelihood of three diseases:
- **Heart Disease**
- **Diabetes**
- **Parkinson's Disease**

## Features
- **User-friendly interface** powered by Streamlit.
- **Three disease prediction models** integrated into a single application.
- **Real-time predictions** based on user-input medical parameters.
- **Easy deployment** and local execution.

## Technologies Used
- Python
- Streamlit
- Machine Learning (Scikit-learn, Pickle for model storage)
- Streamlit Option Menu for UI enhancements

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/shreya-namami/DISEASE-OUTBREAKS
   ```
2. Navigate to the project directory:
   ```bash
   cd DISEASE-OUTBREAKS
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
5. Open the browser and navigate to `http://localhost:8501/`.

## Folder Structure
```
DISEASE-OUTBREAKS/
│-- codes/
│   ├── diabetes.ipynb
│   ├── heart.ipynb
│   ├── parkinsons.ipynb
│-- datasets/
│   ├── diabetes.csv
│   ├── heart.csv
│   ├── parkinsons.csv
│-- models/
│   ├── diabetes_model.sav
│   ├── heart_model.sav
│   ├── parkinsons_model.sav
│-- app.py
│-- requirements.txt
```
