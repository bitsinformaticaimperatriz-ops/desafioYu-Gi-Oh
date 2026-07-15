# 🃏 Yu-Gi-Oh! Jo-ken-po Edition

Este projeto é um jogo de cartas temático inspirado em **Yu-Gi-Oh!** que utiliza as regras clássicas do **Jo-ken-po** (Pedra, Papel e Tesoura) como mecânica de batalha. O projeto foi desenvolvido como parte de um desafio prático da **DIO (Digital Innovation One)**, aplicando conceitos fundamentais de desenvolvimento web frontend com foco em lógica de programação em JavaScript puro.

---

## 🎮 Como Jogar

As regras são simples e nostálgicas:
1. **O Deck**: Você e o oponente (computador) recebem 5 cartas aleatórias viradas para baixo.
2. **Seleção**: Ao passar o cursor (com designs customizados do Yugi!) sobre as suas cartas, o painel lateral esquerdo exibirá os detalhes do card selecionado.
3. **Mecânica de Combate**:
   - 🐉 **Blue Eyes White Dragon** (Atributo: *Paper*) vence de **Dark Magician** (Atributo: *Rock*).
   - 🧙‍♂️ **Dark Magician** (Atributo: *Rock*) vence de **Exodia** (Atributo: *Scissors*).
   - 🧩 **Exodia the Forbidden One** (Atributo: *Scissors*) vence de **Blue Eyes White Dragon** (Atributo: *Paper*).
4. **O Duelo**: Clique em uma carta da sua mão para jogá-la no campo de batalha. O computador fará sua jogada instantaneamente.
5. **Resultado**: O jogo atualiza o placar e emite efeitos sonoros clássicos do anime dependendo se você ganhou, perdeu ou empatou. Clique no botão **JOGAR** para reiniciar o round!

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias limpas e sem frameworks adicionais:

*   **HTML5 Semântico**: Estruturação organizada e acessível das seções do tabuleiro.
*   **CSS3 Personalizado**: Estilização imersiva no estilo Pixel Art de jogos clássicos (com suporte a cursores dinâmicos dos personagens e favicon do Enigma do Milênio).
*   **Vanilla JavaScript (ES6)**: Gerenciamento do estado do jogo (State Pattern), controle do DOM, sorteios de cartas, regras de duelo e manipulação de efeitos sonoros.

---

## 📂 Estrutura de Pastas

O projeto está organizado da seguinte forma para manter o código limpo e de fácil manutenção:

```text
├── assets/
│   ├── audios/           # Músicas de fundo e efeitos sonoros (.mp3, .wav)
│   └── icons/            # Cartas dos personagens, cursores e divisórias (.png, .ico)
├── css/
│   ├── buttons.css       # Estilos específicos para os botões do tabuleiro
│   ├── containers.css    # Layout dos painéis e grids
│   ├── main.css          # Estilos principais, resets e configurações de cursor
│   └── reset.css         # Reset padrão de estilos do navegador
├── js/
│   └── engine.js         # Código principal da engine e lógica do jogo
├── index.html            # Estrutura principal do jogo
└── README.md             # Documentação do repositório