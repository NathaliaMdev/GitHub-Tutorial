# Olá, este é um tutorial do git e github para iniciantes. :hamster:  


## O que é git? 

**Git é um sistema de versionamento de códigos distribuído criado por Linus Torvalds, responsável pelo compartilhamento de projetos de forma local e remota,
facilita a gestão do histórico de alterações, facilitando o controle de versões.**

**O git é utilizado através da CLI (command line interface), no qual possui sua compatibilidade de uso paras as So's Linux e Windowns, nos quais os terminais utilizados no windowns é o Shell e no linux o BASH.**

## O que é github?


**O github é uma plataforma responsável pela hospedagem de códigos fonte utilizando o git, ele permite que qualquer usuário consiga contribuir com projetos privados ou de opensource (que são públicos e autorizados a modificações).**

---
## Segue abaixo alguns comandos e atalhos conhecidos utilizando o terminal Shell:

| Tipo | Significado|
|:---------------------------------------:|:---------------------------------------------------------------------|
cd  | Acessa pastas
cd ..  | Retorna pastas abertas ( o cd e os dois pontos precisam ter espaço entre eles).
cd + Uma letra qualquer + TAB | Completa o nome da pasta
dir | Mostra todos os arquivos naquela pasta.
cls | Limpa a tela
mkdir + nome | Cria uma nova pasta
del/rmdir | Remove um diretório 
nomepasta >echo "hello">hello.txt | Cria um novo arquivo, o echo grava o que está sendo dito e transforma em um nome de arquivo.

---

## Segue abaixo alguns comandos e atalhos conhecidos utilizando o terminal BASH: ( Alguns comandos são os mesmos do shell)

| Tipo | Significado|
|:---------------------------------------:|:---------------------------------------------------------------------|
cd | Acessa pastas
cd .. | Retorna pastas abertas ( o cd e os dois pontos precisam ter espaço entre eles).
ls | Mostra todos os arquivos naquela pasta.
mkdir + nome | Cria uma nova pasta
rm-rf | Remove um diretório 
CRTL + L | Limpa a tela
nomepasta >echo "hello">hello.txt | Cria um novo arquivo, o echo grava o que está sendo dito e transforma em um nome de arquivo.

--- 

## Certo, entendo como utilizar o terminal, agora como compartilhar meus arquivos no meu github? 

        ❗ Dica: Um atalho para utilizar emotes aqui é selecionar o simbolo Windowns + "." no seu teclado

| Tipo | Significado|
|:---------------------------------------:|:----------------------------------------------------------------------------------------------|
git init | Inicializa um repositório git em uma pasta 
git config --list | Te fornece a lista de configuações, se você é novo(a) no git você precisa conferir se tem algum usuário configurado e e-mail também. 
git config --global user.email "" | configura seu e-mail para inserir nos metadados git e em paralelo conectar com o repositório remoto. 
git config --global user.name "" | configura o nome de usuário. 
git remote -v | Verifica se há um repositório remoto conectado
git remote add origin "URL" | Adiciona a URL ( caminho) de um repositório remoto ao repositório git. 
git add * ou . | Adiciona todos os arquivos novos ou alterados. 
git commit -m | Nomeia as alterações, aqui é importante dizer o que realmente foi alterado. 
git status | verifica os status do git, se os arquivos estão rastreados ou não rastreados por ele.
git push origin master ou main | Envia / Empurra todos os arquivos para o repositório remoto. 
git pull origin master ou main | Traz todos os arquivos ou alterações que estão no repositório remoto. 
git checkout -b (main/master)| Muda de Branch - Ex: de master para main  "b" = Cria uma branch se não tiver. 
git log--oneline | Histórico das últimas modificações.





