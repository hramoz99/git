### `COMANDOS`


#### Verificar o histórico de alterações
```
git log
```

#### Visualizar os commits (um em cada linha)
```
git log --oneline
```
#### Visualizar mais como as alterações do commit
```
git log -p
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
#### Adicionar Alterações em um arquivo
```
git add [nome_do_arquivo]
```
#### Adicionar todas as modificações realizadas de uma só vez
```
git add .
```

#### Capturar e salvar o estado atual do repositório
```
git commit.
```

#### Enviar as modificações ao repositório remoto
```
git push [nome_servidor] [nome_ramificação]
```
#### Restaurar arquivos, voltando para um estado anterior
```
git restore [nome_do_arquivo]
```
git add

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
#### Mesclar as alterações
```
git merge [nome_da_branch
```
#### Verificar o histórico de forma gráfica
```
git log --graph
```
#### Reescrevendo as alterações 
```
git rebase titulo;
```

#### Baixar as alterações realizadas
```
git pull [nome_do_repositório] [nome_da_ramificação]
```
#### Desfazer alterações em um repositório, controlar o estado do índice e do diretório
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

11) Rode o comando git revert {hash}, substituindo {hash} pelo hash que você copiou anteriormente;

14) Execute o comando git stash para salvar estas alterações na stash;

17) Execute o comando git stash pop para trazer a última alteração da stash;

18) Execute o comando git add index.html e o comando git commit -m "Alterando o nome do curso de Ansible" para realizar um commit;

19) Execute o comando git push local master para enviar todas as suas alterações;

20) Execute o comando git log --oneline para ver os commits de forma resumida. Copie o hash do commit de merge com a branch lista;

21) Execute o comando git checkout {hash} substituindo {hash} pelo hash que você copiou;

22) Veja que diversas alterações não estão mais presentes;

23) Execute git checkout master para voltar à linha principal de desenvolvimento.


 Execute o comando git log -p para ver, junto a cada commit, as alterações nele realizadas;

2) Execute agora o comando git log --oneline;

3) Execute o comando git diff {hash do commit de merge com lista}..{hash do último commit realizado};

4) Execute alguma (pequena) alteração no index.html;

5) Execute o comando git diff e veja esta alteração;

6) Desfaça esta última alteração;

7) Execute o comando git tag -a v0.1.0 para criar uma tag no seu código;

8) Execute o comando git push origin v0.1.0 para enviar esta tag para o GitHub;

9) Abra a página do repositório do GitHub que você criou e confira a aba de Releases.
----------------------------------------------------------------------------------------
 **LINKS**
  ```
  https://devhints.io/git-log
  https://git-scm.com/docs/git-clone
  https://guilhermeonrails.github.io/manual-do-git-e-github/
  ```
