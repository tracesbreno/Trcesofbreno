# Trcesofbreno
Cadastro CSS

*{
    box-sizing: border-box;
    align-items: center;
}

body{
    background-image:url(background.png);
    background-size:1389px 700px;
    color: white;
    align-items: center;
}
/* Titulo*/
.Titulo {
    font-family: Arsenica Trial Medium;
    color: #ffffff;
    position: absolute;
    align-content: center;
    padding: auto;
    font-size: 12px;
    left: 50px;
    align-items: center;
}

.Titulo span {
    animation: animate 5s linear infinite;
}
@keyframes animate {
    0%,18%,20%,50.1%,60%,65.1%,80%,90.1%,92%
    {
        color: #ffffff38;
        text-shadow: none;
    }
    18.1%,20.1%,30%,50%,60.1%,65%,80.1%,90%,92.1%,100%
    {
        color:rgb(255, 255, 255);
        text-shadow: 0 0 10px #ffffff, 0 0 20px #ffffff, 0 0 40px #ffffff, 0 0 45px #ffffff;
       
    }
}

/* Barras */

.barr1 {
    position: absolute;
    background: #000000;
    width: 5px;
    height: 60px;
    align-items: center;
    top: 9px;
    left: 15px;
}

.barr2 {
    position: absolute;
    background: linear-gradient(to left, rgba(255, 255, 255, 0), #ffffff63);
    width: 300px;
    height: 60px;
    align-items: center;
    top: 9px;
    left: 15px;
    backdrop-filter: blur(7px);
    border-top-right-radius: 13px;
    border-bottom-right-radius: 13px;
}

/* Painel 1*/

.container ul{
    margin: auto;
    width: fit-content;
    background: #ffffff38;
    border-radius: 15px;
    border-left: 4px solid #ffffff;
    border-right: 4px solid #ffffff;
    backdrop-filter: blur(7px);
    text-decoration: dashed;
    padding: 20px;
    box-decoration-break: initial;
    width: 340px;
    height: 293px;
}

.container input  {
    border-color:#ff730000;
    background: rgba(255, 255, 255, 0);
    background: linear-gradient(to left, #ffffff00 , #ffffff70);
    background-attachment:unset;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    font-family: Anonymous Pro;
    color:rgb(0, 0, 0);
}


.container {
    color:#ffffff;
    font-family: Anonymous Pro;
    font-size: 22px;
}

/*Códigos*/

/*lista de inscrição*/
.Código input {
    position: absolute;
    font-size: 17px;
    right: 20px;
    height: 30px;
    padding: 5px;
    left: 50px;
    top: 24px;
}

.Código {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 20px;
}

.txt {
    position: absolute;
    left: 60px;
    top: 28px;
    color: #ffffff23;
    }

.gg-tikcode {
    box-sizing: border-box;
    position: relative;
    display: block;
    transform: scale(var(--ggs,1));
    width: 18px;
    height: 18px;
    background:
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 10px 0/8px 2px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 10px 6px/8px 2px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 10px 10px/2px 8px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 13px 10px/2px 8px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 16px 10px/2px 8px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 16px 0/2px 8px,
    linear-gradient(
    to left,currentColor 10px,
    transparent 0)
    no-repeat 10px 0/2px 8px;
    left: -2px;
    top: -9px;
   }
   
   .gg-tikcode::after,
   .gg-tikcode::before {
    content: "";
    position: absolute;
    display: block;
    box-sizing: border-box;
    width: 8px;
    height: 8px;
    border: 2px solid;
   }
   
   .gg-tikcode::after {
    bottom: 0
   } 

/*Descrição*/

.Descricao input{
    font-size: 17px;
    right: 20px;
    height: 30px;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    padding: 5px;
    position: absolute;
    left: 50px;
    top: 67px;
}

.Descricao {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 20px;
}

.txt1 {
    position: absolute;
    left: 60px;
    top: 72px;
    color: #ffffff23;
    }

.gg-format-center,
.gg-format-center::before {
 display: block;
 box-sizing: border-box;
 height: 2px;
 background: currentColor;
 border-radius: 3px;
 box-shadow: 0 8px 0;
 position: absolute;
 top: -10px;
}

.gg-format-center {
 margin-top: 28px;
 position: relative;
 transform: scale(var(--ggs,1));
 width: 16px;
 left:-1px;
}

.gg-format-center::before {
 content: "";
 position: absolute;
 width: 10px;
 top: 4px;
 left: 3px;
} 

/*Quantidade*/

.Quantidade input{
    font-size: 17px;
    right: 20px;
    height: 30px;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    padding: 5px;
    position: absolute;
    left: 50px;
    top: 110px;
}

.Quantidade {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 20px;
}

.txt2 {
    position: absolute;
    left: 60px;
    top: 115px;
    color: #ffffff23;
    }

.gg-stack,
.gg-stack::after,
.gg-stack::before {
 display: block;
 box-sizing: border-box;
 width: 14px;
 height: 14px;
 border: 2px solid;
}

.gg-stack {
 margin-right: 8px;
 margin-top: 8px;
 transform: scale(var(--ggs,1));
 position: absolute;
 top: 113px;
 left: 16px;
}

.gg-stack::after,
.gg-stack::before {
 content: "";
 position: absolute;
 border-left: 0;
 border-bottom: 0;
 right: -5px;
 top: -5px;
}

.gg-stack::before {
 right: -8px;
 top: -8px;
} 

/*Preço*/

.Preco input{
    font-size: 17px;
    right: 20px;
    height: 30px;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    padding: 5px;
    position: absolute;
    top: 154px;
    left: 50px;
}

.Preco {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 20px;
}

.txt3 {
    position: absolute;
    left: 60px;
    top: 158px;
    color: #ffffff23;
    }

.gg-dollar {
    box-sizing: border-box;
    position: absolute;
    display: block;
    transform: scale(var(--ggs,1));
    width: 2px;
    height: 20px;
    background: currentColor;
    top: 158px;
    left: 23px;
   }
   
   .gg-dollar::after,
   .gg-dollar::before {
    content: "";
    display: block;
    box-sizing: border-box;
    position: absolute;
    width: 10px;
    height: 8px;
    border: 2px solid;
   }
   
   .gg-dollar::before {
    border-right: 0;
    border-top-left-radius: 100px;
    border-bottom-left-radius: 100px;
    top: 3px;
    left: -6px;
    box-shadow: 4px -2px 0 -2px;
   }
   
   .gg-dollar::after {
    border-left: 0;
    border-top-right-radius: 100px;
    border-bottom-right-radius: 100px;
    bottom: 3px;
    right: -6px;
    box-shadow: -4px 2px 0 -2px;
   } 

/*Custo*/


.Custo input{
    font-size: 17px;
    right: 20px;
    height: 30px;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    padding: 5px;
    position: absolute;
    top: 197px;
    left: 50px;
}

.Custo {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 20px;
}

.txt4 {
    position: absolute;
    left: 60px;
    top: 204px;
    color: #ffffff23;
    }

@keyframes gg-doc {
    0% { left: -16px }
    60%,to { left: 0 }
   }
   
   .gg-loadbar-doc {
    display: block;
    position: relative;
    box-sizing: border-box;
    transform: scale(var(--ggs,1));
    border: 2px solid transparent;
    box-shadow: 0 0 0 2px;
    border-radius: 1px;
    width: 12px;
    height: 14px;
    overflow: hidden;
    position: absolute;
    top: 204px;
   }
   
   .gg-loadbar-doc::after,
   .gg-loadbar-doc::before {
    content: "";
    display: block;
    position: absolute;
    box-sizing: border-box;
    height: 2px;
    background: currentColor;
    animation: gg-doc 1s linear infinite alternate;
   }
   
   .gg-loadbar-doc::before {
    width: 14px;
    box-shadow: -4px 4px 0;
   }
   
   .gg-loadbar-doc::after {
    width: 5px;
    top: 8px;
   } 

/*Tributação*/


.Tributacao input{
    font-size: 17px;
    right: 20px;
    height: 30px;
    border-top-color: rgba(240, 248, 255, 0);
    border-left-color: rgba(240, 248, 255, 0);
    border-right-color: rgba(240, 248, 255, 0);
    padding: 5px;
    position: absolute;
    top: 240px;
    left: 50px;
}

.Tributacao {
    font-size: 22px;
    margin-top: 8px;
    margin-bottom: 15px;
}

.txt5 {
    position: absolute;
    left: 60px;
    top: 246px;
    color: #ffffff23;
    }

@keyframes gg-bar {
    10% {box-shadow: inset 0 -4px 0}
    30% {box-shadow: inset 0 -10px 0}
    60% {box-shadow: inset 0 -6px 0}
    80% {box-shadow: inset 0 -8px 0}
    to {box-shadow: inset 0 -2px 0}
   }
   
   .gg-loadbar-sound,
   .gg-loadbar-sound::after,
   .gg-loadbar-sound::before {
    display: block;
    box-sizing: border-box;
    width: 2px;
    height: 12px;
    box-shadow: inset 0 -12px 0;
    animation: gg-bar 1.3s ease infinite alternate;
   }
   
   .gg-loadbar-sound {
    position: absolute;
    transform: scale(var(--ggs,1.2));
    top:250px;
    left:23px;
   }
   
   .gg-loadbar-sound::after,
   .gg-loadbar-sound::before {
    content: "";
    position: absolute;
    bottom: 0;
   }
   
   .gg-loadbar-sound::before {
    left: -4px;
    animation-delay: -2.4s;
   }
   
   .gg-loadbar-sound::after {
    right: -4px;
    animation-delay: -3.7s;
   } 

/*Botões*/

/* Painel2 */

.container2 {
    position: relative;
    align-items: center;
    margin:auto;
    width: fit-content;
}

/*Cadastrar*/

.Cadastro:hover{
    font-size: 18px;
    backdrop-filter: blur(7px);
    border-radius: 20px;
    border-color: #ffffff00;
    background-color: #ffffff0e;
    font-family: Gadugi;
    padding: 5px;
    cursor: grabbing;
}

.Cadastro{
    font-family: Gadugi;
    font-size: 18px;
    border-color: #ffffff00;
    background-color: #ffffff00;
    color:rgb(255, 255, 255);
    padding: 5px;
    border-radius: 20px;
}

/*Pesquisar*/

.Pesquisar:hover {
    font-size: 18px;
    backdrop-filter: blur(7px);
    border-radius: 20px;
    border-color: #ffffff00;
    background-color: #ffffff0e;
    font-family: Gadugi;
    padding: 5px;
    cursor: grabbing;
}

.Pesquisar {
    font-family: Gadugi;
    font-size: 18px;
    border-color: #ffffff00;
    background-color: #ffffff00;
    color:rgb(255, 255, 255);
    padding: 5px;
    border-radius: 20px;
}

/*Limpar Tudo*/

.Limp:hover {
    font-size: 18px;
    backdrop-filter: blur(7px);
    border-radius: 20px;
    border-color: #ffffff00;
    background-color: #ffffff0e;
    font-family: Gadugi;
    padding: 5px;
    cursor: grabbing;
}

.Limp {
    font-family: Gadugi;
    font-size: 18px;
    border-color: #ffffff00;
    background-color: #ffffff00;
    color:rgb(255, 255, 255);
    padding: 5px;
    border-radius: 20px;
}

/*Mostrar*/

.Mostrart:hover {
    cursor: text;
    font-size: 18px;
    backdrop-filter: blur(7px);
    border-radius: 20px;
    border-color: #ffffff00;
    background-color: #ffffff0e;
    font-family: Gadugi;
    padding: 5px;
    cursor: zoom-in;
}
.Mostrart{
    font-family: Gadugi;
    font-size: 18px;
    border-color: #ffffff00;
    color:rgb(255, 255, 255);
    padding: 5px;
    background-color: #00000000;
}

/*Fakes*/

.CriarFakes:hover {
    color:rgb(255, 0, 0);
    cursor: no-drop;
    border: 1px solid #ff0000;
    cursor: no-drop;
    position: absolute;
    top: -35px;
}

.CriarFakes {
    border: none;
    background-color: rgba(255, 0, 0, 0);
    color:rgba(255, 0, 0, 0);
    font-family:Anonymous Pro;
    position: absolute;
    top: -30px;
}

/*figuras*/

.sóprofake {
    position: fixed;
    top: 370px;
    left: 667px;
}

/* Painel3 */

.divPainel:hover{
    top: 500px;
    left: auto;
    border-radius: 10px;
    border: 2px solid hsl(0, 0%, 100%);
    width: fit-content;
    background-attachment: fixed;
    background-color: rgba(0, 0, 0, 0.521);
    margin: auto;
    color: rgb(255, 255, 255) ; 
    font-family: Anonymous Pro;
    padding: 15px;
    box-shadow: 0 0 8px 0 rgb(255, 255, 255),inset 0 0 8px 0 linear-gradient(#ffffff, #ffffff, #ffffff);
    backdrop-filter: blur(7px);
}

.divPainel:hover {
    top: 500px;
    left: auto;
    border-radius: 10px;
    border: 2px solid hsl(0, 0%, 100%);
    width: fit-content;
    background-attachment: fixed;
    background-color: rgba(0, 0, 0, 0.521);
    margin: auto;
    color: rgb(255, 255, 255) ; 
    font-family: Anonymous Pro;
    padding: 15px;
    box-shadow: 0 0 8px 0 rgb(255, 255, 255),inset 0 0 8px 0 linear-gradient(#ffffff, #ffffff, #ffffff);
    backdrop-filter: blur(7px);
}

.divPainel{
    top: 500px;
    left: auto;
    border-radius: 2px;
    width: fit-content;
    background-attachment: fixed;
    background-color: rgba(255, 255, 255, 0);
    margin: auto;
    color: rgba(255, 255, 255, 0) ; 
    font-family: Anonymous Pro;
    padding: 1px;
    box-shadow: 0 0 8px 0 rgba(0, 0, 0, 0);
    backdrop-filter: blur(1px);

}

a {
    position: fixed;
    font-size: 30px;
    color: #ffffff;
    font-family: Anonymous Pro;
    right: 12px;
    top: 620px;
    text-shadow: 0px 2px 10px #3affce;
}
