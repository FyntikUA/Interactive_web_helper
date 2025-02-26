## Interactive Helper

Interactive Helper is a Django web application that allows you to manage contacts, notes, files, and display upcoming contact birthdays.

## Installation

1. Clone the repository:
```bash
   git clone https://github.com/FyntikUA/Interactive_web_helper.git
   cd Interactive_web_helper
```

2. Create and activate a virtual environment:
```bash
   python -m venv env
   source env/bin/activate # For Windows: .\env\Scripts\activate
```

3. Install required packages:
```bash
   pip install -r requirements.txt
```

4. Configure environment variables:
Create a `.env` file in the project's root directory and add the following variables:
```bash
   EMAIL_HOST=smtp_server
   EMAIL_PORT=server_port
   EMAIL_HOST_USER=email@mail.com
   EMAIL_HOST_PASSWORD=password
   SECRET_KEY=your_client_secret
   CLIENT_ID=your_google_client_id
   CLIENT_SECRET=your_google_client_secret
   TOKEN_URI=https://oauth2.googleapis.com/token
```

5. Create and apply database migrations:
```bash
   python manage.py makemigrations files
   python manage.py makemigrations contacts
   python manage.py makemigrations notes
   python manage.py migrate
```

6. Create a superuser for administration:
```bash
   python manage.py createsuperuser
```

7. Start the server:
```bash
   python manage.py runserver 127.0.0.1:8000
```

---


# Interactive Helper

Interactive Helper - це Django веб-додаток, що дозволяє керувати контактами, нотатками, файлами та відображати майбутні дні народження контактів.

## Встановлення

1. Клонування репозиторію:
```bash
   git clone https://github.com/FyntikUA/Interactive_web_helper.git
   cd Interactive_web_helper
```

2. Створення та активація віртуального середовища:
```bash
   python -m venv env
   source env/bin/activate # для Windows: .\env\Scripts\activate
```

3. Встановлення необхідних пакетів:
```bash
   pip install -r requirements.txt
```

4. Налаштування змінних середовища:
Створіть файл .env в кореневій директорії проекту і додайте наступні змінні:
```bash
   EMAIL_HOST=smtp сервер
   EMAIL_PORT=порт серверу
   EMAIL_HOST_USER=імейл@мейл.ком
   EMAIL_HOST_PASSWORD=пароль
   SECRET_KEY=ваш_client_secret
   CLIENT_ID=ваш_client_id google
   CLIENT_SECRET=ваш_client_secret google
   TOKEN_URI=https://oauth2.googleapis.com/token
```

5. Створення та міграція бази даних:
```bash
   python manage.py makemigrations files
   python manage.py makemigrations contacts
   python manage.py makemigrations notes
   python manage.py migrate
```

6. Створення суперкористувача для адміністрування:
```bash
   python manage.py createsuperuser
```

7. Запуск сервера:
```bash
   python manage.py runserver 127.0.0.1:8000
```
