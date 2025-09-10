# 🎯 Caça ao Tesouro  

Um jogo em Python onde dois jogadores competem para encontrar tesouros e evitar armadilhas em um tabuleiro 10x10.  

---

## 🕹️ Regras do Jogo  

- O tabuleiro é uma matriz **10x10** (posições de 0 a 9).  
- Tesouros (**T**) e Armadilhas (**A**) são escondidos aleatoriamente no tabuleiro.  
- Os jogadores começam juntos na posição inicial **(0, 0)**.  
- Cada jogador inicia com **10 pontos**.  
- Em cada rodada, o jogador sorteado rola **dois dados**:  
  - O primeiro define a **linha** (0 a 9).  
  - O segundo define a **coluna** (0 a 9).  
  - O jogador se move para a posição sorteada.  
- **Pontuação**:  
  - Encontrar um **Tesouro (T)**: **+10 pontos**  
  - Cair em uma **Armadilha (A)**: **-5 pontos**  
- O jogo possui **20 rodadas** (10 para cada jogador).  
- Ao final, vence quem tiver a **maior pontuação**.  

---

## ⚙️ Funcionalidades  

- `criar_tabuleiro()` → cria o tabuleiro 10x10 vazio.  
- `mostrar_tabuleiro()` → exibe o tabuleiro com jogadores e elementos.  
- `definir_jogadores()` → cadastra os dois jogadores.  
- `gerar_sigla()` → gera uma sigla única para cada jogador.  
- `posicao_inicial()` → define a posição inicial (0,0) para os jogadores.  
- `esconder_T()` → esconde os tesouros no tabuleiro.  
- `esconder_A()` → esconde as armadilhas no tabuleiro.  
- `verificar_posicao()` → garante que não haja sobreposição de T e A.  
- `exibir_regras()` → mostra as regras do jogo no terminal.  
- `start()` e `verificar_rodada()` → controlam as rodadas.  
- `dado()` → simula a jogada dos dados.  
- `atualizar_posicao()` → move o jogador para a nova posição.  
- `contador()` → calcula e exibe o vencedor.  
- `main()` → executa o jogo principal.  

---
## 👨‍💻 Autores

Projeto desenvolvido por Moisés Waidemann, Gabriel Sbrana e Thiago Mota.
