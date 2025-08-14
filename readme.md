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

Para vericar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Para salvar o arquivo no estado atual,quando o status mostrar o arquivo em vermelho 
é necessário o add para adioconar os arquivos a serem salvos
usamos o add a qualquer momento
```bash
git add
```

quando o status mostrar o arquivo em vermelho 
é necessário o add para adioconar os arquivos a serem salvos e depois colocar onde parou para ter controle
utilizamos o commit -m
```bash
git commit -m "mensagem"
```



