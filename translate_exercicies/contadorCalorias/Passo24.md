# Passo 24 

JavaScript fornece um método .replace() que permite substituir caracteres em uma string por outra string. Este método aceita dois argumentos. O primeiro argumento é a sequência de caracteres a ser substituída, que pode ser uma string ou um padrão regex. O segundo argumento é a string que substitui a sequência correspondente.

Como as strings são imutáveis, o método replace retorna uma nova string com os caracteres substituídos.

Neste exemplo, o método replace é usado para substituir todas as ocorrências da letra l pelo número 1 na string hello.

## Exemplo de código

"olá".replace(/l/g, "1");

Use seu regex para substituir todas as instâncias de +, - e um espaço em str por uma string vazia. Retorne este valor.