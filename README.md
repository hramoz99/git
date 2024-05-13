# Introdução ao Git 

Este repositório contém uma lista de comandos úteis para trabalhar com o Git, um sistema de controle de versão distribuído amplamente utilizado.

## Guia de Comandos Git

Abaixo estão alguns comandos essenciais do Git:

### Configuração Inicial

- `git config --global user.name "Seu Nome"`: Define o nome do usuário para commits.
- `git config --global user.email "seuemail@example.com"`: Define o e-mail do usuário para commits.

### Iniciar um Repositório

- `git init`: Inicia um novo repositório Git no diretório atual.
- `git clone <url>`: Clona um repositório remoto para o seu computador.

### Trabalhando com Mudanças

- `git status`: Verifica o status das alterações no repositório.
- `git add <arquivo>`: Adiciona arquivos ao índice para prepará-los para o commit.
- `git commit -m "Mensagem do Commit"`: Registra as alterações no repositório.

### Ramificações e Mesclagens

- `git branch`: Lista todas as ramificações locais.
- `git branch <nome>`: Cria uma nova ramificação com o nome especificado.
- `git checkout <nome>`: Muda para a ramificação especificada.
- `git merge <ramificação>`: Mescla uma ramificação à ramificação atual.

### Trabalhando com Remotos

- `git remote add <nome> <url>`: Adiciona um novo repositório remoto.
- `git push <remoto> <ramificação>`: Envia alterações locais para um repositório remoto.
- `git pull <remoto> <ramificação>`: Atualiza o repositório local com as alterações do remoto.
- `git fetch <remoto>`: Baixa todas as ramificações do repositório remoto.

