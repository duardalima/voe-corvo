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
| **WPF** | Interface gráfica nativa Windows |
| **XAML** | Definição do layout visual |
| **.NET SDK** | Plataforma de execução |
| **Backtracking** | Geração e validação de puzzles |
| **Fisher-Yates Shuffle** | Embaralhamento para puzzles únicos |
| **async/await** | Geração em background sem travar a UI |
| **DispatcherTimer** | Cronômetro em tempo real |

---

## 📁 Estrutura do projeto

```
SudokuWPF/
├── SudokuEngine.cs       # Lógica do jogo (geração, validação, solução)
├── MainWindow.xaml       # Interface gráfica (layout e estilos)
├── MainWindow.xaml.cs    # Conexão entre interface e lógica
└── SudokuWPF.csproj      # Configuração do projeto .NET
```

---

## 🧩 Como jogar

1. O jogador deve tocar na tela (ou clicar com o mouse ou pressionar a barra de espaço) para fazer o pássaro bater as asas e subir
2. Se você não tocar, o pássaro é puxado para baixo pela gravidade e vai cair em direção ao chão
3. Cada toque dá um pequeno impulso para cima. O segredo não é voar alto, mas sim encontrar um ritmo constante de toques para manter o pássaro pairando na altura certa
   
---

## 📚 O que aprendi

- Algoritmo de **backtracking** para geração e resolução de puzzles
- Criação de **interfaces gráficas** com WPF e XAML
- Uso de **async/await** para não travar a UI durante processamentos pesados
- Organização de código separando **lógica** da **interface**
- Estruturas de dados como **matrizes bidimensionais** e **listas de tuplas**
- Controle de versão com **Git e GitHub**
