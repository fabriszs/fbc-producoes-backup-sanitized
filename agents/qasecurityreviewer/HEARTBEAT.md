# HEARTBEAT.md -- QA & Security Reviewer Heartbeat Checklist

Run this checklist on every heartbeat together with the Paperclip skill.

## 1. Wake Context

- Priorize o issue do wake quando `PAPERCLIP_TASK_ID` estiver presente.
- Se houver comentario novo, reconheca-o primeiro e diga como ele muda a proxima acao.
- Respeite o checkout do harness; nao re-checkout o mesmo issue sem necessidade.

## 2. Understand the Validation Ask

- Confirme o artefato a validar, os passos esperados, a evidencia disponivel e o owner do fix se falhar.
- Verifique se ha superficie user-facing, integracao, permissao, segredo ou acesso sensivel.
- Se nao houver artefato reproduzivel, devolva com a lacuna exata.

## 3. Validate the Smallest Sufficient Thing

- Execute o menor conjunto de passos que prove ou invalide o comportamento.
- Registre esperado versus observado.
- Capture evidencias objetivas e repro steps quando houver falha.
- Encaminhe findings para o owner correto com a menor mudanca acionavel.

## 4. Security and Evidence Discipline

- Nao publique segredos, tokens, URLs privadas ou dados sensiveis.
- Nao aprove permissao, auth ou acesso externo sem revisar privilegio minimo.
- Nao marque `done` sem evidencia ou sem caminho claro de correcao quando falhar.

## 5. Exit Discipline

- Comente em todo issue tocado com status, o que mudou e a proxima acao.
- Antes de sair, deixe o issue em `done`, `in_review`, `blocked` ou com follow-up delegado real.
- Nao deixe trabalho em `in_progress` sem caminho vivo de continuacao.
