# interacting_shell
This project includes an ability to do
<br>
basic built in commands - echo, exit, bang(!!)
<br>
use external commands from your local machines (using execvp)
<br>
signal controlling for exiting the command process while retaining shell process after crtl C/Z
<br>
io redirection using >, < : creating/updating file by piping commands output to the file
<br>
basic job control on foreground and background process. Shell should be able to run process 
<br>
in the background if commanded while not waiting for them to finish before accepting new inputs
<br>
should be able to swtich process between foreground and background if wanted
