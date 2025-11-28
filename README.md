# HAVEN - A SAFE SPACE FOR MENTAL HEALTH

## Title of the Project
**Haven: Integrated Mental Health Platform with Stress Prediction and AI Chatbot**

An integrated web platform combining machine learning-based stress prediction with an empathetic AI chatbot to provide accessible, proactive mental wellness support.

## About
**Haven** is a unified digital mental health platform designed to bridge the gap between physiological health tracking and psychological support. Traditional mental health solutions are often fragmented, requiring users to use separate apps for tracking and communicating.

This project leverages a **Random Forest Classifier** to analyze user lifestyle and biometric data (such as sleep patterns, heart rate, and daily steps) to predict stress levels (Low, Medium, High). Based on this assessment, the system immediately connects the user to a context-aware AI chatbot powered by **Llama 3.1 (via Groq API)**. [cite_start]This provides instant, empathetic support tailored to the user's current mental state, streamlining the journey from assessment to intervention [cite: 361-366].

## Features
- **ML-Based Stress Prediction:** Accurately classifies stress levels using a Random Forest algorithm trained on lifestyle data.
- **Context-Aware AI Chatbot:** Integrates Llama 3.1 to provide empathetic responses that adapt based on the user's predicted stress level.
- **Data Visualization Dashboard:** Interactive charts using Plotly to analyze stress trends across different demographics (e.g., by occupation).
- **User-Friendly Interface:** A clean, accessible web interface built with Flask.
- **High Performance:** Utilizes Groq's LPU for ultra-low latency chatbot responses.
- **Secure Data Handling:** User authentication and secure session management.

## Requirements
* **Operating System:** Windows 10/11, Linux, or macOS.
* **Language:** Python 3.9 or higher.
* **Web Framework:** Flask (for backend logic and routing).
* **Machine Learning:** Scikit-learn (for Random Forest implementation), Pandas, NumPy.
* **AI Integration:** Groq API (accessing Llama-3.1-8b-instant).
* **Visualization:** Plotly (for interactive graphs).
* **Environment Management:** python-dotenv (for secure API key management).
* **Browser:** Google Chrome, Microsoft Edge, or Firefox.

## System Architecture
![System Architecture](https://github.com/YourUsername/Haven-Mental-Health/assets/placeholder-image/architecture-diagram.png)
*(Note: Upload the Architecture Diagram from your report here)*

## Output

#### Output 1 - Stress Prediction Interface
Users input their biometric data, and the model predicts the stress level.

![Stress Prediction](https://github.com/YourUsername/Haven-Mental-Health/assets/placeholder-image/prediction-page.png)

#### Output 2 - AI Chatbot Support
The chatbot provides immediate support based on the prediction context.

![Chatbot Interface](https://github.com/YourUsername/Haven-Mental-Health/assets/placeholder-image/chatbot-interface.png)

#### Output 3 - Data Visualization
Visualizing stress trends across different occupations.

![Visualization Dashboard](https://github.com/YourUsername/Haven-Mental-Health/assets/placeholder-image/visualization.png)

**Model Accuracy:** 97% (Random Forest Classifier)
*Note: Metrics based on the Sleep Health and Lifestyle dataset evaluation.*

## Results and Impact
The **Haven** platform successfully demonstrates that integrating objective health data with subjective conversational support creates a more cohesive user experience. 
- **Proactive Intervention:** By detecting stress markers early, the system prompts interaction before a crisis occurs.
- **Reduced Stigma:** Offers a private, judgment-free space for users to explore their mental health.
- **Accessibility:** Provides 24/7 support without the barriers of cost or appointment scheduling associated with traditional therapy.

## Articles published / References
1.  K. K. Fitzpatrick, A. Darcy, and M. Vierhile, “Delivering Cognitive Behavior Therapy to Young Adults With Symptoms of Depression and Anxiety Using a Fully Automated Conversational Agent (Woebot),” *JMIR Mental Health*, 2017.
2.  J. W. Ayers, et al., “Comparing physician and artificial intelligence chatbot responses to patient questions,” *JAMA Internal Medicine*, 2023.
3.  Y. S. Can, B. Arnrich, and C. Ersoy, “Stress Detection Using Wearable Sensors and Machine Learning: A Review,” *Sensors (Basel)*, 2019.
4.  I. Nahum-Shani, et al., “Just-in-Time Adaptive Interventions (JITAIs) in Mobile Health,” *Annals of Behavioral Medicine*, 2018.
