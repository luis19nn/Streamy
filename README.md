# Streamy
Um site para streams utilizando o OBS, com um CRUD completo produzido com HTML, CSS e JavaScript, feito com o framework React com Redux

# Como utilizar
Primeiro você precisa iniciar o JSON-Server na porta 3001, utilizando o comando `npm start` na pasta `apis`, ele é responsável por conter o "banco de dados" da aplicação, que está no arquivo JSON chamado `db.json`.<br><br>
Após isso, você irá iniciar a aplicação, entrando na pasta `client` e executando o mesmo comando `npm start`, isso irá rodar a aplicação e você já poderá utilizar boa parte dela.<br><br>
No próximo e último passo, você deve iniciar o RTMP server, ele é incubido de se conectar com o OBS, um programa de captura de tela, para poder exibir as streams no site. Para isso, basta executar o comando `npm start` na pasta `rtmpserver`, e então copiar a URL da stream que você deseja enviar sua captura de tela e colar no campo do OBS correspondente à exibição de streams.<br><br>
Pronto, agora você poderá fazer login com sua conta do Google, criar, atualizar, deletar e visualiar streams por toda a aplicação!
