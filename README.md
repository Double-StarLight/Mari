# Mari

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
