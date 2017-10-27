1 - Bajar iTerm2

2- Clonar
sudo git clone --recursive https://github.com/Kronuz/prezto.git /usr/local/share/zprezto

3- Ejecutar en terminal:
sudo chsh -s /bin/zsh

4 - En terminal:
sudo vim ~/.zshrc

5 - Salir de vim
":q"

6 - Terminal:
cd

7 - 
sudo ln -s /usr/local/share/zprezto .zprezto

8 - 
sudo ln -s /usr/local/share/zprezto/runcoms/zpreztorc .zpreztorc

9 -
sudo ln -s /usr/local/share/zprezto/runcoms/zprofile .zprofile

10 -
sudo ln -s /usr/local/share/zprezto/runcoms/zlogin .zlogin

11 -
sudo ln -s /usr/local/share/zprezto/runcoms/zlogout .zlogout

12 -
sudo ln -s /usr/local/share/zprezto/runcoms/zshenv .zshenv

13 -
sudo ln -s /usr/local/share/zprezto/runcoms/zshrc .zshrc

14 - git config --global alias.co checkout

15 - git config --global alias.st status
