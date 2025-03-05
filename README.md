BREAST CANCER PREDICTION: Streamlit Web APP
![image](https://github.com/user-attachments/assets/1fe46b7e-6bf3-4c02-a43c-819e63c172d5)


## Overview
The **Breast Cancer Predictor** is an ML-powered web application designed to assist medical professionals in diagnosing breast cancer. By inputting key cell nucleus measurements, the app predicts whether a breast mass is **benign** or **malignant** using a machine learning model. It also provides a **radar chart** visualization of the input data and displays the probability of each diagnosis.

## Features
- **Interactive Sliders**: Adjust cell nucleus measurements manually via an intuitive sidebar.
- **Machine Learning Prediction**: Predicts if the tumor is benign or malignant.
- **Probability Display**: Shows the likelihood of a benign or malignant diagnosis.
- **Radar Chart Visualization**: Graphically represents input data with mean, standard error, and worst values.
- **Dark Mode UI**: Modern and user-friendly dark-themed interface.

## How It Works
1. Adjust the **cell nucleus measurements** using the sliders.
2. The **machine learning model** processes the data and predicts the tumor type.
3. The result is displayed along with the **probability of being benign or malignant**.
4. The **radar chart** helps visualize the distribution of values.

## Tech Stack
- **Streamlit**: Web framework for UI
- **Python**: Core programming language
- **Scikit-Learn**: Machine learning model
- **Matplotlib & Plotly**: Data visualization
  ![image](https://github.com/user-attachments/assets/5391017e-b2ce-4e6f-b55c-356339eeea2d)


## Installation
To run the application locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/breast-cancer-predictor.git
cd breast-cancer-predictor

# Create a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run main.py
```

## Usage
- Open the **localhost link** (usually `http://localhost:8501/`)
- Adjust the **input sliders** on the left panel
- View the **prediction result and probability** on the right panel
- Check the **radar chart** for data insights

## Important Notes
- This app is a **decision-support tool** and should not be used as a substitute for professional medical diagnosis.
- The model is trained on publicly available datasets and may not generalize to all real-world cases.


## License
This project is licensed under the MIT License.

---

📢 *Contributions are welcome! Feel free to fork the repository and submit pull requests.* 🚀

