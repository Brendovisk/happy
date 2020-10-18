*Essa é a minha versão da aplicação Happy desenvolvida na Next Level Week de 2020.*


Para criar um servidor local nós usamos NodeJs junto ao NPM (Node Package Manager).

/////////////////////////////////////////Instalação/////////////////////////////////////////////

Para criar o seu próprio servidor, execute o seguinte comando no terminal:

    npm start

Para fechar o servidor use "Crtl + c"

///////////////////////////////////////Banco_de_dados///////////////////////////////////////////

Na pasta database.sqlite, de rota NLW > src > database, está armazenado o banco de dados local.

Para EXCLUIR o banco de dados, basta apagar o arquivo database.sqlite, e salvar os arquivos "db.js"
e "SaveOrphanage.js", que se encontram na pasta database.

//////////////////////////////////////////Mudanças////////////////////////////////////////////

As mudanças que eu implementei foram:
-Cor do background, deixando azul/roxo e laranja (com base nas cores complementares do
círculo monocromático);
-Um contorno laranja ao redor da área selecionada, facilitando na visualização do campo atual, 
com a finalidade de aumentar a acessibilidade de pessoas com problemas visuais;
-Deixar o ícone do Happy como um botão que ao ser clicado redireciona o usuário para a tela inicial;
