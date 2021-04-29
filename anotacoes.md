# Componente Angular
    1 - HTML
    2 - CSS
    3 - TypeScript

# Diretiva de Atributo
    1 - Alterar aparência (ex: css)
    2 - Comportamento (ações integrando backend)

# Diretiva Estrutural
    1 - Altera estrutura da sua página DOM

# Binding
    Ligação entre arquivo TS e HTML

# Programação Reativa
    Precisa acontecer algo para o código ser executado

# Padrão Observer
    Padrão orientado a Evento
    1 - Subject: Capacidade de monitorar e detectar quando evento acontece. (Detecta o evento e notifica ao Observer)
    2 - Observer: Os códigos que estão interessadas em determinado evento. (Precisa se registrar no Subject)
    3 - Callbacks: Função como parâmetro para outra função
    4 - Promises: Função como parâmetro, tem capacidade de encadear várias chamadas, sem aninhamento de funções
    5 - Observables: Pode ser reusável, stream de dados(consumir api de tempo em tempo, em sequência), operados: funções que podem ser usadas juntos com observables.

# Services  
    `ng g s services/product`
    São classes que têm como objetivo organizar e compartilha métodos e dados entre componentes

# Injeção de Dependências
    1 - Classe passível
    2 - Só existe um injetor raiz na aplicação
    3 - Recebe apartir de fonte externa
    4 - Quando cria classe com @Injectable, essa classe pode ser Injetada, deve instânciar essa classe
    5 - Cria instância de ProductService
    6 - Quem cria é Framework do Angular

# ProdidedIn
    1 - Apelido para app module, root injector
    2 - Está dizendo que providedin vai ser root
    3 - única instância em toda aplicação
    4 - Services são singletons, instância única
    5 - Injetor de modulo - @NgModule, @Injectable - ÚNICA INSTÂNCIA
    6 - Injetor de elemento - @Directive, @Component - INSTÂNCIA DEDICADA - NOVAS INSTÂNCIAS