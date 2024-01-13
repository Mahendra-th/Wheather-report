# Wheather-report
## 1. HTML (index.html):
DOCTYPE and HTML tag: Specifies the HTML5 document type and opens the HTML document.
Head section: Contains metadata, including character set, viewport settings, title, and a link to the CSS file.
Body section:
Container div: This div holds the entire content of the page.
Heading (h1): Provides a title for the page, such as "Weather Report."
Input for location (city or zip code): Allows the user to input the location for which they want the weather report.
Button: A button triggers the weather data fetching and display when clicked.
Div for weather information (weatherInfo): This empty div will display the fetched weather information.
## 2. CSS (style.css):
Body styling: Applies a background color and styles to the body for a clean layout.
Container styling: Adds styling to the container div, such as background color, padding, border-radius, and box shadow.
Input and Button styling: Provides styling for the input field and button.
Weather Info div styling: Adds styling to the div where the weather information will be displayed.
## 3. JavaScript (script.js):
fetchWeatherData function: This function is triggered when the button is clicked.
Retrieves the input location from the input field.
Uses an API (e.g., OpenWeatherMap) to fetch weather data for the specified location.
Parses the fetched data and extracts relevant information (temperature, description, etc.).
Dynamically updates the content of the weatherInfo div with the fetched information.
