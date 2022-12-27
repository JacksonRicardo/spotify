
# Documentação
## Configurar

A primeira coisa a fazer é clonar o repositório:

```sh
$ git clone https://github.com/JacksonRicardo/spotify.git
$ cd spotify-clone-django
```

Crie um ambiente virtual para instalar as dependências e ative-o:

```sh
$ virtualenv env
$ source env/bin/activate
```

Em seguida, instale as dependências:

```sh
(env)$ pip install -r requisitos.txt
```
Observe o `(env)` na frente do prompt. Isso indica que este terminal
sessão opera em um ambiente virtual configurado por `virtualenv2`.

Assim que o `pip` terminar de baixar as dependências:
```sh
(env)$ cd spotify
(env)$ python manage.py runserver
```
E navegue até `http://127.0.0.1:8000/demo`.