# Passo 31

Declarar uma variável com a palavra-chave let permite que ela seja reatribuída. Isso significa que você pode alterar o caractere posteriormente para um valor completamente diferente.

Para este projeto, você não desejará alterar os valores dessas variáveis. Então, em vez disso, você deve usar const para declará-los. variáveis ​​const são especiais.

Primeiro, uma variável const não pode ser reatribuída como uma variável let. Este código geraria um erro:

## Exemplo de código

const primeiroNome = "Naomi";
primeiroNome = "Jéssica";

Uma variável const também não pode ser não inicializada. Este código geraria um erro:

## Exemplo de código

const primeiroNome;

Substitua suas palavras-chave let por const.