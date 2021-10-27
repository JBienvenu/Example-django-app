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


