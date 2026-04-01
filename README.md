# 🐾 CachorrosPet - Portal de Raças Caninas

Projeto desenvolvido como Trabalho Interdisciplinar (TIAW/DIW) no curso de **Engenharia de Software da PUC Minas**. O portal é uma aplicação completa para consulta, favoritismo e gerenciamento de informações sobre raças de cachorros.

## 🚀 Funcionalidades

- **Sistema de Usuários:** Cadastro de novos usuários e sistema de Login/Logout com controle de acesso.
- **Painel Administrativo:** Área exclusiva para administradores realizarem o CRUD (Criação, Leitura, Atualização e Deleção) de raças.
- **Busca Dinâmica:** Filtro de busca por nome ou descrição na página principal.
- **Visualização de Dados:** Gráfico interativo utilizando **Chart.js** para comparar níveis de energia entre as raças.
- **Favoritos:** Sistema para que usuários logados possam marcar e gerenciar suas raças favoritas.
- **Responsividade:** Interface totalmente adaptável para dispositivos móveis utilizando **Bootstrap 5**.

## 🛠️ Tecnologias Utilizadas

- **Front-end:** HTML5, CSS3 e JavaScript (ES6+).
- **Framework CSS:** [Bootstrap 5.3.3](https://getbootstrap.com/) (Layout, Modais, Navbars e Grid).
- **Gráficos:** [Chart.js](https://www.chartjs.org/).
- **Persistência de Dados:** Integração com Mock API via **JSON Server** (Node.js).

## 📂 Estrutura do Projeto

- `index.html`: Página principal com destaques (Carousel), busca e gráficos.
- `login.html`: Interface de autenticação e criação de conta.
- `cadastro_itens.html`: Painel de gerenciamento (Somente Admin).
- `raca.html`: Detalhamento dinâmico de informações e fotos de cada raça.
- `/assets`: Pasta contendo estilos customizados, imagens e scripts de lógica (`app.js`, `home.js`, etc).

## ⚙️ Como executar o projeto

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Clone o repositório.
3. Instale o JSON Server: `npm install -g json-server`.
4. Inicie o servidor de dados: `json-server --watch db/db.json` (ou o caminho do seu arquivo .json).
5. Abra o arquivo `index.html` no seu navegador (recomenda-se o uso da extensão Live Server no VS Code).

---
**Autor:** [Christiano Gonçalves](https://www.linkedin.com/in/christiano-goncalves-araujo/)  
*Engenharia de Software - PUC Minas*
