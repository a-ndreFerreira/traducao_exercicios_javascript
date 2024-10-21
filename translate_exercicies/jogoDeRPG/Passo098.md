# Passo 098

Ao testar sua função, você deveria ter visto uma mensagem de erro no console. Este erro é devido à condição na função buyWeapon.

A variável currentWeaponIndex é o índice do array de armas, mas a indexação do array começa em zero. O índice do último elemento em uma matriz é um a menos que o comprimento da matriz.

Altere a condição if para verificar armas.length - 1, em vez de armas.length.

Teste sua função buyWeapon novamente para ver a mensagem de erro desaparecer.