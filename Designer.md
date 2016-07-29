<h5> Unoesc Chapecó </h5> 
<h5> Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob </h5> 
<h5> Disciplina: FERRAMENTAS DE EDIÇÃO E CRIAÇÃO DE LAYOUTS </h5> 
<h5> Professor: DIEGO NAUJALIS DOS SANTOS </h5>  
<h5> Acadêmico(a): Jarbas Coltro</h5> 

<article>

<h2>  Artigo de layout Z </h2>

<h1>  Resumo </h1> 

O Layout Z se caracteriza pela pela facilidade ao juntar a forma e objetividade.Baseado no diagrama de Gutenberg que descreve um padrão geral os olhos se movem através quando se olha para uniformemente distribuída informação. Este método descreve os itens abaixo:

```html
* Área óptica primária localizada no topo / esquerda
* Strong área de pousio localizado no topo / direita
* Fraco área de pousio localizado na parte inferior / esquerda
* Área do terminal localizado na parte inferior / direita
```
<li class="comment-container">
	<div class="comment-meta">
		<img src="https://d60f479a-a-62cb3a1a-s-sites.googlegroups.com/site/jarbascltr/img_ref/FLUXO_ARTIGO.png?attachauth=ANoY7cpYRz76MEiT2c8cF2K4elC981ttn0RIomjMspdogGzP-sL6PXNIiErP1-xPddiidfgznnxJjfZJXRCP79hv5SM0-F82QCeTtA7rb3Q7E17XTGPpJj2kiqfuDMdM-xFHTRnXdvuXzrpCV4-f34eTip-I5rKb3jL8OqrtpW9GPwd6VM6uXyoF3l9NCf9L9qz6ZLYH7fh-te_6PAUcqxHIabe5kOETbMvkLM0H3fUE3RaFfpifjlg%3D&attredirects=0" alt="Avatar" />		<h4 class="comment-name"><a href="#">Jarbas Coltro</a></h4>
	</div>
	<div class="comment-text">
		<p>Comentário do artigo sobre Atomic Design</p>
	</div>
</li>

<h2> Artigo de revisão de Atomic Design </h2> 

<h1>  Resumo </h1> 

O atomic design é um método para criação de sistemas de designer inteligente. Explicado pela analogia do mundo biológico relacionado com o desenvolvimento de designers web. Esta analogia descreve desde o átomo até o organismo mais complexo, ou seja, desde os objetos ou tag's até as páginas por completo.

<h2>O que é? </h2>

 Projeto atômico é método para a criação de sistemas de design. É uma estrutura de hierarquia de complexidade, que começa pelo mais simples e vai até o mais complexo.

<h3>Como funciona? </h3>

Átomos    = São objetos de uma forma genérica ou abstrata como queira. <br/>
Exemplos: tag Html (button,Label, Input, outros). <br/>

Moléculas = São conjuntos de Átomos. Combinações de objetos ou tag html que produzem um resultado combinado.   <br/>

Organismos = Conjunto de Moléculas, podem ser definidos como blocos de construção, que aceleram o desenvolvimento;  <br/>

Modelos = Conjunto de organismos, são os projetos definido para as construção das páginas, é onde se define o contexto para as moléculas e organismos;  <br/>

Páginas = As páginas são instâncias específicas de modelos. O mais alto nível. ;  <br/>

<h2>Para que usar </h2>

Esta metodologia está construindo seus pilares na programação web, já é possível através do patternlab.io deslumbrar das facilidades que isso promoverá no contexto de designer. Este método atravessa o abstratismo ao concreto muito rapidamente.

<h2>Onde usar?</h2>

A Atomic Design pode ser usado para a construção de sitemas web.

<h3>Exemplo de cada etapa </h3>

<h2>Átomos</h2>

Exemplo Átomo de Heading em todos os níveis.

