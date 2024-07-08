# Passo 59

Os valores retornados de uma função são usados ​​chamando a função. Você pode usar a chamada de função diretamente como o valor retornado ou capturar o valor retornado em uma variável. Dessa forma, você pode usar o valor atribuído a uma variável com escopo local, fora da função em que foi criada.

## Exemplo de código

function getNome() {
  const nome = "Gato campista";
  return nome;
}

console.log(getNome()); // "Gato campista"

const capturadoReturnValue = getName();
console.log(capturadoReturnValue); // "Gato campista"

console.log(nome); //erro de referência

Para usar seu valor "Teste", retorne-o da função padRow atualizando sua instrução return para retornar apenas a variável de test.