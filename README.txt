A game I made years ago but didn't publish.

               0_0            
______  ______ \_/     ____         _____      >_<           _____
\     \|\     \  s ____\_  \__    /      |_    \_/s     _____\    \
 |     |\|     |s /     /     \  /         \    ^  s   /    / \    |
 |     |/____ /  /     /\      ||     /\    \    ss   |    |  /___/|
 |     |\     \ |     |  |     ||    |  |    \sss  ____\    \ |   ||
 |     | |     ||     |  |     ||     \/      \   /    /\    \|___|/
 |     | |     ||     | /     /||\      /\     \ |    |  \    \ss
/_____/|/_____/||\     \_____/ || \_____\ \_____\|\____\ /____/| ss
|    |||     | || \_____\   | / | |     | |     || |   ||    | | ^_^
|____|/|_____|/  \ |    |___|/   \|_____|\|_____| \|___||____|/  \_/
                  \|____|            
         
*-. Game Play .-*
You are gather money and some boa snakes chase you, they get more willing to eat you the more you get rich.

If you get enough money, you could buy rats who distract boas. 

Despite it being harder than snake(6), you can theoretically attain any score by making a large enough rat army, which is not an easy task.

The main attraction of the gameplay is that unlike snake(6), you could play it for hours, or even days! It was popular among friends and little children of relatives, so i thought it would be nice if I share it on the web.

*-. Installation .-*
You can install it by this command:

sudo pip install boas-game
boas

Have fun!

*-. It's in Python2!? .-*
Yes. It's also so dirty that I get headache surfing through its code.
If I wanted to modify it so much I would rather rewrite it in C from scratch.





































*-. Don't use pycurses .-*
Unlike curses, which is (like many other old libs) a testament that using a library made by C people for C could be actually a nice expreince; pycurses is the absolute opposite of that with it's combinations of an OO pythonic inteface for a bitmask-intensive trivially non-OO API and FREAKING EXCEPTIONS that throw you into a corrupted console, many times for nonsensical reasons. It was such a pain silencing them all and sometimes even exceptpass didn't suffice.

It's also tied to ncurses, limiting you to unix-like platforms.

If you want to do something similar, i recommend using unicurses.
