# djangoproject – Django To-Do Application

> A task management web application built with Django and Bootstrap, featuring full CRUD operations for to-do items.

---

## About the Project

This is a Django-based To-Do application with full CRUD functionality — users can add, update, and delete tasks. The project uses Bootstrap 4 for styling and python-decouple for environment variable management.

---

## Features

- Add new to-do tasks
- Update existing tasks
- Delete tasks
- Responsive UI with Bootstrap 4
- Django admin panel for task management
- Environment variable management with python-decouple

---

## Technologies Used

| Technology | Version |
|---|---|
| Python | 3.10 |
| Django | 4.0 |
| Bootstrap | 4 |
| python-decouple | 3.6 |
| HTML5 / CSS3 | – |

---

## Project Structure

```
djangoproject/
├── main/           # Core Django app (settings, urls)
├── todo/           # To-do app (models, views, urls)
├── templates/todo/ # HTML templates for todo app
├── manage.py
└── requirements.txt
```

---

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/fuatsevinc/djangoproject
   cd djangoproject
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**
   ```bash
   python manage.py runserver
   ```

7. Open your browser and visit: `http://127.0.0.1:8000/`

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

Developed by [fuatsevinc](https://github.com/fuatsevinc)
