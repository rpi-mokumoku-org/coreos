# CoreOS Vagrant

ローカルにCoreOS環境を構築する超簡単手順。

## Create VM with CoreOS 

0) Get Github Account
```
https://techacademy.jp/magazine/6235
https://github.com/join?source=header
```


1) Install dependencies

* VirtualBox 4.3.10 or greater.
* Vagrant 1.6.3 or greater.
* Git

2) Clone repository

```
git clone git@github.com:rpi-mokumoku-org/coreos.git ./{coreos dir}
cd {coreos dir}
```

3) Startup

```
vagrant up
```
※mkdir ./{coreos dir}/../share が必要かも


4) SSH

```
vagrant ssh
```
※vagrant ssh-config もろもろ見れる。詳細はggrks
