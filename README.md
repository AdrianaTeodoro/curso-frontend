# curso-frontend

# GIT
## versionamento
- Histórico
- Controle da versão
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A | Versão 1 | Versão 2
Arquivo B | Versão 1 | Versão 2

## Instalação do Git

Linux (apt-get): sudo apt-get install git
Mac (brew): brew install git

## Criar uma conta go GitHub

## Clonar o projeto
git clone https://github.com/AdrianaTeodoro/curso-frontend.git
## Commits
Informação de alteração
- após testado todo seu código
- git add*
- git commit -m "mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer do Github para sua máquina)

## GitFlow
Fluxo do Git

## Branchs
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)

### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente

git merge main

### Pull Requests
Mescla de branchs no repositório
Permite o code review
O repositório resolve os conflitos automaticamente  

### configura o GitFlow
git flow init
git flow feature start melhoria-html {nome-da-feature}