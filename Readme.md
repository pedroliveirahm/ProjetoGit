-> Integração do Git com o GitHub,

 - Processo: Diretório -> Aréa de standing -> Repositório

 - Após a inicialização do Git Bash na pasta, comandos:

 • git init
 -init(initialized) 

 • git branch -M main
 - acesso a branch principal (main)

 • git add file_name 
 - git add.  \\ para adicionar todos os arquivos em standing

 • git status

 • git commit -m "primeiro commit"  

 • git remote add origin link_do_repositório

-> Salvar novamente, comandos:

 • git add file_name // git add .

 • git status

 • git commit -m "alteração do projeto"

 • git push origin main

-> Criação de uma nova branch, comandos

 • git branch branch_name // git checkout -b "novo-botao"
 - Cria uma nova branch chamada "novo-botao"
 - Com o checkout: branch (main) -> nova branch (novo-botao)

 • git add file_name // git add .

 • git commit -m "caracter"

 • git push origin novo-botao

-> Junção das branches (merge), comandos:
 
 • git merge branch_name

-> Excluir branches
 
 • git branch
 - saber quais os branches disponíveis

 • git branch -d branche_name

-> Renomear branches

 • git branch -m last_name new_name

 -> Clone do repositório

 -Após criar uma nova pasta para guardar o clone do repositório

 • git clone repository_link