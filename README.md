<p align="center">
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/Capa.png" width="100%"
alt="Samuel Machado" />
<hr/>

<h1>2020</h1>
<h2>[App|Web|API] App de leads</h2>
Liderei e atuei no desenvolvimento de um projeto que une prestadores de serviços e clientes. Os prestadores desbloqueiam leads que são postados na plataforma. O desafio do projeto foi criar uma "moeda virtual" que é utilizada dentro do aplicativo.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>PHP7 - Laravel</li>
<li>Ionic 4</li>
<li>Typescript</li>
<li>SCSS</li> 
<li>OSM (Open street maps)</li>
<li>Leaflet</li>
<li>Teste unitário</li>
<li>GCP</li>
<li>Push notification</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/negocios.gif" width="100%">
<hr/>

<h1>2019</h1>
<h2>[Web|API] Projeto de Rotas</h2>
Desenvolvi o painel web e a API que é consumida pelo aplicativo. Nesse projeto temos um controle de alunos e solicitações de transporte, o maior desafio do projeto foi organizar escalas de motoristas, alunos e escolas.<br>
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Bootstrap 3</li>
<li>HTML5</li>
<li>CSS3</li>
<li>jQuery</li>
<li>Vue.js (Em novas features)</li>
<li>PHP7 – Yii2 (API)</li>
<li>Teste unitário</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/projetoRotas.gif" width="100%">
<hr/>

<h2>[App] App de Rotas</h2>
Continuei o desenvolvimento do aplicativo que consome o projeto citado acima, o maior desafio deste app foi aplicar tecnologias de roteirização open source (leaflet routing) para funcionar no modo offline. Os utilizadores do app tem problemas de conexão com a internet móvel, então preparar o aplicativo para enviar as requests somente quando havia conexão, também foi um desafio.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Ionic 3</li>
<li>Typescript</li>
<li>SCSS</li> 
<li>OSM (Open street maps)</li>
<li>Leaflet</li>
<li>Push notification</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/rotasApp.gif" width="100%">
<hr/>

<hr/>
<h1>2018</h1>
<h2>[BOT] BOT NLP de vendas</h2>
<i>⚠️Atenção: Este projeto foi desenvolvido para fins acadêmicos e <B>todos os seus fontes</B> não foram e nem serão comercializados.</i>
<p>
Em 2018 eu tive a seguinte ideia <i>"E se eu programar um jeito de treinar uma IA com base em mensagens que eu enviei para números de Whatsapp aleatórios?".</i><br>
Eu consegui desenvolver uma engenharia para gerar e validar números de telefone com Whatsapp ativo. A partir disso eu integrei a minha API com um bot de Whatsapp não oficial.<br>
Feito isso, passei a treinar a primeira versão do bot em Python, ele gerava uma mensagem aleatória sobre consórcio e enviava para números aleatórios. Com base nas respostas eu comecei a classificar as seguintes intenções:
<table>
    <tr>  
        <th>Intenção</th>
        <th>Descrição</th>
    </tr>
    <tr>  
        <td>comprar</td>
        <td>Alguém que foi identificado como um potencial comprador. Ex. quero saber mais, quero comprar, o que é isso?</td>
    </tr>
    <tr>  
        <td>cumprimento</td>
        <td>O usuário respondeu com um cumprimento. Ex. Oi, Olá, Eae cara!</td>
    </tr>
    <tr>  
        <td>quemVoce</td>
        <td>Bom.. se você está mandando SPAM o mínimo que você espera é um "QUEM É VOCÊ?"</td>
    </tr>
    <tr>  
        <td>negacao</td>
        <td>Essa foi a intenção mais legal, você ficaria admirado com as formas que um brasileiro tem de negar algo. Ex. n quero naum, não quero, nn</td>
    </tr>
        <tr>  
        <td>compraFutura</td>
        <td>O usuário não quer agora. Ex. Hoje não amigo!, estou desempregado, acabei de comprar um</td>
    </tr>
</table><br>
Com o tempo, refinei o modelo, fiz um segundo teste usando node. O sistema classificava um potencial comprador com base em Whatsapp's enviados. No resultado final 50% dos usuários responderam e até 20% se mostraram interessados. Muito promissor, mas <b>enviar SPAM é errado</b>.<br>Encerrei o projeto e valeu como um grande aprendizado.<br>
<h5>Resultado</h5>
Como acho errado mostrar prints do Whatsapp, fiz um fork de uma interface e apliquei o sistema<br>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/NLP.gif" width="100%">

</p>
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Python Flask</li>
<li>RASA/DialogFlow/NodeNLP/brain.js</li>
<li>Node - Express</li>
<li>AWS - EC2 / S3 / RDS</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/Arquiteto.gif" width="100%">
<hr/>

