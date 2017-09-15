Roadmap voor de Mac werkplek op de Vrije Universiteit
=====================================================

De Mac werkplek is constant aan verandering onderhevig, de techniek wijzigt in hoog tempo en ook de eisen van de gebruikers zijn niet constant. Nieuwe technieken zoals Thin Imaging, Mobile Device Management, Device Enrollment Program, etc. kunnen worden toegepast om het beheer te vereenvoudigen en de gebruikerservaring te verbeteren.

Authenticated Software repository
---------------------------------

Op dit moment blokkeren we de toegang tot pakketten buiten de VU omdat we niet willen dat willekeurige mensen onze gelicenseerde software kunnen downloaden. Dit verhindert VU gebruikers om buiten de VU bepaalde pakketten te downloaden. Een oplossing hiervoor is om authenticatie toe te voegen aan de munki software repository die op basis van credentials toegang geeft aan machines die de juiste credentials hebben.

Automatic provisioning
----------------------

Met de komst van EMM (Enterprise Mobility Management) komt ook zgn zero-touch deployment in zicht. Als de EMM het zogenaamde `InstallApplication` commando ondersteunt, kunnen de Macs zonder tussenkomst van IT worden geprovisioned.

Op dit moment beschikt de VU alleen over een licentie voor Intune. Deze heeft (nog) geen DEP (Device Enrollment Program) support en is daarom niet geschikt voor 'Automatic Provisioning'.

EMM oplossingen die wel geschikt zijn:

  * VMWare AirWatch https://www.air-watch.com
  * SimpleMDM (alleen Apple devices) https://simplemdm.com

Meer informatie:

  * http://blog.eriknicolasgomez.com/2017/03/08/Custom-DEP-Part-1-An-Introduction/

Backup voor Mobile
------------------
