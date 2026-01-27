# CSS

- Cascading Stylesheet

---

## O que é CSS?

- Folha de estilo em cascata
- Propriedade e valor
- Estilos para o HTML
- Arquivos `.css`

## Comentários

```
/*
    body {
        backgroundcolor: blueviolet;
    }
*/
```

## Anatomia de um documento CSS

- Declaração
- Seletor
- {} - context
- Propriedades
- Propriedade valor

```
h1 {
    color: blue;
    font-size: 60px;
    letter-spacing: 2;
    text-transform: uppercase;
}
```

## Especificidade

- Cada seletor tem um peso
- Soma dos pesos faz a declaração ser aplicada

-- #id - 100
-- .class - 10
-- element - 1

## Valores e unidades de medidas

Cada propriedade possui valores
`property: value`
`<data-type>`

```
h1 {
    color: blue; /* color */
    font-size: 32px; /* length */
    letter-spacing: 2; /* number */
    text-transform: uppercase; /* keyword */
}
```

## Seletores

- id
- class
- type | element | tag
- atributo
- universal

```
<p id="title" class="title">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas ac erat lobortis, facilisis sem in, iaculis dui. Sed sed viverra eros. Pellentesque fermentum ligula a consectetur euismod. Mauris finibus dignissim auctor. Donec enim tortor, venenatis quis massa quis, commodo lacinia augue. Mauris consectetur leo nec metus placerat finibus vitae vel elit. Cras ut nulla tincidunt, iaculis urna eget, pulvinar massa.
</p>

p {
    color: blue;
}

#title {
    color: yellow;
}

.title {
    color: green;
}
```

## Box Model

- Tudo são caixas
  -- Todos os elementos HTML serão considerados uma caixa.

- Caixas possuem determinadas propriedades
  -- Conteúdo, largura, altura, borda, preenchimento (espaço interno), espaçamento (espaço externo)

## Display: block

1. Ocupa toda a linha, como um `bloco`
2. `width` e `height` são aplicados
3. `padding`, `margin`, `border` funcionam por completo

> elementos
> `<div>, <main>, <header>, <section>, <p>, <h...>`

## Display: inline

1. Ocupa apenas o espaço do conteúdo do elemento
2. Elementos poderão ficar `em linha`
3. `width` e `height` não se aplicam
4. Aplicamos apenas os valores horizontais de `padding`, `margin`, `border`

> elementos
> `<a>, <span>, <strong>, <em>`

## Border

```
border: 1px solid red;
border-width: 4px 2px 6px 15px;
border-style: dotted solid double dashed;
border-color: red green blue black;
border-bottom-style: solid;
border-bottom: solid red 5px;
```

## Width, Height

```
min-width: 200px;
max-width: 300px;
width: 500px;
min-height: 200px;
max-height: 300px;
height: 1500px;
```

## Margin

```
.margin {
    margin: 30px;
    margin-left: 60px;
    margin: 30px 10px 80px 4rem;
    margin: auto;
}
```
