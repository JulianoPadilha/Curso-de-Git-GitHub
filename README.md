# Curso de Git e GitHub

COMANDOS BÁSICOS

<b>Inicializa um repositório Git vazio</b>
<br><code>git init</<code>code>

<b>Definição da assinatura/nome do usuário de cada commit 
O --global aplica a configuração para todos os repositórios que usar no git. Se tirar o --global a configuração fica só no repositório atual.</b> 
<br><code>git config --global user.name "nome"</code>

<b>Definição da email do usuário de cada commit</b> 
<br><code>git config --global user.email email</code>

<b>Mostra o status dos arquivos dentro do repositório (arquivos rastreados) 
Arquivos não rastreados significa que estão apenas no repositório de trabalho local</b> 
<br><code>git status</code>

<b>Adiciona um arquivo no meu index </b>
<br><code>git add nome do arquivo</code>

<b>Adiciona mais de um arquivo no meu index graças ao .</b> 
<br><code>git add .</code>

<b>Enviar o arquivo para o HEAD/fazer o commit 
O -m server para fazer um comentário para o commit </b>
<br><code>git commit -m "comentário"</code>

Mostra o log de uso 
<br><code>git log </code>

<b>Criar um arquivo .gitignore e dentro dele especificar os arquivos e diretórios a serem ignorados pelo git. 
Escrever dentro do .gitignore apenas o que quer ignorar </b>
	<br>.gitignore
	Ex: config.js - ignora um arquivo<br>
	adm/ - ignora uma pasta<br>
	*.extensão - ignora todos os arquivos com essa extensão

<b>Adiciona um novo branch</b>
<br><code>git branch nome do branch</code>

<b>Muda de branch </b>
<br><code>git checkout nome do branch</code>

<b>Cria um novo branch e já muda para ele</b>
<br><code>git checkout -b nome do branch</code>

<b>Apaga um branch </b>
<br><code>git branch -D nome do branch</code>

<b>Mescla branchs </b>
<br><code>git merge nome do branch que quero mesclar</code>

<b>Clonar um repositório </b>
<br><code>git clone endereço do repositório</code>

<b>Mostra os repositórios remotos </b>
<br><code>git remote show</code>

<b>Fazer um push e enviar o commit para o remote </b>
<br><code>git push nome do remote nome do branch</code>
