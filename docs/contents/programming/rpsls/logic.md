# Logic and Flow Control


In this phase of game development, we will program the referee Sprite, which will be responsible for **deciding** the winner after each move.

To achieve this, we need to create several code blocks: *DecideWinner*, *PlayerA_Rock*, *PlayerA_Paper*, *PlayerA_Scissors*, *PlayerA_Lizard*, and *PlayerA_Spock*.

## *DecideWinner* block

The ***DecideWinner*** block will first check the value of **Player A's move**, and based on this value (1, 2, 3, 4, or 5), the corresponding block (PlayerA_Rock, PlayerA_Paper, etc.) will be called to check the value of **Player B's move**. In this latter block, the message for the **winning move** will be displayed, and **points** will be added to each player.

<pre><code class="mermaid">
``` mermaid
graph TD
  A[DecideWinner] --> B{PlayerA_move?};
  B -->|1 Rock| C[PlayerA_Rock];
  B -->|2 Paper| D[PlayerA_Paper];
  B -->|3 Scissors| E[PlayerA_Scissors];
  B -->|4 Lizard| F[PlayerA_Lizard];
  B -->|5 Spock| G[PlayerA_Spock];
  C --> H{PlayerB_move?};
  H -->|1 Rock| I[Tie];
  H -->|2 Paper| J[Paper wins];
  H -->|3 Scissors| K[Rock wins];
  H -->|4 Lizard| L[Rock wins];
  H -->|5 Spock| M[Spock wins];
  D --> N2{?};
  E --> N3{?};
  F --> N4{?};
  G --> N5{?};

```
</code></pre>

![Decide winner](img/decide_winner.png)


## *PlayerA_* blocks

![Decide winner](img/decide_winner_2.png)
