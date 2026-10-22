# SIM Swap Fraud Detection System & Presentation

A comprehensive machine learning and rule-based solution designed to detect and prevent SIM Swap fraud in real-time, accompanied by an executive presentation slide deck framework.

📌 Overview

SIM swap fraud occurs when malicious actors convince a mobile carrier to transfer a victim's phone number to a new SIM card under their control. This system provides a robust detection engine combining risk scoring, behavioral metrics, and machine learning models to identify unauthorized SIM swap attempts before fraudulent transactions occur.

🎯 Key Features

Real-Time Risk Scoring: Evaluates incoming swap requests based on carrier APIs, location deltas, and device metadata.

Machine Learning Detection: Uses historical transaction and swap data to flag high-risk anomalies.

Multi-Factor Trigger Engine: Automatically triggers stepped-up authentication (biometrics, out-of-band verification) when risk scores exceed custom thresholds.

Executive Presentation Deck: Includes a 15-slide presentation framework detailing the business problem, technical architecture, implementation roadmap, and ROI analysis.

Install dependencies:

pip install -r requirements.txt


🧪 Usage

To run the sample risk scoring script:

python src/detection_engine.py


To execute test suites:

pytest tests/
To access : 
https://simswapprojectapp.vercel.app/


🛡️ License

Distributed under the MIT License. See LICENSE for more information.
