# Was ist die iSpindel?

Die iSpindel wurde von den **Hobbybrauer.de** Forums-Mitgliedern entwickelt und ist für nicht kommerzielle Zwecke freigegeben.

## Prinzip:

Die Messung der Dichte erfolgt mit Hilfe des sich neigenden Zylinders. Der Neigungswinkel ändert sich im Verhältnis zum Auftrieb und damit im direkten Zusammenhang mit dem 
Extraktgehalt (Stammwürze). Die iSpindel ist kein Präzisions-Messinstrument, sondern stellt den Extraktabbau über die Zeit dar. Eine höhere Genauigkeit als +/- 0,5 %w/w ist
nicht zu erwarten.

## Funktion:

Die iSpindel (Elektronik Hydrometer) sendet die Daten (Neigungswinkel/Extraktgehalt, Temperatur und Akkuspannung) in einem einstellbaren Intervall über WLAN (mit 2,4GHz!), speichert selbst
aber keine Daten. Als Datenempfänger kann ein konfigurierter, durchlaufender lokaler Server (z.B.: CraftBeerPi, RasPySpindel …) oder ein öffentlicher Server (z.B.: Ubidots STEM, BierBot Bricks, Brewfather, Grainfather-APP ...) dienen. Vom Handy oder PC, kann dann per Browser, auf einen dieser Datensammler zugegriffen werden.

## Betrieb:

Die Laufzeit des Akku beträgt bei einem Sendeintervall von 900 sec. ca. 5 Monate. 
Ich selbst nutze den KleinPC „Raspberry“, auf dem ein vom Hobbybrauer- Forum zur Verfügung gestelltes Image „RasPySpindel“ installiert wurde.
 
Getestet habe ich auch die Variante, wo die iSpindel die Daten an den kostenlosen "Grainfather Connect Server" sendet und am Handy die "Grainfather Connect Mobile App" installiert wird. [Link zu GF-APP Integration](https://github.com/hobipivo/iSpindel/blob/main/iSpindel_GF-APP_Integration.md)

## hobipivo Varianten:

Die hobipivo iSpindel gibt es in zwei Gehäuseausführungen. Diese sind mit einem elektronischen Verpolungsschutz und Verpolungsanzeige sowie bei Verwendung des D1 mini v4.0 Modules mit einer Schutzdiode ausgestattet.
 
&nbsp;
### iSpindel hobipivo v4.0 PET:

![Text](https://github.com/hobipivo/iSpindel/blob/main/-img/iSpindel_hobipivo-v4.0-PET-500.jpg "Bild")

&nbsp;
### iSpindel hobipivo v4.0 PIL:

![Text](https://github.com/hobipivo/iSpindel/blob/main/-img/iSpindel_hobipivo-v4.0-PIL-500.jpg "Bild")

&nbsp;

## Zusätzliche Informationen:

Gesamtübersicht:
www.ispindel.de mit Verweis auf https://braumagazin.de/article/ispindel-die-idee/

Link-Forum:
http://hobbybrauer.de

iSpindel Aufbau und Betrieb:
https://hobbybrauer.de/forum/viewtopic.php?f=58&t=11826&sid=56a730a541ae07d10c799c6e2ac5bcef

iSpindel lokaler Server:
https://hobbybrauer.de/forum/viewtopic.php?f=58&t=12869

iSpindel Einbindung in Brewfather (Englisch):
https://docs.brewfather.app/integrations/ispindel

iSpindel Einbindung in Ubidots STEM (Englisch):
https://help.ubidots.com/en/articles/3979278-connect-the-ispindel-low-cost-diy-hydrometer-with-ubidots

iSpindel Einbindung in Ubidots (Deutsch):
https://braumagazin.de/article/ispindel-die-visualisierung-der-daten/


Allzeit gut Sud

