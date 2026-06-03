# Jogo da Velha em Assembly x86-64

Este projeto é uma implementação do clássico **Jogo da Velha** (Tic-Tac-Toe) desenvolvido inteiramente em **Assembly x86-64** utilizando o montador **FASM** (Flat Assembler). 

O projeto foi desenvolvido para a disciplina de Organização e Arquitetura de Computadores (OAC) do Instituto de Computação da Universidade Federal de Alagoas (UFAL).

## 🚀 Funcionalidades
- Interface textual limpa e centralizada via terminal.
- Menu de regras inicial explicativo.
- Sistema para dois jogadores (Jogador 1 com 'X' e Jogador 2 com 'O').
- Início obrigatório com o Jogador 1 ('X').
- Tabuleiro formatado com divisórias bem definidas.
- Verificação automática de vitória, empate (velha) e jogadas inválidas.
- Opção para reiniciar a partida no final do jogo.

## 🛠️ Como Compilar e Executar
O código foi estruturado utilizando chamadas de sistema (syscalls) nativas do Linux de 64 bits.

1. Certifique-se de ter o FASM (Flat Assembler) instalado.
2. Compile o código com o comando:
   ```bash
   fasm main.s velha
