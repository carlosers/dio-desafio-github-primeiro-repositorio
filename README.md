# Repositório do Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o desafio do projeto para o bootcamp **everis New Talents** - **java**.

## links úteis
[sintaxe básica markdown](https://www.markdownguide.org/basic-syntax)
# Repositório do Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o desafio do projeto para o bootcamp **everis New Talents** - **java**.

## links úteis
[sintaxe básica markdown](https://www.markdownguide.org/basic-syntax)

[Link para download do Git Bash](https://git-scm.com/download)

O Git Bash é um terminal extendido para otimizar o uso do Git.

## Comandos básicos
- **git status** - Visualiza o status atual dos arquivos e diretórios do repositório local;
- **git add .** - adiciona os arquivos modificados na area de staged, pode usar também git add -A;
- **git commit -m "mensagem"** - inclui um commit para as modificações realizadas;
- **git push origin main** - grava as alterações no repositorio remoto realizadas no repositório local para a branch main;

### Problemas ocorridos

Após o git push origin main o repositório não atualiza!
Solução encontrada no [stackoverflow](https://pt.stackoverflow.com/questions/52651/git-n%C3%A3o-envia-commits-para-servidor-erro-everything-up-to-date/52682):
    git reset --hard [sua branch]
    git add .
    git commit -m "...blablabla"
    git push origin [sua branch]
   
