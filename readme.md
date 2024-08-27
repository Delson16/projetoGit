Aprendendo a usar o git para fazer o upload

comando do git

verifica a versão do git instalado no sistema
git --version 

iniciando um repositório vazio
git init

O (master) exibido sinaliza que está é a linha principal de alterações do código 

Manda os arquivos para área de stading (eles ficam preparados para serem upados)
git add

comando que informa o que está na área de stading
git status

Definindo nome e e-mail do usuário que está usando o git (eu no caso)
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"

Realizando o comit
git commit -m "mensagem para o commit"

shift +  insert -> substitui o ctr + v no prompt

comando para conectar o repositório local para o Github -> ele não envia o arquivo, apenas conecta
git remote add origin https://github.com/Delson16/projetoGit.git

remote -> conexão do repositório local com o do github
add -> adiciona o repositório local
origin -> nome que estamos dando para o repositório e seu link

realiza o upload dos arquivos para o github. o ultimo comando (master), deve conter o nome da linha principal de alteração no código, neste caso e master, mas também é comum ser main
git push -u origin master 

Códigos alterados para um segundo commit

retornando a breach master
git  checkout master 

adicionando o branch do novo botão ao branch master
git merge novo-botao

delson disse 








