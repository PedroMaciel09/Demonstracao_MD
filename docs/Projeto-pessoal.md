# Meu Projeto
### Aqui, será publicado o código do meu projeto pessoal.
<br>

# Código HTML

```
<!DOCTYPE html>
<html lang="pt-Br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Proj_Dupepe2.css">
    <link rel="shortcut icon" href="icone.ico" type="image/x-icon">
    <title>Du pepê web</title>
</head>
<body>
        <header>
             <div class="menu">
                <a href="https://www.instagram.com/dupepefitalimentos/">Perfil</a>
                <a href="#">Entre em contato</a>
                <a href="#">Catálogo</a>
             </div>
            <div class="imagemheader">
                <img src="logui-removebg-preview.png">
            </div>
        </header>

        <nav id="slide_int">
            <h1>slide interativo</h1>
        </nav>        
    <div class="divprincipal">
    <section>
        <section class="box">
            <div class="imagem_apresentaçao">
                <img src="Du Pepê 30.jpg">
            </div>
            <h1 class="sub_apresentaçao">Coxinhas</h1>
        </section>
            <section class="box2">
                <div class="imagem_apresentaçao">
                    <img src="Du Pepê 23.jpg">
                </div>
                <h1 class="sub_apresentaçao">Pastéis</h1>
            </section>
            </div>
    </section>    
    </div>


    <footer id="rodapé">
        <p>Footer</p>
    </footer>
</body>
</html>
```

# Código CSS da página

```
    /*projeto dupepe.*/

/* verde dupepe -> #3f7a38
papel de parede -> #a2d950*/


*{
    padding:0;
    margin:0;
}

header{
    background-color: #3f7a38;
    height: 70px;
    width: auto;
    position:static;
    display: flexbox;
    border-radius: 5px;
    box-shadow: gray;
}

.menu{
    float: right;
    padding: 25px;
    margin-top: 0px;
    
}

.menu a{
    text-decoration: none;
    color:#332107;
    font-family:'Times New Roman', Times, serif;
    padding: 30px;
    font-size:x-large;
    position:relative; 
}

.menu a::after{
    content:"";
    width:0%;
    height: 3px;
    background-color: #332107;
    position: absolute;
    left: 0;
    bottom: 20px;
    transition:0.2s
}

.menu a:hover::after{
    width: 100%;
    
}


.imagemheader{
    margin-left:4%;
    padding:8px;
    float:left;
    position:sticky;
    width: 35%;
    height: 85%;
    display: flex;
    margin-top:0;
    
    }

#rodapé{
    clear: both;
    background-color: #3f7a38;
    margin-top: 50%;
    font-size: x-large;
    text-align:center;
    height:15px;
    padding: 25px;
    color:#332107;
    font-family:'Times New Roman', Times, serif ;
    width: auto;
    margin-top: 0;
    border-radius: 7px;
}

.divprincipal{
    background-color: rgb(206, 206, 188);
    height: 600px;
    background-size: 100%;
    padding: 100px;
    width:auto;
}

.box{
    border: solid #3f7a38 5px;
    position: absolute;
    border-radius: 3vh;
    width: 253px;
    text-align: center;
    height: 400px;
    padding: 60px;
    padding-top: 70px;
    left: 20%;
}


.box2{
    border: solid #3f7a38 5px;
    position: absolute;
    border-radius: 3vh;
    width: 253px;
    text-align: center;
    height: 400px;
    padding: 60px;
    padding-top: 70px;
    right: 20%;
}

.imagem_apresentaçao{
    top: 0%;
    left:5%;
    right: 5%;
    position:absolute;
    width: 250px;
    padding: 10px;
    height: 310px;
    display:flex;   
    margin-left: 5%;
    margin-right: 5%;
    transform: translate(5%,5%);    
}

#slide_int{
    background-color: white;
    text-align: center;
    height:30px
}



#centro{
    padding:50px;
    text-align: center;
}

.sub_apresentaçao{
    text-align: center;
    position: relative;
    top: 70%;
    color: #3f7a38;
    font-size: 1.6em;   
}

```