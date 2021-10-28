# Analyse a finished game

Any game played on lishogi can still be viewed and analysed after it is finished. You can access it by clicking the "Analysis board" button after a game, clicking a game link, or following a URL someone shares with you.

In this screen, you can leave messages in chat for others to see, move pieces on the board, analyse the game with an engine running in the browser, or request server-side computer analysis of the game.

The layout of the screen is similar to the game screen, but with a few differences.


## Chat

The spectator chat from the game will be visible here. You can also continue to chat with other users here, and the messages will remain visible for future viewers.


## Board and movelist

You can navigate through the game by scrolling on the board, with the arrow keys after clicking the board, or by clicking moves directly in the move list.

In addition, you can make moves on the board. They will display as variations in the movelist on the right.

**Do note that the moves you make and the board you see here are not saved, and not visible to other users. If you wish to analyse together with another user, use a [lishogi study](/lishogi-study.md).**

Tip: If you want to automatically replay the game in real-time, click the 3 lines at the bottom right of the move list, and select one of the replay modes there.


## In-browser engine

You can analyse the game with an engine in your browser by turning on the switch above the movelist. Currently lishogi uses Fairy-Stockfish for the in-browser analysis. Some engine settings are available by clicking the hamburger icon (the three bars) at the bottom right of the movelist.

The evaluation unit of Fairy-Stockfish is in pawns, while conventional shogi software uses centipawns. Thus an evaluation of +11.9 by Fairy-Stockfish would more commonly be seen as +1190.


## Server-side computer analysis

From the "Computer analysis" tab below the board, you can request server-side computer analysis of the game, which is more powerful than the browser engine. This may take a few minutes to process.

The computer analysis is saved to the server, and will be visible to anyone viewing the game in the future.


## Download the kifu

From the "Export" tab below the board, you can download or export the game. The supported formats are KIF (UTF-8 or Shift-JIS encodings) and CSA. The SFEN string for the current board position is also displayed. You can also generate an animated GIF of the game from here.

**All games played on lishogi are freely available for download and use.**


## Other information

In the other tabs below the board, under "Move time" there is graph of how long players took on each move of the game, and under "Crosstable" you can see the most recent win/loss results of the two players, as well as their total lifetime score against each other.
