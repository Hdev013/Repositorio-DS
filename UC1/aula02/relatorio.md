# Aprendizados do Dia

Nesta etapa, focamos no aprendizado de ferramentas essenciais para o desenvolvimento de software, divididos em dois momentos principais:

## 1. Git & GitHub
* **Git Bash:** Aprendemos a utilizar o terminal e os principais comandos de prompt para controle de versão.
* **GitHub:** Entendemos como funciona a plataforma e como integrar nossos repositórios locais com a nuvem.

---

## 2. Visual Studio Code (VS Code)
* **Instalação:** Passo a passo de como instalar e configurar o editor de código.
* **Funcionalidades:** Exploração inicial da interface e de suas principais ferramentas e extensões.

## ultilização do git

## 1. Conectar usuario

COMANDOS

git config --global user.name "nome de usuario do git"
git config --global user.email "email do usuario do git"

<!-- Este comando usa-se somente uma vez quando necessitar de nova identificação -->
<!-- É importante na primeira vez que o git hub esteja logado, pois o sistema prescisa dar permissão, apos isso, não é nescessario estar logado -->

## para enviar para repositorio

DIGITE:

git add .
<!-- prepare os arquivos para envio -->
git commit -m "nome para rotulação"
<!-- criar chave de identificação -->
git push
<!-- envia os arquivos para repositorio -->

ESTE COMANDOS SERÃO SEMPRE EXECUTADOS, SERA UMA ROTINA A SER EXECUTADA SEMPRE PARA ATUALIZAR SEUS PROJETOS.

## PARA BAIXAR ATWALIZAÇÕES DO REPOSITORIO

git pull
<!-- baixar as atualizações dos repositorios -->
exemplo de casos:
Pedro desenvolve seus projetos no trabalho. Ele executa os comandos git add ., fit commint -m "nome" e git push.
No final de semana, em casa, pedro, clona seu projeto para seu computador pessoal. Realiza algumas alterações no projeto e atualiza no repositorio repetindo novamente os comandos: git add ., git commint -m "nome" e git push.
Na segunda feira ao chegar no trabalho, Pedro abre o terminal e aplica o comando: git pull, para atualizar no trabalho os arquivos que ele alterou no final de semana.

## Codigo para deslogar da conta