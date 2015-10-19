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

```
Nome da funcionalidade;
O que é ou o que faz a funcionalidade;
Onde usar essa funcionalidade, em que contexto deve usar ela;
Como usar essa funcionalidade, ou seja, sua sintaxe de utilização;
Apresentar um exemplo de uso dessa funcionalidade.
Referência de onde extraiu o conteúdo apresentado.
```

<h2>CSS3 Transforms </h2>

Esta propriedade tem a funcionalidade aplicar alguns efeitos visuais nos elementos da tela. Efeitos com girar, transformar, redimencionar, e inclinar deixam os elementos mais interativos. Podem ser aplicados de diversas formas, como: jogos, interações com usuarios, tranformações de textos.

<h3> Como usar? </h3>

```html
div {
    -ms-transform: rotate(7deg); /* IE 9 */
    -webkit-transform: rotate(7deg); /* Chrome, Safari, Opera */
    transform: rotate(7deg);
} 
```
<a href="http://jarbascoltro.weebly.com/css3.html.html" target="_blank" title="Transforms Implementados neste link.">Transformes implementados em  site particular </a>

<footer>
Fonte : http://www.w3schools.com/cssref/css3_pr_transform.asp consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
</footer>



<h2>CSS3 Transition </h2>

A função transition permite que você altere os valores de propriedade de um elemento causando um efeitos visuais durante um determinado período, pode ser nos eventos do mouse ou eventos da tela. Pode ser usado para altefar um elemento e chamar a atenção do usuario, deixando a tela mais interativa.

<h3> Como usar? </h3>

```html
div {
    width: 100px;
    height: 100px;
    background: red;
    -webkit-transition: width 2s; /* Safari */
    transition: width 2s;
}
div:hover {
    width: 300px;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Transition Implementados neste link.">Transformes implementados em  site particular </a>

<footer>
Fonte :http://www.w3schools.com/css/css3_transitions.asp consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
</footer>

<h2>CSS3 Animations </h2>

A função Animation permite que um elemento mude de um estilo de forma interativa e animada sem a utilização de javascript e flash. Voce pode usar no contexto de criação de jogos e animações para sites.

<h3> Como usar? </h3>

```html
div {
    width: 100px;
    height: 100px;
    background: red;
    -webkit-transition: width 2s; /* Safari */
    transition: width 2s;
}
div:hover {
    width: 300px;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Animations Implementados neste link.">Transformes implementados em  site particular </a>

<footer>
Fonte:http://www.w3schools.com/css/css3_animations.asp consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
</footer>

<h2>CSS3 Multiplos Background </h2>

CSS3 permite adicionar múltiplas imagens de fundo para um elemento, através do background-image propriedade.

As diferentes imagens de fundo são separados por vírgulas, e as imagens são empilhados em cima uns dos outros, em que a primeira imagem é mais próximo do espectador.

<h3> Como usar? </h3>

```html
#example1 {
    background-image: url(img_flwr.gif), url(paper.gif);
    background-position: right bottom, left top;
    background-repeat: no-repeat, repeat;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="BackGrounds Implementados neste link.">Transformes implementados em  site particular </a>

<footer>
Fonte:http://www.w3schools.com/css/css3_backgrounds.asp consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
</footer>
