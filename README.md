## Comandos Básicos
- `git add .`: adiciona todos os arquivos para dar o commit
- `git commit -m "MENSAGEM"`: faz o commit (salva) o estado dos arquivos adicionados pelo comando anterior com a mensagem passada em `-m "MENSAGEM"`
- `git log --oneline`: mostra histórico com todos os commits anteriores
- `git checkout <ID_DO_COMMIT>`: volta o repositório ao estado do commit passado

### Enviar código para GitHub
- `git remote add <ALGUM_NOME_ALEATORIO> <LINK_DO_GITHUB>`: adiciona repositório remoto (GitHub) no seu computador para poder enviar os códigos para o GitHub
- Após adicionar o repositório remoto com o comando acima, execute `git push -u <nome_do_repositorio> <nome_da_branch>`. Por exemplo: `git push -u github master`
**OBS:** A flag `-u` só é necessária quando fizer o push pela primeira vez na branch. Essa flag é responsável por criar a branch no repositório remoto


### .gitignore
Arquivo que diz ao Git quais arquivos da pasta ignorar nos commits
