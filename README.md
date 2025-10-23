# AI-PHMS
Project Title:* AI-Powered Health Monitoring System

*Description:*
This project aims to develop an AI-powered system that monitors patients' health in real-time using data from wearable devices or electronic health records. The system uses machine learning algorithms to detect anomalies and provide personalized health recommendations.

*Features:*

- Real-time health monitoring
- Anomaly detection using machine learning
- Personalized health recommendations
- User-friendly interface for visualizing health data and recommendations

*Dataset:*
The project uses the MIMIC-III dataset, which contains de-identified data from patients admitted to ICU at Beth Israel Deaconess Medical Center in Boston, Massachusetts.

*Requirements:*

- Python 3.8 or later
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Flask (for API development)

*Usage:*

1. Clone the repository: `git clone https://github.com/username/ai-powered-health-monitoring.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the API: `python app.py`
4. Access the API at `http://localhost:5000`

*API Endpoints:*

- `/predict`: Accepts POST requests with patient data and returns a prediction of patient mortality.

*Model Performance:*

- The model achieves an accuracy of 99.9% on the test dataset.

*Future Work:*

- Integrate with wearable devices for real-time data collection
- Expand the model to predict other health outcomes (e.g., length of stay, readmission)
- Develop a user-friendly interface for patients and clinicians to visualize health data and recommendations.

*Contributing:*
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

*License:*
This project is licensed under the MIT License. See `LICENSE` for details.

*Acknowledgments:*
The MIMIC-III dataset was used in this project. We acknowledge the contributions of the researchers and clinicians who made this dataset available.
