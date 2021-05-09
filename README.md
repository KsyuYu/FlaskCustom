# Лабораторна робота №3
# Юр'євої Ксенії КМ-81
Сайт магазину (розміщений на хмарному хостингу Heroku) на  дає можливість реєстрації користувача, входу існуючого користувача, вибору продутів та додавання їх у кошик.
Для взаємодії користувача з базою даних у лабораторній роботі використовуються CRUD-операції (для створення користувача, додавання продуктів у кошик). 
Для Front-End частини були використані HTML, CSS, JS та шаблонізатор Jinja2. 
## Інсталяція для Windows
1. Clone This Project
2. Go to Project Directory `cd flaskcustom`
3. Create a Virtual Environment `py -m venv env`
4. Activate Virtual Environment `.\env\Scripts\activate`
5. Install Requirements Package `pip install -r requirements.txt`
6. Expory database `export DATABASE_URL = postgres://zvxzfkypismuhy:4a15b9097a1c7751f0bc843580c9b53d5404b8bc03052d245ebca84fbc26233c@ec2-54-74-156-137.eu-west-1.compute.amazonaws.com:5432/det7ohs5i6h31c`
7. Create Database `py database.py`
8. Finally Run The Project `py main.py`
9. Go to in browser 127.0.0.1:5000/
## Інсталяція для Linux/MacOS
1. Clone This Project
2. Go to Project Directory `cd flaskcustom`
3. Create a Virtual Environment `python3 -m venv env`
4. Activate Virtual Environment `source env/bin/activate`
5. Install Requirements Package `pip install -r requirements.txt`
6. Expory database `export DATABASE_URL = postgres://zvxzfkypismuhy:4a15b9097a1c7751f0bc843580c9b53d5404b8bc03052d245ebca84fbc26233c@ec2-54-74-156-137.eu-west-1.compute.amazonaws.com:5432/det7ohs5i6h31c`
7. Create Database `python3 database.py`
8. Finally Run The Project `python3 main.py`
9. Go to in browser 127.0.0.1:5000/
## Heroku
https://flaskcustshop.herokuapp.com
## Діаграма
![](https://github.com/KsyuYu/FlaskCustom/blob/main/storediagram.png)
