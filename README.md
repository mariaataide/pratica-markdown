# Aprendendo a usar novas marcas da linguagem Markdown

- **Negrito** ou __Negrito__
- *Itálico* ou _Itálico_
- ~~Tachado~~ 
- # Título 1
- ## Título 2
- ### Título 3

Abaixo, temos uma linha horizontal criada com três traços

---

Abaixo, temos uma linha horizontal criada com três asteriscos

***

Podemos misturar duas marcações: _*Negrito e Itálico*_

## Lista Numerada

Um número e um ponto criam lista numerada independentemente de estarem em sequência:

1. Item 1
0. Item 2
8. Item 3
1. Item 4

    5. Subitem

Para inserir um subitem, é necessário adicionar um espaço depois do item e um recuo de um tabulador (ou quatro espaços).

## Lista Demarcada (lista com marcadores)

### Usando *

* Item 1
* Item 2
* Item 3
* Item 4

  * Subitem 4.1

### Usando -

* Item 1
* Item 2
* Item 3
* Item 4

  * Subitem 4.1
  

## Lista de Tarefas

- [ ] Item 1
- [ ] Item 2
- [x] Item 3 concluído
- [ ] Item 4

## Inserindo Imagens

![alt text](MASA-removebg-preview.png) 

## Inserindo Links

[Tutorial](https://mariaataide.github.io/tutorial-resenha-pms)

## Tabelas

1. Inserir o título das tabelas 

Código | Município | Valor
--- | --- | ---
01 | Mucurici | 10
02 | Vitória | 11

## Inserido Comandos

Inserirmos comandos usando Markdown como no exemplo: `glimpse(dados)`.

Aqui temos um exemplo de como inserir um trecho de programa:

```
num = int(input('Digite um valor:'))
if num % 2 == 0
    print(f'O valor {num} é PAR)
else: 
    print(f'O valor {num} é íMPAR)
```

## Inserir Emojis

:nome-do-emoji

Ex: 

:BR -> insere a bandeira do Brazil
:hand -> insere uma mão

[Link para nomes de Emoji](https://github.com/ikatyang/emoji-cheat-sheet)

Para clonar o repositório usando `Git Bash`:

```
cd C:\User\sua-pasta
git clone https://github.com/ikatyang/emoji-cheat-sheet
```

### Inserindo os Emojis no título da *Issue*

Use o site [https://emojipedia.org](https://emojipedia.org)

No site, lique no emoji e procure a botão copiar. Copie e cole no título da sua *Issue*.

## Citações e marcações (no GitHub)

`@nome-do-usuario`

### Repostas de *Issues*

> Sua resposta.

> Isso é uma quote reply.

## Manual do Markdown da Curso em Vídeo [disponível aqui](https://github.com/gustavoguanabara/git-github).

