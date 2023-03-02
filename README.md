# Django Blog Project - my-first-blog

This is a simple blog project created with Django. It allows users to create, edit, and publish blog posts. Built with a PostgreSQL database

## Installation (Linux)
1. Clone the repository
~~~python
git clone https://github.com/AndreConforti/my-first-blog.git
~~~
2. Create a virtual environment:
~~~python
python3 -m venv venv
~~~
3. Activate the virtual environment:
~~~python
source venv/bin/activate
~~~
4. Install the requirements:
~~~pyhton
pip install -r requirements.txt
~~~
5. Run the migrations:
~~~pyhton
python manage.py migrate
~~~
6. Create a superuser:
~~~python
python manage.py createsuperuser
~~~
7. Run the server:
~~~python
python manage.py runserver
~~~

## Usage
To access the blog, open a web browser and go to **http://localhost:8000/**.
To be able to add, edit and delete posts, you must log in as an administrator at the link **http://localhost:8000/admin/** and you must access with the superuser credentials created previously.

To create a new blog post, click on the "**New Post**" button on the top right corner of the page.

To edit an existing blog post, click on the post's title and then click on the "**Edit**" button.

To delete a blog post, click on the post's title and then click on the "**Delete**" button.

## Credits
This project was created following the Django Girls tutorial (https://tutorial.djangogirls.org/).
