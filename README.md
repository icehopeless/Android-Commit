# Android-Commit
Commitando um arquivo .c pelo android, utliziando o <a href="https://termux.dev/en/">Termux</a> (Android terminal emulator and Linux environment app), utilizando o Git e SSH na plataforma.

## Instalar Git e SSH Termux 
```ubuntu
apt install git openssh
```
## Commit
Após a instalação do git, é preciso logar e conectar com a conta do GitHub. Depois de se conectar, os passos para commitar em um repositório são os mesmos:
```bash
git init
git commit -m "commit"
git branch -M main
git remote add origin https://github.com/...
git push -u origin main
```




