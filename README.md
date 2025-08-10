# 📋 API de Tarefas

API REST desenvolvida em **Spring Boot** para gerenciamento de tarefas, com operações **CRUD** (Create, Read, Update, Delete).

---

## 🚀 Tecnologias utilizadas
- ☕ Java 17
- 🌱 Spring Boot
- 🗄️ Spring Data JPA
- 🐬 MySQL
- 📦 Maven

---

## 📂 Estrutura do Projeto
src/main/java/com/vinicius/api_tarefas
├── controller # Endpoints da API
├── model # Entidades do banco
├── repository # Interfaces de acesso ao banco
└── ApiTarefasApplication.java


---

## ⚙️ Endpoints da API

| Método | Endpoint       | Descrição                   |
|--------|----------------|-----------------------------|
| GET    | `/tarefas`     | Lista todas as tarefas      |
| GET    | `/tarefas/{id}`| Busca tarefa por ID         |
| POST   | `/tarefas`     | Cria uma nova tarefa        |
| PUT    | `/tarefas/{id}`| Atualiza uma tarefa         |
| DELETE | `/tarefas/{id}`| Remove uma tarefa           |

---

## 📦 Como executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Vinisantas/ApiTarefa.git
Configure o banco de dados
No arquivo application.properties:

properties
Copiar
Editar
spring.datasource.url=jdbc:mysql://localhost:3306/api_tarefas
spring.datasource.username=SEU_USUARIO
spring.datasource.password=SUA_SENHA
spring.jpa.hibernate.ddl-auto=update
Execute o projeto

bash
Copiar
Editar
mvn spring-boot:run
Acesse a API


http://localhost:8080/tarefas


---

📝 Licença
Este projeto está licenciado sob a licença MIT.


