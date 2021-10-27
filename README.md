# Installer votre environnement Django

## Créer un environnement virtuel

```shell
python -m venv venv
```

## Activer l'environnement virtuel

```shell
./venv/bin/activate # Linux / Mac
.\venv\Scripts\activate.bat # Windows cmd
.\venv\Scripts\activate.ps1 # Windows powershell
```

## Installer les dépendances

```shell
pip install django
pip install djangorestframework
pip install markdown
pip install django-filters
pip install black
```

## Créer un projet django

```shell
django-admin startproject votre_projet
```

## Générer et appliquer des migrations

```shell
python manage.py makemigrations # Générer les migrations
python manage.py migrate # Appliquer les migrations
```

## Démarer le serveur web Django

```shell
python manage.py runserver
```

## Créer le user admin

```shell
python manage.py createsuperuser
```

vous connecter sur l'interface web à l'adresse localhost:8000/admin

## Créer une app

```shell
python manage.py startapp nom_de_votre_app
```

