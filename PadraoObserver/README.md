## OBSERVER

### Nome e classificação

Observer - Padrão Comportamental 

### Intenção/Objetivo

O objetivo desse padrão é permitir que um objeto publique mudanças em seu estado. E também outro objeto ou aplicação consegue se inscrever para receber
notificações sobre esta mudança, ou seja, observar as mudanças de estado de um objeto, quando essa mudança for relevante.

### Motivação

A motivação dele é de conseguir possibilitar a observação de mudanças de estado de um objeto.

### Aplicabilidade

A aplicação deste padrão é diminuir acoplamento entre classes por encapsulamento.
Ou quando uma mudança de um objeto requer também mudanças de outros objetos.

### Estrutura e Participantes

A estrutura deste padrão é divido entre 3 participantes:

- Subject;
- Observer;
- ConcreteObserverA, B ou outros.

### Codigo de Exemplo

Pasta .exemploObserver
