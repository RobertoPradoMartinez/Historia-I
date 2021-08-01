# Apuntes de Historia da Música I

[TOC]

# Presentación

Estes apuntes de Historia da Música están orientados para centros que imparten Ensinanzas Profesionais de Música correspondentes ao 4º curso de Grao Profesional.

# Estrutura e contidos

Os apuntes están redactados íntegramente en `markdown`empregando o IDE `RStudio` dacordo co modelo `oxthesis`.

Están estruturados seguindo como referencia básica a Programación didáctica de Historia da Música do CMUS de Viveiro, tendo en conta igualmente as diferentes programacións de Historia da Música dos CMUS de Ourense e Pontevedra.

## Estrutura principal

Traballando co `markdown` a estrutura dos arquivos é a seguinte:

```markdown
.
+-- index.Rmd
+-- _bookdown.yml
+-- 00-intro.Rmd
+-- 01-unidade-1.Rmd
+-- 02-unidade-02.Rmd
+-- 03-unidade-03.Rmd
+-- 04-unidade-04.Rmd
+-- 05-unidade-05.Rmd
+-- 06-unidade-06.Rmd
+-- 07-unidade-07.Rmd
+-- 08-unidade-08.Rmd
+-- 09-unidade-09.Rmd
+-- 10-unidade-10.Rmd
|   ...
+-- front-and-back-matter
|   +-- _abstract.Rmd
|   +-- 98-appendices.Rmd
|   ...
+-- bibliography
|   +-- references.bib
|   ...
+-- figures
|   ...
+-- docs
|   +-- _main.pdf
|   ...
+-- scripts_and_filters
|   +-- knit-functions.R
|   ...
+-- templates
|   +-- template.tex
|   ...
+-- unidades-didacticas
|   +-- unidade-00
|   +-- unidade-01
|   +-- unidade-02
|   +-- unidade-03
|   +-- unidade-04
|   +-- unidade-05
|   +-- unidade-06
|   +-- unidade-07
|   +-- unidade-08
|   +-- unidade-09
|   +-- unidade-10
|   ...
```

## Compilación

Para compilar o proxecto: 
- facemos `knitr` sobre o arquivo index.Rmd

**Importante:**
Non modificar a estrutura do proxecto para evitar erros de compilación.  

Como principal novidade, as unidades están estruturadas en cartafoles independientes segundo a unidade de que se trate para facilitar a distribución dos diferentes temas.
