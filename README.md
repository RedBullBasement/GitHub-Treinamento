# GitHub-Treinamento
* https://github.com/tiimgreen/github-cheat-sheet
* https://services.github.com/kit/downloads/pt_BR/github-git-cheat-sheet.html
* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* http://redbullbasement.com

##Instalando no Mac - Colar no Terminal
1. /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
2. brew install git

##Funciona no Ruindows Também!
1. Baixar o git em https://git-scm.com/download/win
2. Executar o .exe
3. Abra o PowerShell ou o terminal (windows+R Digite:cmd)
 

###Deixando terminal bonito no Mac - Colar no Terminal
1. brew install zsh
2. brew install curl
3. sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

#Criando um novo Repositorio, dentro da pasta(SEM GIT CONFIGURADO) já criada com o conteudo
- echo "# teste" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin git@github.com:[usuario]/[repositorio].git
- git push -u origin master

#Criando um novo Repositorio, dentro da pasta(COM GIT CONFIGURADO) já criada com o conteudo
- git remote add origin git@github.com:[usuario]/[repositorio].git
- git push -u origin master
