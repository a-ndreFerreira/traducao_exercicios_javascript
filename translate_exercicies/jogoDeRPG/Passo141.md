# Passo 141

Para que o &#x2620; para que o texto do emoticon seja exibido corretamente na página, você precisará usar a propriedade innerHTML.

A propriedade innerHTML permite acessar ou modificar o conteúdo dentro de um elemento HTML usando JavaScript.

Aqui está um exemplo de atualização do conteúdo deste elemento de parágrafo usando a propriedade innerHTML.

## Exemplo de código

<p id="demo">Este é um parágrafo.</p>

## Exemplo de código

document.querySelector("#demo").innerHTML = "Olá, innerHTML!";

Na função de atualização, altere text.innerText para text.innerHTML.