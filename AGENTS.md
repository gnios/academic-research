# academic-research

Projeto de pesquisa acadêmica com foco no Brasil.

## Convenções

- **Idioma**: português brasileiro (pt-BR) por padrão; inglês apenas quando o veículo de destino exigir.
- **Normas**: ABNT — NBR 14724 (estrutura), NBR 6023 (referências), NBR 10520 (citações), NBR 6022 (artigos).
- **Formato de escrita**: LaTeX com [abnTeX2](https://www.abntex.net.br/).
- **Citações**: nunca inventar referências. Toda citação deve vir de fonte verificável (SciELO, OpenAlex, Crossref, Periódicos CAPES, BDTD, DOI). Marcar explicitamente o que não puder ser verificado.

## Estrutura

- `artigos/` — manuscritos em LaTeX (abnTeX2)
- `referencias/` — arquivos `.bib` e exportações de gerenciadores (Zotero etc.)
- `fichamentos/` — fichamentos de leitura
- `notas/` — notas de pesquisa e rascunhos

## Skills instaladas (`.agents/skills`, `.devin/skills`, `.windsurf/skills`)

| Skill | Uso |
|---|---|
| `pesquisador-br` | Fluxo completo de pesquisa BR: ABNT, Qualis CAPES, SciELO, BDTD, metodologia |
| `tcc-abnt` | Pipeline focado em TCC de graduação (NBR 14724) |
| `busca-academica` | Busca bibliográfica (OpenAlex, SciELO, DOAJ, Crossref, Semantic Scholar) + exportação CSV/BibTeX |
| `escritaacademica` | Escrita e revisão acadêmica em pt-BR (Humanidades/Ciências Sociais) |
| `fichamento-academico` | Fichamentos densos e rastreáveis de artigos/livros |
| `parecerista-academico` | Avaliação de manuscritos e respostas a pareceristas |
| `melhorar-prompts-academicos` | Refino de prompts para tarefas acadêmicas |
| `literature-search` | Busca de literatura com scripts (OpenAlex, Crossref, arXiv) |
| `literature-review` | Workflow de revisão de literatura |
| `citation-management` | Colheita e validação de citações |
| `latex-academic-br` | Workflow abnTeX2: estrutura, build PDF/DOCX, CI |

Gerenciadas via [skills CLI](https://skills.sh/): `npx skills list`, `npx skills update`, `npx skills experimental_install` (restaura a partir de `skills-lock.json`).