<h2>[Web] Gerenciamento Financeiro</h2>
Desenvolvi um projeto Web que cria orçamentos e gerencia a parte financeira de um escritório de arquitetura.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>PHP7 - Laravel</li>
<li>HTML5</li>
<li>CSS3</li>
<li>jQuery</li>
<li>AWS - EC2 / S3 / RDS</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/Arquiteto.gif" width="100%">

<hr/>
<h2>[Web] Criptografia de vídeo - HLS</h2>
Desenvolvi uma forma de criptografar e descriptografar vídeos em tempo de execução. Fiz uma integração com o ffmpeg para converter/splitar o vídeo em partes, a partir disso criptografei os segmentos usando o conceito de chave pública/privada.
Usando um player open source consegui "ler" o vídeo em formato HLS e descriptografar as partes. Usei isso em um projeto de plataforma EAD onde os vídeos não podiam ser baixados.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Python</li>
<li>Linux/Shell</li>
<li>ffmpeg</li>
<li>Criptografia</li>
<li>GCP</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/player.jpg" width="100%">
<i>Explicação: O vídeo na tela usa o player open source e no canto superior direito estou demonstrando que é possível baixar um vídeo do vimeo e o meu não.</i>

<hr/>
<h1>2017</h1>
<h2>[Web|API] Gestão de controle de obras</h2>
A proposta era ser uma "rede social" da obra, o engenheiro lançava informações diárias como uma especíe de "diário da obra" e todos na equipe podiam acompanhar a evolução. 
<h5>Tecnologias envolvidas</h5>
<ul>
<li>PHP7 - Laravel / Nodejs</li>
<li>HTML5</li>
<li>CSS3</li>
<li>Vuejs</li>
<li>AWS - EC2 / S3 / RDS</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/obras.jpg" width="100%">

<h2>[BOT|API] ValidatorBOT</h2>
A proposta aqui foi utilizar um recurso nativo do Telegram que envia o PRÓPRIO contato do usuário autenticado para o bot. Dessa forma podemos fazer um 2FA em um sistema web  
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Nodejs</li>
<li>Express</li>
<li>2FA</li>
<li>AWS - EC2</li>
<li>Atlas - Mongodb</li>

</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/validator.gif" width="100%">
<hr/>
<h2>[App] App de promoções</h2>
Projeto de app de promoções de bares e restaurantes. Realizei integração com  geosearch e near by do mongodb
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Nodejs</li>
<li>ReactJS</li>
<li>React Native</li>
<li>Mongodb</li>
<li>GCP</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/restaurante2.jpg" width="100%">

<h1>2016</h1>
<h2>[BOT] ArteiroBOT</h2>
O objetivo desse projeto é pesquisar obras de arte através de um bot do Telegram, o projeto é open source e usa como base a API da Artsy.net.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Nodejs (V2)</li>
<li>mongoDB</li>
<li>Heroku</li>
<li>Spark Java (V1)</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/ArteiroBOT.gif" width="100%">
<hr/>

<h2>[BOT|API] IoT BOT</h2>
Este foi meu trabalho de graduação, coloquei sensores em um arduino e fiz uma comunicação http para que os dados fossem enviados para uma API. A partir disso a API enviava as informações úteis para o usuário através de um bot no Telegram
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Nodejs (V2)</li>
<li>mongoDB</li>
<li>Heroku</li>
<li>Arduino</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/iotbot2.gif" width="100%">
<hr/>

<h1>2015</h1>
<h2>[API] Gateway de SMS</h2>
Desenvolvi um gateway de SMS utilizando modens 3g desbloqueados e Python. O usuário realizava um pedido de envio para API e através de sockets o client conectado ao modem pegava informações da fila de envio de tempo em tempo e enviava o SMS com comandos AT.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>Socket</li>
<li>Python Flask / Comunicação serial</li>
<li>Processamento de fila</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/sms.gif" width="100%">
<hr/>

<h1>2014/2015</h1>
<h2>[Web|API] CRM & ERP</h2>
Sistema de gerenciamento de orçamentos, pedidos, clientes, financeiro e estoque. Apliquei diversos conceitos como rastreio de email, geração de relatórios complexos, sistema de contas a pagar e a receber etc.
<h5>Tecnologias envolvidas</h5>
<ul>
<li>PHP5 e PHP7
<li>CodeIgniter 2 e 3</li>
<li>HTML5</li>
<li>CSS3</li>
<li>jQuery</li>
<li>Envio de emails</li>
</ul>
<br>
<h5>Resultado</h5>
<img src="https://github.com/samuelmachado/samuelmachado/blob/master/.github/assets/crmerp.jpg" width="100%">
<hr/>