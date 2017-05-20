git init
git status

git remote add origin https://github.com/jlanssarini/workshop_epic.git




## ARQUIVO README


#### Efetuar modificacoes e git diff

sempre nessa ordem:
	git add nomedoarquivo
	git commit -m "MENSAGEM"

#### ainda nao está no github. Para isso precisa do git push:

	git  push --set-upstream origin master:master

ele vai conectar as master remota com a branch (master_remota:master_branch)


VARIOS ARQUIVOS.....

COmando para os LOGS
	git log

COMANDO PARA DESFAZER GIT ADD
	git reset ARQUIVO     // eh o oposto do ADD
	git checkout ARQUIVO   //por padrao busca o ultimo commit local mas pode passar novos parametros...


CRIAR BRANCH
	git branch novabranch
Posicionar o HEAD para a nova Brach
	git checkout novabranch

Porem para dar o novo push, eh preciso sincronizar d novo a MASTER pelo comando do set UPSTREAM
	git  push --set-upstream origin master:master

Pra juntar as duas BRANCH basta dar um merge
	git merge NovoBranch
	