# Customer360
Customer360 is a lightweight CRM app built with Django. It allows users to:
- Create and manage customer profiles
- Record interactions by channel and direction
- View a 30-day interaction summary
- Enhance profiles with optional social media data

## 🚀 Getting Started

1. Create a virtual environment:
python -m venv venv


2. Activate it:
- Windows:
  ```
  .\venv\Scripts\Activate.ps1
  ```
- macOS/Linux:
  ```
  source venv/bin/activate
  ```

3. Install dependencies:
pip install django


4. Run the server:
python manage.py migrate python manage.py runserver


Visit `http://127.0.0.1:8000` to access the app.

## 💡 Features
- Customer creation and listing
- Interaction logging by channel (including social media!)
- 30-day summary dashboard
- Dynamic templates with Django

## 🛠 Tech Stack
- Python 3.11+
- Django 5.2+
- HTML, CSS (Bootstrap)

OR just:
Create a virtual environment:
  python -m venv venv
  
pip install -r requirements.txt
