# Passo 149

Se você jogar no estado atual, poderá notar um bug. Se o seu XP for alto o suficiente, a função getMonsterAttackValue retornará um número negativo, que na verdade aumentará sua saúde total ao lutar contra um monstro! Você pode corrigir esse problema usando um operador ternário para garantir que valores negativos não sejam retornados.

O operador ternário é um operador condicional e pode ser usado como uma instrução if-else de uma linha. A sintaxe é: condição? expressãoIfTrue : expressãoIfFalse.

Aqui está um exemplo de retorno de um valor usando uma instrução if-else e um exemplo refatorado usando um operador ternário:

## Exemplo de código

### instrução if-else

if (pontuação > 0) {
  return pontuação;
} outro {
  return pontuação_padrão;
}

### operador ternário

return pontuação > 0 ? pontuação : pontuação_padrão;

Em getMonsterAttackValue, altere return hit para um operador ternário que retorna hit se hit for maior que 0 ou retorna 0 se não for.