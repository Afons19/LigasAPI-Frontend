# Documentação do Frontend
---
# LigasAPI-Frontend
# ⚽ Sistema de Gestão de Ligas Desportivas — Frontend

![Vue](https://img.shields.io/badge/Vue.js-3.x-42b883)
![Vite](https://img.shields.io/badge/Vite-fast-yellow)
![Status](https://img.shields.io/badge/Project-Academic-blue)
![License](https://img.shields.io/badge/License-Educational-green)

**Ano letivo: 2025/2026**  
Frontend desenvolvido com a API de gestão de ligas desportivas (futebol), integrado com API REST em Django.

---

## 1. 📌 Visão Geral

Aplicação frontend construída com **Vue.js 3** e **Vite**, consumindo uma **API REST pública** desenvolvida em **Django REST Framework**.

Permite:
- Visualizar ligas, equipas, jogadores e jogos  
- Gerir dados através de uma interface administrativa  
- Navegar de forma clara e intuitiva  

**Objetivos principais:**
- Simplicidade  
- Clareza visual  
- Separação de responsabilidades  
- Integração correta com o backend  

---

## 2. 🛠️ Tecnologias Utilizadas

- **Vue.js 3**
- **Vite**
- **Vue Router**
- **Axios**
- **CSS puro**

---

## 3. 🗂️ Estrutura do Projeto

```
frontend/
└── src/
    ├── assets/
    │   └── style.css
    ├── componentes/
    │   ├── Navbar.vue
    │   ├── StatCard.vue
    │   └── LigaCard.vue
    ├── router/
    │   └── router.js
    ├── services/
    │   └── api.js
    └── views/
        ├── Home.vue
        ├── Gerenciar.vue
        ├── LigaDetalhe.vue
        ├── EquipaDetalhe.vue
        └── JogadorDetalhe.vue
```

---

## 4. 🧩 Organização do Código

### `assets/`
Estilos globais da aplicação.

### `services/api.js`
Centraliza comunicação com a API:
- URL base
- Chamadas HTTP
- Manutenção e escalabilidade

### `router/router.js`
Gerencia as rotas:
- `/`
- `/gerenciar`
- `/ligas/:id`
- `/equipas/:id`
- `/jogadores/:id`

---

## 5. 🧱 Componentes Reutilizáveis

### Navbar
- Navegação global

### StatCard
- Estatísticas:
  - Ligas
  - Equipas
  - Jogadores
  - Jogos

### LigaCard
- Exibe informações de uma liga e seus jogos

---

## 6. 🖥️ Views (Páginas)

### Home.vue
- Estatísticas globais
- Ligas, jogos e equipas
- Navegação para detalhes

### Gerenciar.vue
- CRUD completo:
  - Ligas
  - Equipas
  - Jogadores
  - Jogos

### LigaDetalhe.vue
- Dados detalhados da liga

### EquipaDetalhe.vue
- Dados da equipa
- Tabela de jogadores

### JogadorDetalhe.vue
- Dados completos do jogador

---

## 7. 🔗 Integração com o Backend

| Funcionalidade | Endpoint          |
|----------------|-------------------|
| Ligas          | `/api/ligas/`     |
| Equipas        | `/api/equipas/`   |
| Jogadores      | `/api/jogadores/` |
| Jogos          | `/api/jogos/`     |

Os dados retornados pelos serializers são utilizados diretamente para otimizar o desempenho.

---

## 8. ⚙ Instalação e Execução

1. Clone o repositório: git clone [https://github.com/Afons19/LigasAPI-Frontend.git](https://github.com/Afons19/LigasAPI-Frontend.git)

```bash
# Instalar dependências
npm install
npm install axios
npm install vue-router

# Executar servidor de desenvolvimento
npm run dev
```

A aplicação estará disponível em:

```
http://localhost:5173
```

---

## 🎓 Projeto Académico

Este projeto foi desenvolvido para fins académicos no âmbito da unidade curricular de desenvolvimento web, cumprindo boas práticas de organização, modularidade e integração frontend-backend.

---

## 🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias abrindo um problema ou enviando um pull request.

---

## 📄 Licença

Este projeto é licenciado sob a Licença MIT.
---

# LigasAPI-Frontend
# ⚽ Sports League Management System — Frontend

![Vue](https://img.shields.io/badge/Vue.js-3.x-42b883)
![Vite](https://img.shields.io/badge/Vite-fast-yellow)
![Status](https://img.shields.io/badge/Project-Academic-blue)
![License](https://img.shields.io/badge/License-Educational-green)

**Academic Year: 2025/2026**  
Frontend developed for the sports league management API (football), integrated with a Django REST API.

---

## 1. 📌 Overview

Frontend application built with **Vue.js 3** and **Vite**, consuming a **public REST API** developed with **Django REST Framework**.

Allows:
- Viewing leagues, teams, players and matches
- Managing data through an administrative interface
- Clear and intuitive navigation

**Main objectives:**
- Simplicity
- Visual clarity
- Separation of responsibilities
- Proper integration with the backend

---

## 2. 🛠️ Technologies Used

- **Vue.js 3**
- **Vite**
- **Vue Router**
- **Axios**
- **Pure CSS**

---

## 3. 🗂️ Project Structure

```
frontend/
└── src/
    ├── assets/
    │   └── style.css
    ├── components/
    │   ├── Navbar.vue
    │   ├── StatCard.vue
    │   └── LeagueCard.vue
    ├── router/
    │   └── router.js
    ├── services/
    │   └── api.js
    └── views/
        ├── Home.vue
        ├── Gerenciar.vue
        ├── LigaDetelhe.vue
        ├── EquipaDetalhe.vue
        └── JogadorDetalhe.vue
```

---

## 4. 🧩 Code Organization

### `assets/`
Global application styles.

### `services/api.js`
Centralizes API communication:
- Base URL
- HTTP calls
- Maintenance and scalability

### `router/router.js`
Manages routes:
- `/`
- `/manage`
- `/ligas/:id`
- `/equipas/:id`
- `/jogadores/:id`

---

## 5. 🧱 Reusable Components

### Navbar
- Global navigation

### StatCard
- Statistics:
  - Leagues
  - Teams
  - Players
  - Matches

### LigaCard
- Displays league information and its matches

---

## 6. 🖥️ Views (Pages)

### Home.vue
- Global statistics
- Leagues, matches and teams
- Navigation to details

### Gerenciar.vue
- Full CRUD:
  - Leagues
  - Teams
  - Players
  - Matches

### LigaDetalhe.vue
- Detailed league data

### EquipaDetalhe.vue
- Team data
- Player table

### JogadorDetalhe.vue
- Complete player data

---

## 7. 🔗 Backend Integration

| Feature      | Endpoint           |
|--------------|--------------------|
| Ligas        | `/api/ligas/`      |
| Equipas      | `/api/equipas/`    |
| Jogadores    | `/api/jogadores/`  |
| Jogos        | `/api/jogos/`      |

Data returned by serializers is used directly to optimize performance.

---

## 🚀 Installation and Execution

1. Clone the repository: [https://github.com/Afons19/LigasAPI-Frontend.git](https://github.com/Afons19/LigasAPI-Frontend.git)

```bash
# Install dependencies
npm install
npm install axios
npm install vue-router

# Run development server
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

---

## 🎓 Academic Project

This project was developed for academic purposes within the web development course unit, following best practices for organization, modularity and frontend-backend integration.

---

## 🤝 Contribution

Feel free to contribute with improvements by opening an issue or submitting a pull request.

---

## 📄 License

This project is licensed under the MIT License.