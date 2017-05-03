Beveiliging van de Mac werkplek
===============================

Updaten
-------

Uit onderzoek is gebleken dat de beste beveiling voor je Mac is er voor te zorgen dat alle software up-to-date is. Dit betekent dat je de laatste versie van het macOS installeert en alle beveiligings- en programma updates. Oudere versies van macOS bevatten kwetsbaarheden die niet meer door Apple gerepareerd worden. Het zelfde geld voor applicaties die op je Mac draaien. De meest kwetsbare zijn natuurlijk de webbrowsers zoals Firefox en Chrome en de web plugins zoals Flash Player en de Java web plugin.

### Apple updates

Apple brengt regelmatig updates uit voor macOS. Gebruikers krijgen een melding dat de nieuwe software beschikbaar is. Er kan ook aangevinkt worden dat de software updates automatisch uitgevoerd moeten worden.


### Software via VU Software Center

Als je software via VU Software Center installeert, wordt deze ook automatisch ge-update. De updates worden eerst getest voordat ze geïnstalleerd worden. Kritieke updates zoals browsers en browser plugins worden via spoed updates geïnstalleerd en zijn vrijwel altijd binnen 24 uur na publicatie beschikbaar.

Systeemintegriteit
------------------

Via SIP (System Integrity Protection) worden delen van het Operating Systeem beveiligd tegen aanpassingen. Deze beveiliging werkt zelfs als de gebruiker administrator is. macOS komt standaard met SIP ingeschakeld, maar het is mogelijk om deze bescherming uit te schakelen.

#### VU policy
We kunnen het aanstaan van SIP monitoren en zonodig afdwingen.

Veilig bestanden opslaan
------------------------



Veilig inloggen
---------------

Je gebruikersnaam en wachtwoord geven toegang tot al je gegevens op de computer. Het is dus belangrijk om een veilig wachtwoord te kiezen. Er is op dit moment geen wachtwoord policy voor Mac computers, maar je kunt wel wachtwoord hints krijgen in het "Wijzig Wachtwoord" panel.

#### VU policy
Het is mogelijk een profiel aan te bieden dat een veilig lokaal wachtwoord afdwingt.

Veilig op (draadloze) netwerken
-------------------------------

Bescherming tegen Malware
-------------------------

MacOS heeft een aantal ingebouwde mechanismen om malware buiten de deur te houden:

#### Gatekeeper

Gatekeeper helpt een Mac te beschermen tegen apps die een negatieve invloed erop kunnen hebben. Programma's die van het internet worden gedownload of via de email binnenkomen worden door Gatekeeper gecontroleerd.

De werking van Gatekeeper kan door de gebruiker zelf worden ingesteld:
* Mac App Store – Alleen apps uit de Mac App Store kunnen worden geopend.
* Mac App Store en ontwikkelaars waarvan de identiteit bekend is (standaard in macOS) - Alleen apps uit de Mac App Store en apps van ontwikkelaars die Gatekeeper gebruiken, kunnen worden geopend.
* Elke willekeurige bron - Alle apps kunnen worden uitgevoerd, ongeacht hun bron op het internet.

#### VU policy

Het is mogelijk een profiel aan te bieden dat een veilige Gatekeeper configuratie afdwingt.

#### XProtect/File Quarantine

Bestanden die via het internet binnenkomen of via de email worden verstuurd, worden door macOS voorzien van een z.g.n. 'quarantine' attribuut. Hierdoor kunnen bestanden niet zomaar worden geopend. De bestanden worden ook gecontroleerd op malware, als die aangetroffen wordt krijgt de gebruiker een waarschuwing.
XProtect blokkeert ook verouderde versies van internet plugins zoals Flash of Java.

XProtect checkt dagelijks of er nieuwe definities zijn en past deze meteen toe als ze beschikbaar komen.

#### Malware Removal Tool (MRT)

macOS heeft een ingebouwde Malware Removal Tool, waarmee geavanceerde malware onschadelijk gemaakt kan worden. De tool wordt door SoftwareUpdate bijgewerkt. Er is geen configuratie van MRT mogelijk.

#### Adware

MacOS heeft geen ingebouwd mechanisme om zgn Adware tegen te gaan. Hiervoor kan een third party tool worden ingezet zoals Malwarebytes.

#### Antivirus

De ingebouwde antivirus voorziening heet XProtect (zie boven). Hoewel er veel antivirus software is voor de Mac, is deze over het algemeen van matige kwaliteit.
De algemene opvatting is dat antivirus software juist de veiligheid van de Mac verlaagd doordat het antivirusprogramma zelf onderwerp van een aanval kan worden.
Selecteren van een antivirus/antimalware oplossing voor de Mac moet gebeuren op basis van ervaring met het product in vergelijkbare omgevingen. Bijvoorbeeld IBM (100.000 Macs) installeert *geen* antivirus op de machines.

Zie ook [Overzicht van Endpoint Protection voor macOS](endpoint_protection.md)

#### VU

De VU biedt het programma ClamXav aan via VU Software Center. Gebruikers moeten dit zelf instellen en er is geen centrale reporting.

Schermbeveiling
---------------

macOS biedt de mogelijkheid om een wachtwoord te vragen (of een vingerafdruk) als de schermbeveiling wordt ingeschakeld of als de Mac wakker wordt gemaakt uit slaapstand (bijvoorbeeld bij een laptop als de laptop geopend wordt). De gebruiker kan de vertraging instellen op meteen, 5 sec, 1 min, 5 min, 15 min, 1 uur, 4 uur, 8 uur.

#### VU policy

Het is mogelijk een profiel aan te bieden dat een wachtwoord voor schermbeveiling afdwingt en ook de vertagingstijd instelt.

Veilig emailen
--------------

De ingebouwde macOS email client (Mail.app) heeft de mogelijkheid om veilig mail op te halen en te versturen via een ge-encrypte verbinding (TLS). Ook de Outlook client kan berichten via een versleutelde verbinding versturen.

### Signed email
Door middel van 'signed email' kan de afzender controleren dat het email bericht inderdaad door de afzender verstuurd is en niet onderweg is gemodificeerd. Zowel Mail.app als Outlook.app hebben ondersteuning voor 'signed email'.

### Encrypted email
Door de email 'encrypted' te versturen kan alleen de ontvanger de email lezen. Zowel Mail.app en Outlook.app hebben de mogelijkheid om email te encrypten.


Referenties
-----------

* [Gatekeeper - Apple website](https://support.apple.com/nl-nl/HT202491)
* [Mac security facts and fallacies](https://blog.malwarebytes.com/101/2017/03/mac-security-facts-and-fallacies/)
* [ClamXav - antivirus software](https://www.clamxav.com)
* [IBM: “Iedere Mac bespaart ons 400 euro tegenover Windows-PC”](https://www.onemorething.nl/2016/10/ibm-mac-bespaart-400-euro-tegenover-windows-pc/)
* [macOS Security and Privacy Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide)
