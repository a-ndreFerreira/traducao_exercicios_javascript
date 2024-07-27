# Passo 15

JavaScript interage com o HTML usando o Document Object Model, ou DOM. O DOM é uma árvore de objetos que representa o HTML. Você pode acessar o HTML usando o objeto document, que representa todo o seu documento HTML.

Um método para encontrar elementos específicos em seu HTML é usar o método querySelector(). O método querySelector() usa um seletor CSS como argumento e retorna o primeiro elemento que corresponde a esse seletor. Por exemplo, para encontrar o elemento <h1> em seu HTML, você escreveria:

## Exemplo de código

let h1 = document.querySelector("h1");

Observe que h1 é uma string e corresponde ao seletor CSS que você usaria.

Crie uma variável button1 e use querySelector() para atribuir a ela seu elemento com o id de button1. Lembre-se de que os seletores de id CSS são prefixados com #.