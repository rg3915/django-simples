# django-simples

Exemplo de um projeto simples com Django.

## Como rodar o projeto?

* Clone esse repositório.
* Crie um virtualenv com Python 3.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/django-simples.git
cd django-simples
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate
```

## Links


[djangoproject.com](https://www.djangoproject.com/start/)

[Tutorial Django 2.2](http://pythonclub.com.br/tutorial-django-2.html)

[python-decouple](https://github.com/henriquebastos/python-decouple)

[Live de Python #97 - Desacoplando configurações com Decouple - com Henrique Bastos](https://www.youtube.com/watch?v=zYJGpLw5Wv4)

[env_gen](https://gist.github.com/rg3915/22626de522f5c045bc63acdb8fe67b24)

[base.html](https://gist.github.com/rg3915/0144a2408ec54c4e8008999631c64a30)

[Live de Python #94 - Django básico - com Regis Santos](https://www.youtube.com/watch?v=YuKdwIhJysU)

[Live de Python #95 - Entendendo o ORM do Django - com Regis Santos](https://www.youtube.com/watch?v=cyxky2QJlwg)

[Emmet](https://emmet.io/)

[Heroku](https://www.heroku.com/home)

[Configuring Django Apps for Heroku](https://devcenter.heroku.com/articles/django-app-configuration)

[Tutorial deploy no Heroku](https://github.com/rg3915/tutoriais/tree/master/django-basic#deploy-no-heroku)

[dj-static](https://pypi.org/project/dj-static/)