
# DIO - Github

## Versionamento de Código com Git e GitHub

👍 Curso adquirido pelo Bootcamp das Bolsas do Santander em parceria com a DIO.

## Comandos Necessários

```
    mkdir nome [Cria uma pasta para trabalho]

    cd .. [Retorna para o diretório anterior]

    git init [Para inicializar um repositório Git no diretório]
    
    touch arquivo.extensão [ex: touch README.md] [cria um arquivo dentro do diretório]

    rm -rf arquivo [Exclui o arquivo do diretório, no caso do rm -rf .git, você tira este diretório do git]

    git commit -m"texto de commit"

    git status [Pode ver quais arquivos ainda não foram adicionados]

    git add nomearquivo [Se usar "git add .", vai ser upado todos os arquivos novos] [Salva alterações no reposítorio, usando o "git add .", você salva todas as alterações]

    git remote add origin URL [Você vai conectar o reposítorio local ao repositório remoto no github, é necessário que a URL seja um repositório seu.]

    git restore <nome_arquivo> [Você restaura o arquivo para a sua última versão salva]
    
    git log [Vê o último commit realizado]

    git commit --ammend -m"nova mensagem" [Atualiza a mensagem do commit]

    git reset <--soft / --mixed / --hard> <id_do_commit(Você acha no git log)> 
    [Desfazer o commit realizado] [<- Parâmetros para restaurar]
    [Esse comando consegue puxar as alterações dos commit's anteriores
    ao indicado pelo id.
    "--soft", ele pega as alterações dos commits anteriores e já adiciona na aréa de trabalho.
    "--mixed", ele pega as alterações anteriores porém não adiciona na área de trabalho
    o que temos que fazer o "git add ." para adicionar
    "--hard", retorna para o commit indicado pelo ID, apagando todos os arquivos que não sejam do commit indicado]

```