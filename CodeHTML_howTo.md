Du möchtest deinen Analysecode als HTML über GitHub öffentlich zeigen?

**So geht's**

1. Öffne in RStudio ein leeres rmarkdown (Rmd) Dokument. (RStudio > File > New File > R Markdown ... Es öffnet sich ein Fenster, klicke links unten auf 'Create empty document').
2. Beginne dieses leere Rmd Dokument hiermit:

``` r
---
title: "Mein Titel"
author: "Mein Name"
date: "`r Sys.Date()`"
output: html
---

## Hauptüberschrift {.tabset}

### Erster Tab

Dieser Code ist zur besseren Übersicht in Tabs unterteilt.

```

3. Speichere das Rmd Dokument unter dem Namen index.Rmd
4. Wenn ein erster Entwurf fertig ist, klicke in RStudio auf den 'Knit' Button oder: File > Knit Document. Das Rmd wird nun in eine html Datei übersetzt, dessen Name 'index.html' sein wird.