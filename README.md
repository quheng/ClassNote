# Git

## multi user

1.add ~/.ssh/config

```c

Host github_mada

 HostName github.com

 IdentityFile ~/.ssh/id_rsa

Host github_quheng

 HostName github.com

 IdentityFile ~/.ssh/quheng_rsa

```

2.git clone git@github_quheng:quheng/repo.git