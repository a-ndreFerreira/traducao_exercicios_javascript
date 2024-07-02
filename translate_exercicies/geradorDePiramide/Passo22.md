# Passo 22

Observe como o valor dentro do seu array rows foi alterado diretamente? Isso é chamado de mutação. À medida que você aprende mais sobre arrays, você aprenderá quando modificar um array e quando não deveria.

Antes de prosseguir, esta é uma ótima oportunidade para aprender um uso comum de array. Atualmente, seu código acessa o último elemento do array com rows[2]. Mas você pode não saber quantos elementos existem em uma matriz quando deseja o último.

Você pode usar a propriedade .length de um array - isso retorna o número de elementos do array. Para obter o último elemento de qualquer array, você pode usar a seguinte sintaxe:

## Exemplo de código

array[array.length - 1]

array.length // retorna o número de elementos do array. Ao subtrair 1, você obtém o índice do último elemento do array. Você pode aplicar esse mesmo conceito ao seu array rows.

Atualize seu rows[2] para acessar dinamicamente o último elemento na matriz rows. Consulte o exemplo acima para ajudá-lo.

Você não deverá ver nada mudar em seu console.