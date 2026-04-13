tutorial html e css 

# ia26-webdesign

Esta disciplina ensina como criar páginas na internet, mesmo para quem está começando do zero. Você vai aprender como montar o conteúdo de um site e como deixá-lo bonito e organizado.

Para isso, usamos principalmente duas coisas:
- **HTML**: para montar a estrutura da página (como títulos, textos, imagens, links)
- **CSS**: para cuidar da aparência (cores, tamanhos, espaçamento, layout)

Também veremos um pouco de **JavaScript**, que serve para adicionar interações (como botões que fazem algo acontecer).

O objetivo do curso é te dar uma base sólida para começar no desenvolvimento web. Mesmo sendo introdutório, ele é muito importante, pois ensina os fundamentos de como sites funcionam.

---

## Antes de começar

Para acompanhar as aulas, é importante ter:
- Um **editor de código** (vamos usar o Visual Studio Code)
- Um **navegador atualizado** (vamos usar o Google Chrome)

---

## O que é HTML?

HTML não é uma linguagem de programação. Ele é uma forma de **organizar o conteúdo** de uma página.

Pense assim:  
o HTML é como o “esqueleto” de um site.

Ele diz coisas como:
- “isso é um título”
- “isso é um parágrafo”
- “isso é um link”

### Como funciona na prática?

O HTML usa **tags** (etiquetas) para marcar o conteúdo.

Exemplo:
- `<h1>` → título
- `<p>` → parágrafo
- `<a>` → link

Essas tags normalmente têm:
- uma **abertura**: `<p>`
- um **fechamento**: `</p>`

Tudo que estiver entre elas é o conteúdo.

Exemplo:

    <p>Este é um parágrafo</p>

---

## Uma forma fácil de entender

Imagine que você está usando o Word ou Google Docs.

Quando você:
- seleciona um texto
- e clica em **negrito** ou *itálico*

No HTML, você faz algo parecido, mas escrevendo código.

Exemplo:

Negrito:

    <strong>texto</strong>

Itálico:

    <em>texto</em>

Ou seja: você “marca” o texto com uma tag.

---

## Estrutura básica de uma página HTML

Toda página HTML segue um modelo padrão:

    <!DOCTYPE html>
    <html>
    <head>
       <title>Título da página</title>
    </head>
    <body>
       Conteúdo da página
    </body>
    </html>

### O que significa cada parte?

- `<html>` → início do documento
- `<head>` → informações sobre a página (não aparecem na tela)
- `<body>` → tudo que aparece para o usuário

---

## O que são atributos?

Atributos dão **informações extras** para as tags.

Exemplo de um link:

    <a href="https://www.google.com">Ir para o Google</a>

- `<a>` é a tag de link  
- `href` diz para onde o link vai  

---

## O que é CSS?

Se o HTML é o esqueleto, o CSS é a **aparência**.

Ele serve para deixar o site bonito:
- cores
- tamanhos
- fontes
- espaçamento
- posicionamento

### Exemplo simples

HTML:

    <h1>Olá, mundo!</h1>

CSS:

    h1 {
      color: blue;
      text-align: center;
    }

Resultado:
- texto azul
- centralizado

---

## Como o CSS funciona?

O CSS funciona com **regras**:

    seletor {
      propriedade: valor;
    }

Exemplo:

    p {
      color: red;
    }

Isso significa:
 “todos os parágrafos serão vermelhos”

---

## Tipos básicos de seleção no CSS

Você pode escolher o que estilizar de várias formas:

Por tipo:

    p { }

Por classe:

    .titulo { }

Por ID:

    #principal { }

---

## Resumindo

- **HTML** = estrutura (o que é cada coisa)
- **CSS** = aparência (como isso vai parecer)

Os dois trabalham juntos para criar páginas web.

---

## Dica importante

A melhor forma de aprender é **praticando**:
- tente criar páginas simples
- experimente mudar cores, textos e estilos
- erre bastante (faz parte do processo)

---

Na próxima aula, você vai colocar tudo isso em prática criando sua própria página. 