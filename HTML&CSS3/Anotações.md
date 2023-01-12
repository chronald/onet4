## HTML5 e CSS3 parte 1: crie uma página da Web - Anotações.



#### HTML - Textos

**index.html** = arquivo principal da pagina.

**<'h1> </'h1>** = Titulo do texto..

**<'p> </'p>** = paragrafo.

**<'strong><'/strong>** = negrito.

**<'em'> <'/em>** = italico '

**<'!DOCTYPE html'> **= para informar que está sendo usado a ultima versão de HTML.

**<'html'> <''/html'> **= para informar tudo que é HTML

**<'meta charset="UTF-8"'>** =para poder usar todos os caracteres que tem nas linguagem e resolver problemas dos acentos

**<'html lang="pt-br"> **= para o sistema entender que a pagina é Português.

**<'title'><'/title'>** = Para atualizar o titulo da aba do navegador.

**<'head> </'head>** = para passar informações para o navegador.

**<'body'></'body'>** = para exibir informações no navegador.

**<'h2> <'/h2> **= Para utilizar como segundo titulo3

**<'ul> <'/ul>** = Lista não ordenada 

**<'ol> <'/ol> **= Lista Ordenada

**<'li><'/li>** = utilizar para cada um dos itens da lista. 

**<'div><'/div>** = para ter uma divisão em HTML e "facilitar" o uso do CSS.

**<'header> <'/header>** = Cabeçalho 

**<'a href="index.html"><'a/>** = para criar um link em html

**<'nav> <'/nav>** = para alterar o css dentro do cabeçario 

**<'main> <'/main> ** = Conteudo principal

**<'footer><'/footer> **= rodapé

**<'form><'/form>** = formulario 

**<'input>** = para coletar informação do usuario 

**<'label><'/label>** = etiqueta para o input

**Utilizar ID no input e for no label com a mesma informação** 

**Toda caixa de texto terá um input type="submit"-**

**Utilizar value"" no input do submit para passar uma nova frase** 

**Para ter um código mais clean com input e label, é possivel incluir o input dentro da label exemplo <'label for="" ><'input type="" name="" id=""><'/label'>**

**<'textarea cols="30" rows="10"> <'/textarea>=** para entradas de texto de mais de uma linha 

**<'input type="radio" value="email">** = terá um valor/ necessário utilizar label  para que tenha um texto.

**<'input type"checkbox">**= Para ter uma caixinha para marca e desmarcar.

**<'select></'select>** = Campo de seleção de um item

**<'option><'/option>** = representa cada opção do seletor. 

**<'input type="text">** = input de texto

**<'input type="email">** = input para email.

**<'input type="tel">** = input para telefone

**<'input type="number">** = input para número. bom para cpf/cep

**<'input type="password">** = input para senha

**<'input type="date">** = input para data

**<'input type="datetime">** = input para data e hora.

**<'input type="month">** = input para mês.

**<'input type="search">** = input para pesquisa.

**utilizar REQUIRED para tornar um campo de preenchimento obrigatório** 

**utilizar placeholder="" pra sugestão de preenchimento**

**utilizar checked para ter uma caixa marcada automaticamente ao entrar na pagina**

**<'fieldset><''/fieldset>** = referente a configuração de um ou mais campos referente a um assunto especifico, utilizado para preenchimento de dados.

**<'legend><'/legend>** = titulo do fieldset

**utilizar alt="" para imagens, sendo uma alternativa para quem não consegue ver as imagens**

**<'table><''/table>** = tag para utilizar tabela.

**<'tr><'/tr>** = para utilizar linha na tabela

**<'td><'/td>** = para utilizar uma célula na tabela

**<'thead><'/thead>** = cabeçalho de uma tabela.

**para informar que a célula é do cabeçalho ao invés de usar td, utilizamos <'th><'/th>**

**<'tbody></'tbody>** = corpo de uma tabela.

**<'tfoot><'/tfoot>** = rodapé da tabela

**utilizar <'td colspan="número de colunas"'> <''/td> para agrupar células**

**<'section> <'/section>** = para um conteúdo que tenha o mesmo significado o mesmo sentido.

**<'iframe src=""'><'/iframe>** = para abrir uma janela e ter informação como video/mapa etc.

**utilizar <'meta name="viewport" content="width=device-width"> para saber a largura do dispositivo** 

### CSS  - Estilos

<'p **style = "font-size: 20px"**> = para  editar o tamanho da fonte.

<'h1 **style="text-align: center"**> Para centralizar o conteúdo.

**CSS INLINE /\ **  - Escrito direto na linha do texto/SOMENTE NELA-

**<'style'> p { text-align: center;} </style'>** = tag  para informar marcações de css referente aos elementos que temos no HTML - **Utilizar no HEAD** - Utilizado na pagina inteira.

**<'link rel="stylesheet" href="style.css"> ** = utilização de um arquivo externo para poder aplicar mais de uma pagina. - **utilizar no HEAD**

**background: ** = Fundo do elemento.

