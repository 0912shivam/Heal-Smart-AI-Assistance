<div align="center">

<a href="https://heal-smart.vercel.app/">
  <img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/logo.png" alt="HealSmart Logo" width="240"/>
</a>

# HealSmart

### AI-Powered Medical Assistant for Disease Prediction, Mental Wellness & Doctor Consultation

Personalized healthcare recommendations, empathetic mental health support, and specialist discovery — powered by Machine Learning and Generative AI.

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![Flask](https://img.shields.io/badge/Flask-Backend-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![scikit-learn](https://img.shields.io/badge/Machine%20Learning-scikit--learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Gemini API](https://img.shields.io/badge/Gemini%20API-Generative%20AI-8E75B2?logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-Firestore-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](#license)
[![Stars](https://img.shields.io/github/stars/0912shivam/Heal-Smart-AI-Assistance?style=social)](https://github.com/0912shivam/Heal-Smart-AI-Assistance/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/0912shivam/Heal-Smart-AI-Assistance)](https://github.com/0912shivam/Heal-Smart-AI-Assistance/commits/main)

**[🚀 Live Demo](https://heal-smart.vercel.app/)**

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Demo](#-demo)
- [Architecture](#-architecture)
- [Tech Stack](#-tech-stack)
- [Machine Learning](#-machine-learning)
- [Dataset](#-dataset)
- [Installation](#-installation)
- [Running Locally](#-running-locally)
- [API Documentation](#-api-documentation)
- [Use Cases](#-use-cases)
- [Project Structure](#-project-structure)
- [Social Impact](#-social-impact)
- [Roadmap](#-roadmap)
- [References](#-references)
- [License](#-license)

---

## 🩺 Overview

**HealSmart** is a full-stack, AI-driven healthcare companion built to close the gap between "I don't feel well" and "I know what to do next." It combines a trained Machine Learning model, a generative AI mental-wellness chatbot, and a doctor-discovery experience into a single, cohesive product.

> HealSmart doesn't replace a doctor — it helps people make sense of their symptoms, get emotional support when they need it most, and find the right specialist faster.

**Who it's for:** Anyone who wants quick, informed guidance on their health — from someone unsure whether a symptom warrants a clinic visit, to someone looking for a safe space to talk through stress and anxiety.

**How AI is used:**
- A **Logistic Regression** classifier trained on a curated symptom dataset predicts probable diseases from user-reported symptoms.
- The **Gemini API** powers two experiences: contextual, AI-generated guidance around a predicted diagnosis, and **Mind-Bot**, an empathetic mental-health conversation partner.
- **Firebase Firestore** backs the doctor-discovery and consultation booking flow.

**Why it's useful:** HealSmart brings preliminary medical guidance, mental health support, and doctor discovery into one accessible, always-on interface — reducing the friction people face before seeking care.

---

## ✨ Features

| Feature | Description | Technology Used |
|---|---|---|
| 🔍 **Symptom Analysis** | Predicts probable diseases from user-reported symptoms and guides users to the appropriate specialist, with AI-generated context around the result. | Flask, scikit-learn (Logistic Regression), Gemini API |
| 💬 **Mind-Bot** | An empathetic mental-wellness chatbot that offers supportive conversation for concerns like loneliness and stress, powered by a Gemini model tuned with system instructions. | Gemini API, Google AI Studio |
| 👨‍⚕️ **Consult Doctor** | Lets users browse specialist profiles, view ratings and availability, and move toward booking an appointment. | Firebase Firestore, React |
| 🎨 **Intuitive Design** | A clean, responsive interface designed for effortless navigation across the symptom-checking, chat, and consultation flows. | React, Tailwind CSS, Styled Components |
| 🌐 **Enhanced Accessibility** | Healthcare guidance and mental health support available anytime, from any device with a browser. | React, Vercel |
| 🎯 **Personalized Recommendations** | Tailors healthcare suggestions to the user's reported symptoms and doctor ratings for more relevant outcomes. | scikit-learn, Firebase Firestore |

<div align="center">
  <a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/hero.png">
    <img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/hero.png" alt="Key Features" width="400"/>
  </a>
</div>

---

## 🎬 Demo

**[Try HealSmart live →](https://heal-smart.vercel.app/)**

### Screenshots

<table>
<tr>
<td align="center"><b>Home Page</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/home_page.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/home_page.png" width="400"/></a></td>
<td align="center"><b>Symptom Analysis</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/symptom_analysis.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/symptom_analysis.png" width="400"/></a></td>
</tr>
<tr>
<td align="center"><b>Analysis Result</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/analysis_result.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/analysis_result.png" width="400"/></a></td>
<td align="center"><b>AI Consultation</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/ai_consultation.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/ai_consultation.png" width="400"/></a></td>
</tr>
<tr>
<td align="center"><b>Mind-Bot</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/mind_bot.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/mind_bot.png" width="400"/></a></td>
<td align="center"><b>Mind-Bot Response</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/mind_bot_response.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/mind_bot_response.png" width="400"/></a></td>
</tr>
<tr>
<td align="center"><b>Consult Doctor</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/consult_doctor.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/consult_doctor.png" width="400"/></a></td>
<td align="center"><b>Doctor Appointment</b><br/><a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/doctor_appointment.png"><img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/doctor_appointment.png" width="400"/></a></td>
</tr>
</table>

---

## 🏗 Architecture

<div align="center">
  <a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/architecture.jpg">
    <img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/architecture.jpg" alt="Architecture" width="800"/>
  </a>
</div>

HealSmart is built around three core divisions that work together to deliver a complete healthcare experience:

1. **Symptom Analysis** — The React frontend sends user-reported symptoms to a Flask API connected to a trained ML model. The model returns a predicted disease, which is then paired with an AI-generated explanation and specialist recommendation via the Gemini API.
2. **Mind-Bot** — A conversational interface backed by Google AI Studio's Gemini 1.5 Pro model, primed with system instructions and example conversations to provide empathetic, supportive responses to mental health concerns like loneliness and anxiety.
3. **Consult Doctor** — Doctor profiles, ratings, and availability are fetched from Firebase Firestore, letting users explore specialists and move toward booking an appointment.

**Request flow:**

```
User
  │
  ▼
Frontend (React)
  │
  ▼
Flask API
  │
  ▼
ML Model (Logistic Regression)
  │
  ▼
Prediction
  │
  ▼
Gemini AI (contextual guidance)
  │
  ▼
Firebase Firestore (doctor data)
  │
  ▼
UI (results rendered to user)
```

---

## 🛠 Tech Stack

### Frontend
| Technology | Purpose |
|---|---|
| React JS | Core UI framework |
| HTML | Page structure |
| Tailwind CSS | Utility-first styling |
| Styled Components | Component-scoped styling |

### Backend
| Technology | Purpose |
|---|---|
| Python | Core backend language |
| Flask | REST API framework serving predictions |

### AI / Machine Learning
| Technology | Purpose |
|---|---|
| Logistic Regression | Multi-class disease prediction |
| scikit-learn | Model training and evaluation |
| pandas / numpy | Data preprocessing and manipulation |
| Gemini API | Generative AI for Mind-Bot and consultation guidance |

### Database
| Technology | Purpose |
|---|---|
| Firebase Firestore | Doctor and appointment data storage |

### Developer Tools
| Technology | Purpose |
|---|---|
| VS Code | Primary IDE |
| Google Colab | Model experimentation and training |
| Postman | API testing |

### APIs
| Technology | Purpose |
|---|---|
| Gemini API (Google AI Studio) | Powers Mind-Bot and AI-driven recommendations |

---

## 🤖 Machine Learning

HealSmart's symptom-analysis engine follows a complete ML lifecycle, from raw data to a deployed prediction API.

<div align="center">
  <a href="https://github.com/0912shivam/Heal-Smart-AI-Assistance/blob/main/screenshots/ml_lifecycle.jpeg">
    <img src="https://github.com/0912shivam/Heal-Smart-AI-Assistance/raw/main/screenshots/ml_lifecycle.jpeg" alt="ML Lifecycle" width="800"/>
  </a>
</div>

| Stage | Details |
|---|---|
| **Dataset** | 42 diseases, 132 symptom columns (categorical, 0/1), 4,920 total samples |
| **Exploratory Data Analysis** | Verified data consistency and corrected naming inconsistencies across symptom columns |
| **Feature Engineering** | Applied Tree-based Feature Importance, Recursive Feature Elimination (RFE), and L1 Regularization (Lasso) to reduce the feature set to 60 columns |
| **Preprocessing** | Excluded irrelevant rows and introduced a new class for uncorrelated symptoms, resulting in a refined dataset of 1,560 rows × 61 columns |
| **Training** | Split data into X (60 feature columns) and Y (1 target column) using an 80:20 stratified train-test split to preserve class balance |
| **Model** | Logistic Regression (scikit-learn) |
| **Validation Accuracy** | 99% |
| **Deployment** | Served via a Flask REST API (`/predict` endpoint) |

**Why Logistic Regression?** The symptom dataset consists of well-structured, binary (0/1) categorical features with clearly separable classes across diseases. Logistic Regression handles multi-class classification on this kind of data efficiently, trains quickly, and — critically for a healthcare-adjacent tool — produces interpretable, probability-based outputs, all while achieving 99% validation accuracy on the reduced feature set.

---

## 📊 Dataset

| Metric | Value |
|---|---|
| **Rows** | 4,920 (original) → 1,560 (after feature reduction) |
| **Features** | 132 symptom columns (original) → 60 (after selection) |
| **Diseases Covered** | 42 |
| **Symptoms Tracked** | 132 |
| **Source** | [Kaggle — Disease Prediction Using Machine Learning](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning) |

---

## 📁 Project Structure

```
Heal-Smart-AI-Assistance/
├── frontend/          # React application — UI, pages, and components
├── server/             # Flask API — ML model, prediction endpoint, and dependencies
├── screenshots/        # App screenshots, architecture diagram, and ML lifecycle image
├── package.json         # Root project dependencies
├── package-lock.json
└── README.md
```

---

## ⚙️ Installation

### Setting up the ML Model API (Backend)

**Prerequisites:**
- Python (version 3.x)
- pip (Python package installer)
- Virtual environment (optional but recommended)

```bash
# 1. Navigate to the server directory
cd server

# 2. Create a virtual environment (optional)
virtualenv venv

# 3. Activate the virtual environment
# On Unix/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the development server
flask run
```

The API will be available at `http://localhost:5000/predict`.

### Setting up the Frontend

**Prerequisites:**
- Node.js (LTS)
- npm (Node package manager)

```bash
# 1. Clone this repository
git clone https://github.com/0912shivam/Heal-Smart-AI-Assistance.git
cd Heal-Smart-AI-Assistance

# 2. Install root dependencies
npm install

# 3. Install frontend dependencies
cd frontend
npm install

# 4. Start the development server
npm start
```

The web app will be available at `http://localhost:3000`.

---

## ▶️ Running Locally

> **Note:** You can also skip local setup entirely and use the hosted app: **[heal-smart.vercel.app](https://heal-smart.vercel.app/)**

To run the full app locally, start the Flask API (`server/`) and the React frontend (`frontend/`) in separate terminals, as described in [Installation](#-installation) above. The frontend will communicate with the local Flask API for symptom predictions.

---

## 🔌 API Documentation

### Predict Disease from Symptoms

| | |
|---|---|
| **Endpoint** | `/predict` |
| **Method** | `POST` |
| **Content-Type** | `application/json` |

**Request Body**
```json
{
  "symptoms": ["hip_joint_pain", "joint_pain", "knee_pain", "painful_walking"]
}
```

**Response**
```json
{
  "prediction": "Osteoarthritis"
}
```

---

## 💡 Use Cases

| Use Case | Description |
|---|---|
| 🩻 **Symptom Analysis & Diagnosis** | Input symptoms to get potential diagnoses and find relevant specialist doctors. |
| 💬 **Mental Health Support** | Engage in empathetic conversations for mental health guidance and professional help suggestions. |
| 👨‍⚕️ **Doctor Consultation** | Find, view profiles, and proceed toward booking healthcare providers. |
| 🛡️ **Preventive Healthcare** | Receive timely recommendations for screenings, vaccinations, and lifestyle changes. |
| 📈 **Disease Management** | Track symptoms and receive personalized recommendations for effective management. |
| 🌍 **Remote Healthcare Access** | Access healthcare guidance and support remotely without physical visits. |
| 🔁 **Post-Appointment Follow-up** | Track symptoms, medication adherence, and access support after appointments. |
| 🤝 **Healthcare Provider Collaboration** | Collaborate with healthcare providers for personalized recommendations and progress monitoring. |

---

## 🌍 Social Impact

HealSmart is designed with a simple belief: informed, supported people make better health decisions.

- **Accessibility** — Lowers the barrier to preliminary healthcare guidance for anyone with an internet connection, regardless of location or time of day.
- **Mental Health** — Normalizes seeking support by offering a judgment-free, always-available space to talk through stress, anxiety, and loneliness.
- **Preventive Care** — Encourages proactive health management through early symptom awareness rather than reactive treatment.
- **Digital Healthcare** — Contributes to the broader shift toward accessible, technology-driven healthcare delivery.

---

## 🗺 Roadmap

- [ ] User authentication for persistent, personalized data
- [ ] Telemedicine integration for virtual consultations
- [ ] Real healthcare database-backed appointment booking system
- [ ] Improved ML model accuracy and expanded disease/symptom coverage
- [ ] Enhanced data privacy and security measures
- [ ] Refined UX based on user feedback
- [ ] Deeper content personalization and customization
- [ ] Notifications for appointments and follow-ups
- [ ] Admin dashboard for provider and content management
- [ ] Usage analytics and insights

---

## 📚 References

- Dataset: [Disease Prediction Using Machine Learning — Kaggle](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning)

---

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">

**Built with ❤️ using React, Flask, Machine Learning & Generative AI.**

[⬆ Back to top](#healsmart)

</div>
