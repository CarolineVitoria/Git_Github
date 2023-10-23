# Branches
Branches são ramificações de um projeto

## Comandos:
### Branch
criar branch: git branch <nome>
listar branches: git branch
deletar branch: git checkout -d
mudar de branch: git checkout <nome>
criar e mudar de branch: git checkout -b <nome>
### Stash
criar stash: git stash
verificar lista de stash: git stash list
recuperar a stash: git stash <nome>
cria mensagem/nome para stash: git stash create<mensagem> / git stash save <mensagem>
apagar uma stash: git stash drop <indice>
apagar todas stashs: git stash clear

### Tags
Tags servem como checkpoint de uma branch. Servem para marcar estágios de desenvolvimento de algum recurso.
criar tag: git tag -a <nome> -m"<msg>"

## Notas:
É necessário commitar antes de mudar de branch
Use o git pull antes de criar uma branch
stash só funciona em mudanças não commitadas