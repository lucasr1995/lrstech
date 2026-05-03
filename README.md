# 🖥️ LRSTech - Platform TI

Uma plataforma completa para a comunidade de Tecnologia da Informação com fórum, catálogo de programas, fichas técnicas e integração com APIs externas.

## 📋 Features

- ✅ **Fórum Comunitário** - Discussões e debates sobre TI
- ✅ **Catálogo de Programas** - Listagem completa com filtros e busca
- ✅ **Download/Distribuição** - Disponibilização segura de softwares
- ✅ **Fichas Técnicas** - Informações detalhadas via APIs externas
- ✅ **Dashboard Admin** - Gerenciamento completo
- ✅ **Sistema de Usuários** - Autenticação JWT
- ✅ **Layout Responsivo** - Mobile first design

## 🛠️ Stack Tecnológico

### Frontend
- React 18
- TypeScript
- Tailwind CSS
- React Router v6
- Axios

### Backend
- Node.js
- Express
- TypeScript
- PostgreSQL
- JWT Authentication
- Cors & Security

### DevOps
- Docker
- Docker Compose
- PostgreSQL 15
- pgAdmin 4

## 🚀 Quick Start

### Pré-requisitos
- Docker & Docker Compose
- Node.js 18+ (para desenvolvimento local)
- Git

### Instalação

```bash
# Clone o repositório
git clone https://github.com/lucasr1995/lrstech.git
cd lrstech

# Suba com Docker Compose
docker-compose up -d

# Acesse
Frontend:  http://localhost:3000
Backend:   http://localhost:3001/api
pgAdmin:   http://localhost:5050 (admin@pgadmin.org / admin)
```

### Desenvolvimento Local

```bash
# Backend
cd backend
npm install
npm run dev

# Frontend
cd frontend
npm install
npm start
```

## 📁 Estrutura do Projeto

```
lrstech/
├── backend/                    # API REST
│   ├── src/
│   │   ├── index.ts
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── middleware/
│   │   └── config/
│   ├── package.json
│   └── Dockerfile
├── frontend/                   # React App
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.tsx
│   ├── package.json
│   └── Dockerfile
├── database/                   # SQL Scripts
│   └── init.sql
├── docker-compose.yml
└── README.md
```

## 🔗 APIs Externas

- GitHub API - Dados de repositórios
- VirusTotal - Análise de segurança
- (Futuro) APIs de fichas técnicas

## 👤 Autor

**Lucas R** - [GitHub](https://github.com/lucasr1995)

## 📝 Licença

MIT License - veja LICENSE para detalhes

---

**Status**: 🟡 Em desenvolvimento | Last Updated: 2026-05-03
