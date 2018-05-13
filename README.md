# opendata_bielefeld

Dieses Repository beinhaltet R-Skripte deren Inhalt eine Analyse der Datenlage zur Wohnsituation in Bielefeld ist. Den Ausgangspunkt für diese Betrachtung bildet der Datensatz zur Wohnlagekarte vom Opendata-Portal der Stadt Bielefeld (open-data.bielefeld.de).

In der Gruppe datascience-bielefeld.de beabsichtigen wir in den kommenden Meet Ups eine Anreicherung dieser Bewertung durch andere  öffentliche Datenquelle vorzunehmen. Pull Requests mit interessanten Ideen zur Anreicherung sind ebenso willkommen wie eine angeregte Diskussion der Möglichkeiten in den "Issues".

![Verteilung der Wohnqualität innerhalb der Stadtberzirke](/wohnlagenEDA_files/figure-html/unnamed-chunk-10-1.png) 

<hr/>

## Requirements

Zum Ausführen der Skript werden die R-Pakete:

  * tidyverse
  * ggmaps
  * sf

benötigt. Hinweis: Für das Plotten der sf-Objekte benötigt man eine aktuelle Version der ggplot2-Library, die zum Erstellungszeitpunkt des Skripts noch nicht über das CRAN installiert werden kann, sondern beispielsweise mit Hilfe der *devtools* installiert werden muss.
