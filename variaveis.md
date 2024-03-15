
## Declaração de variáveis

### Let
As variáveis declaradas com let têm escopo de bloco, o que significa que elas só são acessíveis dentro do bloco onde foram declaradas.
Variáveis declaradas com let podem ser reatribuídas, mas não redeclaradas no mesmo escopo.
let não sofre hoisting da mesma forma que var.

``` JavaScript
let numero = 10; 
console.log(numero); 

if (true) {
  let numero = 20; 
  console.log(numero); 

console.log(numero); 
}
```

### Var

As variáveis declaradas com var têm escopo de função ou global, o que significa que elas podem ser acessadas de qualquer lugar dentro da função em que foram declaradas.
Variáveis declaradas com var podem ser redeclaradas e reatribuídas.
var tem hoisting, o que significa que as declarações de variáveis são movidas para o topo do contexto de execução durante a fase de compilação.

``` JavaScript
var nome = "João";
var idade = 30;
```

## Const
Assim como let, as variáveis declaradas com const têm escopo de bloco.
A diferença chave é que variáveis declaradas com const não podem ser reatribuídas após a sua inicialização. No entanto, isso não impede que os valores armazenados nessas variáveis sejam mutáveis.

```JavaScript
const numero = 10;
console.log("O valor da constante é:", numero);

```