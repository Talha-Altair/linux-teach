---
title: "SSH gen"
date: 2021-07-29T15:44:07+05:30
draft: false
---

# How to generate ssh key on Ubuntu?

```
ssh-keygen -t rsa -b 4096 -C "email@gmail.com"

eval "$(ssh-agent -s)"

ssh-add ~/.ssh/id_rsa

pbcopy < ~/.ssh/id_rsa.pub
or
cat ~/.ssh/id_rsa.pub
    (then copy the content)


then copy the file on Github/Gitlab
```