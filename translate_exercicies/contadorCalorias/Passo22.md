# Passo 22

Seu padrão atual ainda não funcionará. /+-\s/ procura por +, - e um espaço em ordem. Isso corresponderia a +- hello, mas não corresponderia a +hello.

Para que o padrão corresponda a cada um desses caracteres individualmente, você precisa transformá-los em uma classe de caracteres. Isso é feito colocando os caracteres que você deseja corresponder entre colchetes. Por exemplo, este padrão corresponderá aos caracteres h, e, l ou o:

## Exemplo de código

const regex = /[helo]/;

Transforme seu padrão +-\s em uma classe de character. Observe que você não precisa mais escapar do caractere +, pois está usando uma classe de character.