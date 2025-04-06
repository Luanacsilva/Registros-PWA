# 🗂️ Registros PWA — Aplicativo Progressivo com Frontend + Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


**Registros PWA** é uma aplicação web progressiva completa, com backend em Node.js + Express e frontend com funcionalidades de Progressive Web App (PWA), incluindo suporte a instalação, cache offline e estrutura modular.

Este projeto foi construído com foco em demonstrar habilidades práticas de:
- Arquitetura fullstack (client/server)
- Organização RESTful
- Desenvolvimento de PWAs modernos
- Separação clara entre frontend e backend

---

## 🌐 O que é um PWA?

Um **Progressive Web App (PWA)** é uma aplicação web que combina o melhor das páginas web com a experiência dos apps nativos.  
Características:
- Pode ser instalada como app no dispositivo
- Funciona offline (ou com conexão limitada)
- Carregamento rápido com cache via **Service Worker**
- Utiliza um **manifesto** para definição de comportamento, nome, ícone, etc.

---

## 🚀 Funcionalidades

- Backend com Node.js + Express
- Estrutura RESTful com controllers, routes, middlewares e models
- Frontend com HTML, CSS e JavaScript
- Manifesto configurado para tornar o app instalável
- Service Worker para caching e funcionamento offline

---

## 🛠️ Tecnologias Utilizadas

- Node.js
- Express
- JavaScript
- HTML + CSS
- PWA (Manifest + Service Worker)

---

## 🗂 Estrutura do Projeto

```bash
Registros-PWA/
├── Backend/ # API RESTful com Node.js 
├── controllers/ 
├── middleware/ 
├── models/ 
├── routes/ 
├── utils/ 
├── logs/
├── server.js
│ └── package.json 
├── Frontend/ # Interface + lógica PWA 
├── pages/ 
├── scripts/ 
├── app.js 
├── index.html
├── manifest.json 
├── pwa.manifest 
├── service.worker.js 
 └── style.css
```
---


---

## 🧪 Como Executar o Projeto

1. Clone o repositório

```bash
git clone https://github.com/Luanacsilva/Registros-PWA.git
cd Registros-PWA
```

2. Inicie o Backend
   
```bash
cd Backend
npm install
node server.js
```
O servidor irá rodar normalmente em http://localhost:3000

---

## 💻 Como Rodar o Frontend + Instalar o App

Abra o arquivo index.html dentro da pasta Frontend/ com um servidor local (recomendo Live Server no VS Code)

Acesse no navegador (preferencialmente Chrome ou Edge)

Ao abrir, você verá o botão "Instalar aplicativo" na barra de navegação

Pronto! O app estará disponível como se fosse um app nativo no seu dispositivo

---

## 👩‍💻 Autora

Luana Cristina da Silva

---

## ⚖️ Licença

MIT 

---






