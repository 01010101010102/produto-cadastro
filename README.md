# Backend do Cadastro de Produtos

Este é o backend do Cadastro de Produtos, construído utilizando o [Django Rest Framework](https://www.django-rest-framework.org/), fornecendo APIs para deletar, cadastrar, editar e atualizar produtos.

## Pré-requisitos

1. Python >= 3.10
2. Docker e Docker Compose

## Instalação, Configuração e Uso

1. Crie um ambiente virtual:

   ```bash
   python -m venv .cadastro
   ```
   1.1 Entre na pasta:
   
      ```bash
      cd .cadastro
      ```

2. Ative o ambiente virtual:

   ```bash
   source bin/activate
   ```

3. Clone o repositório:

   ```bash
   git clone https://github.com/01010101010102/produto-cadastro.git
   ```

4. Navegue até o diretório clonado:

   ```bash
   cd produto-cadastro
   ```

5. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

6. Copie o que está em exemplo.env -a fim de teste, use os mesmos valores- e crie um arquivo .env na raiz do projeto, onde está manager.py, e cole.os valores necessários.

7. Navegue até o diretório `MYSQL`:

   ```bash
   cd MYSQL
   ```

8. Construa os containers Docker:

   ```bash
   docker-compose build
   ```

9. Inicie os containers Docker:

   ```bash
   docker-compose up
   ```

10. Em outro terminal, execute o servidor Django:
    ```bash
    python manage.py runserver
    ```

## APIs Disponíveis

- Documentação no [Postman](https://documenter.getpostman.com/view/31135629/2sA2xh2CNZ)

## Autor

- Ruan Carlos Ramalho Costa
  - [GitHub](https://github.com/01010101010102/)
  - [LinkedIn](www.linkedin.com/in/ruan-carlos-ramalho-costa-67767b215)
