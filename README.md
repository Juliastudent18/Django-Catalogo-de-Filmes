# Django-Catalogo-de-Filmes
Repositório para Listar os filmes

Este projeto é uma aplicação web desenvolvida com Django, que permite o cadastro e a visualização de filmes. Foi criado como parte de uma atividade prática para consolidar os conhecimentos em desenvolvimento com o framework Django.

Objetivos do Projeto

- Compreender a estrutura de um projeto Django.
- Criar apps e modelos personalizados.
- Utilizar views e templates para exibição de dados.
- Estilizar páginas com CSS.
- Realizar cadastro de dados via Django Admin.
- Renderizar páginas dinamicamente a partir do banco de dados.

 Funcionalidades

- Cadastro de filmes (título, descrição, ano, gênero, capa).
- Visualização de todos os filmes cadastrados em uma página estilizada.
- Interface integrada com Django Admin para gerenciamento dos registros.
- Estrutura organizada com templates e arquivos estáticos.

 Tecnologias Utilizadas

- Python 3.10+
- Django 4.x
- SQLite (banco de dados)
- HTML5 e CSS3
- VSCode (editor recomendado)

Como Executar o Projeto Localmente

1. Clone o repositório

'''bash
git clone https://github.com/Juliastudent18/Django-Catalogo-de-Filmes.git

cd Django-Catalogo-de-Filmes

2. Crie e ative o ambiente virtual

python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\Scripts\activate

3. Instale as dependências

pip install django

4. Execute as migrações

python manage.py makemigrations
python manage.py migrate

5. Crie um superusuário para o admin

python manage.py createsuperuser

6. Rode o servidor

python manage.py runserver

Acesse a aplicação no navegador:
http://127.0.0.1:8000

Acesse o admin em:
http://127.0.0.1:8000/admin

Estrutura de Pastas

Django-Catalogo-de-Filmes/
├── catalogo/             # Configurações do projeto
├── filmes/               # App com modelos, views, templates e static
│   ├── templates/filmes/ # Template lista.html
│   ├── static/filmes/    # Estilo CSS
├── manage.py
└── README.md

Autora

Desenvolvido por Julia
Para a disciplina de Programação Web com Django
Professor: Luís Felipe Santos
Data de entrega: 30/04/2025
