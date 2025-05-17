Healthcare Appointment No-Show Prediction
Objective
Predict whether a patient will miss their medical appointment using historical data, and provide actionable insights to optimize scheduling and reduce no-shows.

  Tools & Technologies
Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
Power BI (for dashboard visualization)
Jupyter Notebook
Decision Tree Classifier

Dataset
Source: noshowappointments.csv
Records: ~110,000
Key Columns: Age, SMS_received, Appointment Day, No-show, etc.

Feature Engineering
 Features used:
Age, SMS_received, Waiting_time, Hypertension, Diabetes, Alcoholism, Scholarship, Weekday
Target:
No_show (Yes/No)

Model
Decision Tree Classifier
Train-test split: 80/20
Accuracy: (insert your score here)

Dashboard
Built an interactive Power BI dashboard showing:
No-show trends by weekday
Effect of SMS reminders
Age vs. attendance
Filters by conditions (diabetes, hypertension, etc.)

 Key Insights
Patients who received SMS reminders are less likely to miss appointments.
Weekends and beginning of the week have higher no-show rates.
Younger patients tend to miss more appointments.
