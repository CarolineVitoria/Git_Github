# Branches
Branches são ramificações de um projeto

### Branch
criar branch: git branch <nome> <br/>
listar branches: git branch <br/>
deletar branch: git checkout -d <br/>
mudar de branch: git checkout <nome> <br/>
criar e mudar de branch: git checkout -b <nome> <br/>

### Stash
criar stash: git stash <br/>
verificar lista de stash: git stash list <br/>
recuperar a stash: git stash <nome> <br/>
cria mensagem/nome para stash: git stash create<mensagem> / git stash save <mensagem> <br/>
apagar uma stash: git stash drop <indice> <br/>
apagar todas stashs: git stash clear <br/>

### Tags
Tags servem como checkpoint de uma branch. Servem para marcar estágios de desenvolvimento de algum recurso. <br/>
criar tag: git tag -a <nome> -m"<msg>" <br/>
lista os nomes das tags: git tag <br/>
lista aos commits e as tags que elas tão vinculadas: git show / git show <nome> <br/>
deletar tags: git tag -d <nome> <br/>
compartilhar uma tag: git push origin <nome> <br/>
compartilhar todas as tags: git push origin --tag <br/>

## Notas:
É necessário commitar antes de mudar de branch <br/>
Use o git pull antes de criar uma branch <br/>
Stash só funciona em mudanças não commitadas <br/>
É importante commitar antes de criar uma tag, pois eal se vincula a commits, diferente da stash <br/>