# Jogo da Velha em Java

Este é um projeto de um Jogo da Velha (Tic-Tac-Toe) desenvolvido em Java durante um hackathon. O objetivo principal do projeto é oferecer uma implementação simples para rodar o jogo em um ambiente de console, permitindo que um jogador enfrente a máquina.

## Funcionalidades

- Jogo no console, com interface textual.
- Jogador humano vs Computador.
- Verificação automática de vitória, empate ou continuação do jogo.
- Exibição do tabuleiro após cada jogada.

## Regras do Jogo

1. O tabuleiro é composto por uma grade 3x3.
2. Dois jogadores: 
   - Jogador humano usa o símbolo **X**.
   - Computador usa o símbolo **O**.
3. O jogador que alinhar 3 símbolos em linha, coluna ou diagonal vence o jogo.
4. Se todas as posições forem preenchidas sem um vencedor, o jogo termina em empate.

## Como Executar

1. Certifique-se de ter o [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) instalado.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/jogo-da-velha-java.git
   ```
3. Compile o código-fonte:
   ```bash
   javac JogoDaVelha.java
   ```
4. Execute o jogo:
   ```bash
   java JogoDaVelha
   ```

## Estrutura do Projeto

- `JogoDaVelha.java`: Contém a lógica principal do jogo.

## Exemplos de Uso

### Exemplo de Tabuleiro

Após cada jogada, o tabuleiro será exibido no console. Um exemplo inicial:

```
 1 | 2 | 3 
---+---+---
 4 | 5 | 6 
---+---+---
 7 | 8 | 9 
```

Após algumas jogadas:

```
 X | O | X 
---+---+---
 4 | X | 6 
---+---+---
 O | 8 | O 
```

## Próximos Passos

- Implementar níveis de dificuldade para o computador.
- Adicionar uma interface gráfica (GUI) para o jogo.
- Melhorar a IA do computador para jogadas mais estratégicas.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests neste repositório.

## Equipe do Projeto

Este projeto foi desenvolvido por uma equipe durante um hackathon. Participaram:
- Alexandro Sousa
- João Oliveira
- Maria Rocha
- Vitor Mendes
- Miry
- Luiz Araujo
- Eduardo


Feito com ❤️ por toda a equipe!
