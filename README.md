# 🐾 CachorrosPet - Portal de Raças Caninas

Projeto desenvolvido para a disciplina de **Desenvolvimento de Interfaces Web (DIW)** no curso de **Engenharia de Software da PUC Minas**. Portal funcional para consulta, gerenciamento e visualização de informações sobre raças de cachorros.

---

## 🚀 Funcionalidades

- **Autenticação por Perfil:** Login/Logout com controle de sessão via `sessionStorage`. Menu e rotas adaptados dinamicamente para perfil admin ou usuário comum.
- **Painel Administrativo:** CRUD completo de raças via REST API (POST, PUT, DELETE) exclusivo para perfil admin.
- **Busca Dinâmica:** Filtro em tempo real por nome ou descrição, com suporte a Enter e limpeza automática.
- **Sistema de Favoritos:** Persistência de favoritos por usuário logado via API com toggle assíncrono.
- **Visualização de Dados:** Gráfico de barras com Chart.js categorizando raças por nível de energia.
- **Detalhes Dinâmicos:** Carregamento de dados via parâmetro de URL (`?id=`) com galeria de fotos e favorito inline.
- **Responsividade:** Interface adaptável com Bootstrap 5 e CSS customizado com media queries e aspect-ratio.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagens:** HTML5, CSS3 e JavaScript (ES6+).
- **Framework CSS:** [Bootstrap 5.3.3](https://getbootstrap.com/).
- **Gráficos:** [Chart.js](https://www.chartjs.org/).
- **Persistência de Dados:** API simulada com **JSON Server** (Node.js).

---

## 📂 Estrutura de Pastas

```text
├── db/
│   └── db.json                  # Banco de dados simulado
├── public/
│   ├── assets/
│   │   ├── css/
│   │   │   └── style.css        # Estilização customizada
│   │   ├── imgs/                # Logos e fotos das raças
│   │   └── scripts/
│   │       ├── app.js           # Sessão, autenticação e menu dinâmico
│   │       ├── home.js          # Carousel, grid, busca e gráfico
│   │       ├── detalhes.js      # Página de detalhes da raça
│   │       ├── login.js         # Login e cadastro de usuário
│   │       └── cadastro_itens.js # CRUD admin via REST API
│   ├── index.html               # Home Page
│   ├── login.html               # Tela de Autenticação
│   ├── raca.html                # Detalhes da Raça
│   └── cadastro_itens.html      # Gestão de Raças (Admin)
├── package.json
└── README.md
```

---

## 🔐 Credenciais de Teste

| Perfil | Login | Senha |
|--------|-------|-------|
| Admin  | admin | 123   |
| Usuário | user | 123   |

---

## ⚙️ Como executar o projeto

**1. Pré-requisitos**

Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.

**2. Instalar o JSON Server**

```bash
npm install -g json-server
```

**3. Iniciar o Servidor de Dados**

```bash
json-server --watch db/db.json
```

**4. Acessar a Aplicação**

Abra o arquivo `public/index.html` no navegador.

> 💡 Recomenda-se a extensão **Live Server** do VS Code para melhor experiência.

---

## 👤 Autor

**Christiano Gonçalves Araujo**  
Engenharia de Software - PUC Minas  
[LinkedIn](https://www.linkedin.com/in/christiano-gonara) | [GitHub](https://github.com/christiano-gonara)
