# BMI Calculator and Diet Planner

## About the Project
The BMI Calculator and Diet Planner is a Python-based web application developed using Streamlit. It calculates Body Mass Index (BMI) based on the user's height and weight, displays the BMI category, and provides general diet suggestions.

## Features
- Enter personal details such as name and age.
- Enter height in feet and inches.
- Enter weight in kilograms.
- Calculate BMI automatically.
- Display BMI categories and suggested diet charts.
- Save BMI assessment records in a text file.
- View previously saved records.

## Technologies Used
- Python
- Streamlit
- File Handling
- GitHub

## BMI Calculation
BMI is calculated using the following formula:

**BMI = Weight (kg) / Height (m)²**

Height is converted from feet and inches into meters before calculating BMI.

## BMI Categories for Adults
| BMI Range | Category |
|---|---|
| Below 18.5 | Underweight |
| 18.5 – 24.9 | Healthy Weight |
| 25.0 – 29.9 | Overweight |
| 30.0 and above | Obesity |

For users under 20 years of age, BMI should be assessed using age-specific growth charts rather than adult BMI categories.

## Installation and Setup

### 1. Clone the Repository
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install Streamlit
```bash
pip install streamlit
```

### 3. Run the Application
```bash
streamlit run BMI.py
```

## Project Files
- `BMI.py` – Main application code.
- `requirements.txt` – Lists the required Python libraries.
- `bmi_records.txt` – Stores saved BMI assessments when the file is available and writable.

## Deployment
The application can be deployed using Streamlit Community Cloud by connecting the GitHub repository and selecting `BMI.py` as the main application file.

## Disclaimer
This application is intended for educational and informational purposes only. BMI is a screening measure, not a medical diagnosis. Diet suggestions are general examples and should not replace personalised advice from a qualified healthcare professional.
