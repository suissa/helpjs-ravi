# Exercicios em JavaScript

## Previa leitura antes de tudo: (não precisa entender só ler ta valendo...)  
[http://tableless.com.br/tenha-o-dom/](http://tableless.com.br/tenha-o-dom/)

Recomendo utilizar o editor de texto de sua preferência para execução dos scripts abaixo.  
A KingHost fez um post bacana, [Lista 10 Editores gratuitos](http://www.kinghost.com.br/blog/2016/04/super-lista-com-os-10-melhores-editores-de-codigo-gratuitos/)  
Eu utilizo o [NotePad++, (Np++ para os íntimos)](https://notepad-plus-plus.org/download/v6.9.2.html), por ser extremamente leve, mas fique a sua escolha.

(Leia os exemplos no final da pagina caso você 'trave' em  algum exercício)
 
## Just.... DO IT:
  - (1) Faça uma mensagem de **'Olá Mundo'**....
  - (2) Faça essa mensagem em um arquivo externo e chame ela... **(Importado)**
  - (3) Faça uma saída de soma de 2 inteiros, ex: alert(2 + 2)
  - (4) Coloque um campo do tipo text chamado 'Click-Me' no seu HTML e exiba ele dentro do alert ao clicar o botão (necessário saber evento 'click') **(Exemplo abaixo)**
  - (5) exiba a quantidade de letras que possuem o texto inserido ao clicar no botão
  - (6) No seu HTML exiba a imagem ['Lampada'](https://github.com/gabrieldarezzo/helpjs-ravi/tree/master/images) ---- [(Exemplo de como fazer)](http://www.clem.ufba.br/tuts/html/c12.htm). 
  - (7) Agora que você já sabe utilizar o evento 'click', aprenda a usar o 'mouseover', ao passar o mouse em cima da 'lampada.jpg' altere ela para 'lampada-on.jpg' (Exemplo abaixo).
  - (8) no campo texto do exercício anterior, preencha um CPF (com pontuação e exiba o mesmo sem pontuação)  
  - (9) no campo texto do exercício anterior, preencha um CPF (sem pontuação e exiba o mesmo sem pontuação)  
  - (10) declare 2 variáveis (valor1,valor2)  com valores 2 ,  6 crie uma terceira variável com o resultado sendo a soma de (valor1,valor2), exiba o mesmo.
  - (11) faça 1 botão, 3 campos texto no html.E passe dinamicamente o primeiro campo valor1, segundo campo valor2, e no terceiro campo ao clicar no botão exiba a soma
 Dica: trabalhe com id="", e no html utiliza a tag <button id="btn-acao">Click-Me</button>
  - (12) Faça um comentário de uma linha no JavaScript
  - (13) Faça um comentário de varias linhas no JavaScript
  - (14) Crie uma div com o id 'resultado' no html (vazia) e insira via JavaScript no ato do 'Load' da página o trecho : 'Esse html veio do JavaScript...'
  - (15) Agora crie um botão que ao clicar faça a mesma coisa que o exercício acima.
  - (16) Crie uma função que recebe 2 parâmetros e retorna a soma deles.
  - (17) Crie uma função que recebe 2 parâmetros e retorna a soma deles, porem caso seja passado um parâmetro vazio ela retorne zero.
  - (18) Exiba o 'resto' da seguinte divisão: (5 / 2)
  - (19) Crie uma função que retorna a palavra (impar/par) de acordo com seu parâmetro.
  - (20) Crie uma função que recebe 2 parâmetros e retorna a multiplicação deles. 
  - (21) Crie uma função que calcula 5% de desconto retornando o valor do desconto.
  - (22) Crie uma função que recebe o ano de nascimento da pessoa informando se ela é maior de idade ou menor.
  - (23) Dentro da div com o id 'resultado', escreva 1x ('Repetição'). @dica 'innerHTML', ``` el.innerHTML = 'Repetição'; ```
  - (24) Dentro da div com o id 'resultado', escreva 2x ('Repetição').
  - (25) Dentro da div com o id 'resultado', escreva 20x ('Repetição'). (use o 'for' pelo amor de deus)
  - (26) Dentro da div com o id 'resultado', escreva 5x ('Repetição'). (agora com forEach)
  - (27) Dentro da div com o id 'resultado', escreva 5x ('Repetição'). (agora com while)
  - (28) Dentro da div com o id 'resultado', escreva 5x ('Repetição'). (agora com while) 
  - (29) Dentro da div com o id 'resultado', os números de 0 ~ 10 (escolha uma das opções acima)
  - (30) Dentro da div com o id 'resultado', os números pares até 20... (ex 2,4,6...)
  - (31) Ok... chega de for, mentira/#SQN... Exiba a tabuada do 1 até o 10 (for dentro de for?) (caso você escreva manualmente a tabuada eu vou te bater HSUAHASHUAS)
  - (32) Crie uma função que informa se tem 'dota' no parâmetro informado.
  - (33) Exiba aleatoriamente um número pelo alert()
  - (34) Agora faça um botão que ao clicar nele informa se a pessoa acertou o número.
  - (35) Exiba a data atual pelo JavaScript no seguinte formato: dia/mês/Ano
  - (36) Exiba o próximo mês (dinamicamente obviamente)

## Just.... DO IT ARRAYS:  
Entenda sobre arrays:
https://pt.wikipedia.org/wiki/Arranjo_(computa%C3%A7%C3%A3o) ou https://en.wikipedia.org/wiki/Array_data_type



- (37.a) Crie o seguinte array: ```var goods = new Array('Aegir', 'Aud', 'Balder');```  
E Exiba a quantidade/comprimento que ele tem com a função [.length](http://www.w3schools.com/jsref/jsref_length_string.asp)  

- (37.b) Crie o seguinte array: ```var goods = new Array('Aegir', 'Aud', 'Balder');```  
E exiba um a um com ```alert();``` - De preferencia para laços de repetição (for, forEach, while, do{}while)

- (37.c) Crie o seguinte array: ```var goods = new Array('Aegir', 'Aud', 'Balder');```  
Adicione os 3 Deuses: ('Loki', 'Odin', 'Frey') com a função [push()](http://www.w3schools.com/jsref/jsref_push.asp)  

- (37.d) Crie o seguinte array: ```var goods = new Array('Aegir', 'Aud', 'Balder');```  
Adicione os 3 Deuses: ('Loki', 'Odin', 'Frey') com a função [.length](http://www.w3schools.com/jsref/jsref_length_string.asp)  

- (37.e) Crie o seguinte array: ```var numbers = new Array(5, 7, 1, 8, 9);```  
E exiba de forma crescente:  @dica: [.sort](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array/sort)   
@dica2: http://pt.stackoverflow.com/questions/9900/como-ordenar-um-array-por-valores

- (37.f) Crie o seguinte array: ```var numbers = new Array(5, 7, 1, 8, 9);```  
E exiba de forma decrescente.


- (38) Crie o seguinte array: ```var goods = new Array('Aegir', 'Aud', 'Balder', 'Bragi', 'Búri', 'Dag', 'Dellingr');```  
E exiba todos os nomes, dentro do html: ```<ul id="nomes"></ul>```

- (39) Crie um campo texto no html que armazena o conteúdo em um array sempre que você clicar no botão, e apresente em uma lista(ul)

- (40) Crie um campo texto no html que armazena o conteúdo em um array sempre que você clicar no botão, e apresente em uma lista(ul) destacando os números pares

- (41) Crie um campo texto no html que armazena o conteúdo em um array sempre que você clicar no botão, e apresente em uma lista(ul) possibilitando excluir individualmente o item/li clicado

JavaScript curiosidade...  
http://pt.stackoverflow.com/questions/8035/qual-a-diferen%C3%A7a-entre-declarar-uma-matriz-com-array-e-em-javascript 




## Tópicos futuros:
  - (feito) Arrays/Matrizes/Vetores?
  - Classes/Prototype
  - JSON
  - Manipulação de CSS pelo JavaScript
  - Explicação do que Jquery


# Temos 3 formas de chamar um JavaScript (Inline, Incorporado, Importado) veja abaixo:


  ## Inline [(Veja o Demo)](http://gabrieldarezzo.github.io/helpjs-ravi/exemplos/inline/)
```html
<!DOCTYPE HTML>
<html lang="pt-br">
<head>
	<meta charset="utf-8">
	<title>JS Examples</title>
</head>
<body>
	<button onclick="alert('Hit-me');">Click-Me</button>
</body>
</html>
```
  
  ## Incorporado [(Veja o Demo)](http://gabrieldarezzo.github.io/helpjs-ravi/exemplos/incorporado/)
```html
<!DOCTYPE HTML>
<html lang="pt-br">
<head>
	<meta charset="utf-8">
	<title>JS Examples</title>
</head>
<body>
	
	<script type="text/javascript">
		alert('Olá');
	</script>
</body>
</html>
```
  

  ## Importado [(Veja o Demo)](http://gabrieldarezzo.github.io/helpjs-ravi/exemplos/importado/) 
```html
<!DOCTYPE HTML>
<html lang="pt-br">
<head>
	<meta charset="utf-8">
	<title>JS Examples</title>
</head>
<body>
	<script type="text/javascript" src="my_script.js"></script>
</body>
</html>
```

Conteúdo do 'my_script.js':
```javascript
alert('Olá!!!');
```

# Exemplos de códigos para resolução dos exercícios...


Isto é um alert...
```javascript
alert('Olá Mundo!');
```
Isto tambem é um alert, pode ser considera um 'exibir' ou 'saída' ou 'output' da linguagem:
```javascript
alert(2 + 2);
```
Entenda:  
https://pt.wikipedia.org/wiki/Entrada/sa%C3%ADda ou  https://en.wikipedia.org/wiki/Input/output 

Isto monitora o evento 'click' no html (Incorporado/Importado)
```javascript
document.getElementById('proximo-quadro').addEventListener('click', function() {
	alert('Click');
});
```
Isto monitora o evento 'click' (Inline)
```html
<button onclick="alert('Hit-me');">Click-Me</button>
```

O código abaixo monitora o evento 'click' do elemento DOM com o id 'my-btn' e depois exibe o valor(value) do elemento my-txt
```html
...
<body>
<p>Preencha Qualquer coisa e depois clique no botão abaixo...</p>
<input type="text" name="" id="my-txt" />
<br />
<button id="my-btn">Outro 'Button'</button>

<script type="text/javascript">
	document.getElementById("my-btn").addEventListener('click', function() {
		var texto = document.getElementById("my-txt").value;
		alert(texto);
	});
</script>
</body>
...
```

O código abaixo seleciona um elemento pelo DOM (id="my-photo"), e altera o src deste elemento para 'foto-diferente.jpg'
```html
...
<body>
	<img src="foto-atual.jpg" alt="Minha Foto" id="my-photo"/>
	<script type="text/javascript">
		document.getElementById("my-photo").src = 'foto-diferente.jpg';
	</script>
</body>
...
```


O código abaixo cria uma função em JavaScript, [leia mais](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Fun%C3%A7%C3%B5es)
```html
...
<body>
	<script type="text/javascript">
		function somaDoisNumeros(primeiro, segundo){
		
			//Armazena o resultado da soma do primeiro parâmetro + segundo parâmetro.
			var resultado = primeiro + segundo;
			
			//E retorna a variavel.
			return resultado;
		}
		
		alert(somaDoisNumeros(1, 3));
		alert(somaDoisNumeros(3, 3));
		alert(somaDoisNumeros(2, 2));
	</script>
</body>
...
```


## Ainda com dúvidas de como executar o Olá mundo no JavaScript?!  
#### Fiz um passo a passo.  
**(Não precisa de servidor cara aqui é só JavaScript.... Qualquer navegador já executa, preferencialmente o Google Chrome.**

  - Copie e cole o conteúdo do 'Inline' acima... (ou escreva, é bom saber algumas tags/codes de cabeça...)
![Código HTML + JavaScript](https://raw.githubusercontent.com/gabrieldarezzo/helpjs-ravi/master/img-readme/1.png)

  - Clique em 'Arquivo' -> 'Salvar Como'
![Salvar->Salvar Como](https://raw.githubusercontent.com/gabrieldarezzo/helpjs-ravi/master/img-readme/2.png)

  - Escolha uma pasta, (de preferencia crie uma para cada exercício. **Exemplo: 'ex', 'ex1', ...)** )
![Salve o arquivo](https://raw.githubusercontent.com/gabrieldarezzo/helpjs-ravi/master/img-readme/3.png)

  - Vá até a pasta escolhida, clique com botão direito no arquivo salvo e depois 'Abrir com' -> 'Google Chrome' **(Caso não apareça a opção só arrasta para o navegador aberto)**
![Salve o arquivo](https://raw.githubusercontent.com/gabrieldarezzo/helpjs-ravi/master/img-readme/4.png)

  - Prontinho... Seu código foi executado @dica: caso você altere o arquivo 'index.html' é só dar um F5 (Ou Ctrl + R) no navegador que você olha a alteração.  
![Salve o arquivo](https://raw.githubusercontent.com/gabrieldarezzo/helpjs-ravi/master/img-readme/5.png)

# Pow eu fiz os códigos, porem não acontece nada/fiz os códigos e não ocorreu o esperado....
  **Ai meu filho você precisa aprender a *debbugar**:
  - http://www.devfuria.com.br/javascript/debugando/
  - http://www.devmedia.com.br/depurando-javascript-com-google-chrome/28367


# Ainda tem dúvida? Cria um 'Issue' tio....
  -  https://github.com/gabrieldarezzo/helpjs-ravi/issues 

# Artigos lekais de JavaScript/HTML/CSS:  
  - http://tableless.github.io/iniciantes/
  - http://wbruno.com.br/category/javascript-puro/
  - https://www.youtube.com/playlist?list=PLQCmSnNFVYnT1-oeDOSBnt164802rkegc
  - http://jstherightway.org/pt-br/#js-code-style
  - http://www.codewars.com/?language=javascript
  - Ebooks gratuitos de JS -> http://jsbooks.revolunet.com/
  - Ebooks gratuitos de JS_2 -> https://devfreebooks.org/javascript/
  
# Motivos para você usar o Google Chrome:  
  - https://www.youtube.com/playlist?list=PLOU2XLYxmsILUKyjDYUVYLeq7yyTxM_3d
  - https://chrome.google.com/webstore/detail/do-it/eppncnmppghbndacgkideegigaminkfg
  
# JQuery  
  - http://try.jquery.com/  
  
  




Entenda o que é ['Vanilla-js'](http://pt.stackoverflow.com/questions/46983/o-que-%C3%A9-o-vanilla-js)  
Powered By:  
[![Vanilla-js](http://vanilla-js.com/assets/button.png)](http://vanilla-js.com/)  


