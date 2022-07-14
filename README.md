# poeseed
Command line parser of Path of Exile Client log file
  
# Requirements
This is currently written for a Windows + Bash (Mingw64) environment. One can install MingW64 through the [git-scm install packages](https://git-scm.com/).
  
# Usage
Place poeseed in your path with executable permissions and run poeseed  
  
> $ poeseed  
![poeseed example 1](/assets/images/poeseed-1.png)  
  
> $ THIST=1000 TRADES=false GCHAT=false SHOWIPS=false poeseed  
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
