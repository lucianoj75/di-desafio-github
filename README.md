# Desafio sobre Github - DIO
Repositório criado para desafio Github na DIO

## Links Úteis
[Sintaxe básica markdown - arquivo md](https://www.markdownguide.org/basic-syntax/)

## Passo a passo
1. Criar repositório no Github
2. Criar este arquivo readme.md (opcional)
3. Clonar o repositório numa pasta local no seu PC
    - Pegar o https na opção "Clone" no seu repositório
    - Abrir o Git Bash numa pasta local no seu PC
    - Clonar repositório: `git clone https://github.com/lucianoj75/dio-desafio-github.git`
4. Subir arquivo no Github
    - Criar um arquivo qualquer dentro da pasta clonada no PC
    - Ver o status do repositório local: `git status`. O novo arquivo será apontando como disponível para commit.
    - Adicionar o novo arquivo para iniciar o commit: `git add .` (o ponto "." significa tudo)
    - Fazer commit do novo arquivo: `git commit -m "Subida de arquivo no Github"` (o comentário é para explicar esse upload)
    - Fazer push do commit para, de fato, o novo arquivo subir para o Gitub: `git push origin main` ("main" é o nome da branch quando foi criado o repositório no Github)
