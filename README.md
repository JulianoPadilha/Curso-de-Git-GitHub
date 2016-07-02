# Curso de Git e GitHub

COMANDOS BÁSICOS

<!-- Inicializa um repositório Git vazio -->
git init

<!-- Definição da assinatura/nome do usuário de cada commit -->
<!-- O --global aplica a configuração para todos os repositórios que usar no git. Se tirar o --global a configuração fica só no repositório atual. -->
git config --global user.name "nome"

<!-- Definição da email do usuário de cada commit -->
git config --global user.email email

<!-- Mostra o status dos arquivos dentro do repositório (arquivos rastreados) -->
<!-- Arquivos não rastreados significa que estão apenas no repositório de trabalho local -->
git status

<!-- Adiciona um arquivo no meu index -->
git add nome do arquivo

<!-- Adiciona mais de um arquivo no meu index graças ao . -->
git add .

<!-- Enviar o arquivo para o HEAD/fazer o commit -->
<!-- O -m server para fazer um comentário para o commit -->
git commit -m "comentário"

<!-- Mostra o log de uso -->
git log 

<!-- Criar um arquivo .gitignore e dentro dele especificar os arquivos e diretórios a serem ignorados pelo git. -->
<!-- Escrever dentro do .gitignore apenas o que quer ignorar -->
.gitignore
Ex: config.js - ignora um arquivo
	adm/ - ignora uma pasta
	*.extensão - ignora todos os arquivos com essa extensão

<!-- Adiciona um novo branch -->
git branch nome do branch

<!-- Muda de branch -->
git checkout nome do branch

<!-- Cria um novo branch e já muda para ele -->
git checkout -b nome do branch

<!-- Apaga um branch -->
git branch -D nome do branch

<!-- Mescla branchs -->
git merge nome do branch que quero mesclar

<!-- Clonar um repositório -->
git clone endereço do repositório

<!-- Mostra os repositórios remotos -->
git remote show

<!-- Fazer um push e enviar o commit para o remote -->
git push nome do remote nome do branch
