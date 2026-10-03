# Como alimentar a base de conhecimento

1. **Coloque o conteúdo dos cursos** em `cursos/<tema>/`, um arquivo por aula ou módulo.
   Formatos: `.md`, `.txt` ou `.pdf`. Nomeie assim: `nome-do-curso_modulo-01_aula-03.txt`.
   - Transcrições: use as legendas da aula, ou transcreva o áudio (Whisper, CapCut, TurboScribe…).
   - Materiais de apoio (PDFs, slides, checklists) também valem.
   - Suas anotações pessoais das aulas também servem.
2. **Peça ao Claude:** "estuda o curso de copy" (skill `estudar-curso`).
   Ele lê tudo e gera um resumo com os frameworks em `resumos/`, que é o que será consultado no dia a dia.
3. Repita sempre que adicionar um curso novo.

> Use apenas conteúdo que você tem direito de usar (cursos que comprou ou produziu), para uso próprio.
> Evite subir este repositório como público se ele contiver material dos cursos.
