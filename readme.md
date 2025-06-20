# InfinityTech

InfinityTech é uma API RESTful desenvolvida com React/TypeScript e Java/Spring Boot. Seu objetivo é monitorar falhas na
API Di2win ExtrAI Dados, fornecendo relatórios detalhados sobre erros e desempenho.

## Referência da API

- **URL Base:** https://api.infinitytech.com
- **Formato dos Dados:** JSON para requisições e respostas.
- **Autenticação:** _A ser definido_
- **Códigos de Status:**
  - 200 OK: Requisição processada com sucesso.
  - 201 Created: Recurso criado com sucesso.
  - 400 Bad Request: Erro na requisição (ex: parâmetros incorretos).
  - 404 Not Found: Arquivo ou recurso não encontrado.
  - 500 Internal Server Error: Erro interno do servidor.

## Funcionalidades

- Dashboard com gráficos e indicadores
- Tabela detalhada de erros
- Filtros de data e busca
- Download de relatórios
- Notificações de erro em tempo real

## Tecnologias

### Frontend

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

[![Ant Design](https://img.shields.io/badge/Ant%20Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white)](https://ant.design/)

[![PNPM](https://img.shields.io/badge/pnpm-22272E?style=for-the-badge&logo=pnpm&logoColor=F69220)](https://pnpm.io/)

### Backend

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com/)

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

[![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)](https://maven.apache.org/)

## Pré-requisitos

### Frontend

- Instale o [Node.js](https://nodejs.org/en) (versão 18 ou superior)
- Instale o pnpm: `npm install -g pnpm`

### Backend

- Instale o [Java 17 ou superior](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- Instale o [Maven](https://maven.apache.org/)
- Instale o [PostgreSQL](https://www.postgresql.org/download/)
- Recomenda-se iniciar o projeto backend usando o [Spring Initializr](https://start.spring.io/)

## Guia de Instalação

- Clone o repositório: https://github.com/zcriticz/infinitytech.git

- Abra o projeto no seu editor de código favorito (recomendamos
  o [IntelliJ IDEA](https://www.jetbrains.com/idea/download/))

### Frontend

- No terminal, acesse a pasta `frontend` e execute:

   ```bash
   pnpm install
   pnpm run dev# InfinityTech

### Backend

Para o backend, abra o terminal na pasta do projeto e execute:

`mvn spring-boot:run`

- Para mais detalhes, consulte a documentação do Spring Boot. Você pode encontrá-la no arquivo `pom.xml` do projeto.

- Certifique-se de que o PostgreSQL está em execução e devidamente configurado.

## Guia de Contribuição

Contribuições são bem-vindas! Para contribuir, siga estes passos:

1. Faça um fork deste repositório.
2. Crie um novo branch para sua feature ou correção: git checkout -b feature/sua-feature
3. Faça suas alterações e faça commit com mensagens claras.
4. Envie seu branch: git push origin feature/sua-feature
5. Abra um Pull Request descrevendo suas alterações.
6. Por favor, garanta que seu código siga o estilo do projeto e inclua testes quando aplicável.

## Autores

- Vitor Marins - Desenvolvedor Frontend
- Vinicius Gabriel - Desenvolvedor Frontend
- Luciano Tomaz - Desenvolvedor Frontend
- Cristian Santos - Desenvolvedor Backend
- Gabriela Pires - Desenvolvedora Backend
- Pedro Vitor - Banco de Dados
- Rayra Lima - Banco de Dados

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.