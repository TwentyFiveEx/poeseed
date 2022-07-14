# poeseed
Command line parser of Path of Exile Client log file
  
# Requirements
This is currently written for a Windows + Bash (Mingw64) environment. One can install MingW64 through the [git-scm install packages](https://git-scm.com/). This might run under Linux, by adjusting the Client.txt file location (maybe..?).

# Install
Simplest self-install steps
* [Install git-scm](https://git-scm.com/)
* Run git-bash
   
```
mkdir $HOME/bin
echo 'export PATH="${PATH}:${HOME}/bin/"' >> $HOME/.bashrc
. $HOME/.bashrc
curl -s -o $HOME/bin/poeseed https://github.com/TwentyFiveEx/poeseed/releases/latest/download/poeseed
chmod -v 755 $HOME/bin/poeseed
```

poeseed is now ready to run and in your default path any time you launch a bash shell  
  
# Usage
  
```$ poeseed```
![poeseed example 1](/assets/images/poeseed-1.png)  
  
```$ THIST=1000 TRADES=false GCHAT=false SHOWIPS=false poeseed``` 
![poeseed example 1](/assets/images/poeseed-2.png)  
  
# Command Line Options
| Variable | Options (default) | Description |
| -------- | ---------------- | ---------------- |
| GCHAT | true, (false) | Display global chat |
| TCHAT | true, (false) | Display trade chat |
| SHOWIPS | (true), false | Display server IPs |
| TRADES | (true), false | Display trade whispers |
| THIST | nnn, (1000) | Lines of Client.txt history to parse on start |
  
# License
This source is released under the MIT license (see the LICENSE file)  
This project is not affiliated with Grinding Gear Games  
