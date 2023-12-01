# alura--

<!DOCTYPE html>
<html lang="pt-br">
     <head>
          <meta charset="UTF-8">
          <title>damburger.com</title>
         
         <link rel="stylesheet" href="style.css">
       
         <style>

         </style>
   
      </head>
   
        <body>
         <header>
            <img id="alogo"src="./img/logo-alura.jpeg">
            <h1><strong>Damburger</strong></h1>
                  <nav>      
                        <ul>
                           <li><a href="index.html">Início</a></li>
                           <li><a href="produtos.html">Produtos</a></li>
                           <li><a href="contato.html">Contato</a></li>
                        </ul>
                  </nav>
          </header>
            <img id="hamburguer2"src="./img/horizontal.jpeg">
            <div class="principal">

              <h2 style="text-align:center ; font-size: 35px;"><strong style="">Sobre a Damburger</strong></h2>

              <p style="font-size: 20px; text-align: center;">localizada no centro de Fazenda Rio Grande a <strong>Damburg</strong> traz lanches e salgados, etc, para cidade.
               Fundada em 2023, a hamburgueria Damburg já é destaque na cidade e conquista um novo cliente todo dia.</p>
         
               <p style="font-size: 30px; text-align: center;"><em>Nossa missão é:<strong> criar lanches saborosos para satisfazer o cliente.</strong></em></p>
         
               <p style="font-size: 20px; text-align: center;">Temos chefs de cozinha muito experientes e antenados ao mundo da comida, para obtermos receitas novas e deliciosas. O atendimento possui
                  padrão de excelência. </p>

            </div>

            <div class="beneficios">
               <h3 style="font-size: 40px;"><strong>Benefícios</strong></h3>
               <ul>

                 <li class="itens">Profissionais Qualificados</li>
                 <li class="itens">Ambiente Agradável</li>
                 <li class="itens">Localização</li>
                 <li class="itens">Estacionamento Gratuito</li>
                 
               </ul>  

               <img src="./img/tradicional.jpeg" class="imgbeneficios">

            </div>
 
       </body>



      //////////////////////////


      body { background: lightgray;

}

#alogo {
width: 168px;
height: 168px;
position: absolute;

}


#hamburguer2 {
width: 900px;
height: 600px;
padding: 10px 0 0 25%;


}

.principal {
background: #A9A9A9;
padding: 30px;
}

h1 {
text-align: center;
color: black;
font-size: 60px;
background: dimgray;
padding: 50px;
}

h2 {
color: black;
text-align: center;
font-size: 45px;
}

h3 {
text-align: center;
font-size: 25px;
}

ul {
display: inline-block;
vertical-align: top;
width: 20%;
margin-right: 15%;
}

.imgbeneficios {
width: 50%;
}

p {
text-align: center;
color: black;
}

em strong {
color: #B22222;
}

.itens {
font-style: italic;
color: black;
font-size: 20px;
}

.beneficios {
background: white;
padding: 20px;
}
nav {
position: absolute;
top: 100px;
right: 0;
}
nav li {
display: inline;
margin: 0 0 0 15px;
}
nav a {
text-transform: uppercase;
color: #000000;
font-weight: bold;
text-decoration: none;
}
nav a:hover {
color: white;
}

//////////////////


<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
        <title>damburg - produtos</title>

        <link rel="stylesheet" href="reset.css">
<link rel="stylesheet" href="produtos.css">



</head>
<body>
<header>
<div class="caixa">
<h1><img src="./img/logo-alura.jpeg"></h1>
<nav>
<ul>
<li><a href="index.html">Início</a></li>
<li><a href="produtos.html">Produtos</a></li>
<li><a href="contato.html">Contato</a></li>



</ul>
</nav>
</div>
</header>

<main>
<ul class="produtos">
<li>
<h2>Hambúrguers Artesanais</h2>
<img src="./img/artesanal.jpeg">
<p class="produto-descricao">hambúrguer artesanal feito na hora !</p>
<p class="produto-preco">R$ 10,00 - R$ 25,00</p>
</li>
<li>
<h2>Hambúrguers "Padrões"</h2>
<img src="./img/tradicional.jpeg">
<p class="produto-descricao">hambúrguers tradicionais que todo mundo conhece !</p>
<p class="produto-preco">R$ 09,00 - R$ 16,00</p>
</li>
<li>
<h2>Crie o seu hambúrguer !</h2>
<img src="./img/crie o seu.jpeg">
<p class="produto-descricao">crie seu hambúrguer do jeito que quiser !</p>
<p class="produto-preco">R$ 10,00 - R$ 50,00</p>
</li>
</ul>
</main>

<footer>
<img src="./img/logo-alura.jpeg">
<p>Copyright Damburg - 2023</p>
</footer>


</body>
</html>


/////////////////////



header {
    background: gray;
    padding: 20px 0;
    }
    .caixa {
    position: relative;
    width: 940px;
    margin: 0 auto;
    
    }
    
    img {
    width: 200px;
    height: 200px;
    }
    nav {
    position: absolute;
    top: 100px;
    right: 0;
    }
    nav li {
    display: inline;
    margin: 0 0 0 15px;
    }
    nav a {
    text-transform: uppercase;
    color: black;
    font-weight: bold;
    text-decoration: none;
    
    }
    nav a:hover {
    color: white;
    }
    .produtos{
    width: 940px;
    margin: 0 auto;
    padding: 50px 0;
    }
    .produtos li {
    display: inline-block;
    text-align: center;
    width: 30%;
    vertical-align: top;
    margin: 0 1.5%;
    padding: 30px 20px;
    box-sizing: border-box;
    background: lightgray;
    border: 3px dashed black;
    border-radius: 0 30px 0 30px;
     }
     .produtos li:hover {
      border-color: #DC143C;
     }
     .produtos li:active {
      border-color: green;
     }
     .produtos li:hover h2 {
      font-size: 35px;
     }
    .produtos h2 {
    font-size: 30px;
    font-weight: bold;
    }
    .produto-descricao {
    font-size: 18px;
    }
    .produto-preco {
    font-size: 22px;
    font-weight: bold;
    margin: 10px 0 0;
    color: #DC143C;
    }
    footer {
    text-align: center;
    background: black;
    color: white;
    padding: 40px 0;
    }
