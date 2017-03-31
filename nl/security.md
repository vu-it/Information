Beveiliging van de Mac werkplek
===============================

Updaten
-------

Uit onderzoek is gebleken dat de beste beveiling voor je Mac is er voor te zorgen dat alle software up-to-date is. Dit betekent dat je de laatste versie van het macOS installeert en alle beveiligings- en programma updates. Oudere versies van macOS bevatten kwetsbaarheden die niet meer door Apple gerepareerd worden. Het zelfde geld voor applicaties die op je Mac draaien. De meest kwetsbare zijn natuurlijk de webbrowsers zoals Firefox en Chrome en de web plugins zoals Flash Player en de Java web plugin.

### Software via VU Software Center

Als je software via VU Software Center installeert, wordt deze ook automatisch ge-update. De updates worden eerst getest voordat ze geïnstalleerd worden. Kritieke updates zoals browsers en browser plugins worden via spoed updates geïnstalleerd en zijn vrijwel altijd binnen 24 uur na publicatie beschikbaar.

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

Bestanden die via het internet binnenkomen of via de email worden verstuurd, worden door macOS voorzien van een quarantine attribuut. Hierdoor kunnen bestanden niet zomaar worden geopend. De bestanden worden ook gecontroleerd op malware, als die aangetroffen wordt krijgt de gebruiker een waarschuwing.
XProtect blokkeert ook verouderde versies van internet plugins zoals Flash of Java.

XProtect checkt dagelijks of er nieuwe definities zijn en past deze meteen toe als ze beschikbaar komen.

#### Adware

MacOS heeft geen ingebouwd mechanisme om zgn Adware tegen te gaan. Hiervoor kan een third party tool worden ingezet zoals Malwarebytes.

#### Antivirus

De ingebouwde antivirus voorziening heet XProtect (zie boven). Hoewel er veel antivirus software is voor de Mac, is deze over het algemeen van matige kwaliteit. Selecteren van een antivirus/antimalware oplossing voor de Mac moet gebeuren op basis van ervaring met het product in vergelijkbare omgevingen. Bijvoorbeeld IBM (100.000 Macs) installeert *geen* antivirus op de machines.

Zie ook [Overzicht van Endpoint Protection voor macOS](endpoint_protection.md)

#### VU

De VU biedt het programma ClamXav aan via VU Software Center. Gebruikers moeten dit zelf instellen en er is geen centrale reporting.

Schermbeveiling
---------------

macOS biedt de mogelijkheid om een wachtwoord te vragen (of een vingerafdruk) als de schermbeveiling wordt ingeschakeld of als de Mac wakker wordt gemaakt uit slaapstand (bijvoorbeeld bij een laptop als de laptop geopend wordt). De gebruiker kan de vertraging instellen op meteen, 5 sec, 1 min, 5 min, 15 min, 1 uur, 4 uur, 8 uur.

#### VU policy

Het is mogelijk een profiel aan te bieden dat een wachtwoord voor schermbeveiling afdwingt en ook de vertagingstijd.

Veilig emailen
--------------




Referenties
-----------

* [Gatekeeper - Apple website](https://support.apple.com/nl-nl/HT202491)
* [Mac security facts and fallacies](https://blog.malwarebytes.com/101/2017/03/mac-security-facts-and-fallacies/)
* [ClamXav - antivirus software](https://www.clamxav.com)
* [IBM: “Iedere Mac bespaart ons 400 euro tegenover Windows-PC”](https://www.onemorething.nl/2016/10/ibm-mac-bespaart-400-euro-tegenover-windows-pc/)
