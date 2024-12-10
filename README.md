# Markdown

# Titulo
## Titulo
### Titulo
#### Titulo
##### Titulo
###### Titulo

Parágrafo Comum

Se você der espaços
entre linhas, então você
terá um novo parágrafo.

Quebra de linha
com dois espaços
ao final da linha.<br> é o mesmo \<br> que você encontra no html

**negrito**
__negrito__
==sublinhado==
~~riscado~~
*italico*
_italico_

Em um **parágrafo** podemos usar todos os anteriores

## listas

1. ordenas  
    1. subitem
2. quando você usa um número, o
3. próximo item será automaticamente incrementados
   1. subtem
   2. outro subtem
   3. outro subtem
       1. subtem


- Não ordenadas
* Você pode usar um asterisco ou hifen
+ Sinal de mais também é aceito

- Não ordenadas
- Você pode usar um asterisco ou hifen
- Sinal de mais também é aceito
    - subitem
    - subitem
    - subitem
- O correto é não misturar os sinais

## Links

[Clique aqui](https://senac.br/)
[GIT](https://github.com)


[ancora](#markdown)


Aqui é um parágrafo com link [Clique aqui](https://senac.br/ "Titulo para esse link") ou aqui é um parágrafo com um link https://senac.br/


## imagens

![Texto alternativo](https://embarcados.com.br/wp-content/uploads/2015/02/imagem-de-destaque-39.png)

![Texto alternativo](https:git-scm.com/images/logos/2color-lightbg@2x.png)

<br>
<br>


## imagem com link

[![]()]()

[![Texto alternativo](https://i.pinimg.com/originals/08/0f/0b/080f0b8de4a7fde193a2c13843c5f880.jpg)](https://google.com) 


<br>



## citação

> Iniciar minha citação

> <br>
> Iniciar minha citação
> <br><br>

> Citação
>> sub citação
> ### Titulo dentro de uma citação


<br>


## toggle

<details>
    <summary>
    clique aqui para ver o conteúdo
    <summary>
</details>


<br>


## separador

pode ser 3 traços

---

ou pode ser 3 asteriscos

***

## checklist

- [ ] item 1
- [x] item 2
- [ ] item 3

## Tabela

| nome | idade |
|------|:-----:|
|Wesley|   19  |
|Jhenny|   26  |

| nome | idade |
|:----:|:-----:|
|Wesley|   19  |
|Jhenny|   26  |

| nome | idade |
|------|-------|
|Wesley|   19  |
|Jhenny|   26  |


## código

Em linha usamos 1 acento grave para abrir o código e outro para fechar

` <h1> Eu sou um título </h1> `

<h1> Eu sou um título </h1> 

` # Eu sou um titulo `

<h1> Eu sou um título </h1> 

` console.log('Olá, mundo!') `



<br> <br>



### bloco de código

Usaremos 3 acentos graves para abrir, seguido da linguagem que eu quero, e para fechar mais 3 acentos graves


``` html


<details>
    <summary>
    clique aqui para ver o conteúdo
    <summary>
    conteúdo
</details>

```


``` css

.container {
   display: flex;
}
```

``` javascript 
console.log(Óla, mundo!´);

function dados(dados) {
    console.log(dados);}

```

## emojis
:rocket:
:D
;( 

```mermai
graph TD;
a-->d
```

<!-- Comentário -- >