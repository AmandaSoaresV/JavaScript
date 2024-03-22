## Operadores Básicos 

# Array
permite armazenar uma coleção de elementos sob um único nome. Os elementos de um array podem ser números, strings, objetos, funções,  etc. Os arrays em JavaScript são indexados começando do índice 0.
* Para mudar um elemento voce acessa ele e muda pelo indice [] 
* para adicinar um elemento ao final vc usa o push
* Para ver o comprimento de um array usa-se o length
* Para remover o ultimo elemento voce pode usar o POP

``` JavaScript

let cores = ['vermelho', 'azul', 'verde'];

// MODIFICANDO UM ELEMENTO
cores[1] = 'amarelo';
console.log(cores); 
// ADICIONANDO UM NOVO ELEMENTO
cores.push('roxo');
console.log(cores);
//REMOVENDO
cores.pop();
console.log(cores);
//TAMANHO
console.log(cores.length); 

```

## Operadores básicos

# Operadores Aritméticos:

* Soma (+): é utilizado para somar dois valores.

* Subtração (-): é utilizado para subtrair um valor de outro.


* Multiplicação (*): é  utilizado para multiplicar dois valores.

* Divisão (/): é utilizado para dividir um valor por outro.

* Módulo (%): Vai trazer o resto da divisão.

* Incremento (++) e Decremento (--): Incrementa ou decrementa em 1 o valor de uma variável.


``` JavaScript
var soma = 2 + 3; 
var subtracao = 5 - 2; igual a 3
var multiplicacao = 3 * 4; 
var divisao = 10 / 2; 
var modulo = 10 % 3; 
var x = 5;
x++; /
var y = 10;
y--; 

```

# Operados de comparação
* Igualdade (==): Verifica se dois valores são iguais, sem considerar o tipo de dados.

* Igualdade estrita (===): Verifica se dois valores são iguais, considerando o tipo de dados.

* Desigualdade (!=): Verifica se dois valores não são iguais, sem considerar o tipo de dados.

* Desigualdade estrita (!==): Verifica se dois valores não são iguais, considerando o tipo de dados.

* Maior que (>) e Menor que (<): Verifica se um valor é maior ou menor que outro.

* Maior ou igual que (>=) e Menor ou igual que (<=): Verifica se um valor é maior ou igual a outro, ou se é menor ou igual a outro.


``` JavaScript
var igual = (5 == '5'); 
var igualdadeEstrita = (5 === '5'); 
var maiorQue = (10 > 5); 
var menorQue = (3 < 8); 
Var maior=(10>=10);

```

# Operadores Lógicos
* AND usa (&&):Ele vai retornar true se ambos os operandos forem true (os dois).
* OR usa (||): Vai retornar true se pelo menos um dos operandos for true ( um ou outro).
* NOT usa (!): Retorna true se o operando for false e false se o operando for true.
## AND

``` JavaScript

var a = 5;
var b = 10;
var c = 15;

if (a < b && b < c) {
    console.log("Ambas as condições são verdadeiras.");
} else {
    console.log("Pelo menos uma das condições é falsa.");
}

```
## OR
``` JavaScript
var idade = 25;

if (idade < 18 || idade > 65) {
    console.log("Pessoa tem direito a desconto.");
} else {
    console.log("Pessoa não tem direito a desconto.");
}
```

## NOT
``` JavaScript
var ativo = true;

if (!ativo) {
    console.log("O usuário está inativo.");
} else {
    console.log("O usuário está ativo.");
}


```

# Typeof
typeof vai retornar o tipo do operador se ele é number,object, boolean, string
``` JavaScript

x = 5;
typeof x; 

x = "Amanda Soares";
typeof x; 

x = true;

x = {};
typeof x; 


```
