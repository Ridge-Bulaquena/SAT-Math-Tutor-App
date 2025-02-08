# 🧮 SAT Math Tutor

An AI-powered SAT Math tutoring platform that provides personalized learning experiences using Google's Gemini Pro. The application adapts to student performance, offers real-time feedback, and generates unique practice questions.

[Live Demo](https://sat-math-tutor.streamlit.app) | [Report Bug](https://github.com/yourusername/sat-math-tutor/issues) | [Request Feature](https://github.com/yourusername/sat-math-tutor/issues)

![Python](https://img.shields.io/badge/python-v3.11+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-1.31.0-red.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## ✨ Features

- **AI-Powered Questions**: Utilizes Gemini Pro to generate unique, contextually relevant math problems
- **Adaptive Learning**: Automatically adjusts difficulty based on student performance
- **Interactive Dashboard**: Real-time progress tracking and performance visualization
- **Smart Scoring**: AI-driven score prediction system
- **Comprehensive Database**: 7500+ unique questions with continuous AI generation
- **Mobile Responsive**: Seamless experience across all devices
- **Step-by-Step Solutions**: Detailed explanations for every problem

## 🚀 Quick Start

### Prerequisites

- Python 3.11 or higher
- Google Cloud API key with Gemini Pro access

### Installation

1. Clone the repository

bash
git clone https://github.com/yourusername/sat-math-tutor.git
cd sat-math-tutor
bash
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
bash
pip install -r requirements.txt
bash
Create .env file and add your API key
echo "GEMINI_API_KEY=your_api_key_here" > .env
bash
streamlit run app/main.py


## 📖 Usage

1. **Select Difficulty Level**
   - Choose between Easy, Medium, or Hard questions
   - System adapts based on your performance

2. **Answer Questions**
   - Type your answer in the input field
   - Submit to receive immediate feedback

3. **Review Progress**
   - Check your performance metrics
   - View predicted SAT score
   - Analyze progress trends

## 🔧 Project Structure


sat_math_tutor/
├── app/
│ ├── main.py # Main Streamlit application
│ ├── config.py # Configuration settings
│ ├── database/ # Database management
│ ├── models/ # Data models
│ ├── services/ # Business logic
│ └── utils/ # Helper functions
├── tests/ # Test suite
├── requirements.txt # Dependencies
└── README.md # Documentation


## 🧪 Testing

Run the test suite:

bash
pytest


## 📱 Deployment

### Streamlit Cloud

1. Fork this repository
2. Sign up for [Streamlit Cloud](https://streamlit.io/cloud)
3. Create a new app pointing to your fork
4. Add your `GEMINI_API_KEY` to Streamlit secrets
5. Deploy!

### Local Deployment

For local deployment, ensure you have all environment variables set in your `.env` file:
