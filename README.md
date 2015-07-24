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

# Why 

To whom is newby in Bash command using , I wrote this little framework to my self at first then I would like to share this with everyone else who wants to use and know how to use bash command for easily and understand. Are you ready for a different commands ? Check it out.

Some examples for understand ;

' $ cd .. ' is classic bash command with .mis you only need to right ' $ up ' to go one file up

' $ cd ~/Desktop ' you can use ' $ desk '

So simple right , it is like talking english 

' $ cd ~/ ' changes into ' $ home ' 

Let's say you want to create a directory and want to go inside it 
Before .mis :

' $ mkdir new && cd $_ '

After .mis :

' $ cargo new ' I think you know what is cargo.. Create and folder and cargo me into it.

You can use  ' desk ' key with cargo .

' $ cargo desk new ' it is the new way of ' $ cd ~/Desktop && mkdir new && cd $_ '

' $ fob newFile.type ' Free on Board .. Just kidding it is stand for File on board.
With this command you will create a new file and open it up. You can also use ' desk ' key here too.

We have also ;

' $ file newFile.type ' it is same as $ fob command but it doesn't open the file.


Let's compare , and look at other commands ; 
- $ list  : 
- - desk  : $ list desk vs $ ls ~/Desktop
- - home  : $ list home vs $ ls ~/        
- - nav   : $ list nav  vs $ ls /c
- $ go    : 
- - desk  : $ go desk   vs $ cd ~/Desktop
- - home  : $ go home   vs $ cd ~/
- - nav   : $ go nav    vs $ cs /c
- $ cargo : 
- - desk  : $ cargo desk newFolder  vs $ cd ~/Dekstop && mkdir newFolder && cd $_
- $ fob   : 
- - desk  : $ fob desk newfile.type vs $ touch newfile.type && start $_
- $ file  : Usage;
- - $ file newFile.type vs $ touch newFile.type

