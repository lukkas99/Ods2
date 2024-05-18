# Documentação da Arquitetura

## Escolhas de Tecnologias
- **Frontend:** React
- **Backend:** Node.js com Express
- **Banco de Dados:** MongoDB
- **Hospedagem:** Heroku (ou outra plataforma de sua escolha)
- **Autenticação:** JWT (JSON Web Tokens)

## Projeto Arquitetural Elaborado

### Context Diagram (Nível 1)
- **Usuário:** Utiliza o aplicativo para cadastrar doações ou buscar alimentos.
- **Aplicativo de Doações de Alimentos:** Plataforma principal que conecta usuários e instituições.
- **Instituição de Caridade:** Recebe doações e distribui para os necessitados.

### Container Diagram (Nível 2)
- **Frontend (React):** Interface do usuário.
- **Backend (Node.js + Express):** Lógica de negócio e API REST.
- **Banco de Dados (MongoDB):** Armazenamento de dados de usuários, doações e instituições.
- **Autenticação (JWT):** Gerenciamento de autenticação e autorização.

### Component Diagram (Nível 3)
- **Frontend:**
  - Componentes de UI (Formulários de cadastro, listagem de doações, etc.)
  - Serviço de Autenticação (Comunicação com o backend)
  - Serviço de Dados (API calls para backend)
- **Backend:**
  - Controladores (Gerenciam as requisições)
  - Serviços (Implementam a lógica de negócio)
  - Modelos (Estrutura de dados)
  - Middleware (Autenticação JWT, validação de dados)
- **Banco de Dados:**
  - Collections (Usuários, Doações, Instituições)

## Justificativa do Modelo Escolhido
- **React:** Escolhido pela sua capacidade de criar interfaces de usuário interativas e reutilizáveis.
- **Node.js + Express:** Tecnologia robusta e eficiente para criar APIs RESTful.
- **MongoDB:** Banco de dados NoSQL flexível, ideal para armazenar dados não estruturados.
- **JWT:** Método seguro e amplamente utilizado para autenticação de usuários.
