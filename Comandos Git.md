# Comandos para usar no Git Bash

 - **git init**: Inicia um repositório local git

 - **git status**: Verifica o estado dos seus arquivos

 - **git add >nomeDoArquivo<**: Envia seu arquivo especificado para o Stage

 - **git add - -all**: Envia todos os arquivos para o stage(Também pode ser usado o simbulo "*")

 - **git commit -m "tituloDoCommit"**: Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o **git add**, para fazer o commit

 - **git config**: A primeira coisa que você deve fazer quando instalar o Git é definir o seu nome de usuário e endereço de e-mail. Isso é importante porque todos os commits no Git utilizam essas informações, e está imutavelmente anexado nos commits que você realiza: Configura user.name e user.email, exemplos;git config --global user.name "John Doe", git config --global user.email johndoe@example.com
 
 - **git clone**: Clona repositório utilizando o endereço URL
 
 - **git config --list**: Mostra toda a configuração do git
 
 - **git config --global --unset**: Remove o user.name ou o user.email

 - **git remote add origin >endereço URL do repositório<**: cadastra uma origem remota
 
 - **git remote -v**: Lista as origems remota cadastrado