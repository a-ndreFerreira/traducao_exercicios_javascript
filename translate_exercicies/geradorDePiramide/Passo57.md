# Passo 57

Variáveis ​​em JavaScript estão disponíveis em um escopo específico. Em outras palavras, onde uma variável é declarada determina onde ela pode ser usada no seu código.

O primeiro escopo é o escopo global. Variáveis ​​​​declaradas fora de qualquer "bloco", como uma função ou loop for, estão no escopo global. Suas variáveis ​​de character, count e rows estão todas no escopo global.

Quando uma variável está no escopo global, uma função pode acessá-la em sua definição. Aqui está um exemplo de uma função usando uma variável title global:

## Exemplo de código

const titulo = "Professor";
function demonstração(nome) {
  retornar título + nome;
}
demonstração("Noemi")

Este exemplo retornaria "Professora Naomi". Atualize sua função padRow para retornar o valor da concatenação de sua variável de character ao início do parâmetro name.