# MacroTrack

## Description
MacroTrack is a Django-based application designed to help users manage their dietary goals by tracking macronutrient consumption and calorie intake. Users can log meals, view nutritional breakdowns, and set personalized calorie goals for weight management, muscle gain, or maintenance. The project also leverages JavaScript for interactive elements, making it easy to use.

## Features
- **Meal Logging**: Add and manage meals with their macronutrient details.
- **Calorie Calculation**: Automatically calculate total daily calories based on user input.
- **Nutritional Breakdown**: Visualize macronutrient ratios (carbs, proteins, fats).
- **Goal Setting**: Customize daily calorie and macronutrient goals.
- **Interactive UI**: Enhanced JavaScript functionalities for a seamless user experience.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<Obitope-Eniola-Nathaniel>/Macro-Nutrient-Calorie-Tracker.git
   cd MacroTrack

2. Set up a virtual environment and install dependencies:
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate
pip install -r requirements.txt

3.Run migrations:
python manage.py migrate

4. Start the development server
python manage.py runserver

5. Open the app in your browser at http://127.0.0.1:8000/.
