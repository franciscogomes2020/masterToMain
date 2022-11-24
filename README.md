# codigos para mover do branch master para main

## clonar meu repositorio
`git clone https://github.com/franciscogomes2020/masterToMain.git`

## mover tudo do branch master para main
`git branch -m master main`

## pegar a url do repositorio que clonei
`git remote get-url origin`

## colocar meu token no url
`git remote set-url origin https://<MEU-TOKEN>@github.com/franciscogomes2020/masterToMain.git`

## enviar o branch main para o repositorio online
`git push origin main`

## deletar o branch master (depois de tirar ele do default)
`git push origin --delete master`

## limpar o rastreamento dos branchs
`git branch --unset-upstream`

## criar novo rastreamento para o branch main
`git branch -u origin/main`

## baixar dados mas não atualizar o repositorio (apenas para verificar se tem atualizações)
`git fetch`

## enviar todo o meu repositorio da minha maquina para o repositorio online 
`git push --force-with-lease`
