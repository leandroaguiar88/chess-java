Chess System em Java

Projeto desenvolvido em Java com o objetivo de simular uma partida completa de xadrez, aplicando conceitos fundamentais de programação orientada a objetos, regras do jogo e lógica de movimentação das peças.

Sobre o Projeto

Este projeto implementa um sistema de xadrez totalmente funcional no terminal, incluindo:

Movimentação das peças conforme as regras oficiais básicas
Validação de jogadas
Captura de peças
Controle de turnos
Verificação de check e checkmate

O foco principal é demonstrar domínio em lógica de programação e modelagem orientada a objetos.
Sobre o Projeto

Este projeto implementa um sistema de xadrez totalmente funcional no terminal, incluindo:

Movimentação das peças conforme as regras oficiais
Validação de jogadas
Captura de peças
Controle de turnos
Verificação de check e checkmate

O foco principal é demonstrar domínio em lógica de programação e modelagem orientada a objetos.
Conceitos Aplicados
Programação Orientada a Objetos (POO)
Encapsulamento, Herança e Polimorfismo
Estruturas de dados (matriz para o tabuleiro)
Tratamento de exceções
Organização em camadas (boardgame / chess / pieces)

Estrutura do Projeto

src/
 ├── boardgame
 │   ├── Board
 │   ├── Piece
 │   └── Position
 │
 ├── chess
 │   ├── ChessMatch
 │   ├── ChessPiece
 │   ├── ChessPosition
 │   └── Color
 │
 └── chess.pieces
     ├── King(rei)
     ├── Queen(rainha)
     ├── Rook(torre)
     ├── Bishop(Bispo)
     ├── Knight(cavalo)
     └── Pawn(peao)

Funcionalidades

Movimentos válidos por peça
Bloqueio de movimentos ilegais
Sistema de captura
Detecção de check
Detecção de checkmate
Alternância automática de jogadores

Exemplo de Execução

O jogo é executado no terminal exibindo o tabuleiro em formato textual, com coordenadas e peças identificadas por letras.
