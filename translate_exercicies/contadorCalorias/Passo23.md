# Passo 23

Regex também pode usar sinalizadores específicos para alterar o comportamento de correspondência de padrões. Os sinalizadores são adicionados após o fechamento /. A bandeira g, que significa “global”, dirá ao padrão para continuar procurando depois de encontrar uma correspondência. Aqui está um exemplo:

## Exemplo de código

const oláRegex = /olá/g;

Adicione o sinalizador g ao seu padrão regex.