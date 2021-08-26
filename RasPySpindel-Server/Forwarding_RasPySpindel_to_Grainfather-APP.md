# Weiterleitung iSpindel-Daten vom RaspPySpindel-Server zur „Grainfather Connect Mobile APP“ 

## Vorbereitung Grainfather Connect Mobile APP:
Die „Grainfather Connect Mobile APP“ **GF-APP** von der Grainfather Community am Mobiltelefon aus dem Store installieren, Konto anlegen und anmelden.

1. In der Grainfather APP auf der Ausrüstungs-Seite auf das **+** Symbol klicken
2. **„Fermentationsverfolgungsanlagen“** auswählen 
3. **„iSpindel DIY electronic Hydrometer“** auswählen
4. iSpindel-Namen eintragen und auf „Speichern“ klicken.

Die gespeicherte iSpindel auswählen und auf „View Instructions“ klicken.

## Konfiguration am RasPySpindel Server:
1.	Auf dem RasPySpindel-Server die "Landing Page" http://meinraspi/ispindle/  **"TCP Server Settings Editieren"** aufrufen
2.	Unter „Section Auswahl“ in der letzten Zeile, neben dem iSpindelNamen, **"Individuelle Settings für Device anlegen"** bestätigen
3.	Unter „Section Auswahl“ bei „Device“ den iSpindel-Namen und bei „Section“ **"GRAINCONNECT"** auswählen
4.	Unter „Value“ bei „ENABLE_GRAINCONNECT“ eine **1** für die Aktivierung der Weiterleitung eintragen
5.	Unter „Value“ bei „GRAINCONNECT_URL“ den Inhalt der „ServerURL“ aus „View Setup Instructions (Geräte-Setup Anweisungen)“ **/iot/xxxx-yyyy/ispindel** eintragen
6.	Unter „Section Auswahl“ **"Settings in DB schreiben"** aufrufen

Die an den „Grainfather Community Server“ gesendeten Daten können nun unter „Ausrüstung“ > „Fermentation Tracking“ > „iSpindel-Name“ eingesehen werden.
Diese kann man dann auch als Device in der Brausession hinzufügen und die Daten (Dichte & Temperatur) mitloggen lassen.


Für jede iSpindel müssen individuelle Settings angelegt werden!

Viel Erfolg
