# 🍕 Pizzaria Sabor da Itália

Sistema web desenvolvido para a **Pizzaria Sabor da Itália**, com interface moderna e integração completa utilizando **Spring Boot**, **Thymeleaf**, **Bootstrap 5** e **MySQL**.

---

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot 3**
- **Spring MVC**
- **Spring Data JPA**
- **Thymeleaf**
- **Bootstrap 5**
- **HTML5 / CSS3 / JavaScript**
- **MySQL**
- **Maven**

---

## 📁 Estrutura do Projeto
pizzaria-sabor-da-italia/
│
├── src/
│ ├── main/
│ │ ├── java/com/pizzaria/
│ │ │ ├── controller/ # Controladores (Pages e APIs)
│ │ │ ├── model/ # Entidades (Cliente, Pedido, Produto)
│ │ │ ├── repository/ # Repositórios JPA
│ │ │ └── service/ # Camada de regras de negócio
│ │ │
│ │ └── resources/
│ │ ├── templates/ # Páginas HTML (Thymeleaf)
│ │ │ ├── index.html
│ │ │ ├── login.html
│ │ │ ├── clientes.html
│ │ │ └── pedidos.html
│ │ ├── static/ # CSS, JS, imagens
│ │ └── application.properties
│ │
│ └── test/java/ # Testes automatizados (JUnit)
│
├── pom.xml
└── README.md
🖥️ Páginas do Sistema
🏠 Página Inicial (index.html)

Bem-vindo à pizzaria, com botões para:

Fazer pedidos

Acessar área do cliente

🔐 Login (login.html)

Tela de autenticação de usuário com validação e mensagem de erro (th:if="${loginError}").

👥 Clientes (clientes.html)

Formulário para cadastro de clientes:

Nome

Telefone

Endereço

🧾 Pedidos (pedidos.html)

Cadastro de pedidos com:

Nome do cliente

Produto

Forma de pagamento (Dinheiro, Cartão, Pix)
🧩 Navegação (Navbar)

Em todas as páginas:

Home | Clientes | Pedidos | Sair
🧠 Princípios Aplicados

SOLID – Separação de responsabilidades entre Controller, Service e Repository.

Clean Code – Código legível e modular.

Boas práticas MVC – Camadas bem definidas e reutilizáveis.
🧪 Testes

O projeto contém testes unitários com JUnit 5.
Execute com:

mvn test
👨‍💻 Desenvolvido por

Alexandre Garcia Martins
Desenvolvido com ❤️ utilizando AGM//SOFTWARE

📸 Interface
Página Inicial

© 2025 - Pizzaria Sabor da Itália | Todos os direitos reservados.
