# Relatório sobre implementação de comunicação entre tarefas em RUST

## Introdução

Este relato faz parte do processo avaliativo da disciplina de sistemas operacionas no curso superior em análise e desenvolvimento de sistemas, ofertado na Diretoria acadêmica de gestão e tecnologia da informação no campus natal-central do instituto federal de educação, ciência e tecnologia do rio grande do norte.

Tem como objetivo principal relatar as implementações de comunicação entre tarefas na linguagem RUST.

O grupo de trabalho foi formado por Julia Rafaelly Siqueira de Lima, Lidia Rebeka da Silva Fernandes e Lyonara da Silva Camelo.

## Comunicação entre tarefas em RUST

### Informações gerais


> qual o objetivo de comunicação entre tarefas?

O objetivo da comunicação entre tarefas é permitir que diferentes partes de um programa troquem informações e trabalhem de forma coordenada. Isso é importante principalmente em sistemas que utilizam várias threads ou processos, pois essas tarefas precisam compartilhar dados, enviar mensagens ou avisar quando determinada atividade foi concluída.

> explicar porque usar docker nesse trabalho.

O Docker foi utilizado para criar um ambiente padronizado para executar os programas. Dessa forma, o código pode ser executado sem depender tanto das configurações específicas do computador.

Neste trabalho, o Docker foi configurado com um ambiente contendo as ferramentas necessárias para compilar e executar os programas. O projeto utiliza um arquivo Dockerfile para definir a imagem e as dependências utilizadas. Assim, todos os testes podem ser realizados dentro de um ambiente controlado.

> qual a configuração do docker


### Comunicação entre tarefas com linhas de execução no mesmo processo

FIXME
> texto explicando o código
> mostrar o código completo

FIXME
> explicar como foi executado
> mostrar as saídas do terminal
> mostrar as saídas do terminal

FIXME
> se houve problema na execução, enumerar os problemas e suas respectivas soluções

### Comunicação entre tarefas em processos diferentes no mesmo computador

FIXME
> texto explicando o código
> mostrar o código completo

FIXME
> explicar como foi executado
> mostrar as saídas do terminal
> mostrar as saídas do terminal

FIXME
> se houve problema na execução, enumerar os problemas e suas respectivas soluções

### Comunicação entre tarefas em processos diferentes em computadores diferentes

FIXME
> texto explicando o código
> mostrar o código completo

FIXME
> explicar como foi executado
> mostrar as saídas do terminal
> mostrar as saídas do terminal

FIXME
> se houve problema na execução, enumerar os problemas e suas respectivas soluções

## Considerações finais

FIXME
> conseguiu implementar tudo e executar?
> qual foi o aprendizado nesse trabalho?
> alguma recomendação para próximos alunos?
