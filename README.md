# 🐍 Snake Battle - Snakeon

**Snake Battle** é uma versão moderna e competitiva do clássico jogo da cobrinha, desenvolvida inteiramente em HTML5 e JavaScript puro (Vanilla JS). O foco é uma experiência "Plug & Play", rodando diretamente no navegador sem necessidade de instalação de dependências.

> **Nota do Desenvolvedor**: Este projeto é um marco pessoal, sendo o **primeiro jogo que desenvolvi com integração server-side e banco de dados**! 🚀

## 🎮 Funcionalidades Principais

*   **Modo PvE (Player vs CPU)**: Enfrente uma Inteligência Artificial que joga contra você.
*   **Condição de Vitória**: O primeiro a atingir **500 pontos** vence a partida!
*   **Ranking Global**: Sistema de High Scores integrado a uma API Backend, persistindo os top 10 melhores tempos.
*   **Controles Híbridos**:
    *   💻 **Desktop**: Teclado (WASD ou Setas).
    *   📱 **Mobile**: D-Pad virtual estilo Gameboy e layout responsivo.
*   **Design Responsivo**: Adapta-se automaticamente a telas de desktops e dispositivos móveis.
*   **Efeitos Visuais**: Animações de morte, contagem de tempo precisa e interface estilo arcade.
*   **Zero Dependências**: Tudo contido em um único arquivo `snake.html`.

## 🕹️ Como Jogar

### Objetivo
Coma as frutas 🍎 para crescer e ganhar pontos. Evite bater nas paredes, no seu próprio corpo ou no oponente.

### Controles
*   **Setas Direcionais** ou **W, A, S, D**: Movem a cobra.
*   **D-Pad Virtual (Celular)**: Toque nos botões na tela para controlar.

### Regras
1.  Cada fruta vale **10 pontos**.
2.  Se você bater na parede ou em uma cobra: **Game Over**.
3.  Se a CPU bater, os pontos dela são transferidos para você!
4.  **Vitória**: Alcance 500 pontos antes da CPU.

## 🛠️ Tecnologias Utilizadas

*   **Frontend**: HTML5, CSS3, JavaScript (ES6+).
*   **Rendering**: HTML5 Canvas API para gráficos de alta performance.
*   **Backend**: Integração via `fetch` API com Cloudflare Workers (para ranking).
*   **Fonte**: 'Press Start 2P' (Google Fonts) para estética 8-bit.

## 🚀 Como Rodar

Basta abrir o arquivo `snake.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari, Opera no celular).

Para testar localmente:
1.  Clone ou baixe a pasta.
2.  Dê dois cliques em `snake.html`.

## 📂 Estrutura do Projeto

*   `snake.html`: Contém todo o código fonte (Lógica, Estilos e Marcação).
*   `README.md`: Este arquivo de documentação.

---
*Desenvolvido por Lucas Feliciano*
