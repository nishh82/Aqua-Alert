Aqua-Alert

 What is Aqua-Alert?

Aqua-Alert is a simple tool that helps monitor water quality in real time. Whether you need to check drinking water, a lake, or a water system, it gives instant updates and alerts if something’s wrong.

 Why Use Aqua-Alert?

Live Monitoring: Tracks key water factors like pH, turbidity, and temperature.

Easy Dashboard: View simple charts and data in one place.

Instant Alerts: Get notified if water quality changes.

Remote Access: Check water status from anywhere.

 How It Works

Built With: Django (Python)

Database: PostgreSQL with TimescaleDB

Sensors: pH, Turbidity, Temperature, and TDS

Visuals: Grafana, Matplotlib

 Get Started

What You’ll Need

Python 3.x

PostgreSQL with TimescaleDB

Virtual environment (optional)

️⃣ Download the Code

 git clone https://github.com/nishh82/Aqua-Alert.git
 cd Aqua-Alert

️⃣ Set Up Your Environment

 python3 -m venv env
 source env/bin/activate  # macOS/Linux
 env\Scripts\activate    # Windows

️⃣ Install Dependencies

 pip install -r requirements.txt

️⃣ Set Up the Database

Update settings.py with your database credentials, then run:

 python manage.py makemigrations
 python manage.py migrate

⃣ Start the App

 python manage.py runserver

Go to http://127.0.0.1:8000/ to check it out.

📌 How to Use It

Connect IoT sensors.

Check the dashboard for real-time data.

Get alerts when water quality changes.


