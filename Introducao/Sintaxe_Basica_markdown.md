# Markdown

### O que é markdown?
>Markdown é uma sintaxe usada para padronizar e facilitar formatação de texto web, utilizada em aplicativos como __Slack__ e __GitHub__.Textos estilizados com **Markdown** são, na maioria dos casos, apenas textos com caracteres não-alfabéticos, como `#, \*, \ e ![]()`, usados para configuração de títulos, listas, itálicos, negritos e inserção de imagem.


### Lista Básica de Comandos

### Titulação
É necessário ter um espaço entre `#` e o texto.
~~~ 
    # Título 1 <h1>
    ## Título 2 <h2>
    ### Título 3 <h3>
    #### Título 4 <h4>
    ##### Título 5 <h5>
    ###### Título 6 <h6>
~~~
##### Saída: 

# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

### Ênfase
>Para adicionar ênfase ao conteúdo que será escrito, usa-se o asterisco `*`ou underline `_`. Temos dois tipos de ênfase o **Negrito** e o *Itálico*. Na ênfese não podemos ter espaços entre o `*` ou `_` com o texto.

#### Negrito:
>Basta adicionar dois asterisco `**` ou dois underline `__` no ínicio e no final da ênfase.

Exemplo: Uns do framework para Python é o `**Django**`
##### Saída:
Exemplo: Uns do framework para Python é o **Django**

#### Itálico 
>Basta adicionar apenas uma `*` ou `_` no ínico e no final para palavra que será ênfatizada.
Exemplo: Uns do framework para Python é o `_Django_`.
##### Saída:
Exemplo: Uns do framework para Python é o _Django_.

### Links
>Existem duas formas de inserir link em Markdown, através de um **link direto** ou usando um __texto-âncora__.
#### Texto-âncora
>Utilize os caracteres `[]()`, adicionando entre os cochetes o texto que você quer que apareça, e entre os parênteses, o endereço de destino, no formato `[exemplo](https://exemplo.net/)`.
##### Saída
Exemplo de como é apresentado: [exemplo](https://exemplo.net/) \*A url fica oculta.

#### Link direto
>Envolva o endereço da web em chaves `<>`. O endereço ficará visível e será clicável.
Exemplo: `<https://exemplo.net/>`
##### Saída
Exemplo: <https://exemplo.net/>

### Lista de Itens
> Listas não ordenadas, utilize um asterisco \* na frente do item da Lista.
~~~
* Item 1
* Item 2
* Item 3
~~~
#### Saída
* Item 1
* Item 2
* Item 3
> Lista ordenadas, utilize o número do item segguido de ponto \(.)
~~~
1. Item 1
2. Item 2
3. Item 3
~~~
##### Saída
1. Item 1
2. Item 2
3. Item 3 

### Imagens
> Inserir uma imagem no conteúdo é semelhante ao código de inserir link-âncora, adicionando antes um ponto de exclamação \! no início do código.  
> Exemplo: `![alt ou título da imagem](url da imagem)`

### Citação 
> Transformar um texto em uma citação ou cometário, utilize o sinal de  maior `>`  no início da linha que será formatada. 

### Código (Code Highlight)
> Dois modos de adicionar trechos de códigos ou comentários
#### Código em Linha(inline)
> adicione um acento grave \` no início e final do código ou comentário
#### Múltiplas linhas de códigos
> envolva as linhas de códigos com três  acentos graves \``` ou três tils ~~~

### Tabela
> Escolha os títulos das colunas e use | para delimitar as colunas. Depois, utilize hifen - na segunda linha para indicar que acima está os títulos das colunas, usando novamente o | para delimitar colunas.

Exemplo:
~~~
Exemplo | Valor Exemplo
-------| ---------
Ex 1 | Valor 1
Ex 2 | Valor 2
~~~
##### Saída

Exemplo | Valor Exemplo
------- | -------------
Exemplo 1 | Valor 1
Exemplo 2 | Valor 2

> Para especificar o tipo de alinhamento que deseja ter, utilize : ao lado do campo horizontal de hifens --, na segunda linha.\
> Alinhamento a esquerda: usar : no lado esquerdo (alinhamento padrão)\
> Alinhamento a direita: usar : no lado direito \
> Centralizado: usar : dos dois lados

Exemplo:
~~~
Alinhamento a esquerda | Centralizado | Alinhamanto a direita
:--------| :---------: | ---------:
Valor | Valor | Valor
~~~
##### Saída
Alinhamento a esquerda | Centralizado | Alinhamanto a direita
:--------| :---------: | ---------:
Valor | Valor | Valor


