# Readme
## Sobre

Essa é a minha versão da aplicação Happy desenvolvida na *Next Level Week #3* de 2020. O projeto se consistia em desenvolver DO ZERO, uma aplicação destinado a gerenciar visitas a orfanatos.

## Requisitos
Para criar um servidor local nós usamos NodeJs junto ao NPM (Node Package Manager). Então, você precisará o NodeJs e o NPM instalados em seu computador para inicializar o servidor e ver a aplicação. 

### Instalação do NodeJs
Para verificar se você tem o nodeJs instalado em seu computador, é só executar o comando abaixo:
```shell
node -v
```
Se não aparecer o número da versão é bem provável que você NÃO tem o node instalado. Para instalá-lo, vá até o site do [nodejs.](https://nodejs.org/en/download/) e siga as instruções. 

### Instalação do NPM
Para verificar se você tem o NPM instalado em seu computador, é só executar o comando abaixo:
```shell
npm -v
```
Uma vez que o NodeJs está instalado em seu computador, execute o seguinte comando no terminal para instalar o NPM
```shell
npm install npm@latest -g
```

## Inicialização do server
Para criar o seu próprio servidor, execute o seguinte comando no terminal:
```shell
npm start
```
Após isso, abra o seu navegador e digite no campo da URL o seguinte endereço padrão: **127.0.0.1:5500**


Para fechar o servidor, use o atalho **Crtl + c** em seu terminal


## Banco de dados
Na pasta *database.sqlite* na rota *nlw 2020 > src > database*, está armazenado o banco de dados local. Esse banco registra TUDO o que é salvo a partir de uma interação na aplicação.

Para **EXCLUIR** o banco de dados basta apagar o arquivo *database.sqlite*, e salvar os arquivos *db.js* e *SaveOrphanage.js*, que se encontram na pasta* database*.

## Mudanças feitas por mim
As mudanças que eu implementei foram:
- Cor do background, deixando azul/roxo e laranja (com base nas cores complementares do
círculo monocromático);
- Um contorno laranja ao redor da área selecionada, facilitando na visualização do campo atual, 
com a finalidade de aumentar a acessibilidade de pessoas com problemas visuais;
- Deixar o ícone do Happy como um botão que ao ser clicado redireciona o usuário para a tela inicial.

## Happy 
