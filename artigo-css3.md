<h1> Introdução </h1>

<article>
O CSS ou Cascading Style Sheets é um poderoso recurso de designer web que formata a informação entregue pelo Html. Através dele e possível definir estilos e variações para deixá-las mais elegantes e atrativas para os usuários. 
O Css surgiu quando a programação para web esta criando seus pilares, inicialmente para atender a necessidade de criar um padrão para renderizar as paginas e posteriormente para agilizar este processo. O Css foi um marco para a programão web, já que permitiu um compartilhamento de formato e reduziu a repetição no conteúdo estrutural de uma página. Muitas funcionalidade foram implementadas e melhoradas. as animações e transições ganharam várias funcionalidade e deixaram experiência do usuário em outro patamar. . Os seletores são a alma do CSS3, utilizando de forma eficaz é possível tornar o código escalável e inteligente. A possibilidade de atribuirmos múltiplos backgrounds em apenas um elemento é a feature que vai ajudá-lo a não sujar seu código.

A combinação de Html5 e CSS 3, promove ao desenvolvedor uma integração nativa capaz de construir efeitos de rotação, movimento e transição, animações tanto em 2D quanto em 3D, possibilitando a construção de softwares cada vez mais interativos e complexos.
</article>
<footer>
Fonte : http://www.w3schools.com/css/ consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
Fonte : http://www.tecmundo.com.br/programacao/2705-o-que-e-css-.htm consulta:<dateTime> 14/10/2015 21:30 </dateTime> <br/> 
Fonte: http://www.w3c.br/pub/Cursos/CursoCSS3/css-web.pdf-css-.htm consulta: <dateTime> 15/10/2015 22:00 </dateTime><br/>
Fonte: http://www.w3schools.com/css/css3_intro.asp consulta: <dateTime> 15/10/2015 22:00 </dateTime><br/>
</footer>

  <style>
        @-webkit-keyframes rodaroda {
            0% {
                -webkit-transform: rotate(0deg);
            }
            50% {
                background: red;
                -webkit-transform: rotate(180deg);
            }
            100% {
                background: blue;
                -webkit-transform: rotate(360deg);
            }
        }
        
        @-webkit-keyframes vaivolta {
            0% {
                top: 0;
            }
            50% {
                top: 20px;
            }
            100% {
                top: 40px;
                border-radius: 40px;
            }
        }
        
        @-webkit-keyframes pendura {
            from {
                -webkit-transform: rotate(0deg);
            }
            to {
                -webkit-transform: rotate(95deg);
            }
        }
        
        @-moz-keyframes rodaroda {
            0% {
                -moz-transform: rotate(0deg);
            }
            50% {
                background: red;
                -moz-transform: rotate(180deg);
            }
            100% {
                -moz-transform: rotate(360deg);
            }
        }
        
        @-moz-keyframes vaivolta {
            0% {
                top: 0;
            }
            50% {
                top: 20px;
            }
            100% {
                top: 40px;
                border-radius: 40px;
            }
        }
        
        @-moz-keyframes pendura {
            from {
                -moz-transform: rotate(0deg);
            }
            to {
                -moz-transform: rotate(95deg);
            }
        }
        
        .giragira {
            width: 50px;
            height: 50px;
            margin: 15px 0 0 15px;
            background: black;
            -webkit-animation: rodaroda 1s linear alternate 3;
            -moz-animation: rodaroda 0.5s linear infinite;
            -o-animation: rodaroda 0.5s linear infinite;
            animation: rodaroda 0.5s linear infinite;
        }
        
        .vaivolta {
            width: 50px;
            height: 50px;
            margin: 35px auto 0;
            background: black;
            position: absolute;
            left: 20%;
            -webkit-animation: vaivolta 1s alternate linear infinite;
            -moz-animation: vaivolta 1s alternate linear infinite;
            -o-animation: vaivolta 1s alternate linear infinite;
            animation: vaivolta 1s alternate linear infinite;
        }
        
        .pendura {
            width: 50px;
            height: 50px;
            margin: 35px auto 0;
            background: black;
            -webkit-transform: rotate(0deg);
            -webkit-transform-origin: 0px 0px;
            -moz-transform: rotate(0deg);
            -moz-transform-origin: 10px 10px;
            -o-transform: rotate(0deg);
            -o-transform-origin: 10px 10px;
            -webkit-animation: pendura 1s alternate ease infinite;
            -moz-animation: pendura 1s alternate ease infinite;
            -o-animation: pendura 1s alternate ease infinite;
        }
        
        .pendura:hover {
            -webkit-animation-play-state: paused;
        }
    </style>
