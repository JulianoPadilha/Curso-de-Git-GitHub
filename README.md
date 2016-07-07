# Curso de Git e GitHub

<h4 align="center">COMANDOS BÁSICOS</h4>

<b>Inicializa um repositório Git vazio</b>
<br><code>git init</code>

<b>Inicializa um repositório Git</b>
<br><code>git init <i>nome do repositório</i></code>

<b>Definição da assinatura/nome do usuário de cada commit 
O --global aplica a configuração para todos os repositórios que usar no git. Se tirar o --global a configuração fica só no repositório atual.</b> 
<br><code>git config --global user.name <i>"nome de usuário"</i></code>

<b>Definição da email do usuário de cada commit</b> 
<br><code>git config --global user.email <i>e-mail</i></code>

<b>Mostra o status dos arquivos dentro do repositório (arquivos rastreados) 
Arquivos não rastreados significa que estão apenas no repositório de trabalho local</b> 
<br><code>git status</code>

<b>Adiciona um arquivo no meu index </b>
<br><code>git add <i>nome do arquivo</i></code>

<b>Adiciona mais de um arquivo no meu index graças ao .</b> 
<br><code>git add .</code>

<b>Enviar o arquivo para o HEAD/fazer o commit 
O -m server para fazer um comentário para o commit </b>
<br><code>git commit -m "<i>comentári</i>o"</code>

Mostra o log de uso 
<br><code>git log </code>

<b>Criar um arquivo .gitignore e dentro dele especificar os arquivos e diretórios a serem ignorados pelo git. 
Escrever dentro do .gitignore apenas o que quer ignorar </b>
	<br>.gitignore
	Ex: config.js - ignora um arquivo<br>
	adm/ - ignora uma pasta<br>
	*.extensão - ignora todos os arquivos com essa extensão

<b>Adiciona um novo branch</b>
<br><code>git branch <i>nome do branch</i></code>

<b>Muda de branch </b>
<br><code>git checkout <i>nome do branch</i></code>

<b>Cria um novo branch e já muda para ele</b>
<br><code>git checkout -b <i>nome do branch</i></code>

<b>Apaga um branch </b>
<br><code>git branch -D <i>nome do branch</i></code>

<b>Mescla branchs </b>
<br><code>git merge <i>nome do branch que quero mesclar</i></code>

<b>Atualizar</b>

<b>Clonar um repositório </b>
<br><code>git clone <i>endereço do repositório</i></code>

<b>Mostra os repositórios remotos </b>
<br><code>git remote show</code>

<b>Fazer um push e enviar o commit para o remote </b>
<br><code>git push <i>nome do remote + nome do branch</i></code>

<b>Puxando as alterações que estão no repositório remoto</b>
<br><code>git pull <i>origin + master</i></code>


Fonte: https://www.youtube.com/watch?v=TReVFOxhh7E&index=1&list=PL77JVjKTJT2h4aACrIx1ECmr8h9esjh16
