#Noções Básicas do markdown

[markdown] (Www.github.com) te permite escrever usando uma formatação de texto fácil de ler e fácil de escrever, que então é convertido para um HTML valido para ser visto no GitHub

##Escrita básica

###Parágrafos
Parágrafos no markdown são uma ou mais linhas de texto consecutivo seguido por um ou mais linhas brancas.

```
No dia 02 de julho, uma nave māe alienígena entraram na orbita da terra e implantaram várias dezenas de “destruidor”, naves espaciais em forma de pires, cada uma com 24 km de largura.
```
```
No dia 03 de julho, os Cavaleiros Negros, um esquadrão da corporação da marinha F/A-18 Hornets, participaram de um assalto a um destruidor perto da cidade de Los Angeles.
```

###Cabeçalhos

Você pode criar um cabeçalho adicionando um ou mais # símbolos antes do seu texto do cabeçalho. O numero de # que você usar vai determinar o tamanho do cabeçalho. 
```
# O maior cabeçalho (an <h1> tag)
## O segundo maior cabeçalho (an <h2> tag)
...
###### O sexto maior cabeçalho (an <h6> tag)
```

##Blockquotes
Você pode indicar blockquotes com uma >.

Nas palabras de Abraham Lincoln:
>Perdoe meu francês 

###Estilo de texto
Você pode fazer texto em **negrito** ou *itálico*.

 * Este texto vai ser itálico *
 ** Este texto vai ser negrito **

Ambos **negrito** e *itálico* podem ser usados tanto com ```*``` quanto com ```_``` ao redor do texto para estilo. Isso lhe permite combinar negrito e itálico se necessário.

```** Everyone  _ must _  attend the meeting at 5 o’clock today. **```

##Listas

###Listas não ordenadas

Você pode fazer uma lista nao ordenada precedendo os itens da lista  com  um * ou com um _, 
```
* Item
* Item
* Item

- Item
- Item
- Item
```

###Listas ordenadas

Você pode fazer uma lista ordenada precedendo os itens da lista com um número. 
```
1. Item 1
2. Item 2
3. Item 3
```

###Listas aninhadas

Você pode criar listas aninhadas identificando itens da lista em dois espaços.
```
1. Item 1
  1. Um corolário do item acima.
  2. No entanto, outro ponto a considerar.
2. Item 2
  * Um corolário que nao precisa ser ordenado.
    * Este é recuado quatro espaços, porque é dois espaços mais longe do que o item acima.
    * Você pode querer considerar fazer uma nova lista.
3. Item 3
```

##Formatacao de código

###Formatos em linha

Use acentos graves individuais (`) para formatar o texto em um formato monospace especial. Tudo dentro dos acentos graves aparece como está, sem nenhuma outra formatação especial.

```
Aqui vai uma ideia:  por que nao pegamos  `ProjetoSuperior` e o tornamos em `**Projeto**Razoável`.
```

##Linhas múltiplas

Você pode usar acentos graves triplos (```) para formatar texto com seu próprio bloco distinto.
```
Confira este programa limpo que eu escrevi:
```
x = 0
x = 2 + 2
o que é x
```
```

##Links

Você pode criar um link em linha envolvendo link texto entre colchetes (```[]```) e em seguida, envolver o link entre parênteses (```()```).

Por exemplo, para criar um hiperlink para www.github.com, com um texto de link que diz, Visita GitHub!, você escreveria isso em Markdown: [Visite GitHub!] (Www.github.com).

