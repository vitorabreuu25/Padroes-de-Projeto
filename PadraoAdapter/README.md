## ADAPTER

### Nome e classificação

Adapter - Padrão Estrutural

### Intenção/Objetivo

O objetivo dele é ligar um sistema legado a um sistema/aplicação a parte. O principal é conseguir criar uma aplicação nova,
utilizando recursos e código do legado, sem afetar o código fonte.

### Motivação

As vezes, uma classe (legado) pode não ser aproveitada, devido ao fato de sua interface não ser correspondente à interface
especifica que uma nova aplicação necessita, fazendo com que seja necessário adapta-la.

### Aplicabilidade

Utilizada em casos que a classe legada não é correspondente à nova interface;
Utilização de classes com interfaces não compatveis.

### Estrutura e Participantes

A estrutura deste padrão é divido entre 3 participantes:

- Alvo;
- Adaptador;
- Adaptado.

### Codigo de Exemplo

Pasta .exemploAdapter