```html
<h1>Heading Level 1</h1>
<h2>Heading Level 2</h2>
<h3>Heading Level 3</h3>  
<h4>Heading Level 4</h4>
<h5>Heading Level 5</h5> 
<h6>Heading Level 6</h6>
```
<h1>Heading Level 1</h1>
<h2>Heading Level 2</h2>
<h3>Heading Level 3</h3>  
<h4>Heading Level 4</h4>
<h5>Heading Level 5</h5> 
<h6>Heading Level 6</h6>

<a href="http://demo.patternlab.io/?p=atoms-headings" target="_blank" title="Atomos.">Atomos em demo.patternlab.io </a>


<h2>Moléculas</h2>

Exemplo de uma molécula - estrutura de um comentário.

```html
<li class="comment-container">
	<div class="comment-meta">
		<img src="../../images/fpo_avatar.png" alt="Avatar" />		<h4 class="comment-name"><a href="#">Lacy Way</a></h4>
	</div>
	<div class="comment-text">
		<p>Comentário do artigo sobre Atomic Design .</p>
	</div>
</li>
```

<li class="comment-container">
	<div class="comment-meta">
		<img src="https://d60f479a-a-62cb3a1a-s-sites.googlegroups.com/site/jarbascltr/img_ref/264306_228552223845203_6389222_n.jpg?attachauth=ANoY7cq4QdfOBSYd5aidpDeMQkozIE4xRYi2GLKWQZ7PcwwPUL2RirhySk0n3JHsTdp_s2-n4ii2kYMRbc3SSBsCfe4loPmZhOGoVuOTGPd2TXhtQ_ZewtG_xSZMyRlti_FyxwtwCSG8LQ8ZomSzm9dr90cncnkym9snWoMdtdQ5suyylAXcVdiMuIhSHmHbcVLy5lqsX2GroHIoJer1UMFyYPCAenQRMTEaUUZF3AlUEi1TMXgCGvuTPgk3LSUy6XtVBND3nWMH&attredirects=0" alt="Avatar" />		<h4 class="comment-name"><a href="#">Jarbas Coltro</a></h4>
	</div>
	<div class="comment-text">
		<p>Comentário do artigo sobre Atomic Design</p>
	</div>
</li>

<a href="http://demo.patternlab.io/?p=molecules-single-comment" target="_blank" title="Moleculas - .">Moléculas em demo.patternlab.io </a>

<h2>Organismo</h2>

Exemplo de uma Organismo - estrutura de um comentário.

