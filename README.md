# setup ansible ubuntu
```sh
sudo adduser devops
sudo usermod -aG sudo devops
su devops
cd ~
ssh-keygen
```

```sh
whoami
```
devops

```sh
ansible-playbook playbook.yml -usonnyyu -bK --ask-pass
```


