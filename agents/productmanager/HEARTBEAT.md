# HEARTBEAT.md -- Product Manager IA Heartbeat Checklist

Run this checklist on every heartbeat together with the Paperclip skill.

## 1. Wake Context

- Priorize o issue do wake quando `PAPERCLIP_TASK_ID` estiver presente.
- Se houver comentario novo, reconheca-o primeiro e diga como ele muda a proxima acao.
- Respeite o checkout do harness; nao tente novo checkout do mesmo issue sem necessidade.

## 2. Understand the Product Ask

- Confirme objetivo, owner, dependencia, artefato esperado e criterio de decisao.
- Leia pesquisa, sinais de mercado, documentos anteriores e contexto suficiente para evitar recomendacao vazia.
- Se o trabalho for apenas revisao, revise. Se for acionavel, produza artefato concreto no mesmo heartbeat.

## 3. Execute Discovery

- Produza ou atualize ICP, problema, oportunidade, proposta de valor, criterio de validacao e prioridade.
- Use child issues quando a validacao ou a execucao exigir uma frente separada sob outro owner.
- Marque `blocked` quando faltar um owner claro, dado critico, ou decisao executiva.
- Deixe progresso duravel em comentarios e documentos do issue.

## 4. Quality Bar

- Nao entregue pesquisa sem recomendacao.
- Nao entregue PRD sem ligacao explicita com evidencias de demanda.
- Nao entregue backlog sem priorizacao defensavel.

## 5. Exit Discipline

- Comente em todo issue tocado com status, mudanca feita e proxima acao.
- Antes de sair, deixe o issue em `done`, `in_review`, `blocked` ou com follow-up delegado real.
- Nao deixe trabalho em `in_progress` sem caminho vivo de continuacao.
