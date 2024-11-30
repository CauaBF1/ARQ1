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

## Questão 3
---
Considere uma arquitetura do tipo registrador-registrador. No ciclo de busca somente há uma leitura da
memória. Considerando as informações conhecidas em seguida (resumidas nos valores de NR, NRI, NCO), encontre o
maior número possível de bits associados ao campo que faz referência à origem de um argumento de instrução
correspondente a uma operação aritmética.
NR: número de registradores manipulados pelo usuário (programador)
NRI: número de bits do registrador de instruções
NCO: número de bits do código de operação

### Resposta:

## Questão 4
---
Considere uma arquitetura do tipo registrador-registrador. No ciclo de busca somente há uma leitura da
memória. Uma equipe de projetistas recebeu a tarefa de alterar uma arquitetura já ultrapassada para o mercado. Para
efeitos de projeto, o seguinte aspecto de arquitetura foi selecionado para alteração:
- NRI: número de novos registradores inseridos
Os custos associados à proposta de alteração da arquitetura é tal como segue:
- Cr = alfa*NRI; Cr: custo de incremento no número de registradores (o número de registradores deve ser compatível
com o número de bits necessários para identificar cada registrador no banco de registradores);
- Cb = beta*NB; Cb: custo de incremento no número de bits no registrador de instruções (NB: número de novos bits no
registrador de instruções).
Considere ainda que:
- Ix: maior investimento possível para execução do projeto, liberado pela diretoria financeira;
- NRA: número de registradores na arquitetura obsoleta.
Sendo assim, encontre uma expressão matemática que relacione o maior número de novos registradores inseridos (NRI)
com o maior investimento possívelb(Ix).

### Resposta:

## Questão 5
---
Considere uma arquitetura do tipo registrador-registrador. No ciclo de busca somente há uma leitura da
memória. Uma equipe de projetistas recebeu a tarefa de alterar uma arquitetura já ultrapassada para o mercado. Para
efeitos de projeto, o seguinte aspecto de arquitetura foi selecionado para alteração:
- NLI: número de novas operações executadas pelo circuito da ULA (capacidade de executar operações lógico-
aritméticas)
Os custos associados à proposta de alteração da arquitetura é tal como segue:

- Cb = beta*NB; Cb: custo de incremento no número de bits no registrador de instruções (NB: número de novos bits no
registrador de instruções);
- Cl = gama*NLI; Cl: custo de incremento no número de operações executadas na ULA.
Considere ainda que:
- Ix: maior investimento possível para execução do projeto, liberado pela diretoria financeira;
- NLA: número de operações distintas presentes na ISA da máquina obsoleta.
Sendo assim, encontre uma expressão matemática que relacione o maior número de novas operações executadas pelo
circuito da ULA (NLI) com o maior investimento possível (Ix).

### Resposta:

