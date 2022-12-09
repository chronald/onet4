##	 Anotações sobre lógica de programação | Alura

Para quebrar linhas no sublime utilizar <'br'>

Utilizar <'h1'> </'h1'> para titulos

para criar links na web utilizar <'a href= "link"></'a'>

Para utilizar javascript no sublime utilizar <'script'> </'script'>

utilizar alert ("") para dar um popup no chrome.

utilizar a tag <'meta charset="UTF-8"'> para não dar problema de acentuação.

todo navegador tem um plugin = depurador que informa onde está o problema no código para utilizar usar f12 ou ctrl + shift + C

todo texto em javascript vem entre aspas.

charset = atributo

alert recebe parâmetro, no javascript = " "

sempre utilizar parênteses () para string

utilizar document.write() dentro do script para escrever em html e deixar mais dinâmico 

para criar uma variável utilizar var nome = resultado;

para a variável funcionar ao utilizar a mesma, tem que está declarado igual a variável, caso tenha uma letra diferente não funcionará.

para arredondar em javascript utilizar Math.round(variável);

variável não guarda apenas número.

utilizar // para fazer um comentário

para pular mais de uma linha utilizar document.write('<.br><.br>')

#### Função

para declarar uma função em javascript a mesma deve ser no começo do script.

função = sempre um verbo.

utilizar function pulaLinha (){

}

#### Função com parâmetro

para utilizar uma função com parâmetro precisa dar um nome dentro da () da function ficando assim

function mostra(frase){

​		document.write(frase)

} 

mostra('Christian tem:' + (ano - 2002) + " anos");

uma função funciona dentro de outra função.

function mostra(frase){

​	pulaLinha()

}

**Caso você passe um parâmetro para uma função e ao utilizar a função não informar nada ficará como undefined**

utilizar a tag <.hr> para separar um resultado do outro.

podemos passar mais de um parâmetro dentro de uma função.

**podemos transformar uma função em uma variavel exemplo:**

var imcChristian = calculaIMC(1.60, 48); 

**para retornar um valor na função utilizar return exemplo:**

function calculaIMC(altura, peso){

​	var imc = peso / (altura * altura);

​	return imc;

}

**pode utilizar somente o return no calculo caso queira.**

function calculaIMC(altura, peso){

​	return peso / (altura * altura);	

}

**para realizar uma interação em javascript utilizar prompt conforme o exemplo abaixo**:

var alturaInformada = prompt('Informe sua altura:');

**para transformar o retorno de prompt em numero ao invés de String utilizar parseInt() exemplo:**

var vitorias = **parseInt**(prompt('Numero de vitorias: '));

**Para utilizar condições em javascript utilizar o exemplo abaixo**

if **(**pontos > 28**)** {

​	resultado.

}

&& = E

|| = OU

! = DIFERENTE

para utilizar o diferente de **if** utilizar **else** exemplo abaixo:

if(pontos>28){

​	resultado

}else {

}

**Para gerar numero aleatório em javascript utilizar *Math.random exemplo:***

Math.round(Math.random() * 10);

**Para realizar repetição em javascript utilizar while exemplo**

while (anoCopa <=2022){

​	mostra("teve  copa em " + anoCopa);

​	anoCopa += 4;

}

**variavel++ = variavel +1**

**Outra forma de utilizar repetição é utilizando o for**

*for (var multiplicador = 1; multiplicador <= 10; multiplicador++);*{

​	var valor = 7

​	mostra('${multiplicador} x ${valor} = ${valor * multiplicador}')

}

**Para interromper uma repetição utilizar  o exemplo abaixo**

while (variavel <= 3){

​	if = acertou

​	mostra();

​	break;

}

**Para criar repetições aninhadas utilizar o exemplo abaixo.**

for(var linha = 1; linha <=3; linha++){

​	for(var coluna = 1; coluna<10; coluna++){

​	document.write("*");

}

}

**Parar converter para números reais(com virgula) utilizar o método parseFloat();**

exemplo :

var numero = parseFloat("12.13");

**bom para utilizar com o prompt**
