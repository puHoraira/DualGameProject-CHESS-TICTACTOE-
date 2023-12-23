Assalamualaikom.

Hello!

Welcome to our game project. It's an undergoing game project of CHESS and TIK-TAK-TOE dual game using SDL2 library, c and c++ programming language for CSEDU 1-2 semester FoP project instructed by Mahmudur Rahman Rana sir (CSEDU).

We took help from some github resources and seniors. Thank you for visit. Hope you will enjoy.

Project owners:

MD. ABU HORAIRA

MD. ADIB AHSAN

SHRABAN KARMOKER AVI

For query : mdabu-2021911202@cs.du.ac.bd

Run command for ubuntu terminal:

Installing SDL2 library:

sudo apt install libsdl2*

Installing GCC and G++:

sudo apt install gcc

sudo apt install g++

Installing and running game:

git clone https://github.com/puHoraira/DualGameProject-CHESS-TICTACTOE-.git

cd DualGameProject-CHESS-

cd sourceCodes

g++ chessmain.cpp tiktakshape.cpp chessAI.cpp game.cpp starter.cpp chessboard.cpp copyofMain.cpp tiktakevent.cpp main.cpp chess.cpp credit.cpp tiktakrender.cpp piecemanager.cpp checkmatePage.cpp -lSDL2 -lSDL2_image -lSDL2_ttf -o openGame

./openGame
