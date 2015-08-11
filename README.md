# Polls
Aplicativo de acompanhamento para estudo da documentação do DJANGO.

## Instalação
Para instalar o ambiente, depois de clonar este repositório, faça:

    $ virtualenv env;
    $ source env/bin/activate;
    $ pip install -r requirements.pip
    $ python manage.py migrate;

Este comando adiciona um superusuario na ferramenta:

    $ python manage.py createsuperuser;

Para rodar o serviço faça:

    $ python manage.py runserver;