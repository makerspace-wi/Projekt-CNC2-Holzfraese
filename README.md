# CNC2 Holzfräse by Michael M.

Es handelt sich dabei um eine <b>CNC-Sperrholz-Fräse</b> aus dem Make(CT Hacks) Magazin 1/2014 
und der Weiterentwicklung nach CNC14 (cnc14.de), mit einer Arbeitsfläche von 600mm x 1200mm, 
davon einer Fräsefläche von 550mm x 900mm und einer Verfahrhöhe von 70mm<br><br>
Achtung! - Im ToolsLocker Fach "CNC-Zubehör" befindet sich ein Zubehörbehälter für die CNC2, bestehend aus: Computer Maus, Fernsteuerung, Werkzeughöhensensor, 2 Schraubenschlüssel (Werkzeugwechsel) und einem 44teiliges Sorotec Stufenspannpratzenset M6 für 6er Nut ([Spann Pratzen Set Teileliste](doc/Pratzen_Set.pdf))

<img width="400" alt="Box_2" src="https://user-images.githubusercontent.com/42463588/126619607-593ac9c1-d0a9-4283-843b-035fd4263459.jpg"><img width="400" alt="Box_1" src="https://user-images.githubusercontent.com/42463588/126619556-e53ee3de-4409-4855-93c3-0f16d925f3c9.jpg">

# Einschalten
Hinter der Fräse befindet sich eine Steckdosenleiste mit Schalter - mit diesem Schalter einschalten:
<br>
<img width="400" alt="Box_3" src="https://user-images.githubusercontent.com/42463588/127311146-514fe918-c521-48f9-8353-5dd8aeab8ffb.jpg">
<br><br>
Der Kleincomputer hat seitlich links einen Ein/Aus-Taster (blaue Kennzeichnung) - diesen für 1 sec drücken, bis die rote LED dauerhaft brennt, der Computer bootet dann (Intel erscheint nach einigen sec auf dem Bildschirm).
<br><br>
<img src="https://user-images.githubusercontent.com/42470750/127994776-5172ce66-92b8-4142-9e16-ca7e70df221d.jpg">

__Achtung: Nicht vergessen die Fernsteuerung einzuschalten und die große ENTER-Taste drücken! Die Fernsteuerung baut dann die Verbindung mit dem Mini-Computer auf.__
# Freigabe mit RFID Chip
Die Nutzung der CNC-Fräse ist nur nach Einweisung und Freischaltung des Mitglieds möglich.
Dazu bitte den roten RFID-Chip vor dem Lesegerät bewegen, bis die Aktivierung bestätigt wird. Bitte auf das Display achten, es könnte hilfreiche Hinweise liefern.

<img src="https://user-images.githubusercontent.com/42463588/128074604-47986882-cf10-4fdd-9c07-c87742d69098.jpg" width="300" border = "0" alt="Box_8">
# Estlcams CNC Controller V11 starten
Zwischenzeitlich sollte der Mini-PC hochgefahren sein und den 'Desktop' zeigen.<br>
<img src="https://user-images.githubusercontent.com/42463588/128076185-05e76ea6-103b-4e6b-ade6-b90337c380f4.JPG" width="200" border = "0" alt="Box_9">

Dort dann das Programm &nbsp;<i>CNC Controller V11</i> &nbsp; mit Doppelklick starten - du erhältst folgenden Startbildschirm:
<br><br>
<img src="https://user-images.githubusercontent.com/42463588/128328089-174bd2f8-ad21-4cdb-ae79-928e339b2ae2.jpg" width="400" border = "0" alt="Box_11">

Die X-, Y- und Z-Position des Fräsmotors kann per Fernsteuerung, als auch per Mausklick auf die blauen Richtungspfeile gesteuert werden.<br>
Jedes Feld und jede Funktion wird ausführlich erklärt, wenn man den Mauszeiger darüber positioniert.
### Funktionserklärungen ###
[Achspositionen](/doc/Estlcam_Achsen_Pos.jpg)<br>
[Kommandozeile nutzen](doc/Estlcam_Kommandozeile.jpg)<br>
[CNC-File öffnen](doc/Estlcam_CNC_Code.jpg)<br>
[Werkzeuglängenmessung](doc/Estlcam_Laengenmessung.jpg)<br>
[Referenzfahrt](doc/Estlcam_Referenz.jpg)<br>

