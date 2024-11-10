# Passo 146

O ataque do monstro será baseado no nível do monstro e no XP do jogador. Na função getMonsterAttackValue, use const para criar uma variável chamada hit. Atribua-lhe a equação (nível * 5) - (Math.floor(Math.random() * xp));.

Isso definirá o ataque do monstro para cinco vezes o seu nível menos um número aleatório entre 0 e o XP do jogador.