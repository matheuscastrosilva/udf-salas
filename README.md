# PROJETO UDF SALAS
Um sistema de ensalamento, que é o processo de distribuição de salas em relação as turmas.

###Instalação

Baixe o código fonte do projeto utilizando [Git](https://git-scm.com/), utilize o branch master:

```bash
git clone -b master https://github.com/wilsonlucena/udf-salas.git
```

Instale as dependências PHP da aplicação através do [composer](https://getcomposer.org/):

```bash
composer install
```

###Informações importantes para desenvolvedores dicas

#### adicionar & confirmar
Você pode propor mudanças (adicioná-las ao Index) usando:

```bash
git add <arquivo que foi alterado> ou git add .
```
Este é o primeiro passo no fluxo de trabalho básico do git. Para realmente confirmar estas mudanças (isto é, fazer um commit), use

```bash
git commit -m "comentários das alterações"
```
Agora o arquivo é enviado para o HEAD, mas ainda não para o repositório remoto.

#### enviando alterações

Para enviar estas alterações ao seu repositório remoto, execute

```bash
git push origin master
```
Agora você é capaz de enviar suas alterações para o servidor remoto selecionado.
