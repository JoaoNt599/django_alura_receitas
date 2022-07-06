// iniciando virtualenv
venv/Scripts/activate

// desativando virtualenv
deactivate

// criando projeto django
django-admin startproject <nome_do_projeto> .

// subindo servidor
python manage.py runserver

// criando um app
python manage.py <nome_do_app>

// copiando arquivos estaticos
python manage.py collectstatic

// criando migracoes
python manage.py makemigrations

// migrando arquivos para o banco
python manage.py migrate