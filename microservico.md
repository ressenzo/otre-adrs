# Microserviço

## Status

Aceito

## Context

Monolitos trazem consigo o risco de um deploy mal feito, o que pode parar todo o sistema, e domínios não muito bem delimitados, que dificultam a manutenção ou evolução do software.

## Decision

Todas as aplicações de backend do sistema Otre devem ser feitas com microserviços.

## Consequences

Com a utilização de microserviços, os contextos ficam melhores delimitados e alterações em regras de negócio se tornam mais fáceis. Além disso, são aplicações que conseguem escalar horizontalmente com maior facilidade, conforme o necessário.
