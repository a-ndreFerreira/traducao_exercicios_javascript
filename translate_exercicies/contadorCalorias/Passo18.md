# Passo 18

Quando o usuário insere seu orçamento diário de calorias, o campo de entrada aceitará apenas valores numéricos. No entanto, se um número for inserido com um sinal + ou -, você precisará remover esses caracteres.

Comece declarando uma função cleanInputString que usa um parâmetro str.

NOTA: Os valores de um campo de entrada HTML são recebidos como strings em JavaScript. Você precisará converter essas strings em números antes de realizar qualquer cálculo. A conversão de valores de string em números será abordada em uma etapa futura.