# 🐶 Dog Snake — Aventura Pet

Um jogo inspirado no clássico **Snake (jogo da cobrinha)**, com uma temática divertida de cachorrinho! 🦴 Ajude o cãozinho a coletar biscoitos, aumentar seu tamanho e conquistar a maior pontuação possível. 🍪

## 🎮 Sobre o projeto

O **Dog Snake** é um jogo desenvolvido para navegadores web, utilizando tecnologias nativas de front-end, sem necessidade de instalar bibliotecas ou frameworks externos.

O jogador controla um cachorrinho em um tabuleiro, movimentando-o para coletar biscoitos. A cada biscoito consumido, a pontuação aumenta e o corpo do cãozinho cresce, tornando o desafio cada vez maior.

O jogo possui uma interface amigável, animações, efeitos visuais e controles adaptados para computadores e dispositivos com tela sensível ao toque. 🐾

## 🛠️ Tecnologias utilizadas

### 🌐 HTML5
Responsável pela estrutura e organização dos elementos da interface, incluindo:

- Cabeçalho e identificação do jogo.
- Placar de pontuação e recorde.
- Área de jogo utilizando o elemento `canvas`.
- Botões para iniciar, pausar e reiniciar.
- Controles direcionais.
- Telas de início, pausa e fim de jogo.

### 🎨 CSS3
Utilizado para estilizar a interface e proporcionar uma experiência visual agradável e responsiva.

Principais recursos aplicados:

- Layouts com Flexbox e CSS Grid.
- Variáveis CSS para padronização das cores.
- Bordas arredondadas, sombras e gradientes.
- Animações e transições de interface.
- Media queries para adaptação a diferentes tamanhos de tela.
- Suporte à preferência do usuário por movimentos reduzidos.
- Estados visuais para interação com botões.

### ⚙️ JavaScript
Responsável pela lógica e pelo funcionamento do jogo.

Principais funcionalidades implementadas:

- Movimentação do personagem.
- Detecção de colisões com as paredes e com o próprio corpo.
- Geração aleatória de biscoitos.
- Controle da pontuação e do recorde.
- Crescimento do personagem ao coletar alimentos.
- Aumento progressivo da velocidade.
- Controle dos estados do jogo: pronto, em andamento, pausado, encerrado e vitória.
- Sistema de partículas para efeitos visuais.
- Eventos de teclado, mouse e toque.
- Salvamento do recorde utilizando `localStorage`.
- Loop de animação com `requestAnimationFrame`.

### 🖌️ Canvas API
Utilizada para desenhar e atualizar os elementos gráficos do jogo em tempo real.

O `canvas` permite representar o cachorrinho, seu corpo, os biscoitos, o gramado e os efeitos de partículas, sem depender de imagens externas.

### 💾 LocalStorage
Utilizado para armazenar o recorde do jogador no próprio navegador, permitindo que a melhor pontuação seja recuperada em visitas futuras, quando o armazenamento estiver disponível.

## 🚀 Como executar o projeto

Não é necessário instalar dependências, configurar servidores ou utilizar ferramentas de build.

1. 📥 Baixe ou clone o projeto.
2. 📂 Localize o arquivo `index.html`.
3. 🌐 Abra o arquivo diretamente em um navegador moderno, como Google Chrome, Microsoft Edge ou Mozilla Firefox.
4. ▶️ Clique em **Começar aventura** para iniciar a partida.
5. 🐶 Divirta-se tentando superar seu recorde!

## 🕹️ Como jogar

### 🎯 Objetivo

Controle o cachorrinho e colete o máximo de biscoitos possível. Cada biscoito vale **1 ponto** e faz o personagem crescer.

Quanto mais você come, maior fica o cãozinho e mais rápido o jogo se torna! 🍪

### ⌨️ Controles pelo teclado

| Tecla | Ação |
|---|---|
| ⬆️ `↑` ou `W` | Mover para cima |
| ⬇️ `↓` ou `S` | Mover para baixo |
| ⬅️ `←` ou `A` | Mover para a esquerda |
| ➡️ `→` ou `D` | Mover para a direita |
| ⏸️ `Espaço` | Pausar ou continuar o jogo |
| ↵ `Enter` | Iniciar ou jogar novamente, conforme o estado da partida |

