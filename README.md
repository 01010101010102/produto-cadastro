# Backend da Cadastro de Produtos

Este é o backend de da Cadastro de Produtos. O backend é construído utilizando [django-rest-framework.], e fornece APIs para deletar, cadastrar, editar e atulizar produtos.

## Instalação, Configuração e Uso

0. instale o python>=10
1. git clone https://github.com/01010101010102/produto-cadastro.git
2. cd produto-cadastro
3. source bin/activate
4. pip install -r requirements.txt
5. copie o que está em exemplo.env e crie um arquivo .env na raiz do projeto, onde está manager.py, e cole. Preencha as variaveis.
6. no console: python manage.py runserver
7. docker build -t meu-mysql .
8. docker run --name meu-mysql -d -p 3309:3309 meu-mysql

## APIs Disponíveis

- [POSTMAN](https://documenter.getpostman.com/view/31135629/2sA2xh2CNZ)

## Autor

- Ruan Carlos Ramalho Costa - [git](https://github.com/01010101010102/) -[LinkedIn](https://github.com/NomeDoGitHub2)
