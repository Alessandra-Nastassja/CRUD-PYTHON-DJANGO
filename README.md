pip.exe install virtualenv

# CRUD-PYTHON-DJANGO

* Criando o ambiente virtualizado

virtualenv venv

cd venv

cd Scripts

activate

* Instalar o Django

pip install django

* Criar o projeto

django-admin startproject project .

* Criar a aplicação

django-admin startapp products

* Rodar a aplicação

python manage.py runserver

* Fazer as imigrações para o banco SQL

python manage.py makemigrations

python manage.py migrate

* Area do admin

python manage.py createsuperuser
