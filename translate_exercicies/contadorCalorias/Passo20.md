# Passo 20

O padrão atual corresponderá exatamente ao texto "olá", que não é o comportamento desejado. Em vez disso, você deseja pesquisar +, - ou espaços. Substitua o padrão em sua variável regex por \+- para corresponder aos caracteres de mais e menos.

Observe que você precisa usar o caractere barra invertida \ para escapar do símbolo + porque ele tem um significado especial em expressões regulares.