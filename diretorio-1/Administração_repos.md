## Limpando arquivos untracked 
<br/>
limpar arquivos untrackeds : git clean <br/>
Utilizado para arquivos que são gerados automaticamente e atrapalham visualização do que realmente é  importante.
<br/>

## Otimizando repositório 
<br/>
Identificar e excluir arquivos que não são mais necessários, otimizando assim a performance do repositório: git gc. <br/>
git gc(garbage collector).
<br/>

## Verificando a integridade dos arquivos <br/>
Verifica a integridade e conectividade de arquivos. É um comando de rotina : git fsck(File System ChecK).<br/>

## Redflog
Mape todos os passos no repositório, é mais completo que o git log.: git reflog.
<br/>
o tempo de expiração padrão dos reflogs é até 30 dias.
<br/>

## Comprimindo o repositório
Transformar o repo em um arquivo compactado: git archive --format zip --output master_files.zip main