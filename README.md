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

_verificando o vínculo do repositório remoto_<br>

```
git remote -v
```

_estando dentro do diretório,  foram colocados os arquivos analgesicos.txt e farmacias.txt, depois adicionei todos os arquivos para a staging area_<br>

```
git add . 
```

_verificando o status_<br>

```
git status
```

_então, fiz o commit_<br>

```
git commit -m "initial commit" 
```

_verificando o log_<br>

```
git log 
```

_e assim, foi feito o push para o repositório na branch main_<br>

```
git push origin main 
```

## Criando a branch feature/readme e adicionando o README.md

_criando outra branch chamada feature/readme_<br>

```
git checkout -b feature/readme 
```

_dando o push dessa branch no repositório_<br>

```
git push origin feature/readme
```

_verificando a branch em que está_<br>

```
git branch 
```

_adicionando o arquivo README.md e adicionando o arquivo para staging area_<br>

```
git add .
```

_git commit_<br>

```
git commit -m "adding README.md"
```

_dando o push da branch para o repositório_<br>

```
git push origin feature/readme
```

_git status_<br>

```
git status
```




  

