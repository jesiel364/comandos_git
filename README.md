# Principais Comandos git 



> Git é um sistema de controle de versão de arquivos. Através deles podemos desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo, 
editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.


## git config

Serve para você fazer as configurações  do git

` $ git config --global user.name "seu nome" `

` $ git config --global user.email "seu email"  `


## git init

Esse é o comando que você irá utilizar para criar um novo projeto de git.

` git init <nome do repositorio> `

## git clone

Esse comando Git cria uma cópia exata de um repositório já existente.

` git clone <Link do projeto> `

### git clone branch 

` git clone -b <link do projeto> `

## git add

o git add adiciona todos os arquivos modificados ao repositório

### Arquivo específico

` git add <nome do arquivo> `

### Todos os arquivos modificados


` git add . `



## git commit

O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log.

` git commit -am "Seu comentário" `


## git branch

A grosso modo, um branch é um caminho independente de desenvolvimento, uma alternativa.


### Listar todas a ramificações

` git branch `

### Criar uma nova ramificação

` git branch <nome da ramificação> `

### Deletar ramificação

` git branch -d <nome da ramificação> `



## git checkout

Serve para trocar de uma ramificação do seu projeto

` git checkout <nome da ramificação> `

### criando e alternando para nova ramificação

` git checkout -b <nova ramificação> `

## git pull

Esse comando atualiza seu repositório local com o remoto

` git pull `