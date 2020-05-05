# Interaktionskonzept Seminar
Das Ziel des Projektes ist es, eine Kommunikationsplattform bereit zu stellen. Diese stellt verschiedenste Themen bereit unter denen die Kommunikation von Endgeräten und Logikeinheit stattfindet.

## Requirements
FREQ00 - Die Schnittstellen müssen Dokumentiert sein. <br/>
FREQ01 - Die Kommunikation muss über ein Protokoll stattfinden. <br/>
FREQ02 - Der MQTT Broker muss über das Internet erreichbar sein. <br/>
FREQ03 - Es müssen definierte Topics bereit gestellt werden. <br/>
FREQ04 - Die Kommunikation muss über die Definierten Topics Stattfinden<br/>
FREQ05 - Der Server muss über ein Webinterface wartbar sein.<br/>

### Use Case

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
