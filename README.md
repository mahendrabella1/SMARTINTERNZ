🚦 Traffic Volume Estimation Web App
This Streamlit-based web application predicts the traffic volume on the Metro Interstate Highway using historical weather, time, and holiday data. It uses a Random Forest Regressor model trained on the Metro Interstate Traffic Volume dataset.

🔍 Features
Predict traffic volume based on:

Holiday status

Temperature, Rain, and Snow

Weather condition

Date and time (year, month, day, hour, minute, second)

Visualize simulated traffic volume for all 24 hours of a day

Identify peak hour with maximum traffic

📊 Dataset
Name: Metro Interstate Traffic Volume

Source: UCI Machine Learning Repository

Size: ~40,000 rows of hourly data from 2012–2018

Features Used:

holiday, temp, rain_1h, snow_1h, weather_main, date_time

🧠 ML Model
Algorithm: Random Forest Regressor

Scaler: StandardScaler

Train/Test Split: 80/20

Performance: Trained locally for demonstration purposes (not optimized for production)

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/<your-username>/traffic-volume-estimation.git
cd traffic-volume-estimation
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Place the dataset:

Download Metro_Interstate_Traffic_Volume.csv and place it in the project folder.

Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
🖥️ UI Preview
Prediction Panel	Hourly Simulation

📂 Project Structure
bash
Copy
Edit
traffic-volume-estimation/
│
├── app.py                     # Streamlit App Code
├── Metro_Interstate_Traffic_Volume.csv
├── requirements.txt           # Python dependencies
└── README.md
📦 Requirements
txt
Copy
Edit
streamlit
pandas
numpy
scikit-learn
matplotlib
Install using:

bash
Copy
Edit
pip install -r requirements.txt
👨‍💻 Team Members
Mahendra Bella – mahendrabella55@gmail.com

Lavanya – 22KH1A3309

Ganesh Raju – 22KH1A3330

Harinath – 22KH1A3311

📜 License
This project is for educational and academic purposes only.
