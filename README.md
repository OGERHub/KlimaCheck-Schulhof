# Schulhof KlimaLab

[**Schulhof KlimaLab**](https://ogerhub.github.io/KlimaCheck-Schulhof/) ist ein vereinfachtes, physikalisch basiertes Vergleichsmodell für das Klima auf einem Schulhof. Es zeigt, wie Flächen, Gebäude, Bäume, Schatten, Dächer und Fassadenbegrünung auf Wärme, Abkühlung und Hitzelast wirken.

Das Modell ist **kein Vorhersagemodell** für reale Temperaturen. Es dient dazu, Unterschiede zwischen Varianten sichtbar zu machen und Maßnahmen vergleichend zu untersuchen.

## Ziel des Modells

Mit dem Modell lassen sich Fragen untersuchen wie:

-   Wo ist es auf dem Schulhof besonders heiß?
-   Welche Flächen heizen sich stark auf?
-   Wie unterscheiden sich Asphalt, Pflaster, Sand, Sportbelag und Rasen?
-   Welche Wirkung haben Bäume, Hecken und Schatten?
-   Was bringen Gründächer oder begrünte Fassaden?
-   Wie verändert sich die Hitzelast durch eine Maßnahme?

## Modellidee

Der Schulhof besteht aus vielen Rasterfeldern. Jedes Feld besitzt eine Bodenart, zum Beispiel Asphalt, Pflaster, Sand, Sportbelag oder Rasen. Zusätzlich können Objekte gesetzt werden, etwa Bäume, Hecken oder Gebäude.

Das Modell berechnet unter anderem:

-   Materialien und Elemente
-   Schattenwirkung
-   Oberflächentemperatur
-   lokale Lufttemperatur
-   aktuelle Hitzelast
-   aufsummierte Hitzelast während der Schulzeit
-   Veränderung der Hitzelast im Vorher/Nachher-Vergleich

Die Schulzeit wird im Modell von **07:00 bis 16:00 Uhr** betrachtet.

![Konzeptidee KlimaLab](images/model-3d_neu.png)

## Bedienung

Mit **Modellstart /-reset** wird das Modell in den Ausgangszustand zurückgesetzt.

Mit **Versuch starten** läuft ein Tagesverlauf durch. Dabei werden Temperatur, Schatten und Hitzelast fortgeschrieben.

Mit **Karte bearbeiten** können Flächen und Objekte verändert werden. Über das Auswahlfeld **Element** lassen sich zum Beispiel Asphalt, Pflaster, Rasen, Sand, Sportbelag, Bäume, Hecken, Gebäude oder Messstationen setzen.

Mit **Karte aktualisieren** wird die aktuelle Ansicht neu berechnet.

Mit **Legende an/aus** wird die passende Kartenlegende ein- oder ausgeblendet.

## Kartenansichten

Das Modell bietet mehrere Kartenansichten:

-   **Materialien & Elemente**: zeigt die räumliche Struktur des Schulhofs.
-   **Schatten aktuell**: zeigt aktuelle Verschattung.
-   **Oberflächentemperatur aktuell**: zeigt die Temperatur der Oberflächen.
-   **Lufttemperatur aktuell**: zeigt die lokale Lufttemperatur.
-   **Hitzelast aktuell**: zeigt die momentane thermische Belastung.
-   **Hitzelast Schulzeit**: zeigt die aufsummierte Belastung während der Schulzeit.
-   **Hitzelast Änderung**: zeigt die Veränderung gegenüber einem Vorher-Zustand.

## Vorher/Nachher-Vergleich

Der Vorher/Nachher-Vergleich ist der zentrale Workflow des Modells.

Ablauf:

1.  **Modellstart /-reset** drücken.
2.  **Versuch starten** und den ersten Tageslauf vollständig durchführen.
3.  **Massnahme aktivieren** drücken.
4.  Maßnahme setzen, zum Beispiel Bäume pflanzen, Rasen anlegen oder Gebäude begrünen.
5.  **Versuch starten** erneut ausführen.
6.  Mit **Gebiet-auswählen** eine Aufenthaltsfläche markieren.
7.  Mit **Auswahlgebiet vergleichen** die Veränderung auswerten.

Der Vergleich zeigt unter anderem, ob kritische Hitzelastklassen kleiner werden und wie viel Fläche in niedrigere Belastungsklassen wechselt.

## Auswertungen

Das Diagramm **Stationen Temperatur** zeigt Temperaturverläufe an gesetzten Messstationen. Linien zeigen die Lufttemperatur, Punkte zeigen die Oberflächentemperatur. Die graue Kurve zeigt den allgemeinen Modellantrieb.

Das Feld **Hitzelast je Klasse für alle Aufenthaltsflächen** zeigt die Verteilung der Aufenthaltsflächen auf fünf Klassen:

-   blau: \< 1 h
-   grün: 1–2.5 h
-   gelb: 2.5–5 h
-   orange: 5–6.5 h
-   rot: \> 6.5 h

Bewertet werden nur Aufenthaltsflächen wie Asphalt, Pflaster, Offenpflaster, Rasen, Sportbelag und Sand.

## Einsatzbereich

Das Modell eignet sich für Unterricht, Workshops und didaktische Vergleiche zu Schulhofklima, Hitzebelastung und klimaangepasster Gestaltung.

Sinnvolle Aussagen sind zum Beispiel:

-   Diese Maßnahme reduziert die Hitzelast stärker als eine andere.
-   Ein Baum verbessert die Situation an dieser Stelle.
-   Schatten senkt die Belastung deutlich.
-   Asphalt ist problematischer als Rasen oder Offenpflaster.

Nicht sinnvoll ist die Nutzung als exakte Wetter- oder Temperaturvorhersage. Die Hitzelast ist kein medizinischer Grenzwert und ersetzt keine Fachplanung.

## Version

Version 1.0

## Lizenz

© 2026 Rieke Ammoneit und Chris Reudenbach

Dieses Material steht unter der Lizenz **Creative Commons Attribution 4.0 International (CC BY 4.0)**. Es darf geteilt und bearbeitet werden, solange die Urheber\*innen genannt werden.
