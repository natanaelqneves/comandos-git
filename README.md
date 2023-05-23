comandos-git
Comandos e funcionalidades da ferramenta de versionamento Git

Define nome de usuário
git config --global user.name "nome-de-usuario"

Define email do usuário
git config --global user.email email-do-usuario@email.com

Clona repositório GIT
git clone gttps://caminho/do/repositorio/no/git

Inicia projeto GIT local
git init

Indica o estado do porjeto GIT, untracked, unmodified, modified, staged
git status

Apresenta modificações entre versões do arquivo observado
git diff 
git diff --staged

Devine e envia a versão recente do projeto
git commit -m "descrição das alterações para essa versão"

Mostra as movimentações/históricos do projeto GIT
git log

Retoma a versão anterior do projeto
git restore caminho/do/arquivo
git restore --staged caminho/do/arquivo

Envia os arquivos do projeto para repositório GIT em nuvem
git push

Recebe alterações do arquivo em nuvem
git pull

Recebe informações sobre alterações realizadas em nuvem antes de realizar o push
git fetch
git diff origin/main (mostra quais alterações foram efetuadas)

Criar nova BRANCH
git branch nome-da-branch

Muda A BRANCH
git checkout nome-da-branch

Juntar arquivos de branchs diferentes
git merge branch-agregado

