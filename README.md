# GitHubHowTo

**Ziel**: Studierende, ohne Kenntnis von GitHub, sollen anhand unten stehender Auflistung ihren Datenanalysecode, z.B. ihr/e R-Skript/e, über GitHub öffentlich teilen können.

**Relevanz**: Alle Studierenden, die eine Masterarbeit abgeben, müssen im Normalfall auch ihren Datenanalysecode abgeben. Es bietet sich an, ihn öffentlich über GitHub zu teilen, anstatt ihn zum Beispiel als separates Dokument per Mail schicken zu müssen.

**Vorschau**: Wenn alles erfolgreich umgesetzt worden ist, dann braucht der/die Studierende lediglich den Online-Link zum eigenen GitHub Repository zu kopieren und in die Masterarbeit einsetzen. Der/die Leser/in kann dann innerhalb der Masterarbeit auf den Link klicken, um auf das **öffentliche**(!) Repository zugreifen und von dort das Dokument mit dem Analysecode runterladen zu können.

**Zweiteilige Umsetzung des Ziels**:

1. Minimalvariante. Empfohlen, wenn Studierende sich sicher sind, dass die Masterarbeit die letzte wissenschaftliche Arbeit ihres Lebens sein soll.
2. Etwas umfangreichere Variante. Empfohlen, wenn Studierende es in Betracht ziehen, weitere wissenschaftliche Arbeiten zu produzieren und vielleicht zu publizieren. Es wird vermutlich bzw. hoffentlich so kommen, dass in Zukunft open science die Norm wissenschaftlichen Publizierens sein wird. Hierzu zählt auch das öffentliche Teilen des Analysecodes, unabhängig davon, ob der Datensatz ebenfalls publiziert wird.

**Generelle Bedingung für die Umsetzung**: Einen eigenen Account bei GitHub besitzen, siehe [hier](https://docs.github.com/de/get-started/start-your-journey/creating-an-account-on-github).

**Zuerst einloggen**: Sofern ein GitHub Account existiert, bitte einloggen, um auf der Begrüssungsseite zu sein, auf der oben 'Home' steht.

**Umsetzung 1**:

1. Klicke New (siehe green button auf der Begrüssungsseite), um neues Repository zu erstellen.
2. Neues Browserfenster öffnet sich. Mache folgende Angaben:
- Welchen Namen soll das Repository haben, z.B. MasterThesisCode
- zusätzliche kurze Erklärung des Zwecks
- Radio button 'Public'? Wähle: Ja.
- Lizenz (z.B. MIT). Lizenz wichtig, wenn es wahrscheinlich ist, dass Dritte euren Code oder Teile davon kopieren und nutzen werden. Die Lizenz sagt, ob und wie der/die Urheber/in des Code zitiert werden müsste.
- README. Sehr empfehlenswert; kann jederzeit editiert werden. Es ist eine Markdown Datei, siehe [hier](https://www.markdownguide.org/basic-syntax/) für Formatierungshinweise.
3. Dokument/e (und/oder Ordner), die öffentlich geteilt werden sollen, müssen auf eigenem Rechner parat sein, z.B. masterThesisCode.R.
4. Im erstelltem GitHub Repository ist ein button namens Add file (klicken), wähle Upload files, dann eigenes R-Skript per drag & drop ablegen.
5. Zuletzt (siehe bottom of GitHub website) klicke: 'Commit changes'.

**Umsetzung 2**:

Bedingung: Es muss die Software GitHub Desktop (GHD) installiert werden, siehe [hier](https://docs.github.com/de/desktop/overview/getting-started-with-github-desktop). Auf der Webseite, siehe Teil 1 'Installieren ...'. Hingegen ist Teil 2 ('Konfigurieren ...') nicht wichtig, um mit folgenden Punkten weitermachen zu können.

1. Öffne GHD.
2. Gehe im GHD Menü auf File und dann auf New Repository. Es öffnet sich ein separates Fenster in GHD.
3. Fülle folgende Felder aus:
- Name (ich nenne es z.B. meinProjekt)
- Local Path: Gebe Pfad an, wo das Repository (also der Ordner) auf dem lokalen Rechner erzeugt werden soll.
- Klicke die 'Initialize ... README' Box an.
- Belasse sowohl Git Ignore und License auf None
- Zuletzt klicke Create Repository button.
Ergebnis: Nun ist der Ordner meinProjekt am gewählten Zielort auf meinem Rechner erzeugt worden. Darin ist eine Datei enthalten, README.md
4. Klicke in GHD auf den Button 'Publish repository'. Es öffnet sich ein separates Fenster in GHD.
5. Belasse die Auswahl 'GitHub.com' und den Namen. Falls gewünscht, trage etwas in das Description Feld. Damit das Repository Public ist, entferne den Haken aus der Tick box 'Keep this code private'. Zuletzt: Klicke Button 'Publish repository'.
6. Alle Änderungen im Verzeichnis 'meinProjekt' auf meinem Rechner, d.h. alle Änderungen in jedem dort befindlichen Dokument werden erkannt. Die geänderten Dokumente können nun über GHD zum GitHub repository transportiert (siehe 'Push origin' in GHD) werden.

Ende beider Umsetzungen. Ab hier heisst es: Ausprobieren. Viel Spass und Erfolg!