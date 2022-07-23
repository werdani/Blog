# Blog

<p>A blog (a shortened version of “weblog”) is an online journal or informational website displaying information in reverse chronological order, with the latest posts appearing first, at the top. It is a platform where a writer or a group of writers share their views on an individual subject. </p>

### Technologies we used :
- Python framework Django .
- PostgreSQL database .

### For live website :

https://werdani.pythonanywhere.com/accounts/signup/

### How to Install and Run the Project on windows :
- Create a virtual environment on the desktop, for example 'env' .
- write this command in CMD to create it :- ' virtualenv env ' .
- open folder 'env' and acvtivate virtualenv using this command : '.\Scripts\activate' .
- clone my project using this command : git clone "https://github.com/werdani/Blog" .
- cd 'Blog' and install requirments using this command : pip install -r requirment.txt .
- now need to create database in PostgreSQL using this name 'blog' .
- 'USER': 'postgres', 'PASSWORD': 'postgres', 'HOST': 'localhost', 'PORT': '5432' .
- add this information in file 'setting.py' .
- need to makemigrations using this command in CMD : 'python manage.py makemigrations' .
- need to migrate using this command in CMD : 'python manage.py migrate' .
- now database is ready to add products, but now you need to create a superuser .
- to create superuser write this command in CMD: 'python mange.py createsuperuser' . 
