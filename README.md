# Teste Git
Com exceção da questão prática, cada questão deve ser respondida com seu próprio commit, ou seja se o teste possuir duas questões objetivas, no mínimo terá 2 commits, um para cada questão.

## Questão 1
Uma desenvolvedora está trabalhando em um projeto cujo repositório de arquivos está em um servidor que usa o modelo descentralizado GIT. Ela não possui internet, mas deseja consolidar as modificações que fez para posteriormente enviá-las para gravação na nuvem assim que tiver conexão à rede. Para executar este versionamento, a desenvolvedora deve:

- [ ] realizar um commit local e, posteriormente, fazer o envio da versão nova para o servidor principal. 
- [ ] fazer uma cópia dos arquivos em uma nova pasta, renomeando esse novo diretório com número de versão acima do atual.
- [ ] fazer solicitação de commit para o servidor, de maneira que esta solicitação fique pendente e, assim que existir conexão à rede, o código será automaticamente enviado para o sistema. 
- [ ] criar uma nova ramificação do repositório local, colocando todos os arquivos da nova versão na pasta trunk.
---

## Questão Prática
### 1. Conteúdo do projeto
1. Adicione um arquivo chamado index.html nesse repositório
2. Adicione o seguinte conteúdo ao arquivo:
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>Título da página</title>
    <meta charset="utf-8">
</head>
<body>
    <h1>Aqui vai um título</h1>
</body>
</html>
```

### 2. Subindo seu projeto para o GitHub

1. Crie um repositório em seu GitHub
2. Abra seu terminal de comando e <b>adicione a origem remota</b> e conecte seu projeto local com o GitHub
    Atenção: Seu repositório local terá duas origens remotas para fins educativos e de fixação
    Dica: `git remote` e `git remote get-url <apelido-do-link-do-repositório>` podem ser úteis nessa etapa
3. Verifique as <b>alterações do seu projeto</b> e adicione ao fluxo de versionamento
4. <b>Faça um commit com uma mensagem útil</b> e na sequência, <b>um push</b> para o novo respositório remoto (GitHub)

### 3. Lidando com alterações
Abra a pasta do seu projeto, crie uma pasta chamada imagens, procure no Google por uma imagem do pokemon mais irado e salve dentro dessa nova pasta. Feito isso, abra seu arquivo index.html e adicione as seguintes modificações e salve o arquivo:
```html
<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <title>Fanpage do Bulba</title>
    <meta charset="utf-8">
  </head>
  <body>
    <h1>Perfil #bulbaonfire</h1>
    <img src="images/nome_da_sua_imagem.jpg" />
  </body>
</html>
```
---

## Referências
### Questão 1
[Prova Oficial 03/2018 CS-UFG - SANEAGO-GO - Analista de Sistemas](https://olhonavaga.com.br/simulados/simulado)

### Questão Prática
[Prova Oficial 03/2018 CS-UFG - SANEAGO-GO - Analista de Sistemas](https://olhonavaga.com.br/simulados/simulado)
[Desvendando Git e GitHub - Exercício 1](https://womakerscode.gitbook.io/desvendando-git-e-github/hands-on/exercicio-1)
