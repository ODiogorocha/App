# 🛍️ E-commerce App

Aplicativo mobile de e-commerce desenvolvido com **Node.js**, **Cordova** e tecnologias web (HTML, CSS, JavaScript), com arquitetura **fullstack (front-end e back-end)**, integração com banco de dados e compatível com dispositivos móveis.

## 📌 Tecnologias Utilizadas

- **Visual Studio Code** – Ambiente de desenvolvimento
- **Node.js** – Execução de scripts no back-end
- **Cordova** – Empacotamento para Android/iOS
- **HTML5, CSS3 e JavaScript** – Estrutura, estilo e lógica do front-end
- **Express.js** – Framework para o servidor Node.js
- **Banco de Dados** – (ex: MongoDB, MySQL, SQLite – substitua pelo seu)
- **Axios / Fetch API** – Comunicação entre front e back-end

## 🚧 Estrutura do Projeto

```
ecommerce-app/
│
├── backend/                # Lógica de servidor Node.js
│   ├── server.js
│   ├── routes/
│   └── controllers/
│
├── frontend/               # Interface feita com HTML, CSS e JS
│   ├── index.html
│   ├── style.css
│   └── app.js
│
├── database/              # Scripts de banco de dados
│   └── db.js
│
├── config/                # Arquivos de configuração
│   └── cordova.config.js
│
├── hooks/                 # Cordova hooks
│
├── platforms/             # Plataformas geradas pelo Cordova
│
├── plugins/               # Plugins Cordova utilizados
│
├── package.json           # Dependências do Node.js
└── README.md
```

## ⚙️ Como Executar o Projeto

### Pré-requisitos

- Node.js e npm instalados
- Cordova instalado globalmente:  
  ```bash
  npm install -g cordova
  ```

### 1. Instalar dependências

```bash
npm install
```

### 2. Rodar o servidor back-end

```bash
cd backend
node server.js
```

### 3. Iniciar o Cordova

```bash
cordova platform add android
cordova build android
cordova emulate android
```

> Ou use `cordova run android` para rodar direto em um dispositivo físico.

---

## 🧠 Funcionalidades

- Cadastro e login de usuários
- Listagem de produtos com imagens
- Carrinho de compras
- Integração com banco de dados
- Comunicação entre front-end e back-end via API REST
- Layout responsivo adaptado para mobile

---

## 🔒 Segurança

- Senhas armazenadas com hash
- Proteção contra requisições maliciosas no back-end
- Validação de formulários no front-end

---

## 💡 Próximos Passos

- Integração com gateways de pagamento
- Histórico de pedidos
- Sistema de avaliação de produtos
- Painel administrativo

---


