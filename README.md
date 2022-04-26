<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto html</title>
    <style>
    body{
        font-family: arial;
        margin: 0;
    }
    .topo {
        /*color: green;
        background-color:black ;
        text-align: center;*/
        padding: 120px;
        background-image: url(https://d2vwsr3mua7yp8.cloudfront.net/d2830acf-b85c-4cbc-805a-6bd2b1092a17.jpg);
    }
    .menu {
        display:flex ;
        background-color: rgb(20, 193, 63);
    }
    .menu a {
        color: white;
        padding:14px 55px;
        text-decoration:none;
        text-align: center;
    }
    .menu a:hover{
        color:greenyellow;
        background-color: gray;
    }
    .conteudo {       
  flex-wrap: wrap;
  margin: 10px;
  border-radius: 20px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  border-color: #fff;
  border-style: solid;
  padding: 20px;
        }
        .c1 {       
  flex-wrap: wrap;
  margin: 10px;
  border-radius: 20px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  border-color: #fff;
  border-style: solid;
  padding: 20px;
 }
        .c2 {            
  flex-wrap: wrap;
  margin: 10px;
  border-radius: 20px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  border-color: #fff;
  border-style: solid;
  padding: 20px;
        }
        .c3 {   
  flex-wrap: wrap;
  margin: 10px;
  border-radius: 20px;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  border-color: #fff;
  border-style: solid;
  padding: 20px;
        }
    @media screen and (max-width: 700px){
        .conteudo, .menu, .c1, .c2, .c3 {
            flex-direction: column
        }
    }     
    </style>
</head>
<body>
    <div class="topo">
        
    </div>
    <div class="menu">
    <a href="#">FRUTAS E LEGUMES</a>
    <a href="#">POLPAS</a>
    <a href="#">FARINHAS E TEMPEROS</a>
    <a href="#">OVOS</a>
    <a href="#">FOLHAGENS</a>
    <a href="#">DIVERSOS</a>
    </div>
    <div class="conteudo">
        <div class=" c1"> 
        <h4>🏍️ Pedido mínimo e Taxa de entrega:</h4>
        <hr>
        <p>🟠Mínimo - R$18,00, Taxa de entrega - R$10,00 <br> 
        </p>🟢Mínimo - R$30,00, Taxa de entrega - R$10,00
    </div>
<div class="c2">
    <h4>🕐Horário de funcionamento:
    </h4>
    <hr>
<p>Segunda - Quinta 08:00 - 17:00 <br> Sábado - 08:00 - 17:00
</p>
</div>
<div class="c3">
    <h4>📍Localização:
    </h4>
    <hr>
<p>Avenida Rômulo Maiorana, 1899, Marco, Belém - PA, 66093675
    <a href="https://g.page/varejaodasfrutasbelem_?share">Varejão das Frutas</a>
</p>
</div>
<div class="c3">
    <h4>☎️Número para contato:
    </h4>
    <hr>
    <a href="+559193312223">+55 91 99331-2223</a>
</div>
</body>
</html>
