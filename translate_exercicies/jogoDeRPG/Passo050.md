# Passo 50

Se o nome da propriedade (chave) de um objeto contiver um espaço, você precisará usar aspas simples ou duplas ao redor do nome.

Aqui está um exemplo de um objeto com um nome de propriedade que possui um espaço:

## Código de exemplo

const espaçoObj = {
  "Nome do Espaço": "Kirk",
};

Se você tentasse escrever uma chave sem as aspas, ocorreria um erro:

## Código de exemplo

const espaçoObj = {
  // Lança um erro
  Nome do espaço: "Kirk",
}; 

Adicione uma nova propriedade com uma chave "Number of legs" e valor 4 ao objeto gato.

Abra o console para ver a saída.