# Passo 75

Infelizmente, agora a base da pirâmide desapareceu. Isso ocorre porque você criou outro erro pontual.

Seu loop original foi para valores de i de 0 a 7, porque a contagem é 8 e sua condição exige que i seja menor que a contagem. Seu loop agora está sendo executado para valores i de 1 a 7.

Seu loop também precisa ser atualizado para ser executado quando i tiver 8 também. Olhando para sua lógica, isso significa que seu loop deve ser executado quando i for menor ou igual à contagem. Você pode usar o operador menor ou igual a <= para isso.

Atualize sua condição de loop para ser executada enquanto i for menor ou igual à contagem.