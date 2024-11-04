# Passo 105

O próximo passo é criar uma variável chamada currentWeapon.

## Exemplo de código

let num = 1;

if (num === 1) {
  let num = 2; // este num tem como escopo a instrução if
  console.log(num); //saída esperada: 2
}

console.log(num); // saída esperada: 1 (a variável global)

Use a palavra-chave let para criar uma variável chamada currentWeapon. Não atribua um valor ainda.