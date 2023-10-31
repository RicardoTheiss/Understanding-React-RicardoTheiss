# CSS (Cascading Style Sheets)

CSS (Cascading Style Sheets) é uma linguagem de estilo utilizada para controlar a apresentação e o layout de páginas da web. Ela desempenha um papel fundamental na criação de páginas web atraentes e funcionais. Neste guia, você aprenderá os conceitos básicos do CSS e alguns comandos essenciais.

## Conceitos Básicos

### Seletores

Os seletores CSS são usados para selecionar elementos HTML aos quais você deseja aplicar estilos. Existem vários tipos de seletores, incluindo:

- **Seletor de elemento:** Aplica um estilo a um elemento HTML específico. Exemplo: `p { cor: azul; }`
- **Seletor de classe:** Aplica um estilo a elementos com uma classe específica. Exemplo: `.destaque { font-weight: negrito; }`
- **Seletor de ID:** Aplica um estilo a um elemento com um ID específico. Exemplo: `#cabecalho { background-color: cinza; }`

### Propriedades

As propriedades CSS determinam como os elementos são estilizados. Algumas propriedades comuns incluem:

- **`cor`**: Define a cor do texto.
- **`background-color`**: Define a cor de fundo.
- **`font-size`**: Define o tamanho da fonte.
- **`margin` e `padding`**: Controlam espaçamento ao redor dos elementos.

### Valores

Cada propriedade aceita valores específicos. Alguns exemplos incluem cores (por exemplo, `vermelho`, `#00ff00`, `rgba(255, 0, 0, 0.5)`), tamanhos de fonte (por exemplo, `16px`, `1.5em`), e unidades de medida (por exemplo, `px`, `%`).

### Cascata

O termo "cascading" refere-se à hierarquia de estilos em CSS. Se vários estilos são aplicados a um elemento, o estilo mais específico e próximo do elemento terá precedência.

## Comandos CSS

Aqui estão alguns comandos CSS comuns que você pode usar:

### Comentários

Você pode adicionar comentários ao seu código CSS para explicar seu trabalho. Comentários são precedidos por `/*` e terminados por `*/`:

```css
/* Este é um comentário CSS */
```

### Definindo Estilos

Para definir um estilo, você seleciona um elemento e especifica as propriedades e valores desejados. Por exemplo, para definir a cor do texto de todos os parágrafos para azul, você pode fazer o seguinte:

```css
p {
  cor: azul;
}
```

### Classes e IDs
Para aplicar estilos a classes ou IDs específicos, use seletores de classe e ID. Aqui está um exemplo:

```css
/* Seleciona elementos com a classe "destaque" */
.destaque {
  font-weight: negrito;
}

/* Seleciona o elemento com o ID "cabecalho" */
#cabecalho {
  background-color: cinza;
}
```

### Incorporação Externa
Você também pode incorporar folhas de estilo CSS externas em seu documento HTML usando a tag <link>. Isso é útil para manter seu código organizado:

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <!-- Seu conteúdo HTML aqui -->
</body>
</html>
```