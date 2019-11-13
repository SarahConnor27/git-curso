#github

Ciclo de vida dos status dos arquivos:

São 4 estados:

untracked -> não marcado, arquivo acabou de ser adicionado no repositório, mas ainda não foi visto pelo git, não há versão para existencia desse arquivo. É um arquivo novo.

unmodified-> depois de adicionar o arquivo para ser enxergado pelo git, ele se torna unmodified, não foi modificado

modified -> ao editar um arquivo adicionado ele passa a ser modified

staged -> quando o arquivo recebe uma versão do git, ele é jogado para a área de staged, isso ocorre qdo damos o commit, todos os arquivos comitados recebem o status de unmodified.


5) Estado do git 
git status

6) adicionar o arquivo para monitoração do git:
git add

7) cria versão/ snapshot dos arquivos
git commit -m "Readme.md" 
git commit -am "Readme.md para arquivos que já existem" 

13d1651 é o número do commit, para retroceder à uam versão, basta usar esse número.
[master (root-commit) 13d1651] 1º Commit Readme.md
 1 file changed, 25 insertions(+)
 create mode 100644 Readme.md


8) Log

git log

git log --decorate

git log --author="Sara"

git shortlog

git shortlog -sn

git log --graph

git show <idDoCommit>


9) Diff

ver mudanças ants de enviar o commit

git diff

git diff --name-only -> somente o nome dos aquivos que foram modificados











