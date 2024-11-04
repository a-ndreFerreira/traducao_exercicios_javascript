# Passo 118

Por padrão, o elemento HTML que mostra as estatísticas do monstro foi ocultado com CSS. Quando o jogador clica no botão "Lutar contra o dragão", as estatísticas do monstro devem ser exibidas. Você pode fazer isso usando as propriedades de estilo e exibição no elemento monsterStats.

A propriedade style é usada para acessar o estilo embutido de um elemento e a propriedade display é usada para definir a visibilidade de um elemento.

Aqui está um exemplo de como atualizar a exibição de um elemento de parágrafo:

## Exemplo de código

const paragrafo = document.querySelector('p');
parágrafo.style.display = 'block';

Exiba o elemento monsterStats atualizando a propriedade display da propriedade style para bloco.