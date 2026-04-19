Du möchtest deinen Analysecode als HTML über GitHub öffentlich zeigen?

**So geht's**

1. Öffne in RStudio ein leeres rmarkdown (Rmd) Dokument. (RStudio > File > New File > R Markdown ... Es öffnet sich ein Fenster, klicke links unten auf 'Create empty document').
2. Beginne dieses leere Rmd Dokument hiermit:

````markdown
---
title: "Mein Titel"
author: "Mein Name"
date: "`r Sys.Date()`"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, message=FALSE)
```

## Hauptüberschrift {.tabset}

### Erster Tab

Dieser Code ist zur besseren Übersicht in Tabs unterteilt.

### Zweiter Tab

Code ...
````

3. Speichere das Rmd Dokument unter dem Namen index.Rmd
4. Wenn ein erster Entwurf des Rmd Dokuments fertig ist, klicke in RStudio auf den 'Knit' Button. Oder: File > Knit Document. Das Rmd wird nun in eine html Datei übersetzt, dessen Name 'index.html' sein wird. Öffne diese html Datei, um sie zu begutachten.
5. Eröffne entweder ein neues Repository auf deinem GitHub Account (siehe [README.md](https://github.com/mmiche/GitHubHowTo)) oder nutze ein bestehendes Repository.
6. Erzeuge auf deinem lokalen Rechner einen neuen Ordner namens docs (es ist wichtig, dass der Ordner so heisst, inkl. Kleinschreibung!).
7. Ziehe die index.html Datei in diesen docs Ordner.
8. Transportiere (siehe [hier](https://github.com/mmiche/GitHubHowTo) beschriebene 'Umsetzung 2') den docs Ordner in das GitHub Repository.
9. Sobald der docs Ordner mit der html Datei darin auf dem Repository ist, gehe innerhalb des Repository (also auf GitHub) auf 'Settings', innerhalb von Settings dann auf 'Pages' (im Inhaltsverzeichnis links auf der Webseite), dann bei 'Build and deployment' siehe 'Branch', klicke darunter den Button 'None' und wähle dann im Dropdown-Menü "main" aus. Es kommt ein weiterer Button zum Vorschein, wähle dort im Dropdown-Menü "docs" aus. Klicke zuletzt den Save Button. Die Webseite wird automatisch eingerichtet.
10. Warte bis die Webseite eingerichtet worden ist (je nach Grösse der html Datei kann dies etwas dauern, z.B. 30 Sekunden).

Wenn es fertig ist, dann kann es ungefähr so aussehen:
[https://mmiche.github.io/GitHubHowTo/](https://mmiche.github.io/GitHubHowTo/)

Formatierungshinweise:
[zu Rmd](https://yihui.org/rmarkdown/markdown-syntax) und
[zu md](https://www.markdownguide.org/basic-syntax/) Dateien.