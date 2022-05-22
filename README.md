# myfirst-html-project

Aqui irei criar uma página simples de puro html/css/js de uma barbearia. Curso dado pela Alura - HTML5 e CSS3 parte 1: a primeira página da Web


#####ANOTACOES#####
força de cada modificador
tag - 1
class - 10
id - 100
inline - 1000

tag + tag - soma-se ps valores das força, como por exemplo, 2.



semantica melhor do form
fieldset - div
legend - p

Html5 - pensou em tipos que ajudam a uma boa experiencia no mobile. viste: mobileinputtypes.com

no css3 tem propriedades novas como transition(fazer transicao de cores por exemplo com uma duração de tempo) 
e transform ( aumentar o tamanho proporcionalmente das coisas)

o css faz a leitura de cima para baixo, o ultimo item sobrescreve o anterior caso tenham propriedades iguais, caso nao queira, 
coloca o valor que  queira um do lado da outra
Ex de sobrescrita:
transform: scale(1.2);
transform: rotate(70deg);

Ex de soma de ações
transform: rotate(70deg) scale(1.2);

para a transition ir para todos, usar o valor all

pseudo classes que conheci, active e hover 

sempre que queremos falar de estilo usamos uma classe, toda vez que queremos usar um comportamento usamos um identificador.(ficara mais claro no js)

nao vale a pena colocar um nome como comportamento por exemplo nome de uma classe como titulo-centralizado

em = medida proporcional para pixel. se tenho uma font de 15 pixel, se colocamos 2 em isso significa 2x  o tamanho base 

position absolute é a mesma coisa que deixar o elemento em cima de outros podendo se mexer em qualquer lugar

float = descolado da pagina da igual a um position aboslute mas a sombra dela dela sobre a pagina tb ocupa o espaço . todos os elementos abaixos da pag. são afetados tb

como criar uma baeeira do float para nao atrapalhar as demais config da pag. usar a propriedade clear 

fonte preparada para a web tende a funcionar em todos os navegadores mantendo o seu comportamento/visual parecido (google fonts)

margin: 1em 0 (1em para cima e para baixo e 0 para as laterais)
margin: 1px 2px 3px 4px (1px cima, 2px direita, 3px baixo, 4px esquerda)
margin: 2px  (aplica-se ao 4 lados)
margin: 10% auto ( 10% vertical cima/baixo, auto horizontal esq/dir)
margin: 4px 0 2em (4px topo, 0 os lado esquerda direita, 2em inferior)

quando uma lista tem o display setado para inline-block, ele s[o permite que a imagem fique ao lado se tirarmos todo o espaçamento do codigo. Olhar linha51 index.html

line-height é o tamanho da fonte quando setado o valor 1
pseudo classe first-child, altera o valor do primeiro elemento da lista
last-child, ultimo da lista
nth-child(colocar o numero da lista)
nth-child(2n) <- todos elementos pares

background: linear-gradient(grau inclinacao xdeg, quantas cores quisermos separados por vírgulas)
do lado da virgula podemos manipular a porcentagem de onde começa e onde termina a cor

background: linear-gradient(45 deg, orange 50%, red, blue)
tem tambem radial gradient

.before ou .after é só conteúdo de exibição, nao da para ser selecionado

usamos os seletores avançados para trabalharmos menos com o html e mais estilização no css
filhos direto da tag 
main > p 

irmaos diretos
img + P

todos seletores depois de um elemento
ims ~ p

escolher todos os elementos menos 1
.principal p:not(#missao)

opacity = 1 vc ve tudo 0 vc ve nada
é possível colocar opacity em elementos e em cores
rgba(0,0,0,0.3)

SOMBRA ATRÁS
box-shadow: eixoX eixoY cor E B;
propriedade espalhamento da borda
propriedade a mais blur  depois da cor
 
 colocando vírgula da pra colocar mais sombras. para esquerda e baixo usar o sinal de negativo

 SOMBRA INTERNA
 box-shadow: inset 0 0  espacamentoEmPixel red;
 As sombras internas não são deslocáveis. Os valores no eixo X e Y devem ser 0.

 responsavidade
 viewport a quantidade de pixel que tem naquela tela

 para descobrir o tamanho da tela do device e mudar o css usamos o media query usando @media screen 

