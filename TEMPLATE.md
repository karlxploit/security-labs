# [Plataforma] Nome do lab / room

| | |
|---|---|
| **Plataforma** | PortSwigger / TryHackMe / HTB / CTF |
| **Categoria** | ex.: SQL Injection |
| **Dificuldade** | Apprentice / Easy / Medium |
| **Data** | AAAA-MM-DD |

## Objetivo
O que o lab pede, em uma ou duas frases.

## Reconhecimento
O que observei antes de atacar: parâmetros, respostas, comportamento da aplicação.

## Exploração
Passo a passo, com as requisições relevantes (Burp, curl) e o porquê de cada tentativa, inclusive as que falharam.

```http
GET /filter?category=... HTTP/1.1
```

## Causa raiz
Por que a vulnerabilidade existe (ex.: concatenação de entrada na query SQL).

## Correção
Como um desenvolvedor resolveria (ex.: prepared statements, validação, menor privilégio).

## Aprendizados
O que levo para o próximo lab.
