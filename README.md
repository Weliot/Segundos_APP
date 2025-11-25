# ⏱️ Segundos APP

Uma aplicação Full-Stack desenvolvida para gerenciar e cronometrar o tempo de estudos, permitindo aos usuários monitorar seu desempenho e visualizar o histórico de horas dedicadas.

## 🚀 Tecnologias Utilizadas

### 🎨 Front-End
O front-end foi construído utilizando **React** com **TypeScript**, focando em tipagem estática e componentes modernos.

* **Core:** React 19, TypeScript 4.9
* **Estilização e UI:**
    * **Material UI (MUI v7):** Biblioteca principal de componentes.
    * **Bootstrap 5 & React-Bootstrap:** Utilizado para grid system e componentes auxiliares.
    * **Emotion:** Engine de estilização (CSS-in-JS).
    * **Roboto Font:** Tipografia padrão.
* **Visualização de Dados:**
    * **MUI X Charts:** Para geração de gráficos de desempenho e horas estudadas.
* **Comunicação:**
    * **Axios:** Cliente HTTP para requisições à API.
* **Ferramentas:** Create React App (react-scripts).

### ⚙️ Back-End (API)
A API foi desenvolvida em **Java 24** com **Spring Boot 3.5**, garantindo alta performance e recursos de linguagem de ponta.

* **Framework:** Spring Boot 3.5.4 (Web, Validation, DevTools).
* **Linguagem:** Java 24.
* **Banco de Dados & ORM:**
    * **MySQL:** Banco de dados relacional (Driver `mysql-connector-j`).
    * **Spring Data JPA:** Camada de persistência e abstração de SQL.
* **Segurança:**
    * **JWT (JSON Web Token):** Implementação segura de autenticação (`jjwt-api`, `jjwt-impl`).
    * **Spring Security Crypto:** Para criptografia de senhas.
* **Documentação de API:**
    * **SpringDoc OpenAPI (Swagger UI):** Documentação interativa dos endpoints.
    * **Spring REST Docs:** Documentação baseada em testes.
* **Ferramentas:**
    * **Lombok:** Redução de código boilerplate.
    * **Maven:** Gerenciador de dependências e build.

## 📦 Instalação e Execução

### Pré-requisitos
* Node.js e npm
* JDK 24
* MySQL Server

### Rodando a API (Back-End)
1.  Navegue até a pasta do servidor.
2.  Configure o banco de dados no `application.properties`.
3.  Execute o projeto:
    ```bash
    mvn spring-boot:run
    ```
    A documentação Swagger estará disponível em: `http://localhost:8080/swagger-ui.html` (padrão).

### Rodando o Cliente (Front-End)
1.  Navegue até a pasta do front-end.
2.  Instale as dependências:
    ```bash
    npm install
    ```
3.  Inicie a aplicação:
    ```bash
    npm start
    ```
    Acesse em: `http://localhost:3000`

## 🧪 Testes

* **Front-end:** Testes configurados com *React Testing Library* e *Jest*.
* **Back-end:** Testes unitários e de integração com *JUnit 5* e *Spring Boot Starter Test*.

---
Desenvolvido por João Mendes
