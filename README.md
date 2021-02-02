# Was ist die iSpindel?

Die iSpindel wurde von den Hobbybrauerforum.de Mitgliedern entwickelt und ist für nicht kommerzielle Zwecke freigegeben.

## Prinzip:

Die Messung der Dichte erfolgt mit Hilfe des sich neigenden Zylinders. Der Neigungswinkel ändert sich im Verhältnis zum Auftrieb und damit im direkten Zusammenhang mit dem 
Extraktgehalt (Stammwürze). Die iSpindel ist kein Präzisions-Messinstrument, sondern stellt den Extraktabbau über die Zeit dar. Eine höhere Genauigkeit als +/- 0,5 %w/w ist
nicht zu erwarten.

## Funktion:

Die iSpindel (Elektronik Hydrometer) sendet die Daten (Neigungswinkel/Extraktgehalt, Temperatur und Akkuspannung) in einem einstellbaren Intervall über WLAN, speichert selbst
aber keine Daten. Als Datenempfänger kann ein konfigurierter, durchlaufender lokaler Server (z.B.: craftbeerpi, RasPySpindel …) oder ein öffentlicher Server (z.B.: Ubidots STEM,
Grainfather Connect ...) dienen. Vom Handy oder PC, kann dann per Browser, auf einen dieser Datensammler zugegriffen werden.

## Betrieb:

Die Laufzeit des Akku beträgt bei einem Sendeintervall von 900 sec. ca. 4 Monate. 
Ich selbst nutze den KleinPC „Raspberry“, auf dem ein vom Hobbybrauer- Forum zur Verfügung gestelltes Image „RasPySpindel“ installiert wurde.
 
Getestet habe ich auch die Variante, wo die iSpindel die Daten an den kostenlosen "Grainfather Connect Server" sendet und am Handy die "Grainfather Connect Mobile App" installiert wird. [Link zu GF-APP Integration] (iSpindel_Grainfather_Connect_Mobile_APP_Integration.md)

## Zusätzliche Informationen:

Gesamtübersicht:

www.ispindel.de mit Verweis auf https://braumagazin.de/article/ispindel-die-idee/

Link-Forum:

http://hobbybrauer.de

iSpindel Aufbau und Betrieb:

https://hobbybrauer.de/forum/viewtopic.php?f=58&t=11826&sid=56a730a541ae07d10c799c6e2ac5bcef

iSpindel lokaler Server:

https://hobbybrauer.de/forum/viewtopic.php?f=58&t=12869

iSpindel Einbindung in Ubidots STEM (Englisch):

https://help.ubidots.com/en/articles/3979278-connect-the-ispindel-low-cost-diy-hydrometer-with-ubidots


Allzeit gut Sud

Christian
