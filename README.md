# Mari - My Pacman-Repo-in-github testing repository

Go to pacman.conf in /etc and add it.

``` bash
[marina]
SigLevel = Optional
Server = https://raw.githubusercontent.com/Double-StarLight/Mari/master
```

Put the packages in a folder and use repose -z <name> to create the repo file. I recomend using -zf instead.

Name of the repository HAS to be the same in repose. In my case I used my <name>

Server format: https://raw.githubusercontent.com/<User>/<Repository>/<Branch>/Path/to/repository

[Thank them!](https://disconnected.systems/blog/archlinux-repo-in-a-git-repo/)


##WARNING
 - This DO NOT work in gitlab. I tried already, there is no raw API like Github. 
 And also github has more storage limit, so... it's better here anyway
