# RockPaperScissors
Server-based tictactoe game (currently LAN only)


# Academic Honesty
This program was written 100% by me. However, due to restrictions in posting academic content online, I cannot post the code here. I have included psuedocode for the most important parts and screenshots that show the functionality of both programs, both the server and the client. If you are interested in seeing the full code, please contact me at evanmhagood@gmail.com

# RPS Server
The server is a simple program that listens for connections on a specified port. When a client connects, it creates a new thread to handle the client. The server then waits for the client to send a message. The message is a string that contains the client's move. The server then generates a random move and compares the two. The server then sends a message back to the client that contains the result of the game. The server then closes the connection and waits for another client to connect.

##
it has been awhile since I have ran this application and I cannot get JavaFX to import correctly. This seems to be a recurring theme with JavaFX and I should have stuck with Swing.
Anways, I will update this repo with this information when I get it working again.