### `COMANDOS`


#### Iniciar um novo repositório Git
```
git init
```

#### Clonar o repositório para uma pasta específica
```
git clone <repositorio-clonado> <meu-projeto-clone>
```

#### Clonar o repositório a partir de uma branch específica
```
git clone -b <nome-branch> <repositorio-clonado>
```

#### Listar todos os arquivos que foram modificados.
```
git status
```
 
#### Adicionar alterações em um arquivo
```
git add <nome-do-arquivo>
```

#### Adicionar todas as modificações realizadas de uma só vez
```
git add .
```
#### Capturar e salvar o estado atual do repositório
```
git commit -m "Informar modificação"
```

#### Mover o seu repositório Git para um commit específico
```
git checkout <hash>
```

#### Mesclar as alterações
```
git merge <nome-da-branch>
```

#### Reescrevendo as alterações 
```
git rebase titulo
```

#### Visualizar as diferenças entre as alterações no seu diretório de trabalho
```
git diff <origem> <destino>
```

#### Verificar o histórico de alterações
```
git log
```

#### Visualizar os commits (um em cada linha)
```
git log --oneline
```

#### Visualizar as alterações do commit
```
git log -p
```

#### Visualização formatada das informações de um commit
```
<> Traz o hash seguido da mensagem de commit

git log --pretty="format:%h %s"
```

#### Verificar o histórico de forma gráfica
```
git log --graph
```

#### Pesquisar as informações do autor
```
git log --author="user-name"
```

#### Visualizar informações detalhadas de um arquivo
```
git blame <nome-do-arquivo>
```

#### Pesquisar informações por data
```
<> Traz as informações do commit desde um mês atrás até o dia anterior

git log --since=1.month.ago --until=1.day.ago
```

#### Enviar as modificações ao repositório remoto
```
git push <nome-servidor> <nome-ramificação>
```

#### Baixar as alterações realizadas
```
git pull <nome-do-repositório> <nome-da-ramificação>
```

#### Desfazer as alterações em um arquivo e controlar o estado do índice
```
<> Desfazer o commit mais recente e manter as alterações na área de preparação

git reset --soft HEAD~1
```

```
<> Desfazer o commit mais recente e remover as alterações da área de preparação

git reset <opção> <commit>
```

```
<> Descartar completamente o commit mais recente, incluindo as alterações no diretório

git reset --hard HEAD~1
```

#### Criar um novo commit que desfaz as alterações salvas
```
git revert <hash>
```

#### Restaurar arquivos, voltando para um estado anterior
```
git restore <nome-do-arquivo>
```

#### Criar uma branch
```
git branch <nova-branch>
```

#### Mudar para uma branch
```
git checkout <nome-da-branch>
```

#### Criar uma nova branch e mudar automaticamente
```
git checkout -b <nome-da-branch>
```

#### Remover uma branch
```
git branch -d <nome-branch>
```

#### Remover uma branch em que os commits ainda não estejam na branch atual
```
git branch -D <nome-branch>
```

#### Encontrar no código alguma alteração ou bug introduzido
```
<> Iniciar o processo de bisect

git bisect start
```

```
<> Indicar o estado: bom e o ruim

git bisect good [commit] 

git bisect bad [commit] 
```

```
<> Finalizar o processo de bisect

git bisect reset
```

#### Copiar um único commit de uma ramificação para outra
```
git cherry-pick [hash_do_commit]
```


#### Salvar temporariamente as alterações locais em um repositório Git
```
git stash
```

#### Trazer as alterações salvas no stash
```
git stash pop
```

#### Criar ou Remover tags em um repositório
> As tags são usadas para marcar pontos específicos no histórico do repositório.
```
git tag <nome-da-tag> <hash-do-commit>
```

----------------------------------------------------------------------------------------
 **LINKS**
  ```
  https://devhints.io/git-log
  https://git-scm.com/docs/git-clone
  https://guilhermeonrails.github.io/manual-do-git-e-github/
  ```
