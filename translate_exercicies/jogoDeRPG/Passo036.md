# Passo 36

button1 representa seu primeiro elemento de botão. Esses elementos possuem uma propriedade especial chamada onclick, que você pode usar para determinar o que acontece quando alguém clica naquele botão.

Você pode acessar propriedades em JavaScript de duas maneiras diferentes. A primeira é com notação de ponto. Aqui está um exemplo de uso da notação de ponto para definir a propriedade onclick de um botão como uma referência de função.

## Exemplo de código

button.onclick = minhaFunção;

Neste exemplo, button é o elemento button e myFunction é uma referência a uma função. Quando o botão é clicado, myFunction será chamado.

Use a notação de ponto para definir a propriedade onclick do seu button1 como a referência da função goStore. Observe que o button1 já está declarado, então você não precisa usar let ou const.