# COMPOSITE

## Nome e classificação

Composite - Padrão Estrutural


## Intenção/Objetivo

O padrão Composite é utilizado quando queremos reaproveitar um método e funções de um determinado objeto e utilizar em qualquer outro, 
significando vários objetos vinculados à um só.


## Motivação

Em certos projetos precisamos de métodos e funções que já estão sendo informadas em um determinado objeto, sendo necessário 
apenas a ligação entre os dois objetos para reutilizar esses métodos e funções.

## Aplicabilidade

Este padrão pode ser usado sempre que desejarmos construir objetos exisitindo objetos do mesmo tipo.

## Estrutura e Participantes

Ambos estao interligados, pois sao eles:

- Componente
Declara a interface para objetos na  composição.

- Folha
Define comportamento para objetos  primitivos na composição.

- Composição
Define comportamento para Componentes que têm filhos.

## Codigo de Exemplo

Pasta .exemploComposite

