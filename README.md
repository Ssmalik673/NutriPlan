
# NutriPlan – AI-Powered Personalized Diet Plan Generator

## About the Project
NutriPlan is an AI-powered diet plan generator developed using Python, Flask, HTML, CSS and Google's Gemini API.

It generates personalized diet plans based on the user's personal details, fitness goals, workout duration, food preferences and allergies.

## Features
- Personalized diet plan generation
- Weekly and monthly diet plans
- BMI calculation
- Vegetarian, non-vegetarian and vegan preferences
- Allergy-based food recommendations
- AI-generated nutritional information
- Print or save diet plans as PDF

## Technologies Used
- Python
- Flask
- HTML5
- CSS3
- Google Gemini API
- python-dotenv

## Project Structure
NutriPlan/
- app.py
- requirements.txt
- .gitignore
- templates/
  - index.html
  - result.html

## Installation and Setup

1. Clone the repository.

2. Install the required dependencies:

   pip install -r requirements.txt

3. Create a `.env` file in the project directory.

4. Add your Gemini API key:

   gemini_api_key=YOUR_API_KEY

5. Run the application:

   python app.py

6. Open the application in your browser:

   http://127.0.0.1:5000/

## Disclaimer
The generated diet plans are for general informational purposes only and should not replace professional medical or nutritional advice.
