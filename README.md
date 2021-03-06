# Api-Backend-Loja


Projeto teste para novos colaboradores Backend da Atenas Software.


Este projeto disponibiliza apenas os arquivos de teste:
- cliente.test
- produto.test
- pedido.test

Baseado na regra de negócio exigida pelo teste é necessário implementar:
- Os Models Cliente, Produto e Pedido.
- O Model Cliente com os atributos: nome, dataNascimento, dataCadastro e dataAtualizacao.
- O Model Produto com os atributos: descricao, preco, dataCadastro e dataAtualizacao.
- O Model Pedido com os atributos: cliente, dataCadastro e dataAtualizacao e produtos[{idProduto, descricao, quantidade, preco}].
- As Routes cliente-route, produto-route e pedido-route com as rotas de cada modelo.
- Os Controllers cliente-contoller, produto-contoller e pedido-contoller com as regras de negócio e validação das rotas.
- Os Repositories cliente-repository, produto-repository e pedido-repository que serão utilizados pelos controllers para persitir e buscar os dados no banco de dados.

# Áreas de conhecimento

- Node.js (https://nodejs.org/en/)
- Express.js (http://expressjs.com/)
- MongoDB (https://www.mongodb.com/)
  * Recomendamos utilizar um banco de dados em memória como o mongodb-memory-server.
- Mongoose.js (https://mongoosejs.com/)
- Testes com Chai.js (https://www.chaijs.com/)
- Testes com Mocha.js (https://mochajs.org/)
