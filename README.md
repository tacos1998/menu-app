# Menu App

This is a simple app for creating, retrieving, updating, deleting, and listing menu items and prices using Django, Django REST, and Next.js. It is based off the project featured in [koladev32's blog](https://koladev.xyz/posts/django-nextjs-crud/).

## Starting with Django and React

First launch the API server.

```bash
cd django-api-nextjs
python3.11 -m venv venv
pip install -r requirements.txt

python manage.py migrate
python manage.py runserver
```

The API server will be available at `http://localhost:8000/`.

Then launch the React client.

```bash
cd menu-frontend
npm install
npm run dev
```

The React client will be available at `http://localhost:3000/`.
