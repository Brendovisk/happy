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
### Instalação do Node.js web framework 
Depois de baixado o npm, ainda será necessário mais uma etapa para iniciar a aplicação, o arquivo *node_modules*, que será criado automaticamente ao executar o comando abaixo:
```shell
npm install express
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
### Página inicial
![tela1](https://user-images.githubusercontent.com/71789884/114742008-b0c34180-9d21-11eb-9ad0-9b95794c5342.png)
### Página que mostra os orfanatos na região
![tela2](https://user-images.githubusercontent.com/71789884/114742522-38a94b80-9d22-11eb-915c-ebf9cb5cff49.png)
### Página de adicionar orfanato
![tela3](https://user-images.githubusercontent.com/71789884/114742575-43fc7700-9d22-11eb-8018-be2c59d142d6.png)
### Orfanato adicionado
![tela4](https://user-images.githubusercontent.com/71789884/114742624-51b1fc80-9d22-11eb-96c4-dc7a9cdd6a48.png)
### Consultar orfanato
![tela5](https://user-images.githubusercontent.com/71789884/114742675-5971a100-9d22-11eb-998d-69ad18910f4c.png)
### Resultado final
![happy](https://user-images.githubusercontent.com/71789884/114743590-34316280-9d23-11eb-92da-ecceced98927.gif)
*Obs: as informações contidas na aplicação são fictícias.*


