Windows programma's uitvoeren op de Mac werkplek
================================================

Hoewel er heel veel programma's beschikbaar zijn voor de Mac (Microsoft Office, Outlook, Adobe Suite, Matlab, etc.) zijn er soms programma's die alleen voor het Windows platform beschikbaar zijn (Microsoft Access, Microsoft Visio). Daarnaast zijn er Concern applicaties zoals SAPGui die niet goed aangepast zijn voor de Mac. Om toch Windows applicaties op de Mac te kunnen gebruiken zijn een aantal methoden beschikbaar. Dit document beschrijft deze en geeft aan welke beschikbaar zijn op de VU.

Citrix Receiver (SaaS)
----------------------

Via het programma Receiver van Citrix kunnen losse Windows programma's gestart worden op de Mac. Deze service staat bekend als SaaS (Software as a Service) en is beschikbaar voor VU medewerkers.
De programma's verschijnen in een eigen venster dat tussen de Mac vensters staat. Vanuit deze programma's heb je toegang tot de netwerkschijven van de VU, maar ook tot de opslag van je eigen computer. Programma's en toegang worden op aanvraag toegekend, maar er is geen overzicht van alle beschikbare programma's.

Voordelen Citrix Receiver (Saas):

* Programma's zijn beschikbaar zonder aanpassingen aan de Mac werkplek
* Programma's worden up-to-date gehouden door IT

Nadelen Citrix Receiver (SaaS):

* Programma's zijn alleen beschikbaar als er netwerk verbinding is.
* Niet alle programma's zijn direct beschikbaar (moeten aangevraagd worden).
* Het opstarten gaat soms wat traag.
* Het instellen van het toetsenbord is soms wat bewerkelijk.

Citrix Reciever (DaaS)
----------------------

In plaats van losse programma's zoals hierboven beschreven bij SaaS, biedt Citrix ook de mogelijkheid om een volledige Windows Desktop te starten. Deze service staat bekend als DaaS (Desktop as a Service) en is ook beschikbaar voor alle medewerkers van de VU.

Voordelen Citrix Receiver (Daas):

* Je kunt op een full-screen Windows desktop werken alsof je achter een (groene) PC zit.
* Het systeem wordt up-to-date gehouden door IT

Nadelen Citrix Receiver (Daas):

* Zie de nadelen van SaaS hierboven.
* Het tegelijk werken met Mac en Windows applicaties is minder handig.

Virtuele Machine (VM)
---------------------

Met een virtuele machine kun je een Windows (of Linux) computer op je Mac gebruiken. Je hebt hiervoor een speciaal programma nodig zoals VMWare Fusion, Parallels Desktop of Virtual Box.

Voordelen van een Virtuele Machine:

* Altijd beschikbaar ook als er geen netwerk connectie is
* Zelf aan te passen/programma's te installeren

Nadelen van een Virtuele Machine:

* Windows en programma's moeten zelf up-to-date gehouden worden.
* Virtuele machine gebruikt processortijd, geheugen en diskruimte, dit is vooral op laptops een issue.
* Configuratie is meer werk.


Remote Desktop
--------------

Met Remote Desktop kun je het scherm van een Windows PC overnemen. Je hebt hiervoor wel netwerktoegang nodig tot deze PC of je gebruikt Remote Desktop via Citrix.

Voordelen van Remote Desktop:

* Je hebt je eigen werkomgeving zoals je die zelf hebt ingericht.
* Remote Desktop gebruikt geen resources van je mac (processor, geheugen, diskruimte)

Nadelen van Remote Desktop:

* Alleen beschikbaar als er netwerk connectie is.
* De PC moet aanstaan.
* Geen directe toegang tot de opslag van de Mac