```html
<section class="comments section">
	<div class="comments-container" id="comments-container">
		<h2 class="section-title">59 Comments</h2>
		<form method="post" action="#" class="comment-form">
			<fieldset>
				<div class="field-container">
					<label for="comment-name">Name</label>
					<input id="comment-name" type="text" placeholder="Enter Your Name" />
				</div>
				<div class="field-container">
					<label for="comment-email">Email</label>
					<input id="comment-email" type="email" placeholder="Your email address" />
				</div>
				<div class="field-container">
					<label for="comment-url">URL</label>
					<input id="comment-url" type="url" placeholder="Website if you got one" />
				</div>
				<div class="field-container">
					<label for="comment-field">Comment</label>
					<textarea id="comment-field" rows="5" placeholder="Write you comment here"></textarea>
				</div>
			</fieldset>
		</form>		<ul class="comment-list">
				<li class="comment-container">
					<div class="comment-meta">
		<img src="http://placeimg.com/100/100/people" alt="Avatar" />						<h4 class="comment-name"><a href="#">Junius Koolen</a></h4>
					</div>
					<div class="comment-text">
						<p>Fizzle crazy tortor. Sed rizzle. Ass pimpin' dolor dapibizzle turpis tempizzle fo shizzle my nizzle. Maurizzle pellentesque its fo rizzle izzle turpis. Get down get down we gonna chung nizzle. Shizzlin dizzle eleifend rhoncizzle break it down. In yo ghetto platea dictumst. Bling bling dapibizzle. Curabitur break yo neck, yall fo, pretizzle eu, go to hizzle dope, own yo' vitae, nunc. Bizzle suscipizzle. Ass semper velit sizzle fo.</p>
					</div>
				</li>				<li class="comment-container">
					<div class="comment-meta">
		<img src="http://placeimg.com/100/100/tech/sepia" alt="Avatar" />						<h4 class="comment-name"><a href="#">Matthias Macguinness</a></h4>
					</div>
					<div class="comment-text">
						<p>Sugar plum wafer soufflÃ© ice cream. Wafer topping biscuit pie gummi bears topping. Gummies toffee powder applicake oat cake cookie. Bear claw candy tootsie roll fruitcake danish applicake candy canes macaroon. Liquorice tiramisu danish cotton candy gummies. Tiramisu dessert gummi bears macaroon sweet roll jelly-o gummi bears marzipan.</p>
					</div>
				</li>				<li class="comment-container">
					<div class="comment-meta">
		<img src="http://placeimg.com/100/100/any/sepia" alt="Avatar" />						<h4 class="comment-name"><a href="#">Jacobus Sneiders</a></h4>
					</div>
					<div class="comment-text">
						<p>I find your lack of faith disturbing. A tremor in the Force. The last time I felt it was in the presence of my old master. Don't act so surprised, Your Highness. You weren't on any mercy mission this time. Several transmissions were beamed to this ship by Rebel spies. I want to know what happened to the plans they sent you. The plans you refer to will soon be back in our hands.</p>
					</div>
				</li>				<li class="comment-container">
					<div class="comment-meta">
		<img src="http://placeimg.com/100/100/arch" alt="Avatar" />						<h4 class="comment-name"><a href="#">Fergus Althuis</a></h4>
					</div>
					<div class="comment-text">
						<p>Beats all you've ever saw, been in trouble with the law since the day they was born. Straight'nin' the curve, flat'nin' the hills. Someday the mountain might get 'em, but the law never will. Makin' their way, the only way they know how, that's just a little bit more than the law will allow. Just good ol' boys, wouldn't change if they could, fightin' the system like a true modern day Robin Hood.</p>
					</div>
				</li>				<li class="comment-container">
					<div class="comment-meta">
		<img src="http://placeimg.com/100/100/people/grayscale" alt="Avatar" />						<h4 class="comment-name"><a href="#">Frans Keegan</a></h4>
					</div>
					<div class="comment-text">
						<p>Like button audience atomization overcome Colbert bump Free Darko inverted pyramid we will make them pay, digital circulation strategy Like button totally blowing up on Twitter church of the savvy. Pictures of Goats section open source discuss Frontline analog thinking filters paidContent.</p>
					</div>
				</li>		</ul>
	</div>
	<ol class="pagination">
		<li class="current"><a href="#">1</a></li>
		<li><a href="#">2</a></li>
		<li><a href="#">3</a></li>
		<li><a href="#">4</a></li>
		<li><a href="#">5</a></li>
		<li><a href="#">6</a></li>
		<li><a href="#">7</a></li>
	</ol></section>
```


<a href="http://demo.patternlab.io/?p=organisms-comment-thread" target="_blank" title="Organismo">Organismo em demo.patternlab.io </a>

<h2>Modelos ou templates</h2>

Segue link um exemplo de Templates - Atomic Design. 

<a href="http://demo.patternlab.io/?p=pages-homepage-emergency" target="_blank" title="Templates">Templates em demo.patternlab.io </a>


<h2>Pages</h2>

Segue link um exemplo de Pages - Atomic Design.

<a href="http://demo.patternlab.io/?p=pages-homepage" target="_blank" title="Pages">Pages em demo.patternlab.io </a>


</article>

<h1>  Referências </h1> 

<a href="http://bradfrost.com/blog/post/atomic-web-design/" target="_blank" title="Pages">bradfrost.com/blog/post/atomic-web-design/ </a> <br/>
<a href="http://malarkey.github.io/Rock-Hammer/" target="_blank" title="Pages">http://malarkey.github.io/Rock-Hammer/ </a> <br/>
<a href="https://stuffandnonsense.co.uk/blog/about/rock-hammer-a-curated-responsive-project-library" target="_blank" title="Pages">stuffandnonsense.co.uk/blog/about/rock-hammer-a-curated-responsive-project-library </a> <br/>
