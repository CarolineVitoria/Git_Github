# Comandos
Para obter todas as branches e tags que ainda não são reconheicidas : git fetch <br/>
Para receber atualizações do repositório remoto: git pull <br/>
Enviar açterações pro repo remoto: git push <br/>
para ver as url do repositório: git remote -v <br/>
para apagar a url do repositório remoto: git remote rm <nome>
para adicionar caminho pro repositório: git remote add <nome> <url>
**submódulo** : 
Forma de possuir dois ou mais projetos em um único repositório.
para adicionar submódulo: git submodule add <repo>
para verfificar os submódulos: git submodule
Para enviar para o repo remoto do submodulo: git push --recurse-submodules=on-demand
