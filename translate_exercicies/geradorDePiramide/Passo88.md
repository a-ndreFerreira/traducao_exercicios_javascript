# Passo 88

O operador de igualdade pode levar a algum comportamento estranho em JavaScript. Por exemplo, "0" == 0 é verdadeiro, mesmo que um seja uma string e o outro seja um número.

O operador de igualdade estrita === é usado para verificar se dois valores são iguais e compartilham o mesmo tipo. Como regra geral, este é o operador de igualdade que você sempre deve usar. Com o operador de igualdade estrita, "0" === 0 torna-se falso, porque embora possam ter o mesmo valor zero, eles não são do mesmo tipo.

Atualize sua condição done == count para usar o operador de igualdade estrita.