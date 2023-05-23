# Passo a passo

_inicialmente foi criado o repositório chamado  **analgesicos-e-farmacias** no GitHub_<br>
_depois o repositório foi clonado na minha máquina utilizando o comando git clone e o ssh do repositório_<br>
```
git clone git@github.com:nic4cio/analgesicos-e-farmacias.git
```

_após isso acessei o diretório do repositório clonado_<br>
```
cd analgesicos-e-farmacias
```
<br>
_verificando o vínculo do repositório remoto_<br>
```
git remote -v
```
<br>
_estando dentro do diretório,  foram colocados os arquivos analgesicos.txt e farmacias.txt, depois adicionei todos os arquivos para a staging area_<br>
```
git add . 
```
<br>
verificando o status<br>
```
git status
```
<br>
_então, fiz o commit_<br>
```
git commit -m "initial commit" 
```
<br>
_verificando o log_<br>
```
git log 
```
<br>
_e assim, foi feito o push para o repositório_ e para a branch main<br>
```
git push origin main 
```

## Criando a branch feature/readme e adicionando o README.md

_criando outra branch chamada feature/readme_<br>
```
git checkout -b feature/readme 
```
<br>
_dando o push dessa branch no repositório_<br>
```
git push origin feature/readme
```
<br>
_verificando a branch em que está_<br>
```
git branch 
```
<br>
_adicionando o arquivo README.md e adicionando o arquivo para staging area_<br>
```
git add .
```
<br>
_git commit_<br>
```
git commit -m "adding README.md"
```
<br>
_dando o push da branch para o repositório_<br>
```
git push origin feature/readme
```
<br>
_git status_<br>
```
git status
```




  

