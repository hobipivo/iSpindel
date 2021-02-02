# iSpindel „Grainfather Connect Mobile APP“ Integration

Die „Grainfather Connect Mobile APP“ **GF-APP** von der Grainfather Community am Mobiltelefon aus dem Store installieren, Konto anlegen und anmelden.
Gehen Sie in der Grainfather App auf die Ausrüstungs-Seite und klicken Sie auf das **+** Symbol, wählen Sie „Fermentationsverfolgungsanlagen“ dort „iSpindel DIY electronic Hydrometer“ auswählen, im Fenster den Gerätenamen (iSpindel-Namen) eintragen und auf „Speichern“ klicken. 
Die gespeicherte iSpindel auswählen und auf „View Instructions“ klicken.
Die Geräte-Setup Anweisungen ausführen:
1.	iSpindel einschalten und die Resettaste am Wemos-Modul (größte Platine auf der iSpindel) 3x schnell drücken. (Wenn die iSpindel noch nicht konfiguriert wurde, geht diese automatisch in den Konfig-Modus)
2.	Zum iSpindel WiFi Netzwerk mit dem Mobile-Telefon oder NB, PC verbinden
3.	Die Configuration Seite anklicken
*Wenn noch nicht eingetragen:*
4.	Wenn noch nicht eingetragen: Ihr WiFi Netzwerk (SSID-Namen) auswählen oder eintragen
5.	Password des WiFi Netzwerks eintragen
6.	Namen für die iSpindel vergeben
7.	Interval **900** sec. oder höher eintragen
8.	Bei „Unit of temperature“ Celsius auswählen
9.	Bei “Service Type” **http** auswählen
10.	 Wenn die Server Address und Port Felder nicht angezeigt werden, ändern Sie erneut den „Service Type“ 
11.	 „Token“ Feld löschen
12.	 Unter „Server Address“ **community.grainfather.com** eintragen
13.	 Unter “Server Port” **80** eintragen
14.	 Unter “Server URL” den angezeigten Wert übertragen **/iot/xxxx-yyyy/ispindel**   *(xxxx-yyyy ist eine individuelle ID)*
15.	 „Username“ und „Password“ falls vorhanden – löschen
16.	 Stellen Sie sicher, dass Ihr Polynom Ihre vollständig kalibrierte Formel enthält.
17.	 Auf „Save“ klicken
Die an den „Grainfather Community Server“ gesendeten Daten können nun unter „Ausrüstung“ > „Fermentation Tracking“ > „iSpindelname“ eingesehen werden.
Diese kann man dann auch als Device in der Brausession hinzufügen und die Daten (Dichte & Temperatur) mitloggen lassen.

Viel Erfolg
Christian
