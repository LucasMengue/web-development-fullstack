# HTML

Hypertext (Hipertexto)
Markup (Marcação)
Language (Linguagem)

## O que é o HTML?

- É linguagem de programação? Não
- `tags` (marcação)
- Links para outros textos
- Imagens, sons e vídeos
- Arquivo com a extensão `.html`

## Anatomia das tags

- Abertura de tag
- Conteúdo
- Fechamento de tag
- Elementos
- Atributos

```
<h1 id="title">Título<h1>
```

- Elementos vazios
- Não possuem conteúdo
- Poderão conter atributos

```
<img src="" alt="" />
<br />
```

## Comentários

- Ignorar o texto no código

```
<!--
 Comentário aqui
-->
```

## Fluxo HTML

- Block

```
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
```

- Inline

```
<p>Lorem ipsum dolor sit amet, <a href="#">consectetur</a> adipiscing elit. Nunc non felis vitae massa sagittis sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc non felis vitae massa <a href="#">sagittis</a> sagittis. Vivamus id mauris laoreet, sollicitudin lectus id, sagittis metus.</p>
```

## Aninhamento de tags

```
<p>Lorem ipsum dolor sit amet, <em>consectetur</em> adipiscing elit. Nunc non felis vitae massa <a href="#">sagittis</a> sagittis. Vivamus id mauris laoreet, <strong>sollicitudin</strong> lectus id, sagittis metus.</p>
```

## Atributos HTML

- Informações extras
- Configurações

```
<img src="" alt="" />
<a href="#">Link</a>
```

### ID

- Atributo de identificação única

```
<div id="nome-1"></div>
<div id="nome-2"></div>
```

### Class

- Atributo de classificação, podendo conter em mais de uma tag

```
<div class="produto tenis">Tênis</div>
<div class="produto camiseta">Camiseta</div>
```

### Data-

- Atributo personalizado podendo ser utilizado no JS

```
<div data-qualquer-coisa="1234"></div>
```

### Style

- Atributo de estilo CSS

```
<div style="color: blue;">Título</div>
```

## Semântica

- Dar significado
- Elementos

## Títulos e parágrafos

```
<h1>Título</h1>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas.
</p>

<h2>Trabalho</h2>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas. Donec ac accumsan lectus, vitae sollicitudin nisl. Phasellus feugiat tellus in dui rhoncus, quis aliquet neque dapibus. Nulla facilisi. Ut hendrerit dui eu tempus euismod. Aliquam erat volutpat. Nullam eu neque dapibus, iaculis metus sed, porta metus. Aenean non feugiat purus, nec bibendum elit.
</p>

<h3>Carga Horária</h3>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas. Donec ac accumsan lectus, vitae sollicitudin nisl. Phasellus feugiat tellus in dui rhoncus, quis aliquet neque dapibus. Nulla facilisi. Ut hendrerit dui eu tempus euismod. Aliquam erat volutpat. Nullam eu neque dapibus, iaculis metus sed, porta metus. Aenean non feugiat purus, nec bibendum elit.
</p>

<h2>Estilo de Vida</h2>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas. Donec ac accumsan lectus, vitae sollicitudin nisl. Phasellus feugiat tellus in dui rhoncus, quis aliquet neque dapibus. Nulla facilisi. Ut hendrerit dui eu tempus euismod. Aliquam erat volutpat. Nullam eu neque dapibus, iaculis metus sed, porta metus. Aenean non feugiat purus, nec bibendum elit.
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas. Donec ac accumsan lectus, vitae sollicitudin nisl. Phasellus feugiat tellus in dui rhoncus, quis aliquet neque dapibus. Nulla facilisi. Ut hendrerit dui eu tempus euismod. Aliquam erat volutpat. Nullam eu neque dapibus, iaculis metus sed, porta metus. Aenean non feugiat purus, nec bibendum elit.
</p>
```

## Formatações básicas

- Strong (Importância)
- em (enfase)
- mark (relevância)
- s (riscado)

```
<p>
Lorem ipsum dolor sit amet, <strong>consectetur</strong> adipiscing elit. Morbi nec accumsan leo. Etiam ullamcorper sapien id leo tincidunt, non commodo diam egestas. Donec ac accumsan <em>lectus</em>, vitae sollicitudin nisl. Phasellus feugiat tellus in dui rhoncus, quis aliquet neque dapibus. Nulla facilisi. Ut <mark>hendrerit</mark> dui eu tempus euismod. Aliquam erat volutpat. Nullam eu neque dapibus, iaculis metus sed, porta metus. Aenean non <s>feugiat</s> purus, nec bibendum elit.
</p>
```

## Listas

- Ordenadas
- Não ordernadas

```
<h1>Bolo de Cenoura</h1>
<h2>Ingredientes</h2>
<ul>
    <li>Farinha 1kg</li>
    <li>Cacau em pó 100g</li>
    <li>1 cenoura ralada</li>
</ul>

<h2>Modo de preparo</h2>
<ol>
    <li>Pegar a farinha e colocar num recipiente</li>
    <li>Misturar o cacau</li>
    <li>Misturar a cenoura</li>
</ol>
```

## Representação de códigos de computador

- <code>
- <pre>
- Caracteres especiais
  &lt;
  &gt;

```
<pre>
    <code>
        &lt;!-- comentário -- &gt;
    </code>
</pre>
```

## Hiperlink

- <a>

Atributos

- href

```
<a href="https://rocketseat.com.br">Conheça a Rocketseat</a>
```

- URL, fragmento

```
<a href="#trabalhos">Trabalhos</a>

<div id="trabalhos"></div>
```

- target

```
<a href="https://rocketseat.com.br" target="_blank">Ver site</a>
```

## Imagens

- <img>
- src
- alt
- width
- height

```
<img src="https://source.unsplash.com/random" height="200" width="300" />
```

## Anatômia de um documento HTML

```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <title>Título da página</title>
    </head>
    <body></body>
</html>
```

## HTML semântico

- <header>
  -- Cabeçalho

- <nav>
  -- Lista de navegação

- <main>
  -- Conteúdo principal

- <section>
  -- Sessão de uma página

- <article>
  -- Artigo de uma página

- <aside>
  -- Conteúdo secundário

- <footer>
  -- Rodapé da página

## Tags genéricas

Estruturação de páginas. Não contém significados.

- Div
- Span
