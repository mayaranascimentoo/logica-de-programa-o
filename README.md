# logica-de-programa-o
# Operadores em JavaScript 

Aprenda a ultilizar os operadores na linguagem JavaScript.

Inicialmente declaramos as variaveis com a palavra `const`.

~~~js
const numero1 = 30;
const numero2 = 20;
~~~

Depois, realizamos as operações utilizando os operadores aritméticos:

* `+`: soma dois numeros 
* `-`: subtrai dois numeros 
* `*`: mutiplica dois numerlos 
* `/`: divide dois numeros 
* `%`: obtem o resto da divisão de dois numeros 

~~~js
console.log(`Os numeros são ${numero1} e ${numero2}`);
console.log(`A soma dos numeros é ${numero1 + numero2}`);
console.log(`A subtração dos numeros é ${numero1 - numero2}`);
console.log(`A mutiplicação dos numeros é ${numero1 * numero2}`);
console.log(`A divisão dos numeros é ${numero1 / numero2}`);
console.log(`O resto da divisão dos numeros é ${numero1 % numero2}`)
~~~

As operações são realizadas no momento da impressão do resultado e
não necessita ser armazenado em variaveis.


## operadores-atribuicao.js

~~~js
let numero = 10 ;
~~~

Declaramos a váriavel `numero` usando a palavra reservada `let`, pois essa 
variável será retribuida ao longo do nosso código.

Em seguida, fazemos uma série de retribuições utilizando os operadores 
de atribuição.

~~~js
console.log(`O numero inicial é ${numero}`)
console.log(`Somando 10: ${numero+= 10}`);
console.log(`Subitraindo 10: ${numero -= 10}`);
console.log(`Mutiplicando por 10: ${numero*= 10}`);
console.log (`Divisão por 10 ${numero/= 10}`);
console.log(`Elevado a potência de 10: ${numero**= 10}`)
console.log(`Obtenha o resto da divisão por 10:${numero%= 10 }`);
console.log(`Incrementando 1:${++numero}`);
console.log(`Decrementando 2:${--numero}`)
console.log(`O numero final é: ${numero}`);
~~~

Operação de atribuição:
* `+=` -> o próprimo valor somado ao novo valor 
* `-=` -> o próprio valor subtraindo-se o novo valor 
* `*=` -> o próprio valor mutiplicado pelo novo valor 
* `/=` -> o próprio valor dividido pelo novo valor 
* `**=`-> o próprio valor elevado à potência do novo valor 
* `%=` -> o resto da divisão do próprio valor pelo novo valor 
* `++` -> o próprio valor **incrementando(somando) com 1** (pode ser
um _pré-incremento_ ou _pós-incremento_).
*`--` ->o próprio valor **decrementando (subtraindo) com 1** (pode ser
um _pré-decremento_ ou _pós-decremento_).