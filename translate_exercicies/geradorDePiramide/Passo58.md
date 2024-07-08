# Passo 58

Variáveis ​​também podem ser declaradas dentro de uma função. Essas variáveis ​​são consideradas no escopo local ou no escopo do bloco. Uma variável declarada dentro de uma função só pode ser usada dentro dessa função. Se você tentar acessá-lo fora da função, receberá um erro de referência.

Para ver isso em ação, use const para declarar uma variável de teste em sua função padRow. Inicialize-o com o valor "Teste".

Então, abaixo da sua função, tente registrar o teste no console. Você verá um erro porque não está definido fora do escopo local da função. Remova esse console.log para passar nos testes e continuar.