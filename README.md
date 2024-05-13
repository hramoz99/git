# Guia de Comandos Git

Este repositório contém uma lista de comandos úteis para trabalhar com o Git, um sistema de controle de versão distribuído amplamente utilizado.

## Introdução ao Git

O Git é uma ferramenta poderosa para o controle de versão de código fonte e colaboração em projetos de software. Abaixo estão alguns comandos essenciais do Git:

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

### Desfazendo Alterações

- `git reset <arquivo>`: Remove o arquivo do índice, mas mantém as alterações no diretório de trabalho.
- `git reset --hard HEAD`: Desfaz todas as alterações locais e retorna ao estado do último commit.
- `git revert <commit>`: Desfaz o commit especificado, criando um novo commit com as alterações revertidas.

## Contribuição

Sinta-se à vontade para contribuir com novos comandos, exemplos ou correções através de pull requests.

## Licença

Este repositório é distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.

