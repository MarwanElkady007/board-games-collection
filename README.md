# Board games (C++)

OOP course assignment. The games are built on a small generic framework (`Board<T>`, `Player<T>`,
`GameManager`) with several Tic-Tac-Toe variants on top of it:

1. 5x5 Tic-Tac-Toe
2. Misère (reverse) Tic-Tac-Toe
3. Pyramid Tic-Tac-Toe
4. Word Tic-Tac-Toe

Each one can be played against another person or against a random computer player.
`Susgame.h` has the SUS game, which isn't hooked into the menu yet.

```
g++ -std=c++17 main.cpp -o games
./games
```

Team project with [Seif Wael](https://github.com/Seiffwaell) and [Mohamed Waleed](https://github.com/MrWeza).
