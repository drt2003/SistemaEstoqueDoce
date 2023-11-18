
# Sistema de Controle de Estoque de Doces

## Descrição do Projeto

O Sistema de Controle de Estoque de Doces é uma aplicação desenvolvida como parte do curso de Programação Orientada a Objetos na USF. A finalidade principal da aplicação é gerenciar o estoque de diferentes tipos de doces, permitindo a realização de operações básicas de CRUD (Create, Read, Update, Delete). Este sistema destina-se a pequenos negócios ou empreendedores que desejam manter um registro organizado de seus produtos.

## Desenvolvedores

- Danilo Ramos Torres (RA: 202105838)
- Lukas Rodrigues de Almeida (RA: 202109235)

## Tecnologia Empregada

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- Linguagem de Programação: Java
- Framework: Spring Boot
- Banco de Dados: H2 Database (em memória)

## Descrição da Arquitetura

A aplicação segue uma arquitetura baseada em Spring Boot, que facilita o desenvolvimento de aplicativos Java. A estrutura inclui classes para representar os doces (modelo), um repositório para interação com o banco de dados e um controlador para gerenciar as operações CRUD. A relação entre esses componentes segue os princípios da Programação Orientada a Objetos, garantindo modularidade e reutilização de código.

## Funcionalidades

O sistema oferece as seguintes funcionalidades:

1. **Listar Todos os Doces:**
   - Endpoint: `/api/candies`
   - Método: GET

2. **Consultar Detalhes de um Doce Específico:**
   - Endpoint: `/api/candies/{id}`
   - Método: GET

3. **Adicionar Novo Doce:**
   - Endpoint: `/api/candies`
   - Método: POST
   - Exemplo de Requisição:
     ```json
     {
       "name": "Brigadeiro",
       "quantity": 10
     }
     ```

4. **Atualizar Quantidade de um Doce:**
   - Endpoint: `/api/candies/{id}`
   - Método: PUT
   - Exemplo de Requisição:
     ```json
     {
       "name": "Brigadeiro",
       "quantity": 15
     }
     ```

5. **Excluir Doce:**
   - Endpoint: `/api/candies/{id}`
   - Método: DELETE

## Instruções para Execução

1. Clone o repositório.
2. Abra o projeto em um ambiente de desenvolvimento Java, como o NetBeans.
3. Execute o projeto.
4. Utilize ferramentas como cURL, Postman ou navegadores web para interagir com os endpoints da API.

---

**Observação:** Adicione capturas de tela ou vídeos explicativos, se necessário, para facilitar a compreensão das funcionalidades.

