# Das Schwarze Auge 5 - Tsa Edition

## Änderungen

2019-10-18: strukturelle Anpassungen durch Tajo, um Sortierreihenfolge bei Übersetzungen z. B. bei Talenten beizubehalten

2019-10-14: Englische Übersetzung durch Tajo. Vielen Dank!

2019-10-07:
- Änderungen des Status lösen nun eine Neuberechnung der Kampfwerte aus --> bestehende Events ergänzt
- Änderungen der Kampftechnikwerte führen zur Neuberechnung der Kampfwerte --> neuer Event Trigger und Change Flag (ktw_change_flag) hinzugefügt.
- Der Status (status_maxi) wird bei Eigenschaftsproben jetzt berücksichtigt.
- Modifikatoren für Regeneration LE/AE/KE hinzugefügt
- Felder für Münzen im Geldbeutel hinzugefügt

2019-09-15:
- Die Attribute für Lebensenergie (le, le_max), Astralenergie (ke_, ke_max) und Karmaenergie (ke, ke_max) wurden umbenannt, um das Zuweisen der Werte an Token zu vereinfachen. Achtung: evtl. werden die aktuellen Werte auf 0 gesetzt und müssen angepasst werden.
- Modifikator für den Fertigkeitswert (FW) der Talente hinzugefügt
- Rüstungsschutz (RS) wird auch im Kopf des Kampfbogens angezeigt
- Auf dem Kmapfbogen wurde ein neuer, freier Modifkator hinzugefügt, der nur beim Würfeln herangezogen wird
- berechnete Werte und Felder, deren Inhalte nicht verändert werden können, werden jetzt grau hinterlegt, um sie besser von Eingabefeldern unterscheiden zu können
- neue Typen für Sonderfertigkeiten, Magie und Götterwirken
- Darstellung und Berechnung der SchiPs auf dem Grundwertetab wurden gefixt
- AE/KE Leiteigenschaft (Grundwertetab) und Traditionseigenschaft (Magie/Götterwirken-Tab) sind jetzt synchronisiert
- für AE/KE kann jetzt der Faktor (Default 1) mit dem die Traditionseigenschaft in den Gesamtwert eingeht, eingegeben werden


2019-09-01:
- Vorteile und Nachteile wurden unter Sonderfertigkeiten zusammenfaßt
- Zauberspruchtyp Zaubertricks hinzugefügt
- Fix: Berechnung Werte für Hiebwaffen im Kampfwerte

2019-08-20: Der Charakterbogen wird erstmalig veröffentlicht.

## Einleitung

Liebe Abenteurer,

lange habe ich mit mir gerungen, einen eigenen Charakterbogen für DSA 5 zu bauen. Denn der alte Bogen deckt viele Inhalte der aktuellen 5. Edition 1:1 ab. Da aber stetig neue Regelbücher mit neuem Crunch erscheinen, wollte ich einen Charakterbogen erstellen, der eher wie ein Baukastensystem funktioniert. Und anhand dessen man Sonderfertigkeiten, Zaubersprüche, Artefakte, Fokusregeln usw. flexibel abbilden kann. Außerdem bietet sich so ein Baukasten auch für Hausregeln an, die per Definition je Gruppe unterschiedlich sind.

