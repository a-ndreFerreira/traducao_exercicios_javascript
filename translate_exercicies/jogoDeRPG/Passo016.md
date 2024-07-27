# Passo 016

Encontramos um pequeno problema. Você está tentando consultar sua página em busca de um elemento de botão, mas sua tag de script está no cabeçalho do seu HTML. Isso significa que seu código é executado antes que o navegador termine de ler o HTML e seu document.querySelector() não verá o botão - porque o navegador ainda não o processou.

Para corrigir isso, mova o elemento script para fora do elemento head e coloque-o no final do elemento body (pouco antes da tag de fechamento </body>).