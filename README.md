# Flask Web App
A simple Flask web application featuring user authentication, a personalized greeting, and a dynamic weather forecast (with optional features for further enhancement).

# Features
- User Authentication: Registration, login, and logout functionality with password hashing and user session management using Flask-Login.

- Greeting: A personalized greeting message based on user input.

- Weather API: Displays current weather information using the OpenWeatherMap API.

- Responsive Design: A sleek, modern design with a background image, form styling, and interactive buttons.

# Tech Stack
- Backend: Flask, SQLAlchemy, Flask-Login

- Frontend: HTML, CSS (Responsive Design)

- Database: SQLite

- API: OpenWeatherMap API (for weather information)

- Other: Werkzeug for password hashing, Requests for API calls

# Installation
1. Clone the repository:

```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
```
2. Create a virtual environment:

```bash
python -m venv venv
```
3. Activate the virtual environment:

- On Windows:

```bash
venv\Scripts\activate
```
- On Mac/Linux:

```bash
source venv/bin/activate
```
4. Install the required dependencies:

```bash
pip install -r requirements.txt
```
5. Run the application:

```bash
python app.py
```
6. Open your browser and go to http://127.0.0.1:5000 to view the app.

# How It Works
- The app has routes for home, register, login, logout, and weather.

- Users can register and log in to access the personalized greeting.

- The weather feature fetches data from the OpenWeatherMap API and displays the current weather for a default city (which can be modified).

- Users can log out, which clears their session.

# Contributing
1. Fork the repository.

2. Create your branch (git checkout -b feature-name).

3. Commit your changes (git commit -am 'Add new feature').

4. Push to your branch (git push origin feature-name).

5. Create a new Pull Request.
