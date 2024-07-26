# Template für Reviews von Seminararbeiten

## Latexmk

Wenn Sie einen LaTeX-Editor mit eingebauter Projekt-Verwaltung nutzen, müssen Sie sich über den Kompilierungs-Vorgang
normalerweise keine Gedanken machen, da der Editor automatisch die benötigten Werkzeuge in der richtigen Reihenfolge aufruft.

Eine Möglichkeit, auch außerhalb eines solchen Editors in den Genuss einer automatischen Kompilierung zukommen,
bietet das Tool [Latexmk](http://mg.readthedocs.io/latexmk.html).
Dieses Werkzeug ist in allen großen LaTeX-Distributionen enthalten (insbesondere auch in MiKTeX und TeX Live für Windows).

Die Vorlage enthält bereits eine Konfigurationsdatei für Latexmk, so dass durch den folgenden Aufruf automatisch
das fertige PDF (inkl. der Literatur-Referenzen, s.o.) erstellt werden kann:

    $ latexmk -pdf Review

Ebenso kann Latexmk die im Verlauf der Erstellung des PDF produzierten Dateien durch Angabe der Option ``-C`` wieder aufräumen:

    $ latexmk -C
