---

# Django Weather App

## Overview

This Django Weather App is a simple web application that allows users to retrieve current weather information and 5-day forecasts for selected cities. The application leverages the OpenWeatherMap API to fetch real-time weather data.

## Features

- **Weather Information:** Get current temperature, weather description, and icons for selected cities.
- **5-Day Forecast:** View a 5-day forecast, including minimum and maximum temperatures, for the chosen locations.
- **Multiple Cities:** Compare weather information for two cities side by side.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Get OpenWeatherMap API Key:**
   - Sign up on [OpenWeatherMap](https://openweathermap.org/) to obtain an API key.
   - Save the API key in a file named `API_KEY` in the project directory.

4. **Run the Application:**
   ```bash
   python manage.py runserver
   ```

5. **Access the App:**
   Open your web browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to use the Weather App.

## Usage

1. **Enter City Names:**
   - Enter the names of the cities you want to compare in the provided input fields.
   - Optionally, provide a second city for comparison.

2. **View Weather Information:**
   - See the current weather information, including temperature, description, and icons.
   - Explore the 5-day forecast for each city.

3. **Compare Cities:**
   - Compare weather information for two cities on the same page.

## Technologies Used

- Django
- Python
- OpenWeatherMap API
- HTML
- CSS
- JavaScript

## Acknowledgments

- This project is built using the [Django](https://www.djangoproject.com/) web framework.
- Weather data is fetched from [OpenWeatherMap](https://openweathermap.org/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template according to your project's specific details and structure. Add more sections if needed, such as "Deployment," "Contributing," or "Troubleshooting," based on the complexity of your project and the information you want to provide to users and contributors.
