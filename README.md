
# Git e GitHub

Projeto criado pelos alunos do programa DevStart quanto a utilização do Git e GitHub. Este repositório será utilizado para armazenar dicas e comandos úteis do Git e da plataforma GitHub.


## Índice

- [Configuração inicial](#configuração-inicial)
- [Comandos Básicos](#comandos-básicos)
- [Versionamento](#versionamento)
- [Stash](#stash)
- [Autor](#autor)

## Configuração inicial

Para utilizar o git pela primeira vez, é necessário configurar seu nome de usuário e email para que os commits possam ser identificados.

Configurando seu nome:
```
git config --global user.name "Seu nome"
```

Configurando seu email:
```
git config --global user.email email@exemplo.com
```

## Comandos Básicos

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| `git init` | Inicia um repositório git na pasta atual |
| `git add` | Adiciona arquivos não monitorados para inclusão no próximo commit |
| `git commit` | Cria uma "snapshot" do repositório. Deve ser acompanhado de uma mensagem |
| `git remote` | Conecta o repositório local à um repositório remoto |
| `git status` | Mostra o estado do branch atual |
| `git clone <url>` | Clona um repositório remoto localmente |
| `git push` | Envia os commits locais para o branch remoto |
| `git pull` | Sincroniza o branch remoto com o branch local |

## Versionamento

| Comando    | Descrição                  |
|:-----------|:---------------------------|
| `git log `| Mostra todos os commits realizados no branch atual e suas informações |
| `git log --oneline`| Mostra todos os commits realizados no branch atual de forma resumida |
| `git branch` | Mostra os branchs existentes |
| `git branch <nome do branch>` | Cria um branch com um nome específico |
| `git checkout <nome do branch>` | Muda a HEAD para o branch designado |
| `git checkout -b <nome do branch>` | Cria um branch e automaticamente muda a HEAD |
| `git checkout -b <nome do branch> <hash do commit>` | Cria um branch em um commit específico |

## Stash

| Comando     | Descrição                           |
| :---------- | :---------------------------------- |
| `git stash` | Grava o estado atual da pasta na memória do sistema e remove todas as alterações realizadas desde o ultimo commit na pasta atual |
| `git stash list` | Lista todos os estados armazenados no stash |
| `git stash pop` | Retorna ao estado mais recente armazenado no stash e remove da lista de stashs |
| `git stash apply` | Similar ao comando pop, mas não remove o estado da lista |
| `git stash@{numero do stash}` | Retorna ao stash especificado na lista |
| `git stash drop` | Remove um stash específico da lista |
| `git stash clear` | Limpa o histórico de stashs |


## Autor

- [@Fellipe Luz](https://www.github.com/chulipinho)

