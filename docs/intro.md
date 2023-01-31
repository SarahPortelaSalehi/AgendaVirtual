---
sidebar_position: 1
---
# Documentação Agenda Virtual

## Lista de requisitos funcionais:

UC1 - Fazer login.

UC2 - Deslogar.

UC3 - Manter usuário.

UC4 - Manter evento.

UC5 - Notificar evento.

UC6 - Enviar e-mail.

UC7 - Visualizar dia.

UC8 - Visualizar calendário.

UC9 - Trocar mês.

## Lista de requisitos não-funcionais:

- O sistema deve ser Web acessado via navegador
- O desenvolvimento deve ser na linguagem JavaScript e com o banco de dados SQLite
- Divisão arquitetural do sistema em camadas para desacoplamento

## Regras de negócio:

- Para entrar no sistema o e-mail cadastrado deve ser válido e a senha deve ter no mínimo 6 caracteres
- Eventos cadastrados são notificados por e-mail 24hrs antes
- Só poderá haver um evento por data/hora
