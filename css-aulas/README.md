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
