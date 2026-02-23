# AI-Healthcare-Assistant

🎯 Problem Statement
In many rural areas:
There are very few doctors
Hospitals are far away
Internet connectivity is poor
People ignore early symptoms
This project builds an offline AI assistant that helps people identify possible diseases based on symptoms and gives basic medical advice.

🧠 What This Project Does
It works like a mini doctor assistant on a laptop or mobile device.

1️⃣ Symptom Checker
User speaks symptoms like:
“I have fever and headache”
The system converts voice → text.

2️⃣ Disease Prediction (Machine Learning)
The system:
Converts symptoms into numbers (fever = 1, cough = 0, etc.)
Sends them to a trained ML model (Decision Tree)
Predicts a disease
Example:
Fever + Cough → Flu
Headache + Fatigue → Migraine
The model was trained using sample medical data.

3️⃣ Medicine Suggestions
After predicting the disease, it suggests:
Basic non-prescription medicines
Home remedies
Rest and hydration advice

⚠️ It does NOT replace a doctor.
It only gives first-level guidance.

4️⃣ Voice Interface (Offline)
The assistant:
Listens to the user (Speech Recognition)
Speaks back using text-to-speech

This helps:
Illiterate users
Elderly people
Non-technical users
It can also support local languages like Hindi or Kannada using offline models.

⚙️ Technical Architecture
User Voice
    ↓
Speech-to-Text
    ↓
Symptom Extraction
    ↓
ML Model (Decision Tree)
    ↓
Disease Prediction
    ↓
Medicine Suggestion Database
    ↓
Text-to-Speech Response

🛠 Technologies Used
Python
Scikit-learn (Machine Learning)
SpeechRecognition (voice input)
pyttsx3 (offline voice output)
Pandas (data handling)

🌍 Why This Project is Powerful

✅ Works offline
✅ Helps rural communities
✅ Reduces hospital overload
✅ Low cost
✅ Easy to deploy on Android
