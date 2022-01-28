## Lab 02

- Name: William Armstrong
- Email: Armstrong.170@wright.edu/willa2000sca@gmail.com

## Part 2 Answers

1. Add a file for tracking: Git add Lab02.md
2. Commit changes: git commit Lab02.md, git config --global user.email willa2000sca@gmail.com
3. Sync local commits with GitHub: git push --all  https://github.com/DrKaboom/Cloneme.git

## Part 3 Answers

1. `ssh` before configuring `config` file:  ssh -i /home/william/labuser.pem ubuntu@3.91.113.40

2. HostName: 3.91.113.40 CEG2350 Ubuntu
3. User: William 
4. IdentityFile: /home/William/labuser.pem
5. `~/.ssh/config` contents:

```
Host dev
HostName 3.91.113.40
user william
port 22
```

6. `ssh` after configuring `config` file: ssh dev
 Small issue: Error about publickey keeps coming, can’t find fix. Everything else is set up correctly to what I can find.
