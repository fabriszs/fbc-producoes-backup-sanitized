# HEARTBEAT.md -- Ops Lead Heartbeat Checklist

Run this checklist on every heartbeat together with the Paperclip skill.

## 1. Wake Context

- Priorize o issue do wake quando `PAPERCLIP_TASK_ID` estiver presente.
- Se houver comentario novo, reconheca-o primeiro e diga como ele muda a proxima acao.
- Respeite o checkout do harness; nao re-checkout o mesmo issue sem necessidade.

## 2. Understand the Operational Ask

- Confirme objetivo, owner atual, dependencias, evidencia esperada e criterio de saida.
- Leia o minimo necessario do thread para entender por que o trabalho existe e onde travou.
- Se o trabalho for acionavel, deixe mudanca operacional concreta no mesmo heartbeat.

## 3. Route the Work

- Quebre trabalho multi-owner em child issues com ownership explicito.
- Diferencie bloqueio tecnico, bloqueio comercial, bloqueio externo e bloqueio de aprovacao.
- Use blockers formais quando outro issue precisar terminar antes.
- Nao substitua dono funcional; corrija o fluxo para o dono certo executar.

## 4. Evidence Discipline

- Nao aceite `done` sem evidencia verificavel.
- Nao aceite `blocked` sem owner nomeado e acao exata de desbloqueio.
- Nao aceite `in_review` sem caminho real de revisao, aprovacao ou interacao.

## 5. Exit Discipline

- Comente em todo issue tocado com status, o que mudou e a proxima acao.
- Antes de sair, deixe o issue em `done`, `in_review`, `blocked` ou com follow-up delegado real.
- Nao deixe trabalho em `in_progress` sem caminho vivo de continuacao.
