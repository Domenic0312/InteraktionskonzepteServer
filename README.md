# Interaktionskonzept Seminar
Das Ziel des Projektes ist es, eine Kommunikationsplattform bereit zu stellen. Diese stellt verschiedenste Themen bereit unter denen die Kommunikation von Endgeräten und Logikeinheit stattfindet.

## Requirements
FREQ00 - Die Schnittstellen zwischen den Teilnehmern müssen Dokumentiert sein. <br/>
FREQ01 - Der Broker muss über das Internet erreichbar sein. <br/>
FREQ02 - Die Kommunikation muss über die Definierten Topics Stattfinden<br/>
FREQ03 - Der Broker muss über ein Webinterface wartbar sein.<br/>
FREQ04 - Endgeräte müssen sich am Server anmelden können.<br/>
FREQ05 - Endgeräte müssen dem Server mitteilen können welche Topics sie abbonieren wollen.<br/>
FREQ06 - Der Broker muss Informationen empfangen.<br/>
FREQ07 - Der Broker muss Informationen nach Bedarf weiterleiten.<br/>

NFREQ00 - Die Kommunikation muss über ein Protokoll stattfinden. <br/>

#### Anleitung zum Kommunikationsaufbau
1. Python Installieren
  -Python Runterladen: https://www.python.org/downloads/
  -Exe Datei ausführen
  -!!! Bei der Installation die Path Variable setzen erlauben!!!

2. paho MQTT Installieren
  -pip Installieren (falls nicht vorhanden) https://pip.pypa.io/en/stable/installing/
  -paho MQTT Installieren (in Kommandozeile ausführen): "pip install paho-mqtt"

3. Test dateien Ausführen (jeweils eine kommandozeile)(Dateien liegen im "Kommunikation" Ordner)
  - python sub.py
  - python pub.py
4. Erfolg haben
  -In dem sub.py fenster ist jetzt ein "Hello World!" zu sehen
