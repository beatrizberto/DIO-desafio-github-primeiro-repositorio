# Git & Github: add, commit, push, pull

## GIT INIT 
- abrir o Git Bash
- entrar na pasta
- criar um repositório: git init
- ls -a (lista arquivos ocultos, vai mostrar uma pasta .git)
- adicionar origem

## GIT REMOTE
- adicionar repositório remoto: git remote add [APELIDO DO REPOSITÓRIO (padrão: origin)] [link do repositório remoto]
- listar repositórios remotos associados ao repositório local: git remote -v 

## GIT ADD
- Git Add [nome de arquivo] [nome de pasta], ou Git Add . (todos os arquivos no diretório)
- manda arquivos para STAGING AREA
- Transforma arquivo UNTRACKED em TRACKED
- Arquivo pode ser MODIFIED ou UNMODIFIED
- usar GIT RESTORE to unstage arquivo ou pasta

## GIT COMMIT
- Manda arquivos STAGED para o LOCAL REPOSITORY
- Arquivo se torna UNMODIFIED
- git commit -m "MENSAGEM EXPLICANDO AS MODIFICAÇÕES"
- retorna o SHA1

## GIT PUSH
- Manda do LOCAL REPOSITORY para o REMOTE 
- git push [APELIDO DO REPOSITÓRIO REMOTO (padrão: origin)] [BRANCH (padrão: main)]

## Extra: Configurar Git no primeiro uso

- GIT config --global user.email "EMAIL"
- GIT config --global user.name "NOME"
