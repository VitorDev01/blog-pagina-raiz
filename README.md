<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/swiffy-slider@1.6.0/dist/js/swiffy-slider.min.js" crossorigin="anonymous" defer></script>
    <link href="https://cdn.jsdelivr.net/npm/swiffy-slider@1.6.0/dist/css/swiffy-slider.min.css" rel="stylesheet" crossorigin="anonymous">
    
    <title></title>
    <style> 
      @import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200&display=swap');

      body { 
              /*Largura da página*/
              min-height: 100vh;
              background-color: #0B1516;
              
      }
      /*Escondendo os botes */
      .hide {
              display:none;
            }
            input[type="checkbox"] {
              display: none;
            }
            #btn-a:checked ~ .hide {
              display: block;
            }
            #btn-a:not(:checked) ~ .hide {
              display: none;
            }
            #btn-b:checked ~ .hide {
              display: block;
            }
              #btn-b:not(:checked) ~ .hide {
              display: none;
            }
            #btn-c:checked ~ .hide {
              display: block;
            }
            #btn-c:not(:checked) ~ .hide {
              display: none;
            }
            #btn-d:checked ~ .hide {
              display: block;
            }
            #btn-d:not(:checked) ~ .hide {
              display: none;
            }
            #btn-e:checked ~ .hide {
              display: block;
            }
            #btn-e:not(:checked) ~ .hide {
              display: none;
            }
            #btn-f:checked ~ .hide {
              display: block;
            }
            #btn-f:not(:checked) ~ .hide {
              display: none;
            }
            #btn-g:checked ~ .hide {
              display: block;
            }
            #btn-g:not(:checked) ~ .hide {
              display: none;
            }
            
            img {
              margin: auto;
              margin-top: 50px;
              display: block;
              height: 206px;
              width: 206px;
              border-radius: 50%;
            }
            
            h1 {
              color: #fff;
              font: 400 30px/1.6 "Source Sans Pro",sans-serif;
              text-align: center;
            }
     
            p {
              color: #fff;
              text-align: center;
              font: 400 19px/1.6 "Source Sans Pro",sans-serif;
              
            }
     
            #btn-1, #btn-2 , #btn-3 , #btn-4, #btn-5, #btn-6, #btn-7{
              background-color: #045256;
              border-color: #DDF7F8;
              margin-left: 10px;
              margin-right: 10px;
              border-radius: 10px;
              width: 95%;
              outline: none;
              
            }
 
            .area p {
              margin: 15px;
              font: 400 20px/1.6 "Source Sans Pro",sans-serif;
            }

            .area {
             border: 3px solid ;
             border-top-color: #0B1516;
             border-bottom-color: #0B1516;
             border-right-color: #0B1516;
             border-left-color: #DDF7F8;
             display: block;
             margin: 10px;
             
             
            }
            ul {
             list-style: none;
           } 
           a { /*Links menu*/
            color: white;
           
            font: 370 20px/1.6 "Source Sans Pro",sans-serif;
          }
        
          a:hover { /*cor ao tocar nos links*/
           background:rgba(0, 0, 0, .09);
           width: 20px;
          }
          i {
            margin-right: 10px;
          }
          .swiffy-slider {
            height: 150px;
            width: 150px;
            margin: 40px;
       
          }
          /*Menu a esquerda*/
          #menu {
            float: right;
            
          }
          
          mark {
            background-color: #045256;
            color: white;
            border-radius: 15px;
          }
    </style>
    <body>
    <!--foto-->
    <img src="https://vitordev01.github.io/pagina-comercial/eu3.jpg">
    <!-- Titulo -->

    <h1>@Vitor Oliveira - Blog Pessoal <i class="fa fa-coffee" aria-hidden="true"></i><i class="fa fa-book"></i></h1>
    
    
    <!-- Parágrafos-->
     <input type="checkbox" id="btn-a">
          <button id="btn-1">
          <!-- botão pessoa -->
          <label for= "btn-a" >
            <p><strong><i class="fa fa-user" aria-hidden="true"></i>Sobre Mim</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p><a href="https://vitordev01.netlify.app/">Mais sobre min</a><br>
              Neste blog vou estar postando assuntos do meu interesse, em sua maioria conhecimentos que adquiro em cursos que ja fiz ou estou realizando no momento.</p>
             </div>
          </div>
         <br><br>
          <input type="checkbox" id="btn-b">
          <!-- Botão -->
          <button id="btn-2">
          <label for= "btn-b" >
            <p><strong><i class="fa fa-list"></i>Contatos</strong></p>
          </label>
          </button>
        
          <div class="hide">
            <div class="area">
           
           <ul id="menu" role="menu">
             <li><a href="https://wa.me/5524992717594?text=Olá+Gostaria+De+Saber+Mais+Sobre+As+Consultas+Online">WhatsApp •  <i class=" fab fa-whatsapp" style="color: white"></i></a></li>
             
             <li><a href="mailto:vitorkw90@gmail.com">Gmail • <i class="fa fa-envelope"></i></a></li>
                          
             <li><a href="https://www.instagram.com/vitorkw89/">Instagram • <i class=" fab fa-instagram"></i></a></li>
              
            <li><a href="https://www.facebook.com/profile.php?id=100078322466753">Facebook • <i class="fab fa-facebook"></i></a></li>  
            
            <li><p>(Respondo em 
            <br>30 minutos <i class="fa fa-clock")></i>)</p></li>
            </ul>
    
          <br>
          <p>Página disponível somente para versão  móvel,para desktop e tv ainda estão em desenvolvimento.</p>    
          </div>
          </div>
          
          <br><br>
          <input type="checkbox" id="btn-c">
          <button id="btn-7">
          <label for= "btn-c" >
            <p><strong><i class="fa fa-id-card" aria-hidden="true"></i>Taro & Numerologia</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>Disponível Apartir de 01 Janeiro 2023<br><a href="#">Veja quais são as influências que estão em grande aspecto em seu ano pessoal segundoa numerologia e taro<br></a>
              
              <mark>#taro #numerologia #anoPessoal</mark></p>
             </div>
          </div>
       
       
       
          <br><br>
          <input type="checkbox" id="btn-d">
          <button id="btn-3">
          <label for= "btn-d" >
            <p><strong><i class="fa fa-globe" aria-hidden="true"></i>O Nascimento Da Internet</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>25 de fevereiro de 2022<br><a href="https://vitordev01.github.io/page-about-internet/">Quando e de onde surgiu? quem esta por trás da crianção da internet? mundialmente presente na vida de todos</a>
              (Página criada em inglês)<br> • 3 min de leitura <br>
              <mark>#www #worldWideWeb #internetDeTudo</mark></p>
             </div>
          </div>
   
          <br><br>
          <input type="checkbox" id="btn-e">
          <button id="btn-4">
          <label for= "btn-e" >
            <p><strong><i class="fa fa-hands" aria-hidden="true"></i>Sincretismo Religioso </strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>22 de maio de 2022<br><a href="https://vitordev01.github.io/estudo-religioes/">Estudo sobre as semelhanças entre as principais religiões do mundo</a>
              <br> • 5 min de leitura <br>
              <mark>#sincretismo #religiões #espiritualidade</mark></p>
             </div>
          </div>
          
          <br><br>
          <input type="checkbox" id="btn-f">
          <button id="btn-5">
          <label for= "btn-f" >
            <p><strong><i class="fa fa-star" aria-hidden="true"></i>Os 12 Signos Do Zodíaco</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>01 de dezembro de 2022<br><a href="https://vitordev01.github.io/pagina-signos-curso/">As principais características dos signos e suas coligações com outros temas</a>
              <br> • 10 min de leitura <br>
              <mark>astrologia #individualidade #signos</mark></p>
             </div>
          </div>
          
          <br><br>
          <input type="checkbox" id="btn-g">
          <button id="btn-6">
          <label for= "btn-g" >
            <p><strong>♏ Lutero & Seu Signo Escorpião</strong></p>
          </label>
          </button>
          <div class="hide">
            <div class="area">
              <p>06 de dezembro de 2022<br><a href="https://vitordev01.github.io/pagina-reforma-protestante/">A ligação de Matinho Lutero e seu signo e suas profundas características</a>
              <br> • 5 min de leitura <br>
              <mark>signo #personalidade #reformaProtestante</mark></p>
             </div>
          </div>
    </body>
</html>
