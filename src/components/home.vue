<template>

    <body>
        <div class="fondo">
        
        
        <h1>ViajanTop </h1>
        <div class="buscador">
            <form>
                
                <br><input type="text" id="fname" name="fname" placeholder="¿Donde quieres Viajar?" ><br>    
            </form>
            <a href="" class="nav-link">Buscar</a>
        </div>
        </div>
        <h2 class="TopLug">Top lugares mas buscados hoy </h2>
        <div class="top">
            <a href="" class="h5"><strong>Cartagena de indias</strong></a>
            <a href="" class="h6"><strong>Paris Francia</strong></a>
            <div class="mas_opciones">
                <a href="" class="h7"><strong>Cancún mexico</strong></a>
                <a href="" class="m-opciones"><strong>Mas lugares</strong></a>
            </div>
        </div>
        <h2 class="OfertasQ">Ofertas que no pueden esperar</h2>
        <section class="ofertas">
            
            <a href="" class="h7">San Andres</a>
            <a href="" class="h8">Santa Marta</a>
            <a href="" class="h9">Ciudad de Mexico </a>
            <a href="" class="h10">Miami</a>
            <a href="" class="h11">Cali</a>
            
            
        </section>
        
        <div class="OfertasExclusivas">
            <img src="imagenes/mail.png" alt="">
            <div class="text">
                <h3>
                    Ofertas exclusivas en tu email
                </h3>
                <h4>
                    Recibí de primera mano nuestras ofertas y beneficios exclusivos.
                </h4>
    
            </div>
            <div class="form">
                <form>
                
                    <br><input type="text" id="mail" name="mail" placeholder="ingresa tu emal" ><br>   
                    <button>!Quiero recibirlas¡</button> 
                </form>
            </div>
            
        </div>
        
        
    </body>
    
    
    </template>
<script>
export default {
name: 'home',
data: function(){
return{

}
},
components: {
},
methods:{}}
</script>
<style>
body{margin:0px;}

a{
    text-decoration: none;
    color:white;   
    }
.fondo{
     background-image:url(@/assets/fondo.png);
    padding: 0px 0px 70px 0px;
    }
nav button{
    color: #ffffff;
    border: none;
    background: none;
    font-family:Tahoma;
    font-size: 15px;
    font-weight: 300;
    padding-left: 10px;
    margin-right: 10px;
}
nav button.xd{
        color: rgb(41, 112, 78);
        font-size: 15px;
        text-align: center;
        border-radius: 5px;
        margin: 10px 10px 0px 10px;   
    }
nav button:hover{
        color: rgb(199, 199, 202);
    }
header a{
    display: flex;
    justify-content: space-between;
    background-color: hsla(0, 0%, 0%, 0.733);
    color: aliceblue;
    align-items: center;
    padding: 20px;
        
    }
.logo{
    margin-left: 40px;
    display: flex;
    align-items: center;
    }
.logo img{
    margin: 2px ;
    height: 35px;
    }
h1{
    font-family:'Lucida Sans Unicode';
    color: #ffffff;
    font-size: 80px;
    display: flex;
    text-align: center;
    margin: -10px 10px -10px 210px; 
    }
.buscador{
    display: flex;
    justify-content: space-between;
    text-align: center;
    align-items: center;
    border-radius: 60px;
    margin: 0px 200px 10px 200px;
    padding: 5px 20px 10px 50px;
    background-color: #ffffff;
        
    }
input{
    text-align: center;
    font-size: 30px;
    margin: 0px 0px 20px 0px;
    padding: 0px auto 0px auto; 
    }

    
.buscador a{
    font-size: 20px;
    color: #ffffff;
    border-radius: 60px;
    margin:0px 0px 0px 0px;
    padding: 5px 70px 5px 70px;
    background-color: #41973e;
    }

.buscador a:hover{
    color: rgb(64, 64, 65);
    background-color: #3b7d39;
    }
h2.TopLug{
    font-family:Arial;
    font-size: 40px;
    margin: 16px 25px 13px 60px;
    }
.top{
    font-family:Arial;
    display: flex;
    justify-content: space-between;
    }
