<h4> Unoesc Chapecó </h4> 
<h4>   Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob </h4> 
<h4>  Disciplina: HTML5+CSS3 </h4> 
<h4>  Professor: Jean Carlo Nascimento </h4>  
<h4> Acadêmico(a): Jarbas Coltro</h4> 

<h2> Artigo de revisão de CSS3</h2> 

<h1>  Introdução </h1> 

<article>
O CSS ou Cascading Style Sheets é um poderoso recurso de designer web que formata a informação entregue pelo Html. Através do Css é possível definir estilos e variações, deixando do visual mais elegantes e atrativo para o usuário. 
O Css surgiu quando a programação web estava criando seus pilares, inicialmente para atender a necessidade de criar um padrão e renderizar as páginas e posteriormente para agilizar este processo. O Css foi um marco para a programão web, já que permitiu um compartilhamento de formato e reduziu a repetição de código no na estrutura da página. Muitas funcionalidade foram implementadas e melhoradas, as animações e transições ganharam várias funcionalidade e deixaram experiência do usuário em outro patamar. Os seletores são a alma do CSS3, utilizando de forma eficaz é possível tornar o código escalável e inteligente. A possibilidade de atribuirmos múltiplos backgrounds em apenas um elemento é a feature que vai ajudá-lo a não sujar seu código.
A combinação de Html5 e CSS 3, promove ao desenvolvedor uma integração nativa capaz de construir efeitos de rotação, movimento e transição, animações tanto em 2D quanto em 3D, possibilitando a construção de softwares cada vez mais interativos e complexos.
</article>

<h2>CSS3 Transforms </h2>

Esta propriedade tem a funcionalidade de aplicar efeitos visuais 2d e 3d nos elementos da tela. Efeitos com girar, transformar, redimencionar, inclinar e outros.

<h3> Onde usar? </h3>

Podem ser aplicados de diversos componentes como: div, img, fig alterando tua propriedade transform com a animação desejada.
A alteração das suas propertys via javascritp é simples, o codigo object.style.transform="rotate(7deg)" ' a e pode ser aplicado de diversas formas, como: jogos, interações com usuários, tranformações de objetos em softwares especialistas.

<h3> Como usar? </h3>

```html
div {
    -ms-transform: rotate(7deg); /* IE 9 */
    -webkit-transform: rotate(7deg); /* Chrome, Safari, Opera */
    transform: rotate(7deg);
} 
```
<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Transforms Implementados neste link.">Transformes implementados em  site particular </a>

<footer>
Fonte : http://www.w3schools.com/cssref/css3_pr_transform.asp consulta: <dateTime> 14/10/2015 22:00 </dateTime> <br/>
</footer>

<h2> CSS3 Media Queries </h2>

A função Media Queries permite consultar atributos das mídias e alterar seu codigo para melhor adaptação. 

<h3> Onde usar? </h3>

Usados em computadores, tablets, smart-phones etc.Sua função é melhorar a usubilidade do sistema sobre o hardware.

<h3> Como usar? </h3>

```html
@media screen and (min-width: 480px) {
    #leftsidebar {width: 200px; float: left;}
    #main {margin-left:216px;}
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Media Queries Implementados neste link.">Media Queries Implementados neste link</a>

<footer>
Fonte:http://www.w3schools.com/css/css3_mediaqueries.asp consulta: <dateTime> 17/10/2015 20:00 </dateTime> <br/>
</footer>


<h2>CSS3 Transition </h2>

A função transition permite que você altere os valores de propriedade de um elemento causando um efeitos visuais durante um determinado período, pode ser nos eventos do mouse ou eventos da tela. 

<h3> Onde usar? </h3>

Para criar um efeito de transição, você deve especificar duas coisas, a primeira é a propriedade CSS que você deseja adicionar um efeito, e a segunda é duração do efeito .

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

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Transition Implementados neste link.">Transition Implementados neste link </a>

<footer>
Fonte :http://www.w3schools.com/css/css3_transitions.asp consulta: <dateTime> 15/10/2015 18:00 </dateTime> <br/>
</footer>

<h2>CSS3 Animations </h2>

A função Animation permite que um elemento mude de um estilo de forma interativa e animada sem a utilização de javascript e flash. 

<h3> Onde usar? </h3>

Podem ser aplicados de diversos componentes como: div, img, fig alterando tua propriedade animation-name: exemplo e informando a duração da animação, animation-duration: 4s;
Utilizando os @keyframes Rule a animação irá mudar gradualmente a partir do estilo atual para o novo estilo em determinados momentos. Voce pode usar no contexto de criação de jogos e animações para sites.

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

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Animations Implementados neste link.">Animations Implementados neste link </a>

<footer>
Fonte:http://www.w3schools.com/css/css3_animations.asp consulta: <dateTime> 17/10/2015 27:00 </dateTime> <br/>
</footer>

<h2> CSS3 Box flexível </h2>

Os box flexíveis  é um recurso que permite acomodar os elementos de forma previsível, deixando confiavel o layout da pagina sobre os diferentes tamanhos de tela e diferentes dispositivos de exibição.

<h3> Onde usar? </h3>

Geralmente aplicados no elemento div.  É utilizado para alinha-lo de forma dinamica, organizando o layout horizontamente, vericalmente.

<h3> Como usar? </h3>

```html
body {
    direction: rtl;
}

