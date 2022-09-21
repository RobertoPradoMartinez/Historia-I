# Apuntes de Historia da Música I

[TOC]

# Presentación

Estes apuntes de Historia da Música están orientados para centros que imparten Ensinanzas Profesionais de Música correspondentes ao 4º curso de Grao Profesional.

# Estrutura e contidos

Os apuntes están redactados íntegramente en `markdown`empregando o IDE `RStudio` dacordo co modelo `oxthesis`.

Unha edición recente para o curso 2022/2023 en `LaTeX`, atópase na carpeta `HM1-2023-Temario-LaTeX` na que se definen entrnos máis personalizados para impresión pdf. 

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
## Dependencias

Para compilar o traballo, é necesario seguir a guía da plantilla "oxforndown" sobre a que se basea este traballo, no arquivo README_OLD.md

### Paquetes de R necesarios

Os paquetes necesarios, son os seguintes: `rmarkdown`, `bookdown`, `tidyverse`, `kableExtra`, and `here`

Cando se instalan algún deles, presenta erros por dependencias incumplidas na distribución Linux.  
É preciso seguir os pasos detallados a continuación:

1. PASO 1. Instalar R e algunhas dependencias básicas.

  $ sudo apt update
  $ sudo apt -y install r-base gdebi-core

2.  PASO 2. Instalar a última versión do RStudio.
3.  PASO 3. Descomprimir o RStudio.  
  Na carpeta onde descargamos o RStudio, executamos:

  $ sudo gdebi rstudio-1.2.5019-amd64.deb

4. PASO 4. Abrimos o RStudio
  Executamos os seguintes comandos para instalar as dependencias:
  
  sudo apt-get install libcurl4-openssl-dev
  sudo apt-get install libssl-dev
  sudo apt-get install libxml2-dev
  
5. PASO 5. Refrescamos a distribución Linux.  

  sudo apt update
  sudo apt upgrade
  sudo apt autoremove

## Compilación

Para compilar o proxecto: 
- facemos `knitr` sobre o arquivo index.Rmd

**Importante:**
Non modificar a estrutura do proxecto para evitar erros de compilación.  

Como principal novidade, as unidades están estruturadas en cartafoles independientes segundo a unidade de que se trate para facilitar a distribución dos diferentes temas.

## Tradución ao galego

Pendiente de traducir da versión en Castelán ao Galego.
