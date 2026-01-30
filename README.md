# 🎮 Jogo do Número Secreto

<p align="center">
  <img src="img/ia.png" alt="Logo do Jogo" width="200">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

## 📋 Sobre o Projeto

O **Jogo do Número Secreto** é uma aplicação interativa desenvolvida para consolidar conceitos fundamentais de lógica de programação e versionamento de código. O projeto foi construído durante a trilha de aprendizado da Alura, especificamente nos cursos:
- **Lógica de programação: mergulhe em programação com JavaScript**
- **Git e GitHub: compartilhando e colaborando em projetos**

No jogo, o sistema gera um número aleatório e o usuário deve tentar adivinhá-lo, recebendo dicas se o número secreto é maior ou menor que o chute atual.

## 🚀 Funcionalidades

- **Geração de Números Aleatórios:** O sistema sorteia um número entre 1 e 100 sem repeti-los imediatamente em rodadas consecutivas.
- **Feedback em Tempo Real:** Indica se o número secreto é maior ou menor que o palpite do usuário.
- **Contador de Tentativas:** Mostra quantas vezes o usuário tentou antes de acertar.
- **Acessibilidade (Web Speech API):** O jogo utiliza síntese de voz para narrar as instruções e os resultados, tornando a experiência mais imersiva.
- **Reinicialização Dinâmica:** Permite iniciar uma nova partida sem recarregar a página.

## 🛠️ Tecnologias Utilizadas

- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) - Lógica principal e manipulação do DOM.
- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) - Estrutura da página.
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) - Estilização e layout responsivo.
- [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) - Recurso de narração por voz.
- [Google Fonts](https://fonts.google.com/) - Fontes *Chakra Petch* e *Inter*.

## 🔧 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-numero-secreto.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd jogo-numero-secreto
   ```
3. Abra o arquivo `index.html` em seu navegador de preferência.

## 📂 Estrutura de Arquivos

```text
├── app.js          # Lógica do jogo em JavaScript
├── index.html      # Estrutura principal da interface
├── style.css       # Estilização visual (CSS)
├── img/            # Ativos visuais (imagens e ícones)
└── temp/           # Códigos didáticos de apoio
```

## 🧠 Aprendizados

Este projeto foi fundamental para praticar:
- Manipulação de elementos HTML através do JavaScript (`document.querySelector`).
- Uso de funções com parâmetros e retornos.
- Estruturas condicionais (`if/else`) e operadores ternários.
- Gerenciamento de listas (Arrays) e geração de números aleatórios.
- Boas práticas de versionamento com Git (Commits, Branches e Push).
