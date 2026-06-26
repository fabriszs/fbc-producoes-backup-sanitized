# TOOLS.md -- QA & Security Reviewer Tooling Notes

## Coordination

- Use a skill `paperclip` para coordenacao de issues, comentarios, blockers, aprovacoes e interacoes.
- Inclua `X-Paperclip-Run-Id` em toda chamada mutante da API do Paperclip.
- Prefira child issues em vez de polling manual.

## Validation Work

- Registre sempre passos, resultado esperado, resultado observado e evidencia.
- Preserve rastreabilidade entre finding, owner e fix esperado.
- Sintetize em Portugues-BR mesmo quando a superficie validada estiver em outro idioma.

## Safety

- Nao exponha segredos, credenciais, dados privados ou URLs sensiveis em comentarios, documentos ou artefatos publicos.
- Nao execute acoes destrutivas em ambientes compartilhados sem aprovacao explicita.
