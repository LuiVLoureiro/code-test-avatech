# Sistema de Login Simples com JWT

Este projeto foi projetado para demonstrar suas habilidades em uma implementação simples de autenticação utilizando **JWT (JSON Web Token)** com backend em **Node.js** e frontend em **React**.

---

## Requisitos para Testar e Enviar

### Pré-requisitos
Antes de iniciar, certifique-se de ter as seguintes ferramentas configuradas no seu sistema:
- **Node.js** (versão atual ou LTS)
- **NPM** ou **Yarn**

### Backend
- Utilize as tecnologias principais:
  - `express`
  - `jsonwebtoken`
  - `bcryptjs`
  - `cors`
  - `body-parser`
  - `dotenv`
- Crie um arquivo `.env` para armazenar variáveis de ambiente, incluindo uma chave secreta para o JWT.

### Frontend
- Tecnologias e ferramentas esperadas:
  - `React`
  - `axios` para chamadas HTTP
- Interface limpa e funcional para testar autenticação e acesso a dados protegidos.


## Rotas do Backend

1. **Registro de Usuário**
   - **Método:** `POST`
   - **Endpoint:** `/register`
   - **Descrição:** Permite registrar novos usuários. Recebe `username` e `password` como payload.
   - **Exemplo de Payload:**
     ```json
     {
       "username": "usuario",
       "password": "senha123"
     }
     ```

2. **Login**
   - **Método:** `POST`
   - **Endpoint:** `/login`
   - **Descrição:** Autentica o usuário e retorna um token JWT válido.
   - **Exemplo de Payload:**
     ```json
     {
       "username": "usuario",
       "password": "senha123"
     }
     ```

3. **Rota Protegida**
   - **Método:** `GET`
   - **Endpoint:** `/protected`
   - **Descrição:** Permite acesso somente com um token JWT válido.
   - **Exemplo de Cabeçalho:**
     ```
     Authorization: Bearer <seu_token_jwt>
     ```

---

## Frontend

A interface é **totalmente a critério do desenvolvedor**. Recomenda-se incluir:

1. **Tela de Registro**
   - Formulário para inserir `username` e `password`.

2. **Tela de Login**
   - Formulário para autenticar o usuário e armazenar o token JWT.

3. **Página Protegida**
   - Exibe conteúdo somente após autenticação bem-sucedida.

---
---

## Critérios de Avaliação
1. **Funcionalidade**:
   - A aplicação deve atender a todos os requisitos descritos.
2. **Qualidade do Código**:
   - Código bem organizado, limpo e seguindo boas práticas.
3. **Entrega no Prazo**:
   - O projeto deve ser entregue em até **3 dias** a partir do momento em que o desafio for recebido.
4. **Repositório Profissional**:
   - Submeta o projeto em um repositório público no GitHub ou GitLab com um README.md bem estruturado e explicativo.

---

## Como Enviar
1. Finalize o projeto garantindo que todas as funcionalidades estejam operacionais.
2. Suba o código em um **repositório público**.
3. Compartilhe o link do repositório antes do prazo final.

**Observação:** Não é necessário implementar funcionalidades extras, mas melhorias e toques pessoais são sempre bem-vindos.

---

## Mensagem Final
Este teste não é apenas uma avaliação técnica, mas também uma oportunidade para você demonstrar como resolve problemas, organiza seu trabalho e executa sob pressão. Use isso como uma chance para se destacar.

Boa sorte aos concorrentes! 🎯 Estamos ansiosos para ver sua solução.
