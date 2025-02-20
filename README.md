# Blog com React e Axios

Este é um projeto de blog desenvolvido com React, React Router e Axios. O blog permite a criação, edição, exclusão e listagem de posts, consumindo uma API externa.

## Tecnologias Utilizadas
- React.js
- React Router
- Axios
- CSS

## Funcionalidades
- Listagem de posts
- Visualização de post específico
- Criação de novo post
- Edição de post existente
- Exclusão de post

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd nome-do-projeto
   ```
3. Instale as dependências:
   ```bash
   npm install
   ```

## Uso
Para iniciar o projeto em modo de desenvolvimento, execute:
```bash
npm run dev
```

Acesse no navegador: `http://localhost:5173/`

## API
A API utilizada para os posts é a `JSONPlaceholder`:
- Base URL: `https://jsonplaceholder.typicode.com`
- Endpoints utilizados:
  - `GET /posts` - Lista todos os posts
  - `GET /posts/:id` - Obtém um post específico
  - `POST /posts` - Cria um novo post
  - `PUT /posts/:id` - Edita um post existente
  - `DELETE /posts/:id` - Exclui um post

## Contribuição
Contribuições são bem-vindas! Para contribuir:
1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)
3. Commit suas alterações (`git commit -m 'Adiciona nova funcionalidade'`)
4. Envie para o repositório (`git push origin minha-feature`)
5. Abra um Pull Request