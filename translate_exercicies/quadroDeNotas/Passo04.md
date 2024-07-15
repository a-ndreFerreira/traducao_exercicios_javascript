# Passo 04

Agora que o professor tem todas as informações de que precisa, ele quer poder enviar uma mensagem ao aluno com os resultados.

Complete a função studentMsg com totalScores e studentScore como parâmetros. A função deve retornar uma string representando uma mensagem para o aluno.

Caso o aluno tenha sido aprovado no curso, a string deverá seguir este formato:

## Exemplo de código

Class average: average-goes-here. Your grade: grade-goes-here. You passed the course.

Se o aluno foi reprovado no curso, a string deverá seguir este formato:

## Exemplo de código

Class average: average-goes-here. Your grade: grade-goes-here. You failed the course.

Substitua a average-goes-here pela média das pontuações totais. Substitua a grade-goes-here pela nota do aluno.

Tips

Use a função getAverage para obter a média da turma.
Use a função getGrade para obter a nota do aluno.
Use concatenação de strings (+) para construir a mensagem.
Tenha cuidado com a pontuação e os espaços na mensagem.