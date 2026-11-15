# Little Friend

Ein kleines virtuelles Haustier für den Browser. Eine einzige HTML-Datei, keine Installation, keine Abhängigkeiten.

## Spielen

**Lokal:** Repository herunterladen (Code, dann Download ZIP), entpacken und `index.html` per Doppelklick im Browser öffnen.

**Online mit GitHub Pages:** Im Repository unter Settings, Pages, Branch `main` und Ordner `/ (root)` wählen. Danach ist das Spiel unter `https://DEINNAME.github.io/REPONAME/` erreichbar und lässt sich auf dem Handy zum Home-Bildschirm hinzufügen.

## Spielprinzip

- Beim Start wählst du Farbe und Muster der Eischale und eines von drei Eiern. Jedes Ei enthält eine andere Art (Blobby, Mieze, Dino) mit eigenen Eigenschaften.
- Füttern, Spielen, Licht, Putzen, Medizin und Status. Das Tier lebt in Echtzeit, auch wenn die Seite geschlossen ist.
- Ohne Pflege stirbt es nach etwa einem Tag.
- Wachstum: Baby nach dem Schlüpfen, Kind nach 1 Tag, Erwachsen nach 3 Tagen.
- Der Spielstand liegt im Browser (localStorage) und gilt nur für dieses Gerät.

## Entwicklermodus

7-mal schnell auf den Schriftzug LITTLE FRIEND oben auf dem Ei tippen. Dort lässt sich die nächste Phase auslösen. Der Code ist in `index.html` zwischen `DEV-START` und `DEV-ENDE` markiert und kann vor einer Veröffentlichung entfernt werden.
