API de Gerenciamento de Livros (CRUD)
Este projeto consiste em uma API REST completa desenvolvida para o Trabalho 2 da disciplina ministrada pelo professor Tiago. A aplicação permite a manipulação de um acervo de livros, realizando operações de persistência em banco de dados.

Sobre o Projeto
O objetivo do trabalho foi a implementação de um sistema CRUD (Create, Read, Update, Delete) seguindo padrões de arquitetura e boas práticas de desenvolvimento de software, garantindo a integridade dos dados e o uso correto dos protocolos de comunicação.

Tecnologias Utilizadas
Linguagem: [Inserir Linguagem, ex: Node.js]

Framework: [Inserir Framework, ex: Express]

Banco de Dados: [Inserir Banco, ex: MongoDB]

Testes e Documentação: Postman

Requisitos Técnicos Atendidos
Implementação CRUD: Endpoints GET, POST, PUT e DELETE totalmente funcionais.

Carga de Dados Inicial: Mínimo de 10 registros cadastrados para fins de teste.

Validação de Dados: Sistema de conferência de campos obrigatórios e tipos de dados.

Tratamento de Erros: Respostas padronizadas com Status Codes HTTP apropriados (200, 201, 400, 404, 500).

Organização de Código: Código fonte comentado, limpo e versionado via Git com histórico de commits.

Documentação dos Endpoints
Abaixo estão apresentadas as evidências de funcionamento da API via Postman:

Status do Servidor
Verificação da inicialização correta do ambiente.
<img width="414" height="172" alt="Servidor Rodando" src="https://github.com/user-attachments/assets/2976e0c9-c6fd-4a33-a7a8-75d6a69273f7" />

Criação de Registros (POST)
Endpoint para inserção de novos livros no banco de dados.
<img width="878" height="554" alt="POST - Criar Livros" src="https://github.com/user-attachments/assets/dd9a3db6-855c-4553-a8f7-423d845faaf2" />

Listagem de Registros (GET)
Retorno de todos os dados armazenados.
<img width="878" height="322" alt="GET - Listar Livros" src="https://github.com/user-attachments/assets/02ecf75f-bfa4-4f7a-a339-5e21ec6a4644" />

Atualização de Registros (PUT)
Modificação de informações de registros existentes por ID.
<img width="878" height="546" alt="PUT - Atualizar Livro" src="https://github.com/user-attachments/assets/c841486c-a35c-4e5c-9da8-ff8d1b566f32" />

Remoção de Registros (DELETE)
Exclusão definitiva de um registro da base de dados.
<img width="878" height="214" alt="DELETE - Remover Livro" src="https://github.com/user-attachments/assets/856d37dc-9cf3-4ab0-8923-699da1752da8" />

Instruções de Instalação e Execução
Clone este repositório para sua máquina local.

Execute o comando de instalação de dependências: npm install (ou equivalente da sua tecnologia).

Inicie o servidor de desenvolvimento.

Importe o arquivo da Collection do Postman disponível na pasta raiz para realizar os testes de requisição.

Informações de Entrega

Aluno: Mnoique Xavier de Castro Merces

Professor: Tiago
