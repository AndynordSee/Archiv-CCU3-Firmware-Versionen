# Archiv-CCU3-Firmware-Versionen
Archiv CCU3 Firmware Versionen. Texte und Firmware Copyright by eq-3


# Changelog
3.47.15
Fehlerbehebungen
[HMCCU-360] Die Daten der Logikschicht wurden beim Abmelden nicht mehr gespeichert.
[HMCCU-357] Funk-Schaltaktoren mit Leistungsmessung (HM-ES-PMSw1-Pl*) zeigten beim EnergieZähler „NaN“ anstatt des Messwertes an.
[HMCCU-354] Bei dem HM-MOD-EM-8Bit Modul (Version 1.0) wurden die Kanalparameter des Kanal 3
in der Gerätekonfiguration nicht mehr dargestellt.
[HMCCU-333] Die Duty-Cycle Anzeige zeigte unter Umständen falsche Werte, wenn weitere Gateways
im System vorhanden sind.
3.47.10
Geräteintegration
[HMCCU-152] Integration HmIP-ASIR-2
[HMCCU-151] Integration Homematic IP Wired Wandthermostat mit Luftfeuchtigkeitssensor,
HmIPW-WTH
[HMCCU-147] Integration Homematic IP Wired Temperatur- und Luftfeuchtigkeitssensor mit Display –
innen, HmIPW-STHD
[HMCCU-146] Integration Homematic IP Wired Temperatur- und Luftfeuchtigkeitssensor – innen,
HmIPW-STH
[HMCCU-28] Integration Homematic IP Fußbodenheizungsaktor – 12-fach, motorisch,
HmIP-FALMOT-C12
[HMCCU-21] Integration folgender Homematic IP Wired FAL-Varianten:
- HmIPW-FAL24-C6
- HmIPW-FAL230-C6
- HmIPW-FAL24-C10
- HmIPW-FAL230-C10
[HMCCU-155] Integration Homematic IP Multi IO Modulplatine - 4x4, HmIP-MIO16-PCB (ELV Bausatz)
Fehlerbehebungen
[HMCCU-317] Kanäle der virtuellen Fernbedienung (HmIP-RCV-50) ließen sich nicht aus Räumen und
Gewerken löschen.
[HMCCU-296] HmIP-MP3P - Bei einer Verknüpfung mit einem Windmesser wurde u. U. fälschlicherweise
die Farbauswahl anstatt der Soundauswahl angeboten.
[HMCCU-294] Die Beschriftung des Buttons „Geräte-Firmware“ auf der Seite „Einstellungen“ wurde in
„Geräte-Firmware-Übersicht“ korrigiert.
[HMCCU-285] Verhindern von Remote-HTML-Injections bei der Abfrage von Addon-Versionsnummern.
[HMCCU-274] Unter bestimmten Voraussetzungen konnte eine SessionID ohne Login erzeugt werden.
[HMCCU-273] Die angezeigte Regenmenge für den HmIP-SWO-* verdoppelte sich nach einem Neustart
der CCU.
Erweiterungen / Verbesserungen
[HMCCU-261] JSON-API: Berechtigungslevel für Zugriff auf get-/setMetadata Aufrufe eingeführt:
setMetadata Aufrufe: ADMIN
getMetadata Aufrufe GUEST
[HMCCU-259] HmIP-MP3P - Dialog zur einfachen Verwendung von Playlisten innerhalb von Programmen
hinzugefügt.
[HMCCU-252] Web Server der CCU schicken HTTP-Header „Server“ nicht mehr mit.
[HMCCU-248] Bei Direktverknüpfungen zwischen Bewegungsmeldern und Schalt-/Dimmaktoren schaltet
sich ein helligkeitsabhängig geschalteter Aktor nicht mehr ungewollt selbstständig aus,
obwohl noch Bewegung detektiert wird.
[HMCCU-213] HM-ES-TX-WM - Geändertes Verhalten mit der demnächst erhältlichen Firmware > 2.x.y
Integration SML-Protokoll, neuer Konfigurationsparameter „DZG-Kompatibilitätsmodus“.
Die Unterstützung von IR-, Gas- und LED-Sensoren wurde entfernt. Es wird ausschließlich
der ES-IEC Sensor unterstützt.
[HMCCU-163] Neue Funktionalität für HmIP-MIOB (Wochenprogramm)
[HMCCU-162] Neue Funktionalität für HmIP-FAL (MIOB-Umschaltung Heizen/Kühlen)
[HMCCU-150] Automatische Übertragung der Standortdaten an neu angelernte HmIP-Geräte für AstroFunktionen.
Bei Änderung der Standortdaten besteht nun die Möglichkeit der Übertragung an alle
dem System bekannten HmIP-Geräte.
[HMCCU-17] Ergänzung der HTTP-Header des lighttpd Web Servers um einige sicherheitsrelevante
Felder.
3.45.7
Geräteintegration
[HMCCU-130] Integration HmIP-WRCD (Homematic IP Wandtaster mit Statusdisplay)
[HMCCU-15] Integration HmIP-SCI (Homematic IP Kontakt-Schnittstelle)
Fehlerbehebungen
[HMCCU-209] Konfigurationsparameter der Heizungsgruppen wurden nicht dargestellt.
[HMCCU-188] Zusatzsoftware konnte nicht installiert oder aktualisiert werden.
3.45.5
Geräteintegration
[HMCCU-20] Integration HmIP-ASIR-O (Homematic IP Alarmsirene – außen)
Erweiterungen / Verbesserungen
[HMCCU-194] HmIP-eTRV/eTRV-2/eTRV-C - Innerhalb von Programmen kann nun auf den Ventilstatus
reagiert werden.
[HMCCU-193] Zeitsynchronisierung des Funk-Koprozessors wird jetzt nur noch alle 6 Stunden anstatt alle
30 Minuten aufgerufen. Dadurch wird der Funkverkehr verringert.
[HMCCU-100] HmIP-eTRV/eTRV-2/eTRV-C - mit der aktuellsten Firmware dieser Geräte steht nun ein
Kanalparameter zur Einstellung des Ultra-Leise-Betriebs zur Verfügung.
[HMCCU-16] Unterstützung von AutoIP.
Fehlerbehebungen
[HMCCU-208] Bei der Verwendung von Zeitspannen über einen Tageswechsel hinweg, konnte es im
Zusammenhang mit der Zeitumstellung bei der Ausführung von Programmen zu
Problemen kommen.
[HMCCU-186] HmIP-BSL - Der Schaltzustand konnte im Wochenprogramm nicht verwendet werden.
[HMCCU-144] HmIP-FCI1/6 - Die Kanalparameter standen nicht zur Verfügung
[HMCCU-137] Die Ein-/Ausschaltdauer innerhalb von Easymode-Profilen kann nun nicht mehr
gleichzeitig auf ‚Nicht aktiv‘ gesetzt werden.
[HMCCU-136] Der Gerätefilter der Gerätliste lieferte bei den Einstellungen „BidCos-RF/Wired“ kein
Resultat.
[HMCCU-135] Ein Problem beim Löschen direkter Verknüpfungen mit HmIP-RCV-50 (virtuelle
Fernbedienung für HmIP) wurde behoben.
[HMCCU-131] Fehler im Zusammenhang mit UPnP behoben
3.43.16
Fehlerbehebungen
[HMCCU-179] Buffer Overflow im ReGa Web Server
Im ReGa Web Server gibt es eine Pufferüberlauf- / Buffer Overflow Schwachstelle. Bei
dieser können in einen Datenbereich (Array) mit fester Größe im Stack Daten beliebiger
Länge geschrieben. Durch „bösartiges“ Schreiben von Daten, ist es prinzipiell möglich, die
Rücksprungadresse im Stack zu Überschreiben und den Rücksprung in den Bereich der
geschriebenen Daten zu lenken. Hierdurch könnte Schadcode ausgeführt werden.
Aktuell ist jedoch kein Exploit bekannt, der dies für einen Angriff auf die CCU ausnutzt.
Der Webserver-Prozess kann aber zum Absturz gebracht werden.
Die Schwachstelle des Pufferüberlauf- / Buffer Overflow wurde geschlossen. Damit kann
hier kein Schadcode mehr eingeschleust werden.
[HMCCU-154] Authentication Bypass durch User „RemoteAPI”
Über einen in der Logikschicht der CCU existierenden internen Benutzer „RemoteAPI“
kann eine gültige Sitzung / SessionID erzeugt werden, die die Basis für weiterführende
Angriffsszenarien darstellt. Die Erzeugung einer Session für den internen Benutzer wird
jetzt unterbunden.
[HMCCU-154] Fehler im Session Handling
Beim Ausloggen / Abmelden eines Benutzers aus der CCU WebUI wird die Sitzung /
SessionID durch ReGa in bestimmten Situationen nicht sofort invalidiert. Dadurch kann die
SessionID unter diesen Umständen zeitweilig für einige Aufrufe weiter verwendet werden.
Die SessionID wird jetzt sofort beim Abmelden eines Benutzers invalidiert. Eine weitere
Verwendung ist damit nicht mehr möglich.
[HMCCU-191] Remote Execution
Unter bestimmten Umständen war eine Remote Execution von Tcl Scripten über das
Heim-LAN möglich.
Hier wurde ein Fehler in einem Script für die Administration behoben.
[HMCCU-143] Schreiben beliebiger Daten
Unter bestimmten Umständen war das Schreiben beliebiger Daten möglich.
Hier wurde ein Fehler in einem Script für die Administration behoben.
Risiko: Folgende Angriffsmöglichkeiten bestanden zuvor bei diesen Fehlern
- aus dem Internet: Wenn Port Forwarding eingerichtet war (siehe Warnung oben)
- aus dem LAN: Wenn unsichere / nicht vertrauenswürdige Systeme Zugang zum LAN
haben
3.43.15
Geräteintegration
[HMCCU-6] Integration HmIP-RCV-50 (virtuelle Fernbedienung für HmIP)
[HMCCU3-1834] Integration HmIP-FCI6 (Homematic IP Kontakt-Schnittstelle Unterputz – 6-fach)
[HMCCU3-1502] Integration HmIPW-DRD3 (Homematic IP Wired Dimmaktor – 3-fach)
[HMCCU3-1501] Integration HmIPW-DRS4 (Homematic IP Wired Schaltaktor – 4-fach)
[HMCCU3-1500] Integration HmIPW-DRS8 (Homematic IP Wired Schaltaktor – 8-fach)
[HMCCU3-1499] Integration HmIPW-FIO6 (Homematic IP Wired IO Modul Unterputz – 6-fach)
[HMCCU3-1498] Integration HmIPW-DRI16 (Homematic IP Wired Eingangsmodul – 16-fach)
[HMCCU3-1497] Integration HmIPW-DRI32 (Homematic IP Wired Eingangsmodul – 32-fach)
[HMCCU3-1496] Integration HmIPW-DRBL4 (Homematic IP Wired Jalousieaktor – 4-fach)
[HMCCU3-1495] Integration HmIPW-DRAP (Homematic IP Wired Access Point)
[HMCCU3-1375] Integration HmIP-WT (Homematic IP Wandthermostat)
[HMCCU-24] Integration HmIP-ASIR-B1
[HMCCU-9] Integration Hm-RC-2-PBU-FM-2 (Funk-Sender 2-fach für Markenschalter,
Unterputzmontage)
Erweiterungen / Verbesserungen
[HMCCU3-2116] Konfig.-Parameter „Optimum Start/Stopp“ für HmIP-WT/WTH/WTH2 hinzugefügt.
[HMCCU3-2115] Konfig.-Parameter „Ventil-Offset“ für HmIP-eTRV/-2/-B/-C hinzugefügt.
[HMCCU3-1926] IP-Adressen (IPv4 / IPv6) unter Netzwerkeinstellungen werden auf Plausibilität geprüft.
[HMCCU-120] Für lokale Verbindungen (localhost) wird keine HTTP Basic-Authentifizierung mehr
durchgeführt.
[HMCCU-109] Bezeichnung Relais in Ausgang geändert
(z. B. „Statusmitteilung Relais“ ist nun „Statusmitteilung Ausgang“)
[HMCCU-74] Der Button Geräte-Firmware springt nun zur neuen Übersichtsseite der Gerätefirmware.
[HMCCU-8] Das Gerätefirmwareupdate wird nur noch über die „Geräte-Firmware Übersicht“
durchgeführt.
 Der entsprechende Button auf der Gerätekonfigurationsseite wurde entfernt.
