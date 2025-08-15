# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos para utilização de git e github

## Configuração Inicial
Rode os comandos abaixo no terminal (cmd) do seu computador.
```bash
git config --global user.name "Gabriel Meronha Vicente"

git config --global user.email gabriel.vicente6@fatec.sp.gov.br
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE**: só é executado 1 vez.
```bash
git init
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e seguir a segunda opção da lista de comandos que apoarece no site.
**IMPORTANTE** Depois do remote deve ser executados os outros 2 comandos da página
```bash
git remote add origin < url_repositorio_github >


Para vericar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Quando o status mostrar o arquivo em vermelho 
é necessário o add para adicionar os arquivos a serem salvos
usamos o add a qualquer momento
```bash
git add
```

quando o status mostrar o arquivo em vermelho 
é necessário o add para adicionar os arquivos a serem salvos e depois colocar onde parou para ter controle
utilizamos o commit -m
```bash
git commit -m "mensagem"
```



