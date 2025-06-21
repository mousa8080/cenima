# Cinema Booking API 🎬

A backend RESTful API for managing cinema bookings, developed using Django and Django REST Framework.

## 🚀 Features

- 🎞️ View available movies and screenings
- 📅 Book tickets for specific showtimes
- 🔐 Token-based authentication for users
- ✍️ One user can book a specific movie only once per screening
- 📊 Admin interface to manage movies, screenings, and bookings
- 📤 Built with clean code architecture using viewsets and serializers

## 🛠️ Technologies Used

- Python 3
- Django
- Django REST Framework
- SQLite (for development)
- Postman (for testing)
- Git & GitHub

## 📦 How to Run the Project

```bash
git clone https://github.com/mousa8080/cenima.git
cd cenima
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
