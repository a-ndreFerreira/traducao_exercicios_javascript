# Passo 51

Sua variável call tem um valor undefined, mesmo que você tenha definido! Isso ocorre porque sua função padRow atualmente não retorna um valor. Por padrão, as funções retornam undefined como valor.

Para retornar outra coisa, você precisa usar a palavra-chave return. Aqui está um exemplo de função que retorna a string "Functions are cool!":

## Exemplo de código

function demonstração() {
  return "Funções são legais!";
}

Use a palavra-chave return para que sua função retorne a string "Hello!".