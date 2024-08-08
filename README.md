O TaskMaster Pro é uma aplicação para o gerenciamento de usuários e tarefas, onde você pode criar, editar, excluir e listar tanto usuários quanto tarefas. O sistema também permite a filtragem e ordenação das tarefas e a associação de tarefas a usuários específicos.  Funcionalidades Cadastro de Usuários: Criação, edição, exclusão e listagem de usuários. Gerenciamento de Tarefas: Criação, edição, exclusão e listagem de tarefas. Filtros e Ordenação: Filtragem de tarefas por status e ordenação por data de vencimento. Associação de Tarefas a Usuários: Atribuição de tarefas a usuários específicos. Testes: Testes unitários no back-end usando JUnit e Mockito. O front-end será testado com Jasmine e Karma. Tecnologias Utilizadas Back-end Java com Spring Boot Spring Data JPA H2 Database (ou outro banco de dados de sua escolha) JUnit e Mockito para testes Front-end Angular TypeScript HTML e CSS Jasmine e Karma para testes Requisitos Java 11 ou superior Maven ou Gradle para gerenciamento de dependências Node.js e npm para o front-end com Angular Angular CLI para o desenvolvimento do front-end


taskmaster-pro/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/exemplo/taskmasterpro/
│   │   │   └── resources/
│   └── pom.xml
└── frontend/
    ├── src/
    └── angular.json
