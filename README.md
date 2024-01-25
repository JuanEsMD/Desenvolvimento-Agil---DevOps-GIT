
git status: deus

git add: move o arquivo do working directory para a staging area

git commit: move a staging area para o local repo (cria um commit) e limpa a staging area

git reset: apaga um arquivo que vc não mudou da staging area

git restore: restora o arquivo da staging area para o working directory

git log: ve todos os commits da branch principal
** git log --oneline: deixa cada commit em uma linha
** git log --all: vê todos os commits de todas as branchs
** git log --graph: mostra um desenho com as branchs de cada commit
** git log -n3: só mostra os ultimos 3 commits

git checkout "nome do commit": atualiza todos os arquivos para a versão do commit
**git checkout main: volta pro presente
**git ckechout HEAD~1: volta 1 commit anterior ao HEAD (o que vc está)
**git checkout -b "nome da branch": cria uma nova branch

git merge (nome da branch_2): junta a branch_2 a branch main

