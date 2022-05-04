
# Integração do Git com o GitHub

<p align="center" >Desktop -> Àrea de unstage -> Repositório</p> 

### Requisitos :
1. Baixar e Instalar o <a href="https://git-scm.com/" target="_blank">Git</a>

* Crie um arquivo.md
* No arquivo (file), com o botão direito do mouse, clique em Git Bash

### Primeiros Passos 
* Alterar o exibir, habilitanto as : 
    * Pastas ocultas
    * Extensão de arquivo
* Abrir o Git Bash
## Comandos
1. Identificação
```bash
git --global user.name "pedroliveirahm"
git --global user.email pedroliveirahm@gmail.com
```
2. Achar o diretório - pasta 
```bash
cd local-do-arquivo
cd ..
# para voltar pastas

* Ou apertar com botão esquerdo do mouse e clicar em git bash na própria pasta
```

3. Criar um repositório no github
### Comandos principais
```bash
git init
# inicia uma conexão com a pasta
# esse comando só é feito 1 vez no diretório

git branch -M main
# entra na branch main (principal)
# esse comando só é feito 1 vez no diretório

git add nome-do-arquivo
# esse passo coloca o arquivo em unstage - estado de preparação para receber um commit

git status
# mostra os status - o que está na pasta, o que está em unstage, o que foi comitado, excluído, alterado ...

git commit -m "descrição do commit"
# o commit é uma efetivação das alterações
# prepara os arquivos que estavam em unstaged para enviar para o servidor

git remote add origin link-do-repositório
# diz para onde o commit será enviado
# essa etapa só precisa ser feita uma primeira vez

git push origin main 
# a partir daqui os arquivos já estarão disponíveis no github
```

### Comandos Secudários
```bash
git reset
# tira os arquivos que estavam em unstaged

git clone repositório_link
# clona algum repositório público do github
```
### Comandos de Branch
```bash
git branch
# semelhante ao git status, o git branch vê quais branchs estão disponíveis

git branch nome-da-branch
# cria uma branch alternativa no nome escolhido

git chekout main
# sai da branch main

git merge nome-branch
# junta as branchs (merge)

git branch -d nome-branch
# -d (delete) exclui a branch 

git branch -m antigo-nome novo-nome
# renomeia a branch
```
### Atalhos
<p>Ctrl + L -> Clear</p>

---
Made with by 💙 Pedro PC 👋 <a href="https://github.com/pedroliveirahm">Seen my GitHub</a>
* <strong>Fale comigo : <a href="https://bio.link/pedroliveirahm" target="_blank">Contato</a></strong>