# CRUD-AGENDA NodeJS

<img align="center" alt="siteAgenda" height="120" width="320" src="./imagemconfigbanco/agenda2.png"><br>

-	Nesse projeto eu fiz um CRUD estilo agenda de telefone usando NodeJS, Express, Sequelize para manipulação do banco de dados e EJS para renderizar o backend no frontend. o banco de dados usado neste projeto foi o MongoDB.
- 	Bom, basicamente você consegue fazer as 4 operações (CRUD) Create, read, update and delete.

<hr>

## Iniciar o projeto

- 	Bom primeiramente para iniciarmos o projeto iremos rodar o seguinte comando:
*		npm i
-	Após rodado esse comando ele irá instalar todas as dependências do projeto que estão salvas no package.json
-	Feito a instalação de todas as dependências iremos configuar o banco de dados.

<hr>

## Configurando o MongoDB

-	Antes de tudo, vale ressaltar que o MongoDB atlas disponibiliza 512MB grátis para usarmos como quisermos. por tanto, cuidado ao escolher a versão que você irá usar.
-	Para configurarmos o MongoDB iremos acessar o <a href="https://www.mongodb.com/cloud/atlas/lp/try-atlas?utm_source=google&utm_campaign=gs_americas_brazil_search_core_brand_atlas_desktop&utm_term=atlas%20mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624308&adgroup=115749705983&gclid=Cj0KCQjw6pOTBhCTARIsAHF23fIV4uepgu1qJL5DBgNZgVvwnjqFpSzSANGNTZsuRU6rrUdYsWl1h48aAlXOEALw_wcB">Site</a>

-	Crie seu Login e Siga os passos das imagens:

<img align="center" alt="configbanco" height="120" width="320" src="./imagemconfigbanco/mongo1.png"><br>
<img align="center" alt="addmongo" height="120" width="320" src="./imagemconfigbanco/addmongo.png"><br>
<img align="center" alt="mongodb" height="120" width="320" src="./imagemconfigbanco/addmongo2.png"><br>
<img align="center" alt="databasemongo" height="120" width="320" src="./imagemconfigbanco/databasemongo.png"><br>
<img align="center" alt="mongoconfigurado" height="120" width="320" src="./imagemconfigbanco/databaseconfig.png"><br>
<img align="center" alt="datasettings" height="120" width="320" src="./imagemconfigbanco/databaseconfig.png"><br>

*	OBS: Em caso de confusão recomendo esse vídeo também para que você possa configurar: 		
<a href="https://www.youtube.com/watch?v=Fz9sGN1YePQ">Vídeo</a>

-	De agora em diante vou considerar que seu banco de dados está 100% configurado, por tanto, seguiremos para o proxímo passo.

-	Agora iremos criar um arquivo chamado .env, para que seja adicionado/conectado o banco com nossa aplicação.

<img align="center" alt=".env" height="120" width="320" src="./imagemconfigbanco/envcomcodigo.png"><br>

*	OBS: Você deve colocar o seguinte código fazendo as alterações necessarias:
-		CONNECTIONSTRING=mongodb+srv://usuario:senha@nomebanco.anm4x.mongodb.net/nomenobancoexAGENDA?retryWrites=true&w=majority

-	Para copiar o seu código acesse o Site novamente e acesse o seguinte local de acordo com as imagens.

<img align="center" alt="codigo.env" height="120" width="320" src="./imagemconfigbanco/envconfigpegarcodigo1.png"><br>
<img align="center" alt="copiar.env" height="120" width="320" src="./imagemconfigbanco/envcodigocopiado.png"><br>

## Rodar o projeto.

-   com o banco de dados configurado, iremos rodar o comando:
*       npm start

-   Nesse momento dando tudo certo, irei passar agora umas rotas que você pode acessar, são elas:
*       Home: http://localhost:3000
*       Logar/Cadastrar: http://localhost:3000/login/index
*       Criar Contato:  http://localhost:3000/contato/index Obs: precisa estar logado para conseguir cadastrar os contatos.

# Obrigado!

-   Espero que gostem desse CRUD, confesso que foi bastante desafiador e um pouco complexo, mas de bastante aprendizado.

-   Minhas redes sociais:

<a href="https://www.instagram.com/joao_vitor_0o/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href = "mailto:contatojoaovtml@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/joão-vitorml-br/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
