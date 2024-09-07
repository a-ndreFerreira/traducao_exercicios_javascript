# Passo 38

A propriedade innerText controla o texto que aparece em um elemento HTML. Por exemplo:

## Exemplo de código

<p id="info">Conteúdo de demonstração</p> 

## Exemplo de código

const info = document.querySelector("#info"); 
info.innerText = "Olá Mundo"; 

O exemplo a seguir alteraria o texto do elemento p de conteúdo Demo para Hello World.

Quando um jogador clica no botão go Store, você deseja alterar os botões e o texto. Remova o código dentro da função goStore e adicione uma linha que atualiza o texto do botão1 para dizer “Buy 10 health (10 gold)”.