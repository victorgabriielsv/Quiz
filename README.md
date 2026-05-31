# 🧠 Quiz Interativo: IA & Empregabilidade

<p align="center">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  <strong>Um web app de quiz dinâmico, focado na conscientização e debate sobre o impacto da Inteligência Artificial no mercado de trabalho atual.</strong>
</p>

---

## 💻 Sobre o Projeto

Este é um web app interativo de **Nível Difícil** projetado no estilo de plataformas de gamificação como o *Kahoot*. O objetivo principal é desafiar profissionais e estudantes sobre como os algoritmos de contratação (ATS), o viés algorítmico, a Inteligência Aumentada e as competências socioemocionais moldam a empregabilidade moderna.

Para quebrar a tensão do nível avançado das perguntas, a interface renderiza **memes dinâmicos** a cada nova questão, unindo conhecimento técnico e humor de forma fluida.

> 🌐 **Precisa de uma demonstração?** Se você fez o deploy (ex: GitHub Pages), coloque o link aqui!

---

## 🚀 Principais Funcionalidades

* **Banco de Dados Crítico (10 Questões):** Discussões profundas sobre *Applicant Tracking Systems* (ATS), Aprendizagem Adaptativa, Processamento de Linguagem Natural (NLP) e impactos éticos/desigualdade no acesso à tecnologia.
* **Mecânica de Game Show:**
  * Cores vibrantes e formas geométricas nas alternativas para rápida identificação.
  * Temporizador regressivo estrito de **25 segundos** por rodada.
  * Sistema de feedback visual instantâneo (Verde para acerto, Vermelho para erro) acompanhado de uma **justificativa teórica**.
* **Gamificação de Resultados:** Painel final que calcula o desempenho do usuário, exibindo títulos ("Perfeito!", "Excelente!", "Mediano") e um sistema de classificação por estrelas.
* **Interface Responsiva:** Layout adaptável via *CSS Grid* e *Flexbox*, ideal para rodar direto no celular ou no desktop.

---

## 🛠️ Arquitetura e Tecnologias

Buscando máxima performance e sem dependências externas (Zero Frameworks / Pure Vanilla):

* **HTML5:** Estruturação semântica e divisão de telas por estados (`.screen`).
* **CSS3:** Estilização em *Dark Mode*, transições suaves de opacidade e interface baseada no padrão moderno de componentes UI.
* **JavaScript (ES6):**
  * Lógica de estado de jogo (perguntas atuais, score e fluxo de telas).
  * Manipulação dinâmica do DOM para injeção de dados.
  * Temporizador assíncrono baseado em `setInterval`.

---

## 📁 Estrutura de Arquivos

Como o projeto é direto e otimizado, ele roda inteiramente em um arquivo único estruturado da seguinte forma:

```text
├── quiz.html        # Estrutura (HTML), Estilos (CSS) e Inteligência do App (JS)
└── README.md        # Documentação do projeto
