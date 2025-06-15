# LockIt! – Sistema de Login com JWT

LockIt! é uma aplicação fullstack de autenticação desenvolvida com Angular no frontend e Java (Spring Boot) no backend. O foco principal é demonstrar a implementação segura de autenticação baseada em **JWT (JSON Web Tokens)**.

Este projeto simula um sistema de login e cadastro com autenticação protegida, ideal como base para sistemas mais robustos.

---

## 🛠️ Tecnologias Utilizadas

### Frontend
- Angular
- TypeScript
- SessionStorage para manter o token JWT
- Estilização básica (adicione framework se estiver usando, ex: Angular Material)

### Backend
- Java 17
- Spring Boot
- Spring Security
- JWT (com geração e validação)
- H2 Database (memória) apenas para demonstração

---

## ✨ Funcionalidades

- Cadastro de novos usuários
- Login com autenticação JWT
- Tela protegida de boas-vindas ao usuário
- Logout que remove o token da sessão

---

## 🚀 Como rodar o projeto

### Backend (Java + Spring Boot)

```bash
# Entre na pasta do backend
cd backend

# Compile e execute
./mvnw spring-boot:run
