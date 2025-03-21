# AI-Powered-Personal-Fitness-Tracker

Overview
The Personal Fitness Tracker is an AI-powered application designed to provide personalized fitness recommendations based on user data and machine learning analysis. Unlike traditional fitness tracking applications that offer generic workout plans, this system customizes exercise routines, predicts calorie burn, and suggests activities based on individual preferences, fitness levels, and real-time data from wearable devices (if available).

Objective
The goal of this project is to enhance fitness tracking accuracy and personalization by utilizing machine learning algorithms. The system allows users to set fitness goals, track their progress, and receive tailored workout suggestions, improving adherence to fitness plans and motivation levels.



Features

User Input Panel: Users can input Age, BMI, Exercise Duration, Heart Rate, Body Temperature, and Gender.

Calorie Prediction: Uses a Random Forest Regressor model to estimate calories burned.

Data Visualization: Displays histograms, scatter plots, and correlation heatmaps to analyze fitness trends.

Model Evaluation: Shows RMSE and R-squared scores for model accuracy.

Feature Importance Analysis: Highlights key factors influencing calorie burn.

Downloadable Results: Users can download predictions as CSV files.

Feedback System: Users can provide feedback on predictions.

Interactive Prediction: Real-time prediction updates based on slider adjustments.




Technology Stack
Programming Language: Python
Machine Learning Framework: Scikit-learn (Random Forest Regression, Classification models)
User Interface: Streamlit
Development Environment: VS Code
Data Collection: User inputs, wearable device data (steps, heart rate)
Methodology
Data Collection – Users input fitness goals, activity levels, and workout preferences. Wearable device data is also integrated if available.
Feature Engineering – Relevant features such as BMI, daily steps, heart rate, and workout duration are processed.
Machine Learning Models –
Classification Models suggest customized workout plans.
Regression Models predict calorie burn and fitness progression.
Recommendation Systems provide exercise recommendations based on past performance.
User Interaction & Deployment – The system is deployed via Streamlit, offering an intuitive interface for users to track progress and receive recommendations.
Key Features & Benefits
✔ Personalized Workout Plans – AI-driven customization ensures that exercises match user capabilities.
✔ Calorie Burn Prediction – Helps users adjust diet and exercise routines for optimal results.
✔ Wearable Device Integration – Supports real-time data tracking for enhanced accuracy.
✔ User-Friendly Interface – Accessible to users with minimal technical expertise.

Installation & Setup
Clone the repository:
git clone https://github.com/yourusername/personal-fitness-tracker.git
Navigate to the project directory:
cd personal-fitness-tracker
Install dependencies:
pip install -r requirements.txt
Run the application:
streamlit run app.py
Usage
Open the application in your browser.
Enter your fitness details and goals.
Receive personalized workout recommendations.
Track progress and adjust your fitness plan as needed.
Future Enhancements
Real-time Biometric Tracking – Enhance data collection by integrating smart devices.
AI-powered Virtual Coaching – Provide interactive feedback and live recommendations.
IoT-based Smart Fitness Recommendations – Use IoT sensors to offer advanced fitness insights.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Contributing
Contributions are welcome! If you’d like to improve this project, follow these steps:

Fork the repository.
Create a new feature branch.
Commit your changes and push them to GitHub.
Submit a pull request.
