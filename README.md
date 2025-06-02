# smart-waste-monitor
Final project for the Building AI course

## Summary
Een AI-systeem dat via camera’s of sensoren automatisch detecteert wanneer publieke vuilnisbakken vol zijn. Hierdoor kunnen stadsdiensten efficiënter plannen en vermijden we overvolle bakken in straten en parken.

## Background
In veel steden zijn publieke vuilnisbakken regelmatig overvol. Dit leidt tot:

zwerfvuil
onnodige ophaalrondes
geur- en hygiëneproblemen
Mijn motivatie is om AI te gebruiken om dit op een slimme manier op te lossen, zonder mensen telkens te laten controleren of bakken vol zijn.

## How is it used?
Het systeem wordt gebruikt door stadsdiensten. Via een dashboard of alerts zien ze:

welke vuilnisbakken (bijna) vol zijn
waar ze het eerst moeten ledigen
Het systeem gebruikt beelden van camera’s (of sensordata) en objectdetectie om het vulniveau in te schatten.

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/Smartbin_city_bin.png" width="300">
## Data sources and AI methods
Camerabeelden van publieke domeinen (bv. parken of pleinen)
Alternatief: IoT-sensoren die gewicht of afstand tot de deksel meten
AI-technieken:

Object detection (bv. YOLOv5)
Classificatie (volle/lege bak)
Eventueel tijdreeksvoorspelling voor ophaalplanning
## Challenges
Beeldkwaliteit en lichtcondities kunnen inschatting moeilijk maken
Privacy: beelden in publieke ruimte moeten anoniem blijven
Moeilijk om vulniveau goed te detecteren zonder referentie
## What next?
Integreren met route-optimalisatie voor vuilnisophaling
Werken met sensorgegevens (hybride AI + IoT)
Samenwerken met steden of lokale overheden voor echte data
UI bouwen voor meldingen (dashboard / app)
## Acknowledgments
Geïnspireerd door bestaande projecten zoals SmartBin
Object detection idee gebaseerd op YOLOv5
Cursus: Elements of AI – Building AI (Reaktor & Universiteit van Helsinki)
