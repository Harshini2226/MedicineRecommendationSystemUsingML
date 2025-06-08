# MedicineRecommendationSystemUsingML
Personalized Health Recommendation System using Machine Learning
Personalized Health Recommendation System using Machine Learning (Google Colab)
This project uses machine learning to create a holistic health assistant that suggests:
✅ Predicted disease
💊 Recommended medicines
🏋️ Workout plans
🍽️ Diet plans

It is implemented in Google Colab, making use of Python libraries and ML models for training, prediction, and user interaction.
🧠 How It Works
# 1. Data Collection
The dataset includes:
Symptoms (e.g., headache, cough, fatigue)
Diagnosed disease
Medicines prescribed
Recommended exercises
Diet suggestions

# 2. Preprocessing
Symptoms are encoded into a numerical format using One-Hot Encoding or MultiLabel Binarization.
The target variable includes disease names, and additional mappings are created for medicine, workout, and diet suggestions.

# 3. Model Training
A multi-class classification model is trained to predict diseases based on symptoms.
Models like:
Decision Tree
Random Forest
Naive Bayes
or Support Vector Machine (SVM)
are typically used.
The model learns patterns of symptom combinations and their likely disease.

# 4. Post-Prediction Mapping
Once the disease is predicted, the system maps it to:
A list of common medicines
Suggested physical activities (e.g., yoga, walking)
Appropriate diet plans (e.g., high-fiber, low-carb)

# 5. Google Colab Interface
# Input:
 User selects or enters symptoms (checkboxes, text input).

# Output:
🎯 Predicted Disease
💊 Medicines
🏋️ Workout Plan
🍲 Diet Plan
Optional: Gradio or Streamlit used for interactive front-end within Colab.

# 🔍 Example
# User Input:
Symptoms: Sneezing, Runny nose, Headache

# System Output:
Predicted Disease: Common Cold
Medicines: Cetirizine, Paracetamol
Workout: Light stretching, Rest
Diet: Warm fluids, Vitamin C-rich food

# ✅ Benefits
End-to-end solution for preventive and curative care
Helps users understand their condition and get initial guidance
Can be enhanced with real-time chatbots, voice input, or wearable integration
