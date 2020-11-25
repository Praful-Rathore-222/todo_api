# todo_api
<h2><b>Django Rest API Todo Application</b></h2>

<p>This is a simple django rest api application which contains all the crud operations of api and moreover, it includes filtering and pagination. </p>

<h2><b>Technology Stack<b></h2>

I have used,
```
1. Python 3
2. Django REST Framework
3. sqlite3 Database
4. Google Chrome v.83.0.4103.61    
5. Google Chrome driver v.83.0.4103.61

```
<h2><b>Project Structure</b></h2>

```
.
├── applist
│   ├── admin.py 
│   ├── apps.py
│   ├── apps.pyc
│   ├── __init__.py
│   ├── __init__.pyc
│   ├── migrations: database migrations
│   ├── models.py: database models for Todo app
│   ├── __pycache__
│   ├── serializers.py: serializers for the models
│   ├── tests.py: test cases for view
│   ├── urls.py: url endpoints of Todo app
│   └── views.py: These views are called by API endpoints
├── db.sqlite3
├── manage.py
├── requirements.txt: requirements needs to be install
└── Todo_app
    ├── __init__.py
    ├── __init__.pyc
    ├── __pycache__
    ├── settings.py: settings file for the project
    ├── settings.pyc
    ├── urls.py: base urls for apps of the projects
    └── wsgi.py

```
<h2><b>Runnning Locally <b></h2>

First, clone the repository to your local machine:
```
git clone https://github.com/Praful-Rathore-222/todo_api.git

cd todo_api
```

Apply the database migrations:

```
python3 manage.py migrate
```  
Create administrator/super user:
```
python3 manage.py createsuperuser 
```

Finally, run the development server:

```
python3 manage.py runserver
```
The site will be available at 127.0.0.1:8000. `
## Linting:

```
make lint
```

## Testing:

```
python3 manage.py test
```



