<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>loja</title>
    <link rel="stylesheet" href="loja.css">
    
</head>
<body>
    <div id="site"> 

    

        <img id="logo" src="logo2.png" alt="logo site">
        <div id=pesquisa>
            <form method=""  action="logo da loja">
                <input type="search">
                <button type="submit">Pesquisar</button>


            </form>
        </div>

        <div id="botoes">
          <div class="btn">
            <i class="bi bi-cart-check-fill"></i>
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cart-check-fill" viewBox="0 0 16 16">
                <path d="M.5 1a.5.5 0 0 0 0 1h1.11l.401 1.607 1.498 7.985A.5.5 0 0 0 4 12h1a2 2 0 1 0 0 4 2 2 0 0 0 0-4h7a2 2 0 1 0 0 4 2 2 0 0 0 0-4h1a.5.5 0 0 0 .491-.408l1.5-8A.5.5 0 0 0 14.5 3H2.89l-.405-1.621A.5.5 0 0 0 2 1H.5zM6 14a1 1 0 1 1-2 0 1 1 0 0 1 2 0zm7 0a1 1 0 1 1-2 0 1 1 0 0 1 2 0zm-1.646-7.646-3 3a.5.5 0 0 1-.708 0l-1.5-1.5a.5.5 0 1 1 .708-.708L8 8.293l2.646-2.647a.5.5 0 0 1 .708.708z"/>
              </svg>

            <a href="#">carrinho</a>
        </div>

        <div class="btn">
            <i class="bi bi-person-square"></i>
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-square" viewBox="0 0 16 16">
                <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z"/>
                <path d="M2 0a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2H2zm12 1a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1v-1c0-1-1-4-6-4s-6 3-6 4v1a1 1 0 0 1-1-1V2a1 1 0 0 1 1-1h12z"/>
              </svg>
            <a href="#">minha conta</a>
        </div>
        
    </div>
    
</div>

<div id="cabecalho">
</div>


</div>

</div>


<div id="categorias">

    <a href="#">Lancamentos</a>

    <a href="#">Mais vendidos</a>

    <a href="#">Jogos gratis</a>

    <a href="#">Em breve</a>



</div>




<div id="container">

    <div id="imagens">
        <img src="witcher.jpg" alt="the witcher">
        <h1>The Witcher 3: Wild Hunt

        </h1>

        <a href="#">R$ 15,99</a>


   </div>

   


    </div>



</div>







</body>
</html>





#logo {
    width: 120px;
    height: 120px;
}

html {
width: 100%;
background-color: rgb(255, 248, 248);
}


#site{
    display: flex;
    justify-content: center;
    width: 100%;
    background-color: #0b146b;
}

#cabecalho {
   
    display: flex;
    background-color:#000000;
    justify-content: space-between;
    width: 1024px;
}

#pesquisa {
    
    display: flex;
    align-items: center;
}

.btn {
    
    margin: 12px;
  
}

#botoes{
display: flex;
align-items: center;
border-color: black;

}

#categorias{
    display: flex;
    justify-content: space-between;
    background-color: rgb(0, 0, 0);
    width: 1024px;
    height: 55px;
    align-items: center;



}
#container{
    height: 50px;
   
}

#imagens{
    height: 220px;
    width: 100px;


}


