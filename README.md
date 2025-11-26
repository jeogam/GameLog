# 🎮 GameLog | Maquete Estática

> **Disciplina:** PRG04 - Programação Web  
> **Foco:** Desenvolvimento de Interface Estática (HTML5 & CSS3)  
> **Status:** ✅ Concluído (Fase de Maquete)

---

## 📄 Sobre o Projeto

O **GameLog** é a maquete visual de uma plataforma de avaliação e catalogação de jogos.

Este projeto foi desenvolvido como atividade prática para a disciplina de Programação Web, com o objetivo exclusivo de aplicar conceitos fundamentais de **Front-end** sem o uso de frameworks ou bibliotecas externas. O foco está na estruturação semântica, estilização via CSS externo e organização de layout.

Embora seja um projeto estático, a interface foi desenhada pensando na experiência do usuário para um futuro sistema completo de reviews e backlog de games.

---

## ✨ Páginas Desenvolvidas

O projeto consiste em 3 telas principais interligadas:

* **🏠 Página Principal (`index.html`):** Apresenta o catálogo de jogos em destaque utilizando Grid Layout.
* **🔍 Página de Detalhes (`detalhes-jogo.html`):** Interface para visualização de informações do jogo (sinopse, capa) e área reservada para reviews.
* **👤 Página de Login (`login.html`):** Formulário estilizado para acesso à plataforma.

---

## 🛠 Tecnologias Utilizadas

* **HTML5:** Estrutura semântica (`header`, `main`, `section`, `footer`).
* **CSS3:**
    * Estilização externa (`style.css`).
    * Flexbox e Grid para responsividade e layout.
    * Uso de variáveis para paleta de cores.
* **Git:** Controle de versão.

---

## 📁 Estrutura de Pastas

A organização dos arquivos segue o padrão de separação de assets para facilitar a manutenção:

```bash
GameLog/
├── assets/
│   ├── css/
│   │   └── style.css      # Folha de estilos principal
│   ├── images/            # Capas de jogos e imagens do layout
│   └── icons/             # Ícones da interface e favicon
├── index.html             # Tela Inicial
├── detalhes-jogo.html     # Tela de Detalhes
└── login.html             # Tela de Login
