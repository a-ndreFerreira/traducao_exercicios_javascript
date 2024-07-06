# Passo 46

Você está chegando mais perto! Neste ponto, você está encontrando o que é conhecido como erro off-by-one, um problema frequente em linguagens de indexação baseadas em zero, como JavaScript.

O primeiro índice do seu array de linhas é 0, e é por isso que você inicia seu loop for com i = 0. Mas repetir uma string zero vezes resulta em nada para imprimir.

Para corrigir isso, adicione 1 ao valor de i na sua chamada .repeat(). Não atribua-o de volta a i como você fez nas condições do loop.