# Flippy Bite and Tic Tac Toe using Jack programming 

                                                                             - nand2tetris project

## File Hirearchy :
In this repo we have a folder named "vm" which has all the jack files :

    repo/                           |          repo/
    ├── README.md/                  |          ├── README.md/
    ├── vm/                         |          ├── vm/
        ├── Board.jack              |              ├── Board.jack   
        ├── Game.jack               |              ├── Board.vm 
        ├── Main.jack               |              ├── Game.jack 
        ├── O.jack                  |              ├── Game.vm 
        ├── Player.jack             |              ├── Main.jack 
        ├── Wall.jack               |              ├── Main.vm 
        └── X.jack                  |              ├── O.jack
                                    |              ├── O.vm
                                    |              ├── Player.jack
                                    |              ├── Player.vm
                                    |              ├── Wall.jack
                                    |              ├── Wall.vm
                                    |              ├── X.jack
                                    |              ├── X.vm

    before Execution                            after Execution

## Execution :

To run the game we will need to first use the jack compiler so as to generate the ".vm" files . Then using those files
now we can use them in the VMTranslator and then run the game and play it.

<p>
<img width="1305" alt="Screenshot 2022-08-12 at 12 49 13 AM" src="https://user-images.githubusercontent.com/84731421/184221994-1ebf57ef-0677-4919-a3fb-f35e4a21835a.png">
<img width="1304" alt="Screenshot 2022-08-12 at 1 02 23 AM" src="https://user-images.githubusercontent.com/84731421/184223968-28334ac1-796e-4d82-b3b6-91b3f87fea83.png">
</p>

".vm" files generated after compiling the jack files using "JackCompiler.sh" from the ` ~/Desktop/nand2tetris/tools/JackCompiler.sh` location.