### 📱 Controles por toque

Em dispositivos com tela sensível ao toque, você pode:

- 👆 Utilizar os botões direcionais exibidos na tela.
- 👉 Deslizar o dedo sobre a área do tabuleiro para mudar a direção do cachorrinho.

### 🖱️ Botões da interface

- **▶️ Começar aventura:** inicia a partida.
- **⏸️ Pausar:** interrompe temporariamente o jogo.
- **↻ Reiniciar:** reinicia a partida e começa um novo jogo.

## 📏 Regras do jogo

1. 🍪 Colete os biscoitos para ganhar pontos.
2. 🐕 Cada biscoito coletado aumenta o comprimento do personagem.
3. ⚡ A velocidade aumenta progressivamente conforme a pontuação cresce.
4. 🧱 Evite bater nas paredes do tabuleiro.
5. 🐾 Não colida com o próprio corpo.
6. 🔄 Não é permitido inverter diretamente a direção do movimento, como passar de direita para esquerda em um único comando.
7. 🏆 O recorde é atualizado quando uma nova pontuação máxima é alcançada.
8. 🎉 Você vence se preencher todo o tabuleiro sem colidir.

**Atenção:** ao colidir com uma parede ou com o próprio corpo, a partida termina. Será possível iniciar um novo jogo e tentar superar a pontuação anterior.

## 🏆 Sistema de pontuação

O jogo apresenta dois indicadores principais:

- 🍪 **Pontuação:** quantidade de biscoitos coletados na partida atual.
- 🏆 **Seu recorde:** maior pontuação registrada no navegador.

O recorde é armazenado localmente por meio do `localStorage`, utilizando a chave `dogSnakeBest`. Ele não é compartilhado automaticamente entre navegadores ou dispositivos.

## 📱 Responsividade e experiência do usuário

O projeto foi desenvolvido com foco em simplicidade, acessibilidade básica e facilidade de utilização.

Entre os recursos disponíveis, destacam-se:

- 📐 Interface adaptável a telas menores.
- 🎮 Controles por teclado e toque.
- 👀 Indicadores visíveis de pontuação e recorde.
- 💬 Mensagens específicas para início, pausa, derrota e vitória.
- ✨ Efeitos visuais ao coletar biscoitos.
- ⏸️ Pausa automática quando a página fica oculta durante uma partida em andamento.
- ♿ Indicações acessíveis em elementos interativos e respeito à preferência por movimentos reduzidos.

## 📁 Estrutura do projeto

O projeto está concentrado em um único arquivo HTML, que contém a estrutura, os estilos e a lógica do jogo.

```text
dog-snake/
└── index.html
    ├── HTML5 — Estrutura da interface
    ├── CSS3 — Estilização e responsividade
    └── JavaScript — Regras, controles e animações
```

Essa organização simplifica a distribuição, a execução e a manutenção do projeto.

## 🔧 Possíveis melhorias futuras

O projeto pode ser expandido com novas funcionalidades, como:

- 🎚️ Seleção de níveis de dificuldade.
- 🔊 Efeitos sonoros e música de fundo.
- 🐶 Diferentes raças e aparências de cachorrinhos.
- 🦴 Novos alimentos e itens especiais.
- 🌎 Temas e cenários desbloqueáveis.
- 📊 Histórico de pontuações.
- 🥇 Ranking de jogadores.
- 📲 Instalação como Progressive Web App (PWA).
- 🧪 Testes automatizados para validar as regras do jogo.

## 📄 Licença e dependências

O projeto utiliza HTML5, CSS3 e JavaScript nativos, sem dependências externas identificadas no código.

Não há um arquivo de licença específico definido no projeto. Caso ele seja distribuído publicamente, recomenda-se estabelecer uma licença adequada para definir as condições de uso, modificação e redistribuição.

---

## ❤️ Considerações finais

O **Dog Snake — Aventura Pet** combina a nostalgia do clássico jogo da cobrinha com uma temática pet divertida, oferecendo uma experiência leve, acessível e fácil de executar diretamente no navegador.

🐶 **Pegue os biscoitos, desvie dos obstáculos e transforme seu cachorrinho em um verdadeiro campeão!** 🏆🦴
