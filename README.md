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
| `secoes/06-prisma.tex` | lista de checagem PRISMA 2020 (documento separado, compila sozinho) |

## Andamento

| Seção | Situação |
|---|---|
| Resumo | a fazer |
| 1. Introdução | a fazer |
| 2. Revisão bibliográfica | **em andamento**: critérios de elegibilidade e avaliação dos estudos |
| 3. Metodologia | a fazer |
| 4. Resultados e discussão | a fazer |
| 5. Considerações finais | a fazer |

## Citações (estilo da SBC)

- `\cite{alongi2022}` → [Alongi et al. 2022]
- `Alongi et al. \citeano{alongi2022}` → Alongi et al. [2022]
