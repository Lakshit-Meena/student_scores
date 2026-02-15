🎓 Student Performance & Job Predictor
Niche diye gaye project mein humne SVM (Support Vector Machine) machine learning algorithm ka use karke students ke academic scores aur unki habits ke base par unki Part-time Job status ko predict kiya hai. Iske saath hi ek interactive Streamlit Dashboard bhi banaya gaya hai.

🚀 Features
Data Cleaning: Raw data ko handle kiya gaya, categories ko fix kiya gaya aur feature scaling ki gayi.

SVM Classifier: Scikit-Learn ka use karke high-accuracy classification model banaya gaya.

Interactive UI: Streamlit web app jahan aap khud values enter karke prediction check kar sakte hain.

Performance Metrics: Accuracy score aur detailed classification report.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, Scikit-learn, Streamlit, NumPy

Model: SVM (Support Vector Machine)

📁 Project Structure
student-scores.csv: Original dataset.

student.ipynb: Data analysis aur model training ki Jupyter Notebook.

app.py: Streamlit web application ka main code.

requirements.txt: Project run karne ke liye zaroori libraries.

⚙️ Installation & Setup
Project ko apne local system par chalane ke liye niche diye gaye steps follow karein:

Repository Clone karein:

Bash
git clone https://github.com/your-username/student-predictor.git
cd student-predictor
Dependencies Install karein:

Bash
pip install -r requirements.txt
Streamlit App Run karein:

Bash
streamlit run app.py
📊 Dataset Overview
Dataset mein niche diye gaye features shamil hain:

Academic Scores: Math, Physics, Chemistry, Biology, History, Geography, English.

Student Habits: Weekly self-study hours, Absence days.

Target Variable: part_time_job (Predict karne ke liye).

📈 Results
Humne linear kernel ke saath SVM use kiya hai jisne 84.50% tak ki accuracy achieve ki hai.

Developed with ❤️ by Lakshit Meena
