## SINGLETON

### Nome e classificação

Singleton - Padrão Criacional

### Intenção/Objetivo

Este padrao é capaz de definir que apenas uma instância concorrente da classe existirá ao longo da aplicação.

### Motivação

Alguns bancos de dados rodam em modo embarcado, estes bancos não suportam diversas 
conexões: cada banco de dados permite apenas uma única conexão ativa (ou seja, uma única instância).

### Aplicabilidade

Ele é aplicado quando você possuí uma classe que precisa controlar o que será instanciado. Como o Singleton permitie apenas uma instância durante a aplicaçao, você consegue monitorar e controlar este comportamento.

### Estrutura e Participantes

Há apenas dois participantes: Singleton e Client (que utiliza o Singleton).

### Codigo de Exemplo

Pasta .exemploSingleton