.top .h5{
    font-size: 30px;
    margin: 50px 10px 25px 50px;
    padding: 20px 150px 400px 10px;
    background-image: url(@/assets/cartagena.jpg);
    background-size: cover;
    background-position:center;
    background-repeat: no-repeat; 
    }
.top .h6{   
    font-size: 30px;
    margin: 50px 10px 20px 10px;
    padding: 20px 180px 400px 10px;
    background-image: url(@/assets/francia.jpg);
    background-size: cover;
    background-position:center;
    background-repeat: no-repeat; 
    }
.top .mas_opciones{
    display:flex;
    flex-direction: column;
    }
.top .mas_opciones .h7{   
    font-size: 30px;
    margin: 50px 60px 20px 10px;
    padding: 20px 220px 370px 10px;
    background-image: url(@/assets/cancun.jpg);
    background-size: cover;
    background-position:center;
    background-repeat: no-repeat; 
}
.top .mas_opciones .m-opciones{   
    font-size: 30px;
    margin: 0px 60px 20px 10px;
    padding: 20px 20px 75px 10px;
    background-color: rgb(219, 143, 0);  
    }
h2.OfertasQ{
    font-family:Arial;
    font-size: 30px;
    margin: 20px 0px 0px 50px;
    color: black;
     }
.ofertas {
    justify-content: space-between;
    display:flex;
    text-align: center;
    align-items: center;
    font-family:Arial;
    margin: 25px 50px 80px 40px; 
    }
section.ofertas{
    display: flex;
    width: 93%;
    height: 430px;
}
section.ofertas a{
    width: 0px;
    flex-grow: 1;
    object-fit: cover;
    opacity: 08;
    transition: .5s ease;
    
}
section.ofertas a:hover{
    cursor: crosshair;
    width: 200px;
    opacity: 50;
    filter: contrast(120%);
}
    
.ofertas .h7,.h8,.h9,.h10,.h11{
    border: 0.5px solid rgba(218, 144, 33, 0.719);
    height: 430px;
    font-size: 25px;
}
.ofertas .h7 text{
    border: 0.5px solid rgba(218, 144, 33, 0.719);
    
        
}
    .ofertas .h7{
        background-image: url(@/assets/san\ andres.jpg);
        background-size: cover;
        background-position:right;
        background-repeat: no-repeat;
    }
    .ofertas .h8{
        background-image: url(@/assets/santamarta.jpg);
        background-size: cover;
        background-position:center;
        background-repeat: no-repeat;
    }
    .ofertas .h9{
        background-image: url(@/assets/CIUDAD\ DE\ MEXICO2.jpg);
        background-size: cover;
        background-position:center;
        background-repeat: no-repeat;
    }
    .ofertas .h10{
        background-image: url(@/assets/miami.jpeg);
        background-size: cover;
        background-position:center;
        background-repeat: no-repeat;
    }
    .ofertas .h11{
        background-image: url(@/assets/cali.png);
        background-size: cover;
        background-position:center;
        background-repeat: no-repeat;
    }

 /* ofertassssssssssssss */ 

    .OfertasExclusivas{
        display:flex;   
        place-items: top;
        background-color: rgb(223, 218, 211);
    }
    .OfertasExclusivas img{
        margin: 80px ;
        height: 10px;
    }
    .OfertasExclusivas .text{
        margin: 10;
        height: 10px;
        display: grid;
        font-family:Arial;
    }
    .OfertasExclusivas .text h3{
        height: 2px;
        font-size: 25px;
        color: green;
    }
    .OfertasExclusivas .text h4{
        height: 2px;
        font-size: 22px;
    }

    .OfertasExclusivas .form {
        display:grid;
        text-align: center;
        margin: 20px 20px 20px 40px;
    }
    .OfertasExclusivas  form button{
        margin: 0px 20px 20px 10px;
        font-size: 20px;
        font-family:Arial;
        border-radius: 30px;
        padding: 8px 80px 8px 80px;
        background-color: #41973e;
        border: none;
        color: #ffffff;
    }
    .OfertasExclusivas  form button:hover{
        color: rgb(108, 108, 108);
    }
    .OfertasExclusivas form input{
        margin: 0px 20px 20px 20px;
        padding: 10px 50px 20px 50px;
        font-size: 20px;
        font-family:Arial;
        
    }
    </style>