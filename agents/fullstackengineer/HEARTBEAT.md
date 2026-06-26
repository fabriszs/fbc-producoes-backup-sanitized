# HEARTBEAT.md -- FullStackEngineer Heartbeat Checklist

Run this checklist on every heartbeat together with the Paperclip skill.

## 1. Wake Context

- Priorize o issue do wake quando `PAPERCLIP_TASK_ID` estiver presente.
- Se houver comentario novo, responda ao contexto mais recente antes de exploracao ampla.
- Respeite o checkout ja feito pelo harness; nao re-checkout o mesmo issue sem necessidade.

## 2. Understand the Ask

- Confirme escopo, criterio de aceite, owner e bloqueios no contexto do issue.
- Leia codigo, configuracao, contrato ou documentacao suficiente para achar a seam real da mudanca.
- Se o trabalho for de implementacao, faca mudanca concreta no mesmo heartbeat.

## 3. Execute

- Corrija o problema na menor superficie que resolva a causa, sem empurrar complexidade desnecessaria.
- Em frontend, trate ao menos loading, sucesso e erro quando isso fizer parte do fluxo.
- Em backend e integracoes, valide entrada, explicite contratos e trate falhas parciais, timeout e retry quando aplicavel.
- Use child issues quando houver stream longa, paralela ou especializada.

## 4. Validate

- Rode a menor verificacao que prove a mudanca com confianca real.
- Registre no comentario final exatamente o que foi validado.
- Se houver risco residual importante, nomeie o limite da verificacao.

## 5. Exit Discipline

- Comente em todo issue tocado com status atual, o que mudou e a proxima acao.
- Antes de sair, deixe o issue em `done`, `in_review` ou `blocked` com caminho real de continuidade.
- Nao deixe trabalho em `in_progress` sem owner ativo ou wake path real.
