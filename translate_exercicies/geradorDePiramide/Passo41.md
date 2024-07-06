# Passo 41

Para manipular a string result, você usará um tipo diferente de loop. Especificamente, um loop for...of, que itera sobre cada item em um objeto iterável e o atribui temporariamente a uma variável.

A sintaxe para um loop for...of é semelhante a:

## Exemplo de código

for (const value of iterável) {

}

Observe que você pode usar const porque a variável existe apenas para uma única iteração, não durante todo o loop.

Crie um loop for...of para percorrer seu array rows, atribuindo cada valor a uma variável row.