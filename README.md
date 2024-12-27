# Diabetes-Prediction
A machine learning project to predict diabetes with personalized recommendations

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

**Project Overview**
This project is a machine learning-based application designed to predict the likelihood of diabetes based on patient-specific input parameters. The application provides personalized health recommendations based on the prediction and the input values to assist users in taking proactive steps toward managing their health.
The application leverages a Random Forest classifier trained on synthetic diabetes data generated using Synthea. It is built with a user-friendly interface using Gradio and incorporates a blood pressure calculator for added functionality.

**Key Features**
Diabetes Prediction: Determines whether a user is diabetic or non-diabetic based on provided health metrics.
Personalized Recommendations: Delivers tailored health advice depending on the prediction and the user's input values.
Blood Pressure Calculator (MAP): Calculates the Mean Arterial Pressure (MAP) based on systolic and diastolic blood pressure.
User-Friendly Interface: Built using Gradio for seamless interaction.
Customizable Thresholds: Supports dynamic health recommendations based on feature values such as glucose level, BMI, insulin level, and blood pressure.

**Technologies Used**
Python
Gradio: For creating the interactive user interface.
Random Forest Classifier: For prediction.
Pandas: For data manipulation.
Joblib: For model loading.
Synthea: For generating synthetic diabetes data.

**How It Works**
Input Health Metrics:
Diabetic Pedigree Function
Age
BMI (Body Mass Index)
Glucose Level
Blood Pressure (MAP)
Insulin Level
Blood Pressure Calculator:
Enter systolic and diastolic blood pressure to compute MAP.
Prediction and Recommendations:
Based on the inputs, the model predicts if the user is diabetic or non-diabetic.
Provides dynamic health recommendations for diabetic users based on input values.
