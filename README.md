# mis
.mis ( Make it Simple ) : Using bash command just like native languages.

For some commands you will need git bash.
If you don't have , it is recommended to have it otherwise you might have errors sometimes.

Clone this repo into your ' ~/ ' directory.
or
Download on your desktop after you download it copy the mis folder into yout home directory.
After you down load you will see an empty folder but it is not . If you list it with  ' $ ls -la ' on your bash you will see an file '.mis' it is all you need to use.

Then you will need a configration :

While you are in your ~/ directory there is a file called ' .bashrc ' or ' .bash_profile ' I recommend to use ' .bashrc '
Open ' .bashrc ' file with your lovely editor or Just type ' $ start .bashrc ' it will open it in notepad or your choice .
then you will need to write :

$ if [[ -f ~/mis/.mis ]];
     then
     source ~/mis/.mis
  fi


