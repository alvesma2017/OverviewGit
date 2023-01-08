
GIT = GERENCIADOR DE CÓDIGO FONTE

Sistema de controle de versão distribuido, usando principalmente no desenvolvimento de SW.

Por que devemos controlar versão de código fonte?
    - Segurança (Quem?)
    - Rastreabilidade (Quando?)
    - Rollback
    - Histórico
    - Colaboração (repo centralizado e disponibilizado a todos)

Utilização: linha de comando ou SourceTree

PRINCIPAIS COMANDOS:
https://github.com/joshnh/Git-Commands

git init = Inicializa um repositório Git local
git clone ssh://git@github.com/[usuario]/[nome-repositorio].git = Cria uma cópia local de um repositório remoto
git status = Checa o status
git add [nome-arquivo.txt] = Adiciona um arquivo para área de stage
git add -A OU git add . = Adiciona todos os arquivos novos ou modificados para a área de stage
git commit -m "[Mensagem de Commit]" = Comita as alterações
git rm -r [nome-arquivo.txt] = Remove um arquivo (ou pasta)
git pull = Atualiza o repositório local para o último commit
git push = Envia as alterações para o repositório remoto (branch atual)

BRANCHES:
Ramificação do código principal para que seja possível fazer alterações sem nenhum tipo de problema. 
É importante ressaltar que uma ramificação não depende da outra para ser desenvolvida.

git branch = Lista as branches (o asterisco denota a branch atual)
git branch -a = Lista todas as branches (local e remoto)
git branch [nome da branch] = Cria uma nova branch
git branch -d [nome da branch] = Deleta uma branch
git push origin --delete [nome da branch] = Deleta uma branch remota
git checkout -b [nome da branch] = Cria uma nova branch e muda para ela
git checkout -b [nome da branch] origin/[nome da branch] = Clona uma branch remota e muda para ela
git checkout [nome da branch] = Seleciona uma branch
git merge [nome da branch] = Faz um merge de uma branch na branch atual
git merge [source branch] [branch alvo] = Faz um merge de uma branch em outra branch
git push origin [nome da branch] = Enviar uma branch para seu repositório remoto
git pull origin [nome da branch] = Recebe alterações do repositório remoto