# NaukriSaathi – Job Matching and Candidate Screening Chatbot

NaukriSaathi is an intelligent NLP-based chatbot that evaluates a candidate’s suitability for a selected job domain.  
It performs skill matching using lemmatization, analyzes academic performance, evaluates hobbies and soft skills, and generates a final recruitment-style recommendation.

---

## Features

- NLP-based skill extraction using NLTK
- Lemmatization-consistent skill matching
- Technical skill fit scoring
- Academic performance evaluation (10th and 12th)
- Hobby relevance scoring
- Soft skill keyword extraction
- Composite candidate recommendation

---

## Supported Domains

- Data Analyst  
- Machine Learning Engineer  
- Web Developer  

---

## Technologies Used

- Python  
- NLTK  
- Regular Expressions  

---

## How to Run the Project

## Step 1: Clone the Repository

git clone https://github.com/<your-username>/NaukriSaathi.git
cd NaukriSaathi

## Step 2: Install Dependencies

pip install -r requirements.txt

## Step 3: Download NLTK Resources

import nltk
nltk.download("punkt")
nltk.download("wordnet")
nltk.download("omw-1.4")

## Step 4: Run the Chatbot
python naukrisaathi.py


## Sample Output
Enter domain you want to apply for: data analyst
Describe your skills: I know Python, SQL and Pandas

Matched Skills: python, sql, pandas
Missing Skills: excel, power bi
Match Percentage: 60%

Enter your 10th percentage: 82
Enter your 12th percentage: 78
Enter your hobbies: chess, coding
Enter your strengths: teamwork, problem solving
Enter your weaknesses: procrastination

Final Recommendation: Partial Fit
