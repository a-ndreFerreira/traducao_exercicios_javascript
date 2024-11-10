# Passo 144

Embora seu jogo esteja completo neste estágio, há coisas que você pode fazer para torná-lo mais divertido e envolvente. Para começar, você dará aos monstros um valor de ataque dinâmico.

Dentro da sua função de ataque, mude sua saúde -= monstros[luta].nível; linha para saúde -= getMonsterAttackValue(monstros[fighting].level);. Isso define a saúde igual à saúde menos o valor de retorno da função getMonsterAttackValue e passa o nível do monstro como argumento.