🚀 QuickPost — Rede Social Instantânea

Clone moderno do X (Twitter), criado pela comunidade [nome da comunidade] com foco em simplicidade, velocidade e compartilhamento rápido de ideias.

O QuickPost permite que usuários publiquem mensagens curtas, sigam outras pessoas, curtam postagens e visualizem um feed personalizado — tudo com uma arquitetura moderna, escalável e open-source.

📌 Visão Geral do Projeto

O QuickPost é uma plataforma social minimalista que busca reproduzir a experiência do X/Twitter com algumas melhorias, oferecendo:

📝 Postagens rápidas (texto curto)

🧑‍🤝‍🧑 Sistema de seguidores (follow/unfollow)

❤️ Curtidas em posts

📰 Feed personalizado com conteúdo dos usuários seguidos

🔐 Autenticação JWT (register/login)

🎨 Design leve e responsivo com Tailwind CSS

⚡ API REST moderna com Java + Spring Boot

🐘 Banco de dados PostgreSQL

🐳 Suporte completo a Docker / Docker Compose

O objetivo é criar uma base sólida e 100% open-source para estudo, expansão comunitária e aplicação real.

🧪 Status do Projeto

🚧 Em desenvolvimento ativo pela comunidade
Este repositório reúne a base inicial do frontend e backend, que estão sendo evoluídos aos poucos.

Qualquer pessoa pode contribuir!

🛠️ Tecnologias Utilizadas
Frontend

React (Create React App)

Tailwind CSS

JavaScript/HTML/CSS

Backend

Java 17

Spring Boot 3

Spring Security + JWT

Spring Data JPA

PostgreSQL

Maven

Docker / Docker Compose

📁 Estrutura do Repositório
/frontend
    React + Tailwind + integração com API

/backend
    Java + Spring Boot + JWT + PostgreSQL

/docs
    documentação, diagramas, anotações da comunidade

🚀 Como Rodar o Projeto Localmente
🔧 1. Clonar o repositório
git clone https://github.com/SEU_USUARIO/QuickPost.git
cd QuickPost

🖥️ Rodando o Frontend (React + Tailwind)
cd frontend
npm install
npm start


Acesse:
👉 http://localhost:3000

🛡️ Rodando o Backend (Java + Spring Boot)
Via Maven
cd backend
mvn spring-boot:run


A API sobe em:
👉 http://localhost:8000

Via Docker (recomendado)
docker-compose up --build


Isso inicia:

PostgreSQL

Backend Java

Persistência automática no volume pgdata

🔌 Principais Endpoints da API
Autenticação
POST /api/auth/register
POST /api/auth/login

Posts
POST /api/posts
GET  /api/posts/user/{username}

Feed
GET /api/feed

Follow
POST /api/users/{username}/follow
POST /api/users/{username}/unfollow


Swagger UI (documentação automática):
👉 http://localhost:8000/swagger-ui.html

🤝 Como Contribuir

O QuickPost é feito pela comunidade e para a comunidade.
Toda contribuição é bem-vinda — desde código até design, ideias, documentação ou testes.

Passos para contribuir:

Faça um fork do repositório

Crie uma branch de funcionalidade

Commit e push

Abra um Pull Request explicando sua contribuição

📌 Melhorias Planejadas (Roadmap)

🔥 Upload de imagens e suporte a mídia

💬 Comentários em posts

🔔 Sistema de notificações

🎨 Novo layout inspirado no X 2025

🌓 Tema dark/light

📱 App mobile (React Native)

🌎 Deploy em produção (Railway/Vercel/Render)

💬 Comunidade

Este projeto nasceu dentro da comunidade [nome da comunidade], com o objetivo de ensinar, aprender e construir algo grande juntos.

Participe, contribua e deixe sua marca no QuickPost! 🚀

📄 Licença

MIT — Livre para estudar, modificar e usar em seus próprios projetos.
