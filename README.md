# Django-3-Testes-seguranca-lapidacoes

API desenvolvida a partir do curso Django 3 Rest Framework da plataforma Alura:

https://cursos.alura.com.br/course/api-django-3-testes-seguranca-lapidacoes

Para inicializar essa API, abra o terminal e digite os seguintes comandos:

>pip install Django==3.0.7

>python3 -m venv ./venv

>venv\Scripts\activate

>pip install -r requirements.txt

>python manage.py makemigrations

>python manage.py migrate

>python seed.py

>python manage.py runserver

Devemos instalar o GetText e Inconv em nosso PC
https://mlocati.github.io/articles/gettext-iconv-windows.html

Para realizar os testes:

>python manage.py test

Modulo 1:

- Carregamos o projeto base local e executamos o arquivo seed.py, para criar alunos e cursos;

- Aprendemos como trabalhar com arquivos estáticos no Django Rest Framework;

- Vimos na prática como realizar uma requisição POST e PUT de uma foto.

Modulo 2:

- Aprendemos como melhorar a performance da API utilizando cache;

- Instalamos e subimos o servidor do Redis;

- Integramos o Django e o Redis.

Modulo 3:

- Vimos como inclui um middleware de internacionalização;

- Aprendemos como alterar as mensagens padrões do Django;

- Incluímos na prática a negociação de conteúdo, seja ele um JSON ou XML com base no cabeçalho Accept.

Modulo 4:

- Aprendemos como criar um cenário de teste, sem utilizar os dados da aplicação;

- Escrevemos os testes das principais requisições do recurso de cursos.

Modulo 5:

- Entendemos a importância de alterar o path para acessar o área de Admin do Django;

- Incluímos uma falsa tela de login de administrador do Django para registrar e notificar os administradores sobre tentativas de acesso não autorizado.


_________________________________________________________________________________________________________________________________________________________

API developed from the Django 3 Rest Framework course on the Alura platform:

https://cursos.alura.com.br/course/api-django-3-testes-seguranca-lapidacoes

To initialize this API, open the terminal and enter the following commands:

>pip install Django==3.0.7

>python3 -m venv ./venv

>venv\Scripts\activate

>pip install -r requirements.txt

>python manage.py makemigrations

>python manage.py migrate

>python seed.py

>python manage.py runserver

We must install GetText and Inconv on our PC
https://mlocati.github.io/articles/gettext-iconv-windows.html

To run the tests:

>python manage.py test

Module 1:

- We loaded the local base project and executed the seed.py file, to create students and courses;

- We learned how to work with static files in Django Rest Framework;

- We saw in practice how to perform a POST and PUT request for a photo.

Module 2:

- We learned how to improve the performance of the API using cache;

- We installed and uploaded the Redis server;

- We integrate Django and Redis.

Module 3:

- We saw how it includes an internationalization middleware;

- We learned how to change Django's default messages;

- We have included content negotiation in practice, be it JSON or XML based on the Accept header.

Module 4:

- We learned how to create a test scenario, without using the application data;

- We wrote the tests of the main requests of the course resource.

Module 5:

- We understand the importance of changing the path to access the Django Admin area;

- We've included a fake Django admin login screen to log and notify admins of unauthorized access attempts.
