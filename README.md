# Sistema de Gerenciamento de Tarefas

Este projeto foi desenvolvido como atividade avaliativa da disciplina de Programação Básica.

## Descrição da Lógica do Programa

O presente programa consiste em um sistema de gerenciamento de tarefas, permitindo ao usuário adicionar, listar, concluir e remover tarefas de uma lista.

Inicialmente, o sistema apresenta um menu interativo com opções numeradas, que é exibido continuamente por meio de uma estrutura de repetição (while), até que o usuário escolha encerrar a execução.

As tarefas são armazenadas em uma lista, sendo cada tarefa representada por um dicionário contendo dois campos: nome e status. O status indica se a tarefa está pendente ou concluída.

Quando o usuário seleciona a opção de adicionar tarefa, o sistema solicita uma descrição e armazena essa informação na lista.

Na opção de listagem, o programa percorre a lista utilizando um laço de repetição (for), exibindo todas as tarefas com seus respectivos índices e status.

Para concluir ou remover uma tarefa, o usuário deve informar o índice correspondente. O sistema valida se o índice está dentro dos limites da lista por meio de operadores de comparação e estruturas condicionais.

## Funcionalidades

- Adicionar tarefas
- Listar tarefas
- Concluir tarefas
- Remover tarefas

## Conceitos utilizados

- Variáveis
- Entrada e saída de dados
- Estruturas condicionais
- Estruturas de repetição
- Listas e dicionários

## Como executar

1. Execute o arquivo `tarefas.py`
2. Utilize o menu interativo
