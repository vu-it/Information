Bestanden op de Mac werkplek
============================

De VU biedt een aantal plekken aan waar bestanden opgeslagen kunnen worden. De keuze welke opslagplaats geschikt is, is afhankelijk van verschillende factoren. Dit document beschrijft de mogelijkheden en de voor- en nadelen.

Op je Mac
---------

Je kunt bestanden op je Mac opslaan, deze staan dan op de lokale schijf. Je kunt deze bestanden delen met andere Mac gebruikers in de buurt via Airdrop.

Voordelen van bestanden op de lokale Schijf:

* Bestanden zijn altijd beschikbaar en snel doorzoekbaar
* Snel delen met andere Mac gebruikers in de buurt via Airdrop

Nadelen van bestanden op de lokale Schijf:

* Als de computer kapot gaat of gestolen wordt zijn de bestanden weg (zie ook onder: Backup)
* Als je niet achter je Mac zit zijn de bestanden niet toegankelijk


Persoonlijke folder (Homedirectory)
-----------------------------------

Elke medewerker (en student?) krijgt bij indiensttreding een persoonlijke folder die op een Fileserver van IT staat. Deze folder is op verschillende manieren te bereiken:

* SMB/CIFS - alleen op bedraad groen en rode netwerken toegankelijk, niet op draadloos of buiten de VU.
* WEBDAV - beschikbaar op alle netwerken, maar niet voor FEW/FALW medewerkers. Daarnaast zijn er issues met permissies, onzichtbare files en performance op de Mac.
* NFS - NFSv4 werkt alleen op groene netwerken en werkt niet goed met macOS.
* SFTP - beschikbaar op alle netwerken. Voor de Mac is extra software nodig (bijvoorbeeld ExpanDrive of CyberDuck).

Voordelen van de persoonlijke folder:

* Inhoud is alleen leesbaar voor de gebruiker
* Kan op elk Platform ontsloten worden
* Wordt regelmatig backup van gemaakt(op de server)

Nadelen van de persoonlijke folder:

* Grootte is beperkt (3GB initieel)
* Kan alleen benaderd worden als er een netwerk verbinding is
* Gewiste bestanden kunnen alleen door IT worden teruggehaald en dat heeft een lange doorlooptijd
* Je kunt geen bestanden delen met collega's op de VU of buiten de VU

Groepsfolder (G Schijf)
-----------------------

Elke afdeling heeft 1 of meer groepsfolders waarin de gedeelde bestanden staan. Deze folders zijn op dezelfde manier te bereiken als de persoonlijke folder.

Voordelen van de groepsfolder:

* Je kunt bestanden delen met collega's
* Kan op elk platform ontsloten worden
* Wordt regelmatig backup van gemaakt
* Gewiste bestanden kunnen alleen door IT worden teruggehaald en dat heeft een lange doorlooptijd

Nadelen van de groepsfolder:

* Je kunt geen bestanden delen met externen
* Permissies: Het is onduidelijk welke mensen bij welke folder kunnen (op de Mac)
* Discoverability: je moet weten welke folder je nodig hebt (server + pad) anders lastig te vinden

SURFdrive
---------

Surfdrive is een externe bestandsoplossing die beschikbaar is voor alle medewerkers. SURFdrive is op verschillende manieren bereikbaar:

* Via het web - je kunt bestanden uploaden/downloaden en verwijderen via een webbrowser
* Via de SURFdrive client applicatie - Je gebruikt een map op je Mac die gesynchroniseerd wordt met de SURFdrive server. Dit betekent dat je ook offline kunt werken.
* Via WEBdav - Er zijn wel issues met onzichtbare files en performance op de Mac.

Voordelen van SURFdrive:

* Beschikbaar binnen en buiten de VU
* Mogelijkheid tot offline werken
* Je kunt bestanden delen met collega's
* Je kunt gewiste bestanden tot 30 dagen zelf terughalen

Nadelen van SURFdrive:

* Niet alle bestandsnamen worden gesynchroniseerd en ook symlinks gaan niet mee met synchronisatie.
* De grootte is 100GB en niet uitbreidbaar
* Er is eigenlijk geen support binnen de VU

Cloud diensten (Dropbox, Onedrive, Google Drive)
------------------------------------------------

De VU biedt op dit moment geen andere Cloud diensten aan dan SURFdrive voor bestandsopslag. Toch zijn er veel VU medwerkers die hier gebruik van maken. Uit ons onderzoek blijkt dat Dropbox de meest compatibele oplossing is voor Mac gebruikers.

Voordelen van Dropbox:

* Beschikbaar binnen en buiten de VU
* Mogelijkheid tot offline werken
* Je kunt bestanden delen met collega's binnen en buiten de VU
* Versiebeheer: je kunt oudere versies van een document terughalen

Nadelen van Dropbox:

* Wordt niet gesupport door VU IT
* Kost geld
* De bestanden staan in Ierland (als je een Europese gebruiker bent) maar kunnen toch door de Amerikaanse overheid opgevraagd worden.

Backup
------

Om de lokale bestanden veilig te stellen is het raadzaam om een backup oplossing te gebruiken. Er zijn een aantal backup oplossingen mogelijk. Hieronder worden de meest gebruikte beschreven:

### Timemachine

macOS heeft een ingebouwde backup voorziening genaamd "Timemachine". Met Timemachine kun je automatisch backups maken van je bestanden op een externe opslag. De externe opslag kan een externe harde schijf zijn of een netwerk schijf.

Voordelen van Timemachine:

* Ingebouwd in macOS
* Backup is doorzoekbaar
* Terughalen van bestanden is eenvoudig

Nadelen van Timemachine:

* De VU biedt geen voorziening aan voor netwerk backups
* Externe schijf moet elke keer aangekoppeld worden om de backup te laten plaatsvinden

### Cloud Backup

Er zijn een aantal aanbieders van Cloud Backup voorzieningen die goed werken met macOS, bijvoorbeeld: CrashPlan Pro, Archiware Backup2go. De VU biedt helaas (nog) geen Cloud Backup voorziening aan.

Voordelen van Cloud Backup:

* De bestanden worden automatisch veiliggesteld als er netwerk verbinding is.
* Bestanden zijn zelf terug te halen als er netwerk verbinding is.

Nadelen van Cloud Backup:

* De VU biedt geen voorziening aan voor cloud backups
* De bestanden staan bij een derde partij, en kunnen mogelijk opgevraagd worden door één of andere instantie

Veiligheid
----------

Het is belangrijk dat de bestanden niet zomaar door iedereen te openen zijn, daarom wordt geadviseerd om de bestanden versleuteld op te slaan. Hieronder een opsomming van de meest gehanteerde technieken om bestanden versleuteld te bewaren:

* Bestanden op de Mac: gebruik Filevault
* Homedirectory en groepsfolder - bestanden zijn niet versleuteld,
* Timemachine backup: gebruik encrypted backups
* Cloud backup: kies een aanbieder die de bestanden versleuteld opslaat.
* Dropbox encrypt standaard de bestanden op de server
* SURFdrive: gebruik encrypted disk images (alleen op een Mac) of een third-party programma zoals Boxcrypt

Referenties
-----------

* Timemachine: https://support.apple.com/nl-nl/HT201250
* Filevault: https://support.apple.com/kb/PH25553?viewlocale=nl_NL&locale=nl_NL
* Crashplan Pro: https://www.crashplan.com/en-us/
* SURFdrive FAQ: https://www.surfdrive.nl/faq.html
