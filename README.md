# gitAtalhos

## primeiro de o comando

git config --global core.editor code

## Depois de esse comando

git config --global --edit

## Copie e cole o codigo a baixo

[user]  

name =  
email =  
editor = vscode  

[core]  
	editor = code  
[alias]  

c = !git add --all && git commit -m  
s = !git status -s  
l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'  
d = !git diff #pode ser encadeado com os hashs dos commits  
di = !git diff --staged #mostra a diferença entre o arquivo atual e o ultimo commit  
li = !git log --oneline #mostra o log em uma linha  
amend = !git commit --amend -m #junta dois commits  
b = !git checkout -b #cria nova branch  
p = !git push  
ch = !git checkout #navegar entre branchs e commits  
br = !git branch #mostra a branch  
bd = !git branch -d #remove a branch  
BD = !git branch -D #remove a branch mesmo que ela nao tenha sido mergeada  
m = !git merge#junta as branchs  
pu = !git pull#atualiza o repositorio  
r = !git rebase#faz um merge porém ele re faz a base do projeto, lembre de colocar o nome da branch "git r branch"  
f = !git fetch#baixa os arquivos mas nao realiza o merge depois de dado esse comando e preciso dar o comando "git r" para dar um rebase  

