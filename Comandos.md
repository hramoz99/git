### `COMANDOS`


#### Iniciar um novo repositório Git
```
git init
```

#### Clonar o repositório para uma pasta específica
```
git clone [repositorio_clonado] [meu-projeto-clone]
```

#### Clonar o repositório a partir de uma branch específica
```
git clone -b [nome_branch] [repositorio_clonado]
```

#### Listar todos os arquivos que foram modificados.
```
git status
```
 
#### Adicionar alterações em um arquivo
```
git add [nome_do_arquivo]
```

#### Adicionar todas as modificações realizadas de uma só vez
```
git add .
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

#### Verificar o histórico de forma gráfica
```
git log --graph
```

#### Pesquisar as informações do autor
```
git log --author="user_name"
```

#### Pesquisar informações por data
> Apresenta as informações do commit desde um mês atrás até um dia atrás.
```
git log --since=1.month.ago --until=1.day.ago
```

#### Formatar a visualização das informações de commit
> Traz o hash seguido da mensagem de commit.
```
git log --pretty="format:%h %s"
```

#### Capturar e salvar o estado atual do repositório
```
git commit
```

#### Enviar as modificações ao repositório remoto
```
git push [nome_servidor] [nome_ramificação]
```

#### Restaurar arquivos, voltando para um estado anterior
```
git restore [nome_do_arquivo]
```

#### Criar uma branch
```
git branch [nova_branch]
```

#### Mudar para uma branch
```
git checkout [nome_da_branch]
```

#### Criar uma nova branch e mudar automaticamente
```
git checkout -b [nome_da_branch]
```

#### Remover uma branch
```
git branch -d {nome_branch} remove uma branch que já tem seu trabalho unido à branch atual
```

#### Remover uma branch em que os commits ainda não estejam na branch atual
```
git branch -D {nome_branch}
```

#### Encontrar no código alguma alteração ou bug introduzido
```
Iniciar o processo de bisect
git bisect start

Indicar o bom e o ruim:
git bisect good [commit] (Indica um commit bom.)
git bisect bad [commit] (Indica um commit ruim.)


Repetir até encontrar o commit problemático:

Finalizar o processo de bisect:
git bisect reset
```

```
git cherry-pick <hash-do-commit>
```

#### Visualizar quem é o responsável por cada linha no código
```
git blame
```

#### Mesclar as alterações
```
git merge [nome_da_branch
```

#### Reescrevendo as alterações 
```
git rebase titulo;
```

#### Baixar as alterações realizadas
```
git pull [nome_do_repositório] [nome_da_ramificação]
```

#### Desfazer as alterações em um repositório, controlar o estado do índice
> Move a HEAD para um commit específico e redefine o índice, mas mantém as alterações nos arquivos.
```
git reset 
```

> Move a HEAD para um commit específico, mas mantém todas as alterações no índice e no diretório
```
git reset --soft HEAD~1
```
> Redefine o índice e descarta todas as alterações nos arquivos em seu diretório de trabalho.
```
git reset --hard HEAD~1
```
#### Criar um novo commit que desfaz as alterações de um commit específico (identificado pelo seu hash)
```
git revert {hash}
```

#### Salvar temporariamente as alterações locais em um repositório Git
```
git stash
```

#### Trazer as alterações salvas no stash
```
git stash pop
```

#### Mover o seu repositório Git para um commit específico
```
git checkout {hash}
```

#### Visualizar as diferenças entre as alterações no seu diretório de trabalho
```
git diff [origem]} [destino]
```

#### Criar ou Remover tags em um repositório
> As tags são usadas para marcar pontos específicos no histórico do repositório.
```
git tag -a v0.1.0 para criar uma tag no seu código;
```

----------------------------------------------------------------------------------------
 **LINKS**
  ```
  https://devhints.io/git-log
  https://git-scm.com/docs/git-clone
  https://guilhermeonrails.github.io/manual-do-git-e-github/
  ```
