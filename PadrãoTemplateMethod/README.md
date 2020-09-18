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

Fornece uma estrutura fixa, de um algoritmo, esta parte fixa deve estar presente na superclasse, sendo obrigatório uma classeAbstrata que possa conter um método concreto, pois em uma interface só é possível conter métodos abstratos que definem um comportamento.

### Codigo de Exemplo

Pasta .exemploTemplateMethod