Fehlerbehebungen
[HMCCU3-2114] HmIP-BSL - die obere Gerätetaste stand u. U. für Programme nicht zur Verfügung.
[HMCCU3-2104] HmIP-FBL/BBL - fehlende Lamellenposition im Wochenprogramm hinzugefügt.
[HMCCU3-2103] HmIP-FBL/BBL - die Lamellenposition ließ sich nicht über die WebUI setzen.
[HMCCU3-2095] Das Konfigurationsfenster des RGBW-Controller in Programmen wiederhergestellt.
[HMCCU3-2093] HmIP-FCI1/6 - fehlende Easymodes hinzugefügt.
[HMCCU3-2088] Die Funktion „Aktion bei Spannungszufuhr“ für Homematic IP-MP3P und Dimmaktoren
war fehlerhaft.
[HMCCU3-2087] HmIP-FCI1/6 - Parameter „Eventverzögerung“ entfernt.
[HMCCU3-1837] Die „Geräte-Firmware Übersicht“ wurde bei vorhandenem Philips HUE Gateway nicht
korrekt geladen.
[HMCCU3-1467] Der CCU-Wert des Energiezählers verdoppelte sich nach einem Reboot der CCU.
[HMCCU-153] Unberechtigtes Login durch Manipulation mit der SessionID
(Security Update des Web Session Managements der CCU)
Durch das Aufrufen der WebUI wird bereits vor dem Login eines Benutzers eine Sitzung /
SessionID erzeugt. Diese kann für weiterführende Angriffe missbraucht werden. In der
Problembehebung wird die Erzeugung einer Sitzung / SessionID ohne vorherigen Login
verhindert
Risiko: Angriffsmöglichkeiten bestanden
- aus dem Internet: Wenn Port Forwarding eingerichtet war (siehe Warnung oben)
- aus dem LAN: Wenn unsichere / nicht vertrauenswürdige Systeme Zugang zum LAN
haben
[HMCCU-97] HmIP-PCBS2 – Wohnort (Längen-/Breitengrad) ist jetzt einstellbar. Die Angabe wird für
eine korrekte Ausführung des Wochenprogramms benötigt.
3.41.11
ACHTUNG: Beachten Sie die Hinweise zur Version 3.41.7.
Fehlerbehebungen
• Ereignisse wurden in einigen Fällen doppelt verarbeitet, wodurch u. a. Programme
doppelt ausgeführt wurden.
• Neue Version von Mediola NEO SERVER (Version 2.3.4) sowie Korrekturen an den Firewall-Regeln
für Mediola NEO SERVER.
• Unter gewissen Voraussetzungen konnte der Aufruf einiger Seiten der Web-Oberfläche mehrere
Minuten dauern.
• Texte zum USB-Stick zur Messdatenspeicherung wurden korrigiert.
• HmIP-PSM: In Direktverknüpfungen steht der Entscheidungswert des Kanal 7 jetzt zur Verfügung. Beim Kanal
6 (Messwertkanal) kann der Mindestsendeabstand auf über 30 Sekunden eingestellt werden.
3.41.7
ACHTUNG: Dieses Update enthält relevante Anpassungen der Sicherheitseinstellungen. Diese können sich auf die
Funktionen von Zusatzsoftware auswirken. Darunter fallen erweiterte Firewalleinstellungen und die
obligatorische Vergabe eines Anmeldepassworts.
Erstellen Sie ein Backup der Zentrale, bevor Sie dieses Update installieren!
[HMCCU3-1860] - Integration HmIP-RCB1 (Homematic IP Fernbedienung mit Montagegurt – 1-Kanal)
[HMCCU3-1750] - Integration HmIP-FCI1 (Homematic IP Kontakt-Schnittstelle Unterputz – 1-fach)
[HMCCU3-1718] - Integration HmIP-eTRV-C (Homematic IP Heizkörperthermostat – kompakt)
[HMCCU3-1383] - Integration HmIP-MP3P (Homematic IP MP3 Kombisignalgeber)
Erweiterungen / Verbesserungen zur CCU3
[HMCCU3-1653] - Einrichtungswizard bei Erstinbetriebnahme
Nach der Installation dieses Updates
• wird jeder Benutzer ohne Passwort aufgefordert, ein Passwort zu vergeben.
• wird ein Administrator zur Überprüfung der Sicherheitseinstellungen aufgefordert.
Das Blinken der Info LED bei Service- u. Alarmmeldungen kann deaktiviert werden.
(Einstellung unter Systemsteuerung/Allgemeine Einstellungen)
3.37.8
Initiale Firmware Version der CCU3
Erweiterungen / Verbesserungen zur CCU2
• Neue Seite mit übersichtlicher Darstellung der Firmware Versionen aller vorhandenen Geräte.
• Vorinstallierter NeoServer der Firma mediola.
• Änderungen an den Logikschicht-Varianten:
o Die Version „Community“ der CCU2 heißt „Standard“ in der CCU3 (Default).
o Die Version „Standard“ der CCU2 heißt „Kompatibilitätsmodus“ in der CCU3.
o Die Version „Legacy“ der CCU2 wurde entfernt.