**color:** = cor do elemento.

**em strong {}** = marca especificamente o strong que está em italíco.

**<'tag id="fonte"> ** = para marcar um paragrafo para poder utilizar o mesmo no CSS.

**'#fonte {} ** = utilizar no style.css para usar identificador. 

**<'img src = "nomedaimagem.formato">**

**height: 100px** - Altura do elemento

**width: 100%**- largura do elemento

**border: 10px solid cor;** - Borda 

**padding: 20px;** - Espaçamento interno

**padding-top** - espaçamento para cima 

**margin: 40px** - espaçamento externo.

**margin-left:40 px ** - espaçamento externo para esquerda 

**margin-right:** - Direita 

**margin: 0(para cima para baixo) auto;** = para calcular e centralizar automaticamente. 

**<'tag class="itens">** = marcar itens para posteriormente colocar estilo em cada um deles

**'.itens{}** = utilizar no style.css para utilizar classe.

**font-style: italic;** Para utilizar estilo de fonte.

**<'display: inline-block;>** = ocupa só o tamanho do conteúdo mas deixa mexer na largura e espaçamento.

**<'vertical-align: top;>** = para alinhar pela linha de cima. 

**nav li{}** = Para alterar itens da lista que estão dentro da tag de navegação

**nav a{}** = para alterar os links

**text-transform: uppercase;** = para colocar o texto visivelmente em letras maiúsculas 

**font-weight: bold;** = para deixar a fonte em negrito.

**text-decoration: none;** = Para não ter alguma coisa de diferente no texto.

**position: static;** = posição natural

**position: relative;** =  Relativa a posição inicial.

**position: absolute;**= posicionamento absoluto em qualquer lugar da página.

**top = 0px ** = para utilizar a distancia entre o texto  e o topo

**left: 10px** = espaçamento entre o texto e o ponto inicial.

**box-sizing: border-ox** = mudar a forma como pensa para que o espaçamento lateral esteja dentro do percentual

**border: width style color;** = borda unificada/uma unica linha

**border-color: ;** = Cor da borda

**border-width: ;** = espessura da borda

**border-style: ;** = estilo da borda. solid/dashed/dotted(pontilhado)

**border-radius:** = para ter o elemento arredondar todos os cantos de forma igual.

**:hover{}** = quando o usuário passa o cursor sobre o elemento

**:active {}** = quando um elemento está sendo ativado pelo usuário

**text-decoration: underline;** = para deixar sublinhado 

**:hover h2{}**= Para sobrescrever caso a tag ja tenha recebido um parametro.

**background: url("");** = Para utilizar uma imagem como background

**transition: 1s all; ** = para ter uma transição para mudar algum estilo utilizado em hover.

**transform: scale(1.2)** = para aumentar um elemento propocionalmente

**2em** = medida proporcional para pixels, se tem uma fonte de 15px utilizando 2em significa que é 2x o tamanho base

**float: left** = Para deixar frases em volta de imagem./afeta completamente a estrutura da página.

**clear: posição do float;** = utilizar no texto abaixo do float para limpar o mesmo.

**:first-child{}** = para utilizar em casos que tenha mais de um objeto dentro da classe e necessite pegar a primeira linha

**:last-child{}** = para utilizar em casos que tenha mais de um objeto dentro da classe e necessite pegar a ultima linha

**:nth-child(numero da linha){}** = para utilizar em casos que tenha mais de um objeto dentro da classe e necessite pegar uma linha especifica.

**para ter uma transição de cor com css utilizar linear-gradient(cor, cor);** **utilizar 90deg para escolher o grau da transição de cor**

 **radial-gradient() para ter a mudança de cor em formato de circulo**

**utilizar :before para quando queremos criar um elemento na pagina via css antes do elemento do HTML**

**utilizar :after para quando queremos criar um elemento na pagina via css depois do elemento do HTML**

**para selecionar os filhos diretos da main utilizar main > p{}**

**para escolher o primeiro paragrafo que sucede uma imagem utilizar img + p**

**para selecionar todos os parágrafos localizados depois de uma imagem usamos o seletor ~**

**Se quisermos excluir todos os parágrafos que não compõe uma id utilizamos:  p:not(#id){}**

**para realizar calculo com css utilizar calc()**

**utilizar opacity: 0 a 1;  para alterar a visibilidade de algo.**

**utilizar rgba(0,0,0,0,0.3) para ter mais uma camada de opacidade.**

**Para ter uma sombra em um elemento utilizar box-shadow: Xpx Ypx COR;**

**Para ter uma sombra em texto utilizar text-shadow: 2px 2px cor;**

**utilizar @media screen and (max-width: tamanho da tela até valor x) para ter estilo diferente, reescrito**

#### Cores hexadecimais

''#'' _ _ (red) _ _ (green) _ _ (blue)

0 = ausência de cor

F = máximo de cor

podemos representar as cores de 3 formas.

**Através do nome**

**Através do seu hexadecimal ** 

**Através do seu RGB**

