# Student-Dropout-Early-Warning-System
Problem: Student Dropout Early Warning System (ML)

A university is losing students every semester.

They want an early warning system so advisors can help students before they drop out.

Your Task

You are hired as a data scientist.

Build a machine learning system that:

Predicts which students are at risk of dropping out
Flags high-risk students early in the semester
What You Must Do

Use academic activity and basic student data
Train a model to predict Dropout / Continue
Focus on early detection, not end-semester data
Dataset

https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data

Expected Output

A risk score for each student
A list of high-risk students for advisors
Success Criteria

Catch as many dropout students as possible
Keep false alarms reasonable
Model should be easy to explain to non-technical staff
Real-World Constraints

Data is noisy and incomplete
Advisors need results early
Decisions must be fair and transparent
Final Deliverables

Trained ML model
Prediction results
Short explanation: why students are at risk
Final Submission (Required)

1) Code + Model

Training notebook/script (.ipynb or .py)
Saved trained model (model.pkl / model.joblib)
Saved preprocessing pipeline (recommended as one pipeline file)
2) Predictions File

Submit a CSV like:

student_id (or row index)
risk_score
risk_label (Low/Medium/High)
predicted_dropout (0/1)
3) Streamlit App

Submit app.py that:

Uploads a CSV student file
Shows a Top High-Risk Students table (top 20)
Shows a selected student’s risk score + risk label
Shows top reasons (simple feature importance is fine)
4) Short Report (README)

Include:

How you cleaned data
Features used
Model choice + metrics
How you set the risk thresholds
Key reasons behind dropout predictions
Bonus (Optional)

Student risk levels (Low / Medium / High)
Simple action suggestions for advisors
