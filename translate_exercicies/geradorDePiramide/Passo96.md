# Passo 96

Você também pode substituir a referência done na sua chamada padRow.

Observe que rows.length aqui causaria um erro off-by-one, porque done é incrementado antes da chamada.

Portanto, você precisará substituir done aqui por rows.length + 1. Ao fazer isso, você poderá ver um erro de intervalo, porque criamos outro erro off-by-one.

Você precisará alterar a condição while para usar o operador menor que, em vez do operador menor ou igual.