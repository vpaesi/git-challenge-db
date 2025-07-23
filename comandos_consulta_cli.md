# Exercício Prático

## 1. Criação do Ambiente de Trabalho:
```bash
cd Desktop/Projetos/estudos-db_server
mkdir -p trilha-qa-git/desafio1
cd trilha-qa-git/desafio1
```
> Navegado até o repositório com os outros desafios e criada uma pasta para a trilha e desafio atual:
> ![Captura de tela do terminal bash com os comandos descritos acima](screenshots/capture_250723_085814.png)

## 2. Criação de Arquivos: 
```bash
touch README.md comandos-consulta.md
code .
mkdir screenshots
```
> Criados os dois arquivos Markdown (README.md e comandos-consulta.md), abertos no `VSCode` para inserir os comandos utilizados, e, criada a pasta `screenshots` para armazenar os prints do terminal:
> Criada a pasta screenshots para armazenar os prints do bash:
![Captura de tela do terminal bash com os comandos descritos acima](screenshots/capture_250723_090617.png)

## 3. Instalação do Terminal Bash (se necessário):
> Etapa desnecessária. Já utilizo o `git bash`.

## 4. Inicialização de Git no Projeto:
> Para inicializar o repositório no git pela primeira vez, utilizei:
```bash
git init
git add .
git commit -m "primeiro commit"
git remote add origin https://github.com/vpaesi/estudos-db_server
git branch -M main
git push -u origin main
```

> Dessa vez, como o repositório na máquina já está vinculado ao remoto, eu retornei até a raíz pelo terminal, verifiquei se apenas a nova trilha tinha sido alterada, adicionei as alterações, confirmei novamente as alterações adicionadas, commitei e dei push na branch que eu me localizava:
```bash
cd ../..
git status
git add .
git status
git commit -m "feat(trilha-qa-git): inicializa o desafio 1"
git push origin HEAD
```
![Captura de tela do terminal bash com os comandos descritos acima](screenshots\capture_250723_094026.png)
![Captura de tela do terminal bash com os comandos descritos acima](screenshots\capture_250723_094127.png)

Observação: A Etapa 5 está no arquivo [comandos-git.md](comandos-git.md) e a etapa 6 está na pasta [screenshots](screenshots).
