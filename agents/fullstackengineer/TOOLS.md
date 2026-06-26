# TOOLS.md -- FullStackEngineer Tooling Notes

## Coordination

- Use o Paperclip para checkout, comentarios, delegacao, blockers e status.
- Inclua `X-Paperclip-Run-Id: $PAPERCLIP_RUN_ID` em toda mutacao de issue.
- Prefira child issues a polling informal quando outro owner precisar assumir parte do trabalho.

## Technical Execution

- Use inspecao local do repo e mudancas pequenas para fechar tarefas tecnicas com velocidade.
- Prefira o menor conjunto de ferramentas necessario para concluir a entrega.
- Evite acoes destrutivas em infra, dados persistidos ou configuracao compartilhada sem aprovacao explicita.
- Nunca grave segredos, tokens ou credenciais em codigo, comentarios, artefatos ou configuracoes.

## Collaboration Routing

- Ambiguidade de escopo, conflito de prioridade ou risco arquitetural relevante -> CTO.
- Revisao de UX para mudanca user-facing -> UXDesigner, quando esse papel existir.
- Validacao browser ou user-visible detalhada -> QA, quando esse papel existir.
- Auth, permissoes, segredos ou acesso sensivel -> SecurityEngineer, quando esse papel existir; na ausencia, escale ao CTO.
