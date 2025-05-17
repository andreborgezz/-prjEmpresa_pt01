# -prjEmpresa_pt01

Esta API REST permite gerenciar **Departamentos** e **Funcionários** de uma empresa, com operações completas de CRUD (Criar, Ler, Atualizar e Deletar). O projeto é desenvolvido com **Java Spring Boot** e ideal para estudos e portfólio.

---

## 🛠 Tecnologias Utilizadas

- Java 17
- Spring Boot
- Maven
- MySQL 
- Postman ou Insomnia para testes de API (opcional)

---

## 📂 Entidades

### 🏢 Departamento

- `depCodigo` (Long) — Código do departamento  
- `depNome` (String) — Nome do departamento

### 👨‍💼 Funcionário

- `funCodigo` (Long) — Código do funcionário  
- `funNome` (String) — Nome do funcionário

---

## 🚀 Endpoints da API

### 📁 Departamento

- `GET /departamentos` — Lista todos os departamentos  
- `POST /departamentos` — Cria um novo departamento  
- `PUT /departamentos/{id}` — Atualiza um departamento existente  
- `DELETE /departamentos/{id}` — Remove um departamento  

### 👥 Funcionário

- `GET /funcionarios` — Lista todos os funcionários  
- `POST /funcionarios` — Cadastra um novo funcionário  
- `PUT /funcionarios/{id}` — Atualiza um funcionário existente  
- `DELETE /funcionarios/{id}` — Remove um funcionário
  
---

## 💻 Como Rodar Localmente

### Requisitos

- Java 17+
- Maven
- MySQL
- IDE (VS Code, IntelliJ, etc.)

### Passos

1. **Clone o projeto**

```bash
git clone https://github.com/seu-usuario/api-empresa.git
cd api-empresa
```

2. **Crie o banco de dados**

```sql
CREATE DATABASE db_empresa;
```

3. **Configure o `application.properties`**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/db_empresa
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha
spring.jpa.hibernate.ddl-auto=update
```

4. **Rode o projeto**

```bash
mvn spring-boot:run
```

---

## 📧 Contato

Feito por **André Borges** • Projeto para estudos de APIs REST com Java Spring Boot.
