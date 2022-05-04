# Contêiner

## Status

Aceito

## Context

O ambiente de desenvlvimento pode ter diferenças muito grandes para o ambiente produtivo. Minimizar essas diferenças significa não correr riscos no momento do deploy. Além disso, ficar refém da capacidade de um servidor com pouca escalabilidade pode tornar uma aplicação instável.

## Decision

Todas as aplicações e bancos de dados do sistema Otre devem ser feitos em contêineres.

## Consequences

Com aplicações conteinerizadas, o desenvolvimento fica mais fácil, pois é possível simular o ambiente de produção e, desta forma, evitar surpresas no deploy, auxilia no deploy de microserviços, requer um menor conhecimento de infraestrutura e torna as aplicações mais resilientes, uma vez que elas auxiliam na escalabilidade horizontal dos microserviços.
