# 🐾 CachorrosPet - Portal de Raças Caninas

Projeto desenvolvido para a disciplina de **Desenvolvimento de Interfaces Web (DIW)** no curso de **Engenharia de Software da PUC Minas**. O portal é uma aplicação funcional para consulta, gerenciamento e visualização de informações sobre raças de cachorros.

## 🚀 Funcionalidades

- **Sistema de Usuários:** Cadastro de novos usuários e sistema de Login/Logout com controle de acesso.
- **Painel Administrativo:** Área para CRUD (Criação, Leitura, Atualização e Deleção) de raças (exclusivo para perfil admin).
- **Busca Dinâmica:** Filtro de busca por nome ou descrição na página principal.
- **Visualização de Dados:** Gráfico interativo utilizando **Chart.js** para comparar níveis de energia das raças.
- **Detalhes Dinâmicos:** Página de raça que carrega informações e fotos específicas via parâmetros de URL.
- **Favoritos:** Sistema para usuários logados marcarem suas raças preferidas.
- **Responsividade:** Interface adaptável para dispositivos móveis desenvolvida com **Bootstrap 5**.

## 🛠️ Tecnologias Utilizadas

- **Linguagens:** HTML5, CSS3 e JavaScript (ES6+).
- **Framework CSS:** [Bootstrap 5.3.3](https://getbootstrap.com/).
- **Gráficos:** [Chart.js](https://www.chartjs.org/).
- **Persistência de Dados:** API simulada com **JSON Server** (Node.js).

## 📂 Estrutura de Pastas

```text
├── db/              # Banco de dados simulado (db.json)
├── public/          # Diretório principal da aplicação
│   ├── assets/      # Recursos estáticos
│   │   ├── css/     # Estilização customizada (style.css)
│   │   ├── imgs/    # Logos e fotos do sistema
│   │   └── scripts/ # Lógica JS (app.js, home.js, login.js, etc.)
│   ├── index.html   # Home Page
│   ├── login.html   # Tela de Autenticação
│   ├── raca.html    # Detalhes da Raça
│   └── cadastro_itens.html # Gestão de Raças (Admin)
├── package.json     # Configurações do Node.js
└── README.md        # Documentação do projeto
```
## ⚙️ Como executar o projeto
1. Pré-requisitos
Certifique-se de ter o Node.js instalado em sua máquina.

**2. Instalar o JSON Server**
Caso ainda não tenha o servidor globalmente, execute o comando no seu terminal:
Bash
npm install -g json-server

**3. Iniciar o Servidor de Dados**
Navegue até a pasta do projeto e inicie o monitoramento do banco de dados simulado:
Bash
json-server --watch db/db.json

**4. Acessar a Aplicação**
Com o servidor de dados rodando, abra o arquivo public/index.html no seu navegador.

Dica: Recomenda-se utilizar a extensão Live Server do VS Code para uma melhor experiência de desenvolvimento.

**Autor: Christiano Gonçalves Araujo**
Engenharia de Software - PUC Minas
