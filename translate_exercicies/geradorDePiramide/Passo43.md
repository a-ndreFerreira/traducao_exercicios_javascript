# Passo 43

Agora todos os seus números aparecem na mesma linha. Isso não funcionará para criar uma pirâmide.

Você precisará adicionar uma nova linha a cada linha. No entanto, pressionar a tecla Enter para inserir uma quebra de linha entre aspas em JavaScript resultará em um erro de análise. Em vez disso, você precisa usar a sequência de escape especial \n, que é interpretada como uma nova linha quando a string é registrada. Por exemplo:

## Exemplo de código

linhaUm = linhaUm + "\n" + linhaDois;

Use um segundo operador de adição para concatenar uma nova linha entre o valor do resultado existente e o valor da row adicionada.