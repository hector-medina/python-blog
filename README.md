# python-blog
This is a test blog from the book 'Django 3 By Example Build powerful and reliable Python web applications from scratch' by Antonio Melé.

## INSTALLATION

To install this app you have to run the following steps:

**1. Clone the repository.**

```
git clone https://github.com/hector-medina/python-blog.git
```
**2. Chage the directory.**

```
cd python-blog
```

**3. Create a virtual environment.**

```
python3 -m venv env
```

**4. Activate the virtual environment.**

```
source env/bin/activate
```

This might change a little bit if you're using windows OS. 

**5. Install required dependencies.**

```
pip install doc/requirements.txt
```

**6. Update database.**

```
python manage.py migrate
```

**7. Enable dev server.**

```
cd mysite
python manage.py runserver
```

**8. Access your app.**

You should be able to access the development server by typing http://localhost:8000 or http://127.0.0.1:8000 in your browser.

