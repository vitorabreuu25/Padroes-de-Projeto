# PADROES DE PROJETO

## COMPOSITE

### Nome e classificação

Composite - Padrão Estrutural


### Intenção/Objetivo

O padrão Composite é utilizado quando queremos reaproveitar um método e funções de um determinado objeto e utilizar em qualquer outro, 
significando vários objetos vinculados à um só.


### Motivação

Em certos projetos precisamos de métodos e funções que já estão sendo informadas em um determinado objeto, sendo necessário 
apenas a ligação entre os dois objetos para reutilizar esses métodos e funções.

### Aplicabilidade

Este padrão pode ser usado sempre que desejarmos construir objetos exisitindo objetos do mesmo tipo.

### Estrutura e Participantes

Ambos estao interligados, pois sao eles:

- Componente
Declara a interface para objetos na  composição.

- Folha
Define comportamento para objetos  primitivos na composição.

- Composição
Define comportamento para Componentes que têm filhos.

### Codigo de Exemplo

Pasta .exemploComposite


## TEMPLATE METHOD

### Nome e classificação

Template Method - Comportamental de Classes

### Intenção/Objetivo

Definir a esquematização da operação de um algoritmo. O template method permite que as subclasses definam, sem mudar a estrutura do código, certos passos deste algoritmo.

### Motivação

Basicamente oferece um método que define um algoritmo (uma sequência de passos) que pode, por sua vez, ser definido como abstrato para posteriormente ser implementado por uma subclasse. Pode-se notar que a estrutura do algoritmo fica inalterada mesmo com as subclasses fazendo parte da implementação.

### Aplicabilidade

Pode ser usado para implementar as partes invariantes de um algoritmo uma só vez e deixar para as subclasses a implementação do comportamento que pode variar.

### Estrutura e Participantes



### Codigo de Exemplo

Pasta .exemploCTemplateMethod
