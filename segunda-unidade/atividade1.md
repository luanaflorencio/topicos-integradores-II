# Atividade para compor a nota Tópicos Integradores

## 1. Por que devemos fazer testes automatizados nas aplicações que desenvolvemos?

### Testes automatizados tem o intuito de validação de um software por meio de ferramentas das quais realizam testes repetidades vezes em cenários diferentes, dessa forma faz com que a validação do software seja mais eficaz e rápida, livre de erros humanos nos testes, encontrado falhas que poderiam passar despercebidas, dessa forma o tempo que seria gasto para fazer esses testes manualmente, pode ser usado para desenvolver melhorias no sistema, corrigir bugs encontrados, etc. Com os testes automatizados o tempo de validação e entrega ficam mais rápidos, dessa forma o custo fica menor, a qualidade dos requisitos entregues tem segurança e confiabilidade, com tudo isso levando a um software de qualidade e com ciclos de entrega mais rápidos.

## 2. O que são testes unitários?

### Testes unitários são testes de unididades, ou seja dependendo do sistema que alguém esteja desenvolvendo vai ser a menor parte testável daquele sistema, como uma função por exemplo, o teste unitário irá testar aquela função específica, são de rápida criação e execução, testes unitários também são mais baratos e ráṕidos comparados a testes em níveis de usuários (GUI), pois podem executar testes em diversas partes de um sistema em segundos.

## 3. O que são testes automatizados? 

### Testes automatizados são testes que facilitam a etapa de teste usando programas que executam testes de forma padronizada em softwares, onde é possível por exemplo, programar o que será testado e quando, diminuidno o risco de falhas passarem despercebidas por erro humano.

## 4. Escolha uma pirâmide de testes e descreva com suas palavras cada secção da pirâmide.

### Na pirâmide de testes temos 3 partes de baixo pra cima: Unit, Integration e E2E, ou ponta a ponta(end to end).

### Unit ou teste de unidade está na base da pirâmide, é onde é verificado o funcionamento da menor unidade de teste de um software independente do tamanho da unidade, os testes de unidades são pequenos pois como dito anteriormente, testa a menor unidade da aplicação, portanto são rápidos de rodar, quando um teste falha, pode saber exatamente onde está a falha, sem gasto de tempo procurando. Para realização não é necessário criar objetos reais podem ser criados alguns objetos falsos, que vão simular o comportamento de um objeto real para que o teste seja excutado de forma isolada naquela unidade.

### Integration ou Testes de Integração, segunda camada da pirâmide, os testes de unidades apesar de eficiente não é suficiente, pois o teste unitário testa apenas uma unidade, já o teste de interação vai testar um conjunto de unidades interagindo entre si, testes de integração também são usados para testar a comunicação com o BD, API's, etc. O teste unitário pode ser útil para testar mais de uma unidade, mas quando essas unidades interagem apenas o teste de integração é que vai validar se essa interação está ou não funcionando como deve.

### E por último, no topo da pirâmide temos o E2E(End to End) ou Ponta a Ponta, nessa etapa os testes são mais a nível de usuário, o objetivo maior desse teste é validar se a aplicação está funcionando como deve do que encontrar possíveis erros, no teste e2e é verificado o fluxo completo do software, da inicilização as fases que o usuário passe (como por exemplo preencher um formulário de dados bancários) até chegar ao objetivo final validando se o comportamento está funcionando como deveria ou não. Esse tipo de teste, demanda muito mais tempo, é mais complexo e portanto custa mais do que os outros testes da pirâmide, por isso esse teste é indicado ser executado menos vezes e apenas no foco principal do fluxo, os pontos onde não podem haver erros na interação do usuário com a aplicação, caso contrário traria perdas que devem ser evitadas, nesses casos e nesses pontos o teste E2E é indicado.