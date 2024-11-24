# Lista Formatação avaliação 1
---

## Questão 1
---
Considere uma arquitetura do tipo registrador-registrador. No ciclo de busca somente há uma leitura da
memória. Considerando as informações conhecidas em seguida (resumidas nos valores de NR, NRI e NCO), apresente
uma relação (IGUALDADE OU DESIGUALDADE) entre tais variáveis que indique restrições para efeitos de projeto
de arquitetura.

NR: número de registradores manipulados pelo usuário (programador)
NRI: número de bits do registrador de instruções
NCO: número de bits do código de operação

### Resposta:

O numero de bits do codigo de operação (NCO) deve ser diferente do NRI, pois o NRI deve conseguir receber o NCO além do log2(NR), numero minimo de registradores é 2 portanto relação entre as variaveis é:

NRI >= NCO + 2 x log2(NR)

#### Resposta Kevin:
NBR = numero de bits de resgistradores manipulados pelo usuario -> logb(NR)
NO = numero de operaçoes -> NCO >= log2(NO)
NRI = NCO + 3 x NBR

## Questão 2
---
Considere uma arquitetura do tipo registrador-registrador. No ciclo de busca somente há uma leitura da
memória. Considerando as informações conhecidas em seguida (resumidas nos valores de NR e NRI), apresente o
maior número de instruções distintas que podem ser executadas pelo processador.

NR: número de registradores manipulados pelo usuário (programador)
NRI: número de bits do registrador de instruções

### Resposta:

