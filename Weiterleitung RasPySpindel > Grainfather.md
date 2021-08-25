# Weiterleitung iSpindel-Daten vom RaspPySpindel-Server zur „Grainfather Connect Mobile APP“ 

## Vorbereitung Grainfather Connect Mobile APP:
Die „Grainfather Connect Mobile APP“ **GF-APP** von der Grainfather Community am Mobiltelefon aus dem Store installieren, Konto anlegen und anmelden.
Gehen Sie in der Grainfather App auf die Ausrüstungs-Seite und klicken Sie auf das ** + ** Symbol, wählen Sie „Fermentationsverfolgungsanlagen“, anschließend „iSpindel DIY electronic Hydrometer“ auswählen, im Fenster den Gerätenamen (iSpindel-Namen) eintragen und auf „Speichern“ klicken. 
Die gespeicherte iSpindel auswählen und auf „View Instructions“ klicken.

## Konfiguration am RasPySpindel Server:
1.	Auf der RasPySpindel-Server Webseite **"TCP Server Settings Editieren"** aufrufen
2.	Unter „Section Auswahl“ in der letzten Zeile, neben dem iSpindelNamen, **"Individuelle Settings für Device anlegen"** bestätigen
3.	Unter „Section Auswahl“ bei „Device“ den iSpindel-Namen und bei „Section“ **"GRAINCONNECT"** auswählen
4.	Unter „Value“ bei „ENABLE_GRAINCONNECT“ eine **1** für die Aktivierung der Weiterleitung eintragen
5.	Unter „Value“ bei „GRAINCONNECT_URL“ den Inhalt der „ServerURL“ aus der „View Setup Instructions (Geräte-Setup Anweisungen)“ **/iot/xxxx-yyyy/ispindel** eintragen
6.	Unter „Section Auswahl“ **"Settings in DB schreiben"** aufrufen

Die an den „Grainfather Community Server“ gesendeten Daten können nun unter „Ausrüstung“ > „Fermentation Tracking“ > „iSpindelname“ eingesehen werden.
Diese kann man dann auch als Device in der Brausession hinzufügen und die Daten (Dichte & Temperatur) mitloggen lassen.

Viel Erfolg
