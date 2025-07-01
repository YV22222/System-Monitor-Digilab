# System-Monitor-Digilab

## Projektübersicht

Das Projekt "System-Monitor-Digilab" ist ein lokal betriebenes Überwachungssystem für den Raspberry Pi. Es verwendet ein Digilab-Touchdisplay zur Anzeige von Systeminformationen in Echtzeit. Ziel ist es, wichtige Daten wie CPU-Auslastung, Temperatur, RAM-Nutzung und Netzwerkstatus übersichtlich darzustellen – ohne Internetverbindung oder zusätzliche Geräte. Das System eignet sich gut für Serverüberwachung, Technikprojekte oder den Einsatz im Labor.

## Hauptfunktionen

Der System-Monitor zeigt auf dem Digilab-Touchscreen verschiedene Systemdaten des Raspberry Pi an. Dazu gehören die CPU-Temperatur, die CPU-Auslastung (gesamt und pro Kern), die aktuelle RAM-Nutzung, die IP-Adresse und der Netzwerkstatus. Zusätzlich werden die Systemlaufzeit (Uptime) und der Hostname angezeigt. Die Benutzeroberfläche ist für Touchbedienung ausgelegt und aktualisiert die angezeigten Werte automatisch im Abstand von wenigen Sekunden.

## Erweiterungsmöglichkeiten

Das System kann durch zusätzliche Hardware ergänzt werden. Möglich sind unter anderem LEDs zur Anzeige bestimmter Zustände (zum Beispiel bei Überhitzung), Taster für Funktionen wie Herunterfahren oder Neustart, sowie externe Displays wie LCDs oder OLEDs. Auch ein akustisches Warnsignal über einen Buzzer kann eingebaut werden.

## Verwendete Technologien

Die Anwendung basiert auf Node.js. Für das Auslesen der Systeminformationen wird das npm-Modul "systeminformation" verwendet. Für die Ansteuerung von GPIO-Pins (z. B. für LEDs oder Tasten) können Bibliotheken wie "onoff" oder "rpi-gpio" eingesetzt werden. Optional kommen Python-Skripte zum Einsatz, etwa zur Ansteuerung von LCDs über I2C. Die grafische Oberfläche wird direkt auf dem Digilab-Touchscreen angezeigt.

## Voraussetzungen

Für dieses Projekt wird ein Raspberry Pi ab Modell 5 benötigt. Ein funktionierender Digilab-Touchscreen muss angeschlossen und konfiguriert sein. Außerdem muss Node.js in Version 18 oder höher installiert sein. Falls zusätzliche Hardware wie LEDs oder Displays verwendet wird, müssen diese korrekt über GPIO angeschlossen und eingebunden werden.

## Zukünftige Erweiterungen

Geplant sind unter anderem eine Warnanzeige bei zu hoher Temperatur, eine grafische Darstellung der CPU-Last, eine steuerbare Hintergrundbeleuchtung für das Display sowie ein Energiesparmodus bei längerer Inaktivität. Zusätzlich soll beim Start des Systems ein Selbsttest erfolgen, der grundlegende System- und Netzwerkinformationen überprüft..

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz und darf für schulische, private und technische Zwecke verwendet, verändert und weitergegeben werden.

