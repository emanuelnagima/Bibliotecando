# Bibliotecando (Bibli)

O **Bibliotecando** é um sistema completo para gerenciamento do acervo da biblioteca da **Escola Prof. Oswaldo Ranazzi**, desenvolvido para uso interno. Ele foi criado para tornar o controle de empréstimos, reservas e consultas de livros mais **eficiente, seguro e organizado**, garantindo que o acervo da biblioteca esteja sempre atualizado.

O sistema permite o cadastro de **alunos, professores, usuários gerais, livros, autores e editoras**, além de gerenciar todo o ciclo de empréstimos, incluindo:

- Saídas de livros  
- Devoluções  
- Renovação de empréstimos  
- Reservas de livros  

O **Bibliotecando** também garante que apenas **exemplares disponíveis possam ser emprestados**, registra automaticamente a entrada de novos livros e realiza a baixa de exemplares descartados.

---


## Benefícios do sistema

- Automatiza processos que antes eram manuais, economizando tempo da equipe da biblioteca.  
- Melhora o controle sobre empréstimos e devoluções, evitando perdas e atrasos.  
- Facilita o planejamento de aquisições de livros, identificando os mais utilizados e os menos procurados.  
- Proporciona uma experiência organizada para alunos e professores, incentivando o uso do acervo.  

O **Bibliotecando** é, portanto, uma **solução completa, confiável e moderna** para gerenciamento de bibliotecas escolares, que alia tecnologia, segurança e praticidade para melhorar a gestão do acervo e o atendimento aos usuários.

---


# 📚 Instalção

Projeto desenvolvido para gestão de uma biblioteca, dividido em **Frontend** e **Backend**.  
Este guia explica como instalar, configurar e executar o sistema localmente.  

## 📦 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão LTS recomendada)  
- [npm](https://www.npmjs.com/)  
- Banco de dados (MySQL ou outro compatível, conforme scripts do projeto)  

---

## 🚀 Primeira instalação e execução

### 🔹 Frontend

1. Acesse a pasta do frontend:
   ```bash
   
   cd Bibliotecando/Bibli/Frontend
   
   npm install
   
   npm install react-bootstrap bootstrap
   
   npm install react-router-dom
   
   npm install react-icons
   
   chmod +x node_modules/.bin/vite (execute somente se precisar)

   npm run dev (rodar)

### 🔹 Banco de dados
 Crie um database com o nome de "biblioteca"

### 🔹 Backend

2. Acesse a pasta do backend:
   ```bash
   
   cd Bibliotecando/Bibli/Backend
   
   npm install

   npm start (rodar)

 ---
   
## 🚀 Execução normal 
1. Acesse a pasta do frontend:
   ```bash
   
   cd Bibliotecando/Bibli/Frontend
   
   npm run dev (rodar)
   

2. Acesse a pasta do backend:
   ```bash
   
   cd Bibliotecando/Bibli/Backend
   
   npm start (rodar)
