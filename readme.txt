PYTHON + DJANGO:

1. mkdir + nomedapasta (cria uma pasta no console)
2. cd + nome da pasta (abre a pasta)
3. python -m venv env (cria o ambiente virtual)
4. source env/Scripts/activate (ativa o ambiente virtual)
5. pip install django (instala os arquivos de Django)
6. pip freeze (mostra todos os arquivos instalados)
7. pip freeze > requirements.txt
8. django-admin startproject + nome_projeto
9. python manage.py runserver
10. code .
11. django-admin startapp website


Explicações:
#1#Abrir no navegador localhost: 8000 e verificar se o django tá ok###

#2#Em settings.py DATABASE (Banco de dados) - dependendo da empresa, pode mudar o tipo de Database e você precisará  instalar esse tipo de database no django.
****banco de dados não relacional: tem uma base e você não precisa relacionar todos os elementos
****SGBD - sistema de gerenciamento de banco de dados

#3#Depois do passo 11 você clica no VScode na pasta website e cria um arquivo urls.py

#4#Vscode - Cria uma pasta templates dentro de website e cria dentro desse templates um arquivo index.html

#5#Criar uma pasta shared para compartilhar arquivos com conteúdo em comumn, cria dentro desta pasta o arquivo layout.html

#6#

Links úteis:
https://stackoverflow.com
banco de dados sqlite3 => https://sqliteonline.com





git commit -m "criar projeto em django e base de dados"




