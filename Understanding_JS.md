# JavaScript: Conceitos e Principais Comandos

JavaScript é uma linguagem de programação amplamente utilizada para adicionar interatividade e funcionalidade a páginas da web. É uma linguagem de script versátil e de alto nível que permite aos desenvolvedores criar aplicativos web dinâmicos e ricos em recursos. Neste guia, exploraremos os conceitos fundamentais do JavaScript e alguns dos principais comandos que você precisa conhecer.

## Conteúdo

1. [Introdução ao JavaScript](#introdução-ao-javascript)
2. [Variáveis](#variáveis)
3. [Tipos de Dados](#tipos-de-dados)
4. [Operadores](#operadores)
5. [Estruturas de Controle](#estruturas-de-controle)
6. [Funções](#funções)
7. [Objetos](#objetos)
8. [Manipulação do DOM](#manipulação-do-dom)
9. [Eventos](#eventos)
10. [Conclusão](#conclusão)

## Introdução ao JavaScript

JavaScript é uma linguagem de programação de alto nível que é interpretada pelo navegador do usuário para fornecer funcionalidade dinâmica a uma página da web. Ela pode ser usada para validar formulários, criar animações, manipular o DOM (Modelo de Documento do HTML) e muito mais.

## Variáveis

As variáveis são usadas para armazenar dados. Em JavaScript, você pode declarar variáveis usando as palavras-chave `var`, `let` ou `const`. Exemplo:

```javascript
var idade = 30;
let nome = "João";
const pi = 3.14;
```

## Tipos de Dados
JavaScript possui vários tipos de dados, incluindo números, strings, booleanos, objetos e arrays. Exemplo:

```javascript
var numero = 42;
var texto = "Olá, Mundo!";
var ativo = true;
var frutas = ["maçã", "banana", "laranja"];
```

## Pegar dados HTML
Para estipular os valores de suas variáveis JS, você pode receber valores HTML no JS. Exemplo:

```html
<input type="text" id="idNome">
<output id="idsaida"></output>

<script>
    var nome = document.getElementById("idNome").value
    var saida = "Olá, " + nome + "!"

    document.getElementById("idSaida").innerText = saida
</script>
```

## Operadores
Operadores são usados para realizar operações em variáveis e valores. Os operadores incluem operadores aritméticos, de comparação, lógicos e de atribuição. Exemplo:

```javascript
var a = 10;
var b = 5;
var soma = a + b; // Operador de adição
var maior = a > b; // Operador de comparação
var and = (a > 0) && (b < 0); // Operador lógico
```

## Estruturas de Controle
Estruturas de controle permitem que você tome decisões e controle o fluxo do programa. As estruturas de controle incluem condicionais (if, else, switch) e loops (for, while). Exemplo:

```javascript
var idade = 19

if(idade >= 18){
    saida = "Maior de idade"
} else {
    saida = "Menor de idade"
}

for(i = 0; i>=18; i++){
    num += i + " "
}
console.log(saida)
console.log(num)
```

## Funções
Funções são blocos de código reutilizáveis que podem ser chamados com argumentos. Elas são usadas para organizar o código e realizar tarefas específicas. Exemplo:

```javascript
function saudacao(nome) {
    return "Olá, " + nome + "!";
}

var mensagem = saudacao("Ana");
console.log(mensagem); // "Olá, Ana!"
```

## Arrays em JavaScript

Em JavaScript, um array é uma estrutura de dados que permite armazenar e acessar uma coleção de elementos. Os arrays são objetos indexados, o que significa que os elementos são acessados por meio de um índice numérico. Você pode criar um array vazio ou inicializá-lo com elementos. Exemplos:

```javascript
const meuArrayVazio = [];
const frutas = ["maçã", "banana", "laranja"];
```

## Objetos
Objetos são coleções de propriedades e métodos que representam entidades. Eles são uma parte fundamental da programação orientada a objetos em JavaScript. Exemplo:

```javascript
var pessoa = {
    nome: "Maria",
    idade: 25,
    saudacao: function() {
        return "Olá, meu nome é " + this.nome;
    }
};

console.log(pessoa.nome); // "Maria"
console.log(pessoa.saudacao()); // "Olá, meu nome é Maria"
```

## Eventos
Eventos são ações do usuário ou do navegador que podem ser detectadas e tratadas com JavaScript. Você pode anexar funções a eventos para criar interatividade em sua página. Exemplo:

```javascript
var botao = document.getElementById("meuBotao");
botao.addEventListener("click", function() {
    alert("Botão clicado!");
});
```