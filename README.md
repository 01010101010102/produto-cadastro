# Backend da Cadastro de Produtos

Este é o backend de da Cadastro de Produtos. O backend é construído utilizando [django-rest-framework.], e fornece APIs para deletar, cadastrar, editar e atulizar produtos.

## Instalação

1. git clone https://github.com/01010101010102/produto-cadastro.git
2. cd produto-cadastro
3. source bin/activate
4. pip install -r requirements.txt
5. copie o que está em exemplo.env e crie um arquivo .env na raiz do projeto, onde está manager.py, e cole. Preencha as variaveis.
6. no console: python manage.py runserver
7. docker build -t meu-mysql .
8. docker run --name meu-mysql -d -p 3309:3309 meu-mysql

## Configuração

1. Crie um arquivo `.env` na raiz do projeto.
2. Adicione as seguintes variáveis de ambiente ao arquivo `.env`:

```
PORT=3000
DATABASE_URL=URL_DO_BANCO_DE_DADOS
```

Substitua `URL_DO_BANCO_DE_DADOS` pela URL do seu banco de dados.

## Uso

1. Execute `npm start` para iniciar o servidor.
2. O servidor estará disponível em `http://localhost:3000` por padrão, a menos que a porta seja alterada no arquivo `.env`.

## APIs Disponíveis

- [POSTMAN](https://documenter.getpostman.com/view/31135629/2sA2xh2CNZ)

## Contribuição

Contribuições são bem-vindas! Para contribuir com o backend da aplicação XYZ, siga estas etapas:

1. Faça um fork deste repositório.
2. Crie uma branch para sua modificação (`git checkout -b feature/nova-feature`).
3. Faça commit de suas alterações (`git commit -am 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Crie um novo Pull Request.

## Autores

- Nome do Autor 1 - [NomeDoGitHub1](https://github.com/NomeDoGitHub1)
- Nome do Autor 2 - [NomeDoGitHub2](https://github.com/NomeDoGitHub2)

## Licença

Este projeto está licenciado sob a [Licença XYZ](https://opensource.org/licenses/XYZ).

## Agradecimentos

- Agradecimento 1
- Agradecimento 2
- ...

---

Sinta-se à vontade para personalizar o README de acordo com as necessidades específicas do seu projeto.
