# final_score_exam_prediction
My attempt to predict the final score of a student based on factors


## Dataset
- Features: ['Hours_Studied', 'Attendance', 'Parental_Involvement',
       'Access_to_Resources', 'Extracurricular_Activities', 'Sleep_Hours',
       'Previous_Scores', 'Motivation_Level', 'Internet_Access',
       'Tutoring_Sessions', 'Family_Income', 'Teacher_Quality', 'School_Type',
       'Peer_Influence', 'Physical_Activity', 'Learning_Disabilities',
       'Parental_Education_Level', 'Distance_from_Home', 'Gender']
- Target:  Exam_Score
- Size: 6378

## Model
- Deep learning architecture: [Sequential, 4, (relu,linear)]
- Loss function: Mean Squared Error
- Optimizer: Adam

## Results
- MAE on test data: 1.15
- MAE on training data: 0.9

## Installation
1. Clone the repo: `git clone <repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
