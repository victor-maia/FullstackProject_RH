# Gerenciamento de Funcionários - Fullstack Project📋👨‍💼👩‍💼

Este projeto consiste em uma aplicação completa para o gerenciamento de informações de funcionários, com backend desenvolvido em .NET e frontend em Angular. O sistema oferece funcionalidades para criar, visualizar, atualizar, inativar e excluir registros de funcionários.

## Funcionalidades Principais 🛠️

1. **Visualizar Funcionários** 📜
   - Exibe uma lista de todos os funcionários registrados na base de dados.
   - Rota: `/funcionarios`

2. **Detalhes do Funcionário** 🔍
   - Exibe os detalhes de um funcionário específico com base no ID fornecido.
   - Rota: `/funcionarios/{id}`

3. **Cadastrar Novo Funcionário** 📝
   - Permite criar um novo registro de funcionário com os dados fornecidos.
   - Rota: `/cadastro`

4. **Editar Funcionário** ✏️
   - Permite atualizar os detalhes de um funcionário existente.
   - Rota: `/editar/{id}`

5. **Inativar Funcionário** 🚫
   - Permite inativar o registro de um funcionário específico com base no ID fornecido.
   - Rota: `/funcionarios/inativar/{id}`

6. **Excluir Funcionário** 🗑️
   - Permite excluir o registro de um funcionário específico com base no ID fornecido.
   - Rota: `/funcionarios/excluir/{id}`

## Backend

### Endpoints da API

1. **GetFuncionarios** 📜
   - Método: GET
   - Rota: `/api/funcionario`
   - Descrição: Retorna uma lista de todos os funcionários registrados na base de dados.

2. **GetFuncionarioById** 🔍
   - Método: GET
   - Rota: `/api/funcionario/{id}`
   - Descrição: Retorna os detalhes de um funcionário específico com base no ID fornecido.

3. **CreateFuncionarios** 📝
   - Método: POST
   - Rota: `/api/funcionario`
   - Descrição: Cria um novo registro de funcionário com os dados fornecidos no corpo da requisição.

4. **InativaFuncionario** 🚫
   - Método: PUT
   - Rota: `/api/funcionario/{id}`
   - Descrição: Inativa o registro de um funcionário específico com base no ID fornecido.

5. **UpdateFuncionario** ✏️
   - Método: PUT
   - Rota: `/api/funcionario`
   - Descrição: Atualiza os detalhes de um funcionário com os dados fornecidos no corpo da requisição.

6. **DeleteFuncionario** 🗑️
   - Método: DELETE
   - Rota: `/api/funcionario/{id}`
   - Descrição: Exclui o registro de um funcionário específico com base no ID fornecido.
