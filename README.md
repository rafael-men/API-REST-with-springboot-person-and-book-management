# REST API with Spring Boot

Este é um projeto de exemplo de uma API RESTful completa construída com **Spring Boot**. A API oferece funcionalidades básicas para gerenciamento de pessoas, livros e usuários.

---

## 🛠️ Tecnologias Utilizadas

- **Spring Boot**
- **Spring Data JPA**
- **Spring Web**
- **Banco de Dados PostgreSQL**
- **Maven**
- **Hibernate**
- **Flyway**
- **Docker**

---

## 🚀 Funcionalidades

A API oferece as seguintes funcionalidades:

- **CRUD (Create, Read, Update, Delete)** para recursos principais.
- **Autenticação de usuários**.
- **Endpoints bem documentados** com Swagger.

---

## 🐳 Passo a Passo para Executar o Projeto com Docker Compose

A seguir, apresentamos um passo a passo detalhado para executar o projeto utilizando **Docker Compose**. Este processo inclui a configuração do ambiente para o **backend** e **banco de dados**, bem como a inicialização do sistema.

### ✅ Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas na sua máquina:
- **Docker**: Para conteinerização da aplicação.
- **Docker Compose**: Para orquestração dos contêineres.

### 🛠️ Construção e Execução do Projeto

1. **Clone o repositório** (se ainda não tiver feito):
   ```bash
   git clone https://github.com/seu-repositorio/api-springboot.git
   cd api-springboot
2.**Execute o Comando a seguir na pasta anterior a raíz do projeto:**
```bash
docker-compose up --build


