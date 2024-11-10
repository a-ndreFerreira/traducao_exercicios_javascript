# Passo 05

CamperBot criou uma nova variável chamada bgHexCodeSpanElement para armazenar a referência ao elemento span com o id do código bg-hex. No entanto, quando eles tentam registrar essa variável no console, eles ficam nulos.

null é um valor especial em JavaScript que representa a ausência de um valor. Isso pode acontecer quando você tenta acessar uma propriedade de um objeto que não existe.

Neste caso, o CamperBot não está passando o seletor correto para o método document.querySelector.

Corrija a linha document.querySelector("bg-hex-code") para que ela selecione corretamente o elemento com o id de bg-hex-code.