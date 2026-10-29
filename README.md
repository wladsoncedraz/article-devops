# Observabilidade aplicada à cultura DevOps na Administração Pública

Artigo científico **em construção**, escrito em LaTeX no modelo da SBC (Sociedade
Brasileira de Computação), no Projeto Integrador da Pós-graduação em DevOps (IFMT).

## Como compilar

**No Overleaf (recomendado):**

1. Baixe este repositório em ZIP (*Code › Download ZIP*).
2. No [Overleaf](https://www.overleaf.com), crie um projeto a partir do ZIP
   (*New project › Existing project (.zip)*).
3. Compile com **pdfLaTeX**. O documento principal é `main.tex`; se o Overleaf não o
   detectar, escolha em *Menu › Main document*.

**Localmente** (TeX Live ou MiKTeX): `latexmk -pdf main.tex`

## Estrutura

| Caminho | Conteúdo |
|---|---|
| `main.tex` | documento principal |
| `secoes/` | uma seção por arquivo |
| `referencias/referencias.bib` | referências (BibTeX, estilo da SBC) |
| `config/` | pacotes, comandos, título e autores |
| `sbc-template.sty`, `sbc.bst` | modelo oficial da SBC |
| `secoes/06-prisma.tex` | lista de checagem PRISMA 2020: entra no fim do artigo como apêndice e também compila sozinho |

## Andamento

| Seção | Situação |
|---|---|
| Resumo | a fazer |
| 1. Introdução | a fazer |
| 2. Revisão bibliográfica | **em andamento**: 2.1 cultura DevOps, 2.2 observabilidade e 2.3 setor público escritas |
| 3. Metodologia | **em andamento**: critérios, registro da seleção e fontes complementares; detalhes da busca e triagem pendentes |
| 4. Resultados e discussão | **em andamento**: nove aprovados, três excluídos e dois textos não recuperados; fluxo completo e discussão pendentes |
| 5. Considerações finais | a fazer |

## Organização da revisão e da seleção

A seção 2 contém os três eixos teóricos: 2.1 Cultura DevOps e seus fundamentos,
2.2 Observabilidade de aplicações e infraestrutura e 2.3 DevOps e observabilidade
na Administração Pública. A numeração é definida pelos comandos LaTeX; os nomes
dos arquivos de apoio não a determinam.

Os critérios e o processo de seleção ficam na seção 3; os resultados da seleção
e suas tabelas ficam na seção 4. O resumo editorial de Gomes et al. (2025) é usado
como referência conceitual complementar, fora dos nove estudos aprovados.
Gomes e Kumar permanecem registrados como textos integrais não recuperados.

O checklist PRISMA acompanha essas localizações e identifica os relatos ainda
parciais. Os quantitativos por etapa e o fluxograma completo dependem da
consolidação dos registros de busca.

## Citações (estilo da SBC)

- `\cite{alongi2022}` → [Alongi et al. 2022]
- `Alongi et al. \citeano{alongi2022}` → Alongi et al. [2022]