Herausgekommen ist ein neuer Charakterbogen, der anders aussieht und anders funktioniert als wie gewohnt, aber einem mehr Freiheiten lässt und hoffentlich auch mehr Unterstützung und Spaß beim Spielen bringt. Da dieses aber der erste Wurf ist, kann es sein, dass noch Fehler vorhanden oder Dinge noch nicht umgesetzt sind. Bei Fragen oder Feedback wendet euch gerne an mich per Email ( trestolt(at)gmail.com ). Ich findet mich auch auf der Drachenzwinge (https://www.drachenzwinge.de/) sowie im Orkenspalter-Forum (https://www.orkenspalter.de/).


## Charaktererstellung

Dieser Charakterbogen ist nicht für die Erstellung von Charakteren gedacht, ich empfehle die Nutzung des selbstrechnenden PDF-Charakterbogens oder anderer Werkzeuge aus dem Scriptorium Aventuris. Ihr könnt die Werte entsprechend aus dem PDF-Bogen in den Roll20-Charakterbogen übertragen. Die abgeleiteten Werte werden grundsätzlich berechnet.  Die Talente sowie Kampftechniken können 1:1 übernommen werden.

Bei Vor- und Nachteilen, allen Arten von Sonderfertigkeiten, Effekten sowie Artefakten kommt das Baukastenprinzip ins Spiel.

### Vorteile / Nachteile / Sonderfertigkeiten

Vor-/Nachteile sowie Sonderfertigkeiten funktionieren gleich, weswegen diese unter Sonderfertigkeiten zusammengefaßt wurden.

SF können und sollen  nur unter dem entsprechendem Reiter Sonderfertigkeiten angelegt werden.
Zuerst wird der Typ der Sonderfertigkeit angegeben. Nach diesem Typ kann später auch gefiltert werden. Und auch späAchtung, wenn in einer Sonderfertigkeit ein Modifikator doppelt verwendet wird, kann es zu falschen Berechnungen kommen. Daher niemals einen Modifkator innerhalb einer SF mehrfach verwenden. Allerdings kann ein Modifkator in mehreren Sonderfertigkeiten verwendet werden, da diese normal verrechnet werden.

In anderen Reitern des Charakterbogens können auch Sonderfertigkeiten mit ihrem Namen sowie der Aktivierungscheckbox angezeigt werden. Das ist nur gedacht, die SF dort zu aktivieren bzw. deaktivieren und ggfs. die geänderten Werte im Bogen besser beobachten zu können.

Beispiel Wochtschlag I :

```
Kampfsonderfertigkeit Wuchtschlag I
1. Modifikator  AT -2
2. Modifikator  TP +2

```


Beispiel Vorteil Beidhändig:

```

Vorteil Beidhändig
1. Modifikator Falsche-Hand-Mod. +4

```




### Liste der Modifikatoren

```

Eigenschaften
* Mut
* Klugheit
* Intuition
* Charisma
* Fingerfertigkeit
* Gewandheit
* Konstitution
* Koerperkraft

abgeleitete Werte
* Lebensenergie
* Astralenergie
* Karmalenergie
* Seelenkraft
* Zähigkeit
* Initiative
* Ausweichen
* Geschwindigkeit
* Schicksalspunkte

Kampfsonderfertigkeiten
* Attacke
* Parade
* Ausweichen
* Trefferpunkte
* Fernkampf
* Nebenhand AT
* Nebenhand PA
* Nebenhand TP
* Zusätzliche PA (Modifikator für die zweite oder x. Parade)
* Zusätzliches AW (Modifikator für das zweite oder x. Ausweichen)
* Beidhändigkeit-Mod. (Modifikator für das gleichzeitige Führen von zwei Waffen)
* Falsche-Hand-Mod.  (Modifikator für Waffen in der falschen Hand)

Würfel- / Probenmodifikator
sowie Modifikator des Fertigkeitwertes (FW)
Körpertalente
* Fliegen
* Gaukeleien
* Klettern
* Körperbeherrschung
* Kraftakt
* Reiten
* Schwimmen
* Selbstbeherrschung
* Singen
* Sinnesschärfe
* Tanzen
* Taschendiebstahl
* Verbergen
* Zechen

Gesellschaftstalente
* Bekehren
* Betören
* Einschüchtern
* Etikette
* Gassenwissen
* Menschenkenntnis
* Überreden
* Verkleiden
* Willenskraft

Naturtalente
* Fährtensuchen
* Fesseln
* Fischen
* Orientierung
* Pflanzenkunde
* Tierkunde
* Wildnisleben

Wissenstalente
* Glückspiel
* Geographie
* Geschichtswissen
* Götterkulte
* Kriegskunst
* Magiekunde
* Mechanik
* Rechnen
* Rechtskunde
* Sagenlegenden
* Sphärenkunde
* Sternkunde

Handwerkstalente
* Alchemie
* Boote
* Fahrzeuge
* Handel
* Heilkunde Gift
* Heilkunde Krankheiten
* Heilkunde Seele
* Heilkunde Wunden
* Holzbearbeitung
* Lebensmittelbearbeitung
* Lederbearbeitung
* Malen und Zeichnen
* Metallbearbeitung
* Musizieren
* Schlösserknacken
* Steinbearbeitung
* Stoffbearbeitung

Magie und Glaube
* Zauberwirken
* Göttliches Wirken

```

### Status und Talentfertigkeiten

Unter Status lassen sich die unterschiedlichen Zunstände eintragen. Entsprechend der Regeln wird maximal eine Obergrenze von -5 auf die Kampfwerte sowie die Talente angerechnet. Bei den Talenten kann anhand der kleinen Checkboxen ausgewählt werden, wann welcher Status bei einer Talentfertigkeit berücksichtigt werden soll. Anhand der Kontexthilfe wird der entsprechende Status beschrieben. Zum Beispiel Belastung wirkt sich nicht auf alle Fertigkeiten aus, entsprechend sind diese per Default nicht angehakt.  Ein bensonderer Status ist Entrückung, der sich je nach Profession sich positiv oder negativ auf eine Talentfertigkeit oder eine Kampftechnik auswirkt. Entsprechend kann an dort bei Entrückung einen Bonus statt eines Malus (Default) auswählen.


### Magie und Götterwirken



### Ausrüstung


### Kampfbogen


## Nützliche Makros für Pro-Benutzer


## Interessante Links

* [Ulisses DSA 5 Regelwiki ](https://ulisses-regelwiki.de/) - Offizielle Wiki zu den DSA 5 - Regeln


## Ausblick
* Überarbeitung Artefakte
* Überarbeitung Inventar
* Einführung von Effekt-Modifkatoren für die Auswirkung von Zaubersprüchen, Liturgien, Artefakten etc. auf den Helden
* Umschalten des PC-Bogens zu einems NSC-Bogen (eher langfristig)

## Danksagung

Großer Dank geht an die Entwickler des DSA5 Character Sheet German   Patrick Gebhardt, enhanced by Sönke Holsten, Adam Fedor. Einige Teile des Charakterbogens habe ich von dort übernommen oder mich inspirieren lassen.
Noch größerer Dank geht an alle, deren Anregungen und Feedback in den Bogen eingeflossen sind, insbesonders an: Perceval, Igraine, Lodge, Paladose, Danii, Tiro sowie Tajo für die englische Übersetzung.
