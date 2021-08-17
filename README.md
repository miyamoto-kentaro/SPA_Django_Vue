# git setup

```
echo "# SPA_Django_Vue" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/miyamoto-kentaro/SPA_Django_Vue.git
git push -u origin main
```

# python setting

```
$ create venv
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py createsuperuser
```

# vue setting

## create app

```
install vue/cli
$ npm install -g @vue/cli
$ vue create your_project_name
as frontend

---------------------------
-manual select

-nessesary
% Choose Vue vertion
% Babel
% Router
% Vuex
% CSS Pre-processors
remove % Linter

-version: 3

-history mode : Y

-Css preprocessor
dart-scss

-Where do you prefer placing config ...
In dedicated config files

-Save this as apreset for future projects : N
---------------------------

```

```
running
$ npm install
$ npm run serve
```
