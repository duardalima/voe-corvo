# 🎮 Voe Corvo 

Jogo desenvolvido em **Python**, onde o jogador controla um corvo que voa sem fim por um cenário repleto de obstáculos gerados automaticamente. 

---

## 📸 Preview

<img src="MenuBg.png" alt="voe-corvo" width="50%">

## 🚀 Historia

Baseado no clássico Flappy Bird, Voe Corvo é um jogo side-scroller onde o jogador assume o controle de um corvo em um voo. O objetivo é guiar a ave através de obstáculos compostos por colunas, desviando deles com precisão.  

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
|------------|-----|
| **Python** | Linguagem principal |
| **Pygame** | Biblioteca gráfica e de áudio |
| **PNG Art** | Banco de sprites 2D com imagens PNG transparentes para personagens, cenários e obstáculos. |
| **CraftPix** | Banco de assets gráficos |

---

## 📁 Estrutura do projeto

```
VoeCorvo/
├── main.py                          # Arquivo principal do jogo
├── assets/                          # Pasta com todos os recursos do jogo
│   ├── sprites/                     # Imagens do jogo
│   │   ├── Background.png           # Plano de fundo
│   │   ├── Base.png                 # Chão
│   │   ├── Corvinho_DOWN.png        # Sprite do corvo com asas para baixo
│   │   ├── Corvinho_MEIO.png        # Sprite do corvo com asas no meio 
│   │   ├── Corvinho_UP.png          # Sprite do corvo com asas para cima
│   │   ├── Game_Over.png            # Tela de fim de jogo
│   │   ├── MenuBg.png               # Tela de menu inicial
│   │   └── pipe-red.png             # Obstáculo
│   └── sounds/                      # Áudios do jogo
│       ├── Menu.mp3                 # Música da tela de menu
│       ├── hit.ogg                  # Som de colisão 
│       └── jump.ogg                 # Som ao pular 
├── main.exe                         # Executável do jogo

```

---

## 🧩 Como jogar

1. O jogador deve tocar na tela (ou clicar com o mouse ou pressionar a barra de espaço) para fazer o pássaro bater as asas e subir
2. Se você não tocar, o pássaro é puxado para baixo pela gravidade e vai cair em direção ao chão
3. Cada toque dá um pequeno impulso para cima. O segredo não é voar alto, mas sim encontrar um ritmo constante de toques para manter o pássaro pairando na altura certa
   
---

## 📚 O que aprendi

Aprendi a utilizar a linguagem Python para jogos, mecânicas de jogos 2D, análise de estrutura de projetos, formatos de arquivo, documentação profissional.
