# github 账号添加sshkey

1. 首先检查你的电脑是否已经有SSH key
```bash
cd ~/.ssh
ls
```

2. 如果没有，创建一个SSH key
```bash
ssh-keygen -t rsa -C "your_email@example.com"
```
