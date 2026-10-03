---
name: estudar-curso
description: Lê as transcrições/materiais de um curso em conhecimento/cursos/ e extrai frameworks, fórmulas e princípios acionáveis para conhecimento/resumos/. Use quando o usuário adicionar conteúdo novo de curso ou pedir "estuda o curso X".
---

# Estudar curso

1. Liste os arquivos em `conhecimento/cursos/<tema>/` (pergunte qual curso, se não estiver claro).
2. Leia todos os arquivos do curso. Se forem muitos, processe por módulo.
3. Crie/atualize `conhecimento/resumos/<nome-do-curso>.md` com:

```markdown
# <Nome do curso> — resumo acionável
Fonte: conhecimento/cursos/<tema>/...

## Frameworks e fórmulas
### <Nome do framework> (Módulo X, Aula Y)
- O que é (1–2 linhas)
- Passo a passo
- Exemplo do curso
- **Como aplicar no TikTok Shop / produto físico**: (adaptação concreta)

## Princípios e regras
- ...

## Modelos prontos (headlines, ganchos, CTAs, estruturas)
- ...

## Erros que o curso manda evitar
- ...
```

4. Atualize `conhecimento/resumos/INDICE.md`: uma linha por framework com nome, curso e quando usar
   (ex.: "PAS — Copy — gancho de dor para vídeo de 15s"). É esse índice que as outras skills consultam primeiro.
5. Seja fiel ao curso: não invente frameworks que não estão no material. Onde adaptar, marque como "adaptação".
6. Ao final, mostre ao usuário os 5–10 frameworks mais úteis para vender produto físico no TikTok.
