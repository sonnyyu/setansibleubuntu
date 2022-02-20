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
git clone https://github.com/sonnyyu/setupansibleubuntu
cd setupansibleubuntu
```
Edit hosts-dev with IP address
```sh
[webservers]
app1 ansible_host=192.168.1.2
app2 ansible_host=192.168.1.3
```
Run Playbook
```sh
ansible-playbook playbook.yml -usonnyyu -bK --ask-pass
```


