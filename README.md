
TalonPower development tree

TalonPower is a PoS-based cryptocurrency.


1.)  create the file TalonPower.conf in the folder "%APPDATA%\TalonPower\"

your file should look this

======= CONF  File  ========

rpcuser= CREATE YOUR USER

rpcpassword=CREATE YOUR PASS WORD

rpcallowip=127.0.0.1

rpcport=4210

rpcallowip=127.0.0.1

listen=1

server=1

txindex=1

daemon=1

addnode=37.97.242.80


===========================


NOTE:  do not have spaces in your username and password  and do NOT add the  "========= "  Lines


2.) for the 1st 10,000 Blocks you can mine with your CPU 

Download the latest version of cpuminer from https://bitcointalk.org/index.php?topic=55038.0  and extract the zip file. 

In that same folder create a .BAT file names  talonPowerMiner.BAT

Your Bat File Should look like this:


========   BAT File  =======

minerd --url=http://127.0.0.1:4210 --userpass=USER NAME CREATED ABOVE:PASS WORD CREATED ABOVE

Pause

============================


NOTE:  do not have spaces in your username and password  and do NOT add the  "========= "  Lines

3.)  If your wallet was open please exit now, to be sure the changes were made.

4.)  Re open your wallet

5.)  double click the talonPowerMiner.BAT  File in your Cpu Miner Folder
