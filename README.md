# Django JWT Auth Backend

This project is a Django backend that implements JWT authentication using Django REST Framework and Simple JWT. The backend includes features for user registration, login, logout, and fetching user details.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine
- Django installed
- Django REST Framework installed
- Simple JWT package installed

## Getting Started

Follow these steps to get the Django backend up and running.

### 1. Clone the Repository

```bash
git clone https://github.com/Silversatility/authentication-api.git
cd authentication-api


python -m venv venv
source venv/bin/activate 

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver

