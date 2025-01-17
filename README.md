# <img src="/src/Markdown_logo.png" width="40" height=23>     Markdown

Oi, bem vindo!  
Esse repositório é um tutorial com as funcionalidades básicas da linguagem Markdown.  
Criado como complemento para a aula de monitoria da disciplina de Técnicas de Programação do Instituto Federal da Paraíba, campus João Pessoa, utilizando o [esse](https://github.com/LucVeloso/Tutorial-de-Markdown/blob/master/src/Apresenta%C3%A7%C3%A3o.pptx) material.

*******

Tabelas de conteúdo   

1. [O que é Markdown?](#whatis)
1. [Sintaxe](#syntax)
    1. [Cabeçalho](#headers)
    1. [Citação](#quotes)
    1. [Divisões de texto](#divisions)
    1. [Quebra de linha](#breaks)
1. [Estruturas de texto](#structures)
    1. [Emoji](#emoji)
    1. [Links](#links)
        1. [Imagem](#images)
    1. [Listas](#lists)
        1. [Ordenada](#ordered)
        1. [Desordenada](#unordered)
        1. [Tarefas](#tasks)
    1. [Tabelas](#tables)
    1. [Código](#code)
1. [Referências](#references)

*******

<div id='whatis'/>  

# O que é Markdown?

Markdown é uma linguagem de marcação

<div id='sintax'/>  

# Sintaxe 

| Estilo                 | Sintaxe            | Exemplo                              | Saída                              |
|:-----------------------|:------------------:|:------------------------------------:|:----------------------------------:|
| Negrito                | `** **` ou `__ __` | `**Este texto está em negrito**`     | **Este texto está em negrito**     |
| Itálico                | `* *` ou `_ _`     | `*Este texto está em itálico*`       | *Este texto está em itálico*       |
| Marcado                | ``` ` ` ```        | ``` `Este texto está marcado` ```    | `Este texto está marcado`          |
| Riscado                | `~~ ~~`            | `~~Este texto foi um erro~~`         | ~~Este texto foi um erro~~         |
| Todo negrito e itálico | `*** ***`          | `***Todo esse texto é importante***` | ***Todo esse texto é importante*** |

<div id='headers'/>

## Cabeçalhos

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

<div id='quotes'/> 

## Citação

<div id='divisions'/>  

## Divisões de texto 

```
***
---
- - -
```

***
---
- - -

<div id='breaks'/>  

## Quebra de linha  

```
Frase 1
Frase 2

Frase 1  
Frase 2

Frase 1

Frase 2
```

Frase 1
Frase 2

Frase 1  
Frase 2

Frase 1

Frase 2

<div id='structures'/>  

# Estruturas de texto

<div id='emoji'/> 

## Emoji
:octocat:  
:squirre:

<div id='links'/> 

## Links



<div id='images'/> 

### Imagens

<img src="/src/Markdown_logo.png" width="80" height=46>

É possível adiconar imagens usando a seguinte estrutura  
gfhgg

``` Formato: ![Texto](url)```

ou como uma tag HTML (sendo ainda possível alterar atributos da imagem como largura e altura)  

``` <img src="/src/Markdown_logo.png" width="40" height=23> ```

<div id='lists'/> 

## Listas

<div id='ordered'/> 

### Ordenada



```
1. Item 1
1. Item 2
1. Item 3
    1. Item 3.1
    1. Item 3.2
```

1. Item 1
1. Item 2
1. Item 3
    1. Item 3.1
    1. Item 3.2

<div id='unordered'/> 

### Desordenada



```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b
    *Item 

<div id='tasks'/> 

### Tarefas

```
- [x] Finalizar minhas mudanças
- [ ] Fazer o push dos meus commits
- [ ] Criar um pull request
```

- [x] Finalizar minhas mudanças
- [ ] Fazer o push dos meus commits
- [ ] Criar um pull request

<div id='tables'/> 

## Tabela

```
| Tabelas         | São                     | Legais  |
| --------------- |:----------------------: | -------:|
| a coluna 3 está | alinhada para a direita |   $1600 |
| a coluna 2 está | centralizada            |     $12 |
| a coluna 1 está | alinhada                |      $1 |
```

| Tabelas         | São                     | Legais  |
| --------------- |:----------------------: | -------:|
| a coluna 3 está | alinhada para a direita |   $1600 |
| a coluna 2 está | centralizada            |     $12 |
| a coluna 1 está | alinhada                |      $1 |

<div id='code'/> 

## Código

C++

````
```c++
#include <iostream>

using namespace std;

int main()
{
    cout << "Hello world!" << endl;
    
    return 0;
}
```
````



```c++
#include <iostream>

using namespace std;

int main()
{
    cout << "Hello world!" << endl;
    
    return 0;
}
```

Python

````
```python
print("Hello world!")
```
````



``` python
print("Hello world!")
```

<div id='references'/> 

# Links uteis e referênias

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code  
https://blog.da2k.com.br/2015/02/08/aprenda-markdown/  
https://stackedit.io/editor  
https://guides.github.com/features/mastering-markdown/  
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md  
https://help.github.com/en/github/writing-on-github  
https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_pt-BR.md  
https://pt.wikipedia.org/wiki/Markdown  

