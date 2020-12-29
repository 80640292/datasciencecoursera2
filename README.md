# datasciencecoursera2
## This is a markdown file
---
título: "HelloWorld"
autor: "Nelson"
fecha: "29/12/2020"
salida: html_document
---

`` `{r configuración, incluir = FALSO}
knitr :: opts_chunk $ set (echo = TRUE)
''

## R Markdown
## Este es un archivo de rebajas ##

Este es un documento de R Markdown. Markdown es una sintaxis de formato simple para la creación de documentos HTML, PDF y MS Word. Para obtener más detalles sobre el uso de R Markdown, consulte <http://rmarkdown.rstudio.com>.

Al hacer clic en el botón ** Tejer **, se generará un documento que incluye tanto el contenido como la salida de cualquier fragmento de código R incrustado dentro del documento. Puede incrustar un fragmento de código R como este:

`` `{r coches}
resumen (coches)
''

## Incluyendo parcelas

También puede incrustar gráficos, por ejemplo:

`` `{r presión, eco = FALSO}
trama (presión)
''

Tenga en cuenta que el parámetro `echo = FALSE` se agregó al fragmento de código para evitar la impresión del código R que generó el gráfico.
