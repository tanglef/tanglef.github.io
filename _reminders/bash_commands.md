---
title: Bash and other shell commands
---

Some shell commands that can be useful sometimes and keep spending too much time to find back.
For some commands I put the Windows equivalent (might be handy when not on you own machine).


## Basics



## SSH (not much)


## Time related

* Chronometer (when you don't have your phone at arms length)

```sh
date1=`date +%s`; while true; do echo -ne "$(date -u --date @$((`date +%s` - $date1)) +%H:%M:%S)\r"; done
```

* Display time

```sh
timedatectl #a lot of infos
date + "%d-%m-%y" #date with a format
date --date='23 Nov' +%u #which week day for my birthday?
```

* In Windows

```sh
date /T
time /T
```