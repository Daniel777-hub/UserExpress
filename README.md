# UserExpress:

Este é um projeto simples de API RESTful usando Node.js e Express. Ele permite criar, ler, atualizar e deletar usuários.

## Dependências

- Express: Framework web rápido, flexível e minimalista para Node.js.
- uuid: Para a criação de identificadores únicos universais.

## Rotas

- `GET /users`: Retorna todos os usuários.
- `POST /users`: Cria um novo usuário. Espera um corpo de requisição com um objeto contendo `name` e `age`.
- `PUT /users/:id`: Atualiza um usuário existente com base no `id` fornecido. Espera um corpo de requisição com um objeto contendo `name` e `age`.
- `DELETE /users/:id`: Deleta um usuário existente com base no `id` fornecido.

## Como executar

1. Clone este repositório.
2. Instale as dependências com `npm install`.
3. Inicie o servidor com `node index.js` (ou o nome do seu arquivo principal).
4. O servidor estará ouvindo na porta 3000.

Lembre-se de que este é um projeto simples e não inclui persistência de dados. Quando o servidor é reiniciado, todos os dados são perdidos. Para um projeto mais robusto, considere usar um banco de dados.
