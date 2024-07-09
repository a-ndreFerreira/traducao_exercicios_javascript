# Passo 83

Às vezes, você desejará executar um código diferente quando todas as condições if...else if forem falsas. Você pode fazer isso adicionando um bloco else.

Um bloco else avaliará apenas se as condições nos blocos if e else if não forem atendidas.

Aqui o bloco else é adicionado ao bloco else if.

## Exemplo de código

if (condição) {
  //este código será executado se a condição for verdadeira
} else if (condição2) {
  // este código será executado se a primeira condição for falsa
} else {
  //este código será executado 
  // se a primeira e a segunda condições forem falsas
}

Adicione um bloco else ao bloco else if. Dentro do bloco else, registre a string "Este é o bloco else" no console.

Para ver os resultados no console, você pode alterar manualmente o < na instrução else if para >. Isso tornará a condição falsa e o bloco else será executado.