# Flippy Bite and Tic Tac Toe using Jack programming 

                                                                             - nand2tetris project

## File Hirearchy :
In this repo we have a folder named "vm" which has all the jack files :

    repo/                                   |   repo/
    ├── README.md/                          |   ├── README.md/
    ├── vm/                                 |   ├── vm/
        ├── Board.jack                      |       ├── Board.jack   
        ├── Game.jack                       |       ├── Board.vm 
        ├── Main.jack                       |       ├── Game.jack 
        ├── O.jack                          |       ├── Game.vm 
        ├── Player.jack                     |       ├── Main.jack 
        ├── Wall.jack                       |       ├── Main.vm 
        └── X.jack                          |       ├── O.jack
                                            |       ├── O.vm
                                            |       ├── Player.jack
                                            |       ├── Player.vm
                                            |       ├── Wall.jack
                                            |       ├── Wall.vm
                                            |       ├── X.jack
                                            |       ├── X.vm

    before Execution                            after Execution

To run the game we will need to first use the jack compiler so as to generate the ".vm" files . Then using those files
now we can use them in the VMTranslator and then run the game and play it.

for that :

