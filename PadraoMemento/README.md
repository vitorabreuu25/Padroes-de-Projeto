## MEMENTO

### Nome e classificação

Memento - Padrão Comportamental

### Intenção/Objetivo

O objetivo do padrão é permitir que seja possível atender a demanda de registrar o estado de um objeto para implementar mecanismos
de checkpoint e desfazer operações em casos de erro, isso sem quebrar ou violar o encapsulamento da Orientação a Objetos.

### Motivação

As vezes, é necessário registrar o estado de um objeto. Isso é necessário em implementações de mecanismos de checkpoints e de desfazer operações.

### Aplicabilidade

Utilizada quando é necessário criar pontos de restauração de estado de objetos ou se necessário permitir o programa desfazer operações errôneas.

### Estrutura e Participantes

A estrutura deste padrão é divido entre 3 participantes:

- Memento;
- Originador;
- Caretaker.

### Codigo de Exemplo

Pasta .exemploMemento