Nach laden der CNC-File: [G-Code & Werkstückdarstellung](doc/Estlcam_Codeanzeige.jpg)

# Datenträger (USB-Stick) einstecken #
<img src="https://user-images.githubusercontent.com/42463588/128076473-a8692cfa-2d47-4370-b53b-c83a559315cd.jpg" width="300" border = "0" alt="Box_10">

# Fräsmotor mit Fernsteuerung bewegen und Fräser montieren #

![REMOTE](https://user-images.githubusercontent.com/42463588/128599642-06dfa2aa-7fdc-4fdb-a3ca-056b4d05d5d5.jpg)


# Werkstück einspannen #
### Horizontales einspannen ###
[Spannpratzen Set Teileliste](doc/Pratzen_Set.pdf)

<img src="https://user-images.githubusercontent.com/42463588/128347999-0ca39f10-766b-45a8-beaa-dbfe2bed5d88.jpg" width="300" border = "0" alt="Box_12"> 

<img width="300" alt="Bildschirmfoto 2021-08-03 um 19 40 27" src="https://user-images.githubusercontent.com/42463588/128348315-10720b31-07db-4886-a029-c2f4f445cf3f.png"> <img width="300" alt="Bildschirmfoto 2021-08-03 um 19 41 06" src="https://user-images.githubusercontent.com/42463588/128348234-1c877c6b-0459-4ba3-af51-481c5ebb7b43.png"> <img width="300" alt="Bildschirmfoto 2021-08-03 um 19 40 59" src="https://user-images.githubusercontent.com/42463588/128348268-16e7ea15-e996-4bef-bb09-265867835e81.png">

### Vertikales einspannen ###

<img src="https://user-images.githubusercontent.com/42463588/127312994-6e0c8802-4759-4f5c-81bd-af389516bfb8.jpg" width="300" border = "0" alt="Box_5"> <img src="https://user-images.githubusercontent.com/42463588/127313679-64bd7a75-b21e-49f5-abad-8df5950e09c4.jpg" width="300" border = "0" alt="Box_6"> <img src="https://user-images.githubusercontent.com/42463588/127313493-08838aa2-08c9-4748-abaf-e10df9ba130d.jpg" width="300" border = "0" alt="Box_7" >

## Fräsprojekt  Ablauf ##

* Fräse und Zubehör einschalten und mit RFID-Chip anmelden
   * [Einschalten](#Einschalten)
   * [Einloggen](#Freigabe-mit-RFID-Chip)
* Programm CNC Controller V11 starten
   * [Einloggen](#Estlcams-CNC-Controller-V11-starten)
* Referenzfahrt
   * [Referenzfahrt](#Freigabe-mit-RFID-Chip)
* Zu verarbeitende File mit Estlcam CNC-Steuerung öffnen
    * aaa
* Nullpunkt anfahren und Achsen 'nullen'
    * bbb
    * ccc  
* Z-Nullpunkt automatisch mit Sensor ermitteln

<img src="https://user-images.githubusercontent.com/42463588/128348039-859f8c6a-bd0f-4af7-ab58-33d2fa53a9ae.jpg" width="300" border = "0" alt="Sensor">


## Fräse runter fahren (ausschalten)
<ol>
<li>Per 'Referenzfahrt' den Fräsmotor nach links/oben bringen</li>
<li>Programm Estlcam CNC-Steuerung schließen</li>  
<li>PC herunterfahren</li>
<li>Am Zugangsgerät abmelden</li>
<li>Computer Maus ausschalten</li>  
<li>Fernsteuerung ausschalten</li>
<li>Steckdosenleiste ausschalten</li>
<li>CNC zudecken mit grünem Tuch</li>
</ol>

## Weiterführende Dokumentationen

[Rampa Muffen Einbau](doc/RampaMuffen%20Einbau.pdf)

[Schaltbilder CNC-Steuerung](doc/CNC_SteuerungGRBL_SSR_V2.pdf)

[Zeichnung Riemenschutz](doc/Riemenschutz%20Zeichnung%20v2.pdf)

[Schnittwerteberechnungen](doc/schnittwerte.pdf)

[Spann Pratzen Set Teileliste](doc/Pratzen_Set.pdf)

----