.flex-container {
    display: -webkit-flex;
    display: flex;
    width: 400px;
    height: 250px;
    background-color: lightgrey;
}

.flex-item {
    background-color: cornflowerblue;
    width: 100px;
    height: 100px;
    margin: 10px;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Box flexível Implementados neste link.">Box flexível Implementados neste link</a>

<footer>
Fonte:http://www.w3schools.com/css/css3_flexbox.asp consulta: <dateTime> 17/10/2015 21:00 </dateTime> <br/>
</footer>

<h2>CSS3 Multiplos Background </h2>

CSS3 permite adicionar múltiplas imagens de fundo para um elemento, através do background-image propriedade.
As diferentes imagens de fundo são separados por vírgulas, e as imagens são empilhados em cima uns dos outros, em que a primeira imagem é mais próximo do espectador.

<h3> Onde usar? </h3>

Pode ser usado para aterar o backgroud de site de forma dinâmina e intinerante.

<h3> Como usar? </h3>

```html
#example1 {
    background-image: url(img_flwr.gif), url(paper.gif);
    background-position: right bottom, left top;
    background-repeat: no-repeat, repeat;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="BackGrounds Implementados neste link.">BackGrounds Implementados neste link </a>

<footer>
Fonte:http://www.w3schools.com/css/css3_backgrounds.asp consulta: <dateTime> 17/10/2015 22:00 </dateTime> <br/>
</footer>

<h2>CSS3 Gradients </h2>

A função gradiente permite exibir a transição de cores no elemento. Antigamente era necessário utilizar uma imagem para simular este exemplo.

<h3> Onde usar? </h3>

A utilização dese recurso torna efeitos visuais mais interessantes.

<h3> Como usar? </h3>

```html
#grad {
  background: -webkit-linear-gradient(180deg, red, blue); /* For Safari 5.1 to 6.0 */
  background: -o-linear-gradient(180deg, red, blue); /* For Opera 11.1 to 12.0 */
  background: -moz-linear-gradient(180deg, red, blue); /* For Firefox 3.6 to 15 */
  background: linear-gradient(180deg, red, blue); /* Standard syntax */
}

```
<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Gradientes Implementados neste link.">Gradientes Implementados neste link </a>

<footer>
Fonte:http://www.w3schools.com/css/css3_gradients.asp consulta: <dateTime> 18/10/2015 13:00 </dateTime> <br/>
</footer>

<h2>CSS3 Multi-colunas </h2>

A função multi colunas pemite você tabular o texto em várias colunas com  muita facilidade. 

<h3> Onde usar? </h3>

É utilizada para melhorar a visualização de texto no formato de jornal e faciliar a leitura.

<h3> Como usar? </h3>

```html
div {
    -webkit-column-count: 3; /* Chrome, Safari, Opera */
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Multi Colunas Implementados neste link.">Multi Colunas Implementados neste link</a>

<footer>
Fonte:http://www.w3schools.com/css/css3_multiple_columns.asp consulta: <dateTime> 18/10/2015 14:00 </dateTime> <br/>
</footer>


<h2> CSS3 border-radius </h2>

A função border radius permite altear o estilo da imagem, arendodando as bordas de forma dinamica. Esta funcionalidade permite transformar elementos quadrados em redondos em poucas linas de códigos. 

<h3> Onde usar? </h3>

Pode ser utilizado no desenvolvimento de jogos e interações com o usuário.

<h3> Como usar? </h3>

```html
div {
    -webkit-column-count: 3; /* Chrome, Safari, Opera */
    -moz-column-count: 3; /* Firefox */
    column-count: 3;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title="Borders Colunas Implementados neste link.">Borders radiun  Implementados neste link</a>

<footer>
Fonte:http://www.w3schools.com/css/css3_borders.asp consulta: <dateTime> 19/10/2015 22:00 </dateTime> <br/>
</footer>

<h2> CSS3 Shadow Effects </h2>

A função permite colocar sombras nos textos. 

<h3> Onde usar? </h3>

Pode ser usado para agregar efeitos de designer.

<h3> Como usar? </h3>

```html
h1 {
    text-shadow: 2px 2px 5px red;
}
```

<a href="http://jarbascoltro.weebly.com/css3.html" target="_blank" title=" CSS3 Shadow Effects Implementados neste link."> CSS3 Shadow Effects Implementados neste link</a>

<footer>
Fonte:http://www.w3schools.com/css/css3_shadows.asp consulta: <dateTime> 12/10/2015 20:00 </dateTime> <br/>
</footer>

