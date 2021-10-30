## Constructie Principes

### Inleiding

Dit hoofdstuk gaat over het daadwerkelijk construeren van een samenhangende architectuur voor digital twinning. Op basis van de hoofdlijnen van de architectuurprincipes worden in dit hoofdstuk de constructieprincipes en de daarbij behorende standaarden beschreven.

#### Wat is het doel van constructieprincipes?
De constructieprincipes geven richting aan de innovaties, de pilots en andere ontwikkelingen in het digital twin ecosysteem om de doelstellingen & visie van het programma NL-DFTL te behalen.
De constructieprincipes geven de kaders waarbinnen de innovaties, de pilots en andere ontwikkelingen zich moeten begeven, tenzij een tijdelijke afwijking noodzakelijk is. Hierop wordt gestuurd binnen het programma NL-DFTL.

#### Waarop zijn de constructieprincipes gebaseerd?
De constructieprincipes zijn gebaseerd op:
* De ontwerpprincipes van het programma NL-DFTL
* Wetgeving: Wet Open Overheid; Wet Hergebruik Overheidsinformatie, Archiefwet, Digitale toegankelijkheid
* Landelijke richtlijnen voor architectuur: NORA
* Landelijke richtlijnen voor gegevensbescherming: AVG & GDPR
* Landelijke richtlijnen voor software ontwikkeling: Common Ground
* overig <>...

#### Relatie constructieprincipes en capabilities/ bouwblokken
Voor de ordening van de constructieprincipes hebben we het overzicht van de capabilities of te wel "bouwblokken" gebruikt. De constructieprincipes zijn direct te relateren aan 5 lagen waarin de capabilities opgenomen zijn.
Om een digital twin toepassing te realiseren, bijvoorbeeld een landelijk geluid-simulatiemodel, is een combinaties van capabilities/ bouwblokken nodig. Doordat de constructieprincipes gerelateerd zijn aan de capabilities/ bouwblokken, is direct inzichtelijk welke constructieprincipes op de realisatie van toepassing zijn.  

De constructieprincipes zijn geordend op de 5 lagen van capability overzichtsplaat volgens Common Ground:
* Laag 1 - interactielaag met de gebruikersinterface van Digital twins waarin functionaliteit aanwezig is zoals bijvoorbeeld: 3D visualisatie, simulatie, what-if scenario, tijdreizen en gamification 
* Laag 2 - proceslaag met daarin functionaliteit voor bijvoorbeeld BIM gerelateerd werken.
* Laag 3 – integratielaag met functionaliteit voor data uitwisseling in digital twin ecosysteem
* Laag 4 - servicelaag met functionaliteit om allerlei soorten data uit laag 1 registratie-laag beschikbaar te stellen aan de boven liggende lagen middels open standaard services, datatransformatie en datamodel mapping, etc.
* Laag 5 – Registratielaag met datareristraties zoals bijvoorbeeld taakapplicaties, (basis)administraties, sensoren, complex event processing, maar ook digital twins als een bronsysteem.

Onderstaand een overzicht van de capabilities/ bouwblokken in het digital twin ecosysteem:

<figure id="infographic capabilities">
    <img src="media/infographic bedrijfsarchitectuur NLDFTL.jpg" alt="infographic capabilities">
    <figcaption>Dit is de plaat van het capability overzicht</figcaption>
</figure>

Onderstaand een overzicht van een toepassing in het digital twin ecosysteem die capabilities (in rood) gebruikt uit het overzicht:
<figure id="infographic capabilities2">
    <img src="media/infographic bedrijfsarchitectuur NLDFTL2.jpg" alt="infographic capabilities2">
    <figcaption>Dit is de plaat van een toepassing die capabilities (in rood) gebruikt uit het overzicht</figcaption>
</figure>

### Laag 1. Interactie- & business laag
De constructieprincipes die van toepassing zijn op de capabilities/ bouwblokken in de interactie- en business laag zijn beschreven in deze paragraaf. De capabilities, bouwstenen in deze laag 1 zijn:
* *####* Algoritmen
* *####* Business logic
* *#####* [Welk gebruiksdoel (= user story) wordt door de software geleverd?]
* *###* Analytics
* *####* (Big data) analyse tools
* *####* Self learning systems
* *####* Artificial Intelligence
* *####* Visualisatie componenten
* *#####* 2D afbeeldingen (data statisch)
* *#####* 3D afbeeldingen (data statisch)
* *#####* Dashboards
* *#####* Grafieken
* *#####* Monitors (data dynamisch)
* *#####* Simulaties (manipuleerbare data en modellen)
* *####* Rekenmodellen
* *####* Simulatiemodellen

| Principe 01 | Eerst hergebruik, dan ontwikkelen we open source programmacode voor functionaliteit die herbruikbaar en onafhankelijk is van dashboard-, monitor-, visualisatie- & simulatie tooling en is platform agnostic.                                |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Voor een nieuwe toepassing hergebruiken we functionaliteit, de programmacode, die al binnen het ecosysteem beschikbaar is. Indien de functionaliteit niet beschikbaar is ontwikkelen we open source, zodat de programmacode herbruikbaar is. We publiceren de de ontwikkelde programmacode incl. documentatie zodat andere daarop verder kunnen ontwikkelen. Een voorbeeld van een ontwikkeling is een simulatie- model voor mobiliteit. Indien van toepassingen spreken we organisatorische samenwerkingsverbanden af in ontwikkeltrajecten. |
| implicatie  | * we maken gebruik van programmacode onafhankelijke software   |
| | * We herbruiken beschikbare functionalitei, programmacode                  |
| | * We publiceren ontwikkelde functionaliteit, programmacode op GitHub (public tenzij private) incl. documentatie voor herbruikbaarheid.                                                              |
| | * We documenteren programmacode volgens de voorgeschreven standaarden      |
| | * We beheren de programmacode in een community, samenwerkingsverbanden     |
| | * We gebruiken software (dit kan betaalde software zijn met een licentie) die open source ontwikkelen ondersteunt |
| | * We ontwikkelen dashboard-, monitor-, visualisatie- & simulatie op infrastructuur die agnostisch is voor tooling |
| | * We ontwikkelen op infrastructuur die voldoet aan Common Ground richtlijnen, d.w.z. “haven-compliant” |
| |                                                                   |

| Principe 02 | Vertrouwd - Privacy & security worden integraal meegenomen in het ontwerp van de 3D visualisaties, simulaties, monitors, dashboards en voorspelmodellen.                                                      |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We houden ons aan wettelijke richtlijnen, nemen maatregelen om risico’s te minimaliseren, en verantwoorden naar betrokkenen wat we doen. We zorgen voor een goede beveiliging van gegevens en garanderen privacy. We ontwikkelen en borgen technische, organisatorische, fysieke en procedurele maatregelen voor privacy en informatiebeveiliging. |
| implicatie  | * Vanuit de informatiebeveiliging worden eisen gesteld aan de integriteit en vertrouwelijkheid van gegevens |
| | * Uitvoeren van de Data Protection Impact Assessment (DPIA) nieuwe en bestaande verwerkingen |
| | * Burgers hebben vanuit de Algemene Verordening Gegevensbescherming (AVG) het recht om op te vragen welke persoonsgegevens door de gemeente zijn verwerkt (inzagerecht) |
| | * We hebben een verwerkingsregister dat actueel wordt bijgehouden |
| | * 3D visualisaties, informatieproducten en data worden beveiligd afhankelijk van hun gevoeligheid |
| | * Vastleggen wie, wanneer en waarom welke persoonsgegevens heeft verwerkt |
| | * Inrichting monitoring en controle op gebruik van 3D visualisaties, informatieproducten en data |
| | * We auditen regulier op het gebruik van persoonsgegevens conform vastgestelde protocollen op gegevensbeveiliging|
| | * De data en informatie zijn alleen inzichtelijk voor die personen die het betreft en op zo'n wijze dat deze het inzicht bieden dat past bij de rol van de medewerker binnen de organisatie               |
| |                                                                   |

| Principe 03 | We ontwikkelen algoritmen die voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’. |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We toetsen de ontwikkeling en het gebruik van algoritmen op het risico van oneerlijke, bevoordeelde of discriminatoire uitkomsten. We houden toezicht op algoritmes wat betreft de beginselen van ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (fairness). Bij het ontwerpen en bij het gebruik van algoritmen nemen we gepaste waarborgen en maatregelen: dataprotection by design. |
| implicatie  | * We toetsen de algoritme op rechtmatigheid |
| | * We hebben de werking van het algoritme in begrijpelijke taal uitgelegd en gecommuniceerd met medewerkers en de burgers in een algoritme register ten behoeve van transparantie |
| | * We weten met welke data het algoritme getraind en ontwikkeld is, wat de data kwaliteit is en de eventueel gebreken in de trainingsdata. We letten op de vooroordelen en de bias en voorkomen dat die erin zijn |
| | * We voeren assessment uit en voorkomen eventueel bias en minderheden in de data en algoritime|
| | * We ontwikkelen het algoritme zodanig dat er gelijkwaardige uitkomsten gerealiseerd worden |
| | * We voeren een assessment van de fairness van het machine-learning algoritme en testen op basis van de maatstaven die belangrijk worden geacht. Deze maatstaven dienen gemonitord te worden zolang het algoritme wordt ingezet. Alle intenties, motivatie en potentiële gevaren van algoritme is gedocumenteerd  |
| |                                                                   |

| Principe 04 | Standaard - We standaardiseren maximaal in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang. We maken gebruik van software voor visualisatie, simulatie, dashboards, monitors op basis van open standaard webservices, data formaten, datamodellen en ontologiën.                         |
| implicatie  | * We gebruiken open standaarden: IFC 2.0; NLCS; BCF; 3D vector tiles; NLRS; NL/Sfb, COINS2 |
| | * Open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc                                  |
| | * We maken gebruik van ETSI CIM NGSI-LD Saref4City ontologie                                           |
| | * We maken gebruik van API strategie en design rules: API design rules en update API strategie         |
| | * We maken gebruik van Linked data open standaarden: JSON-LD, SparQL en RDF of OWL voor ontwikkelen ontologie |
| | * We gebruiken de INSPIRE Europese richtlijnen: INSPIRE - Europese leefomgeving                        |
| | * We gebruiken voor geografische data uitwisseling WMS en WFS en 3D data: CityGML en CityJSON          |
| | * We gebruiken NEN 3610 Basismodel Geoinformatie en ISO 19136: GML                                     |
| | * Europese richtlijnen Minimal Interoperability Mechanisms en Synchronicity architectuur                                                                     |
| | * Common Data Environment CDE conform ISO 19650; NEN2660                 |
| | * Datamodelleren conform de MIM standaard  |

| Principe 05 | Eenmalige vastlegging - Gegevens worden eenmalig vastgelegd, rechtstreeks bij de bron bevraagd en meervoudig gebruikt.                                                            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We voorkomen duplicatie (kopieën) van gegevens in de cloud omgeving van de aanbieder van visualisatie- dashboard-, simulatie tooling. Dit ten behoeve van leveranciersonafhankelijkheid en ter voorkoming van verouderde kopiegegevens die gebruikt worden. Het bronsysteem is een administratie, (basis)registratie, een documentregistratie, sensor en kan ook een digital twin of BIM zijn.                                                                |
| implicatie  | * Gegevens worden gescheiden van visualisatie- dashboard-, simulatie tooling bewaard, zodat opslag van gegevens onafhankelijk is van de gebruikte applicaties & softwareleveranciers en gegevens te (her)gebruiken zijn in verschillende applicaties voor verschillende doeleinden.                                       |
| | * Ieder gegeven wordt op precies één plek bijgehouden, zodat altijd duidelijk is wat het actuele brongegeven is en waar dat wordt beheerd. Dubbele opslag betekent synchroniseren, zodat partijen altijd naar dezelfde gegevens kijken. Dit geldt zowel binnen als buiten de oplossing, dus ook voor eventuele afgeleide opslag die geoptimaliseerd is ten behoeve van verstrekking.                                                        |
| | * Gegevens zijn alleen te registreren, wijzigen en raadplegen via dataservices, zodat de registratieservices kunnen garanderen dat de gegevens en metagegevens altijd voldoen aan de eisen en dat logging altijd plaatsvindt.                                       |
| | * Gegevens worden op betrouwbare en veilige wijze beheerd, zodat aangetoond kan worden dat gegevens niet bedoeld of onbedoeld gemanipuleerd zijn.                                                  |
| | * Samenhangend gebruik van gegevens is makkelijk mogelijk, zodat gegevens uit verschillende gegevensverzamelingen te combineren zijn.                                                                |
| |                                                                  |

| Principe 06 | Verbinden digital twins in ecosysteem - We maken gebruik canonieke data-objecten om digital twins met elkaar te kunnen verbinden en gemeenschappelijke smart city-ontologieen.              |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We gebruiken afgesproken canonieke data objecten. Dit betekent dat elk 3D visualisatie, simulatiemodel etc. uniforme data objecten heeft. In een volgend ontwikkel plateau kunnen we relaties leggen tussen digital twins (in verschillende domeinen) en navigeren via een graph, niet alleen via canoniek dataobjecten zoals “locatie”, maar in een gemeenschappelijke smart city-ontologie. Dit is een kennisgraaf met samenhang tussen de ontologieën van digital twins waarmee cross-domein data analyse mogelijk is. We relateren digital twins aan elkaar daar waar nuttig voor analyse en visualisatie.         |
| implicatie  | * We gebruiken afgesproken canonieke data objecten: 3D model heeft uniforme data objecten “RD- coördinaten”, “NAP”, “tijd”, “0-punt” (mogelijk aanvullende data objecten).                                    |
| | * In een volgend ontwikkel plateau maken we gebruik van Europese open standaard ontologie mapping SAREF extension: SAREF extension for Smart Cities (mariapoveda.github.io)                                                  |
| |                                                                                       |

| Principe 07 | Taken, bevoegdheden en verantwoordelijkheden in het gebruik van digital twins is in de organisatie belegd en werkafspraken zijn gemaakt.                                          |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We maken afspraken over het eigenaarschap van digital twins, bedrijfs- en dataobjecten en diverse rollen en verantwoordelijkheden die nodig zijn in het ontwikkelen, onderhouden, data- en informatie delen en beheren van digital twins. |
| implicatie  | * We hebben nieuwe rollen van medewerkers belegd in de Organisatie. Men is getraind en geïnstrueerd op de nieuwe taken te kunnen uitvoeren:                                                 |
| | * Digital twin eigenaar                                          |
| | * Digital twin coordinator                                       |
| | * Digital twin regisseur                                         |
| | * Digital twin analist                                           |
| | * Digital twin modelleur/ beheerder                              |
| | * Digital twin engineer                                          |
| | * Datasteward                                                    |
| | * Alle bedrijfsobjecten en onderliggende dataobjecten, hebben een eigenaar die verantwoordelijk is voor de integriteit, vertrouwelijkheid, kwaliteit en beschikbaarheid van de data.         |

De constructieprincipes voor de capabilities, bouwstenen in laag 1:
* *###* Presentatie
* *####* User interface
* *####* Customer Experience

| Principe 08 | Digitale toegankelijkheid - De presentatie van data- & informatie voldoet aan digitale toegankelijkheid.|
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We toetsen of de digitale informatie en diensten in het digital twin ecosysteem voldoet aan de digitale toegankelijkheid zodat de data- & informatie zowel bruikbaar is voor mensen met een functiebeperking als voor mensen zonder functiebeperking. Overheidsinstanties zijn bij wet verplicht om alle websites van de organisatie, websites, (mobiele) apps en digitale documenten waar de organisatie aan meebetaalt of medeopdrachtgever voor is, toegankelijk(er) te maken.                         |
| implicatie  | * We passen bij het maken van digitale informatie de standaarden toe: EN 301 549; WCAG 2.1 en WCAG-EM          | 
| | * We toetsen publicatie van digitale informatie op digitale toegankelijkheid en zorgen voor een toegankelijkheidsverklaring. Deze verklaring moet gemaakt zijn volgens het officiële model en geaccordeerd zijn door een bestuurder of tekenbevoegde medewerker                                           |
| | * We publiceren de actuele toegankelijkheidsverklaring(en) online. Dit is verplicht                        |
| | * Het is niet zo zwart-wit dat men op elk moment 100% aan de standaard voor digitale toegankelijkheid moet voldoen. Wel moet men als overheidsinstantie ‘in control’ zijn. Dat betekent dat men weet, ook als bestuurder, voor welke digitale communicatie de overheidsinstantie verantwoordelijk is, dat men de status weet en maatregelen benoemt met een planning om de toegankelijkheid te vergroten en grip te krijgen          |

### Laag 2. Proces- & business logica laag
In deze paragraaf zijn de constructieprincipes beschreven die van toepassing zijn op de capabilities/ bouwblokken in de proces- & business logica laag. De capabilities, bouwstenen in deze laag 2 zijn:
* BIM gerelateerd werken; samenwerken; workflow management; issue tracking

| Principe 09 | Proces logica is software onafhankelijk - De business rules en proces logica kunnen meervoudig worden gebruikt en is transparant naar de burger.                                          |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We zorgen en toetsen dat de proceslogica en businessrules zoals bijvoorbeeld beslisbomen is software tool onafhankelijk ontwikkeld worden en meervoudig gebruikt kunnen worden in andere software producten. In de proceslogica worden berekeningen gedaan, volgordelijkheid bijgehouden (proces of state) en functies uitgevoerd.          |
| implicatie  | * We maken gebruik van software tool onafhankelijk talen zoals BPMN, Python, Django, Go                                                                              |
| | * De proceslogica in BIM oplossing is software onafhankelijk en transparant |
| | * We zijn transparant en publiceren de proceslogica                         |
| | * We ontwikkelen proces logica in laag 2 en niet in de presentatie laag 1   |
| |                                                                             |

### Laag 3. Integratie laag
In deze paragraaf zijn de constructieprincipes beschreven die van toepassing zijn op de capabilities/ bouwblokken in de integratie laag.
De capability, bouwsteen in deze laag 3 is:
##### Gateway

| Principe 10 | Uniforme gegevensuitwisseling en integratie - De gegevens worden in digital twin ecosysteem uitgewisseld op basis van open standaard integraties en de integraties zijn software onafhankelijk.                                    |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We passen open standaarden en dataformaten toe en gebruiken landelijke referentie implementatie in het ontwikkelen van integraties tussen informatiesystemen in het digital twin ecosysteem ten behoeve van optimale gegevens uitwisseling.      |
| implicatie  | * We maken gebruik van de landelijke referentie implementatie NLX                                         |
| | * We ontwikkelen (systeem)integraties op basis van privacy-by-design                                                  |
| | * We ontwikkelen (systeem)integraties op basis van open standaarden en zorgen voor documentatie.                      |
| | * De ontwikkelde (systeem)integraties zijn vindbaar (Github) en herbruikbaar middels de actuele documentatie.         |

### Laag 2. Service laag
In deze paragraaf zijn de constructieprincipes beschreven die van toepassing zijn op de capabilities/ bouwblokken in de service laag.
De capabilities, bouwstenen in  deze laag 2 zijn:
* *####* Semantiek / ontologie
* *####* Dataobjectmodellen
* *####* Metadata
* *####* Attribuutbeveiliging
* *###* Masterdata / begrippen & definities
* *###* Datacommunicatie

<aside class='note'>
    JvG: Data Uitwisseling? 
    JvG: én Data Uitwisselingsstandaarden. 
</aside> 

* *####* Berichtformaat
* *####* Communicatieprotocol
* *#####* Service/ API
* *#####* Verwijsindex
* *###* Transformaties
* *####* Transformatieregels
* *####* Transformatiecomponent
* *###* Databewerking
* *####* Data verwerving
* *####* Dataverrijking
* *####* Toegang

<aside class='note'>
    JvG: Authenticatie noemen? zie ook [NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)
</aside> 

<aside class='note'>
    JvG: Vallen hier ook de informatiemodellen onder zoals de [NEN3610](https://www.geonovum.nl/geo-standaarden/nen-3610-basismodel-voor-informatiemodellen)? 
</aside> 

| Principe 11 | Voor de inrichting van processen, informatievoorziening en applicaties hanteert de gemeente een service-gerichte architectuur, de landelijke API strategie.      |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Voor de inrichting van processen, informatievoorziening en applicaties hanteren wij een service-georiënteerde architectuur. Informatievoorziening is gebaseerd op applicatiecomponenten in de proces-laag die elk een specifieke bedrijfsfunctie ondersteunen. Interactie tussen de registraties waarin de data opgeslagen is en de applicatiecomponenten vindt plaats op basis van gestandaardiseerde services om flexibiliteit en koppelbaarheid te vergroten. Deze services kunnen andere services aanroepen waardoor een gelaagde service-architectuur ontstaat.                                                                            |
| implicatie  | * Data in authentieke registers wordt via gestandaardiseerde- en beschreven services ontsloten.        |
| | * Service georiënteerd werken heeft altijd de voorkeur boven andere manieren van koppelen. Dit is enerzijds door het ontmoedigen van "silo-applicaties" en leverancier specifieke integraties                                                           |
| | * Servicegerichte architectuur betekent gebruik maken van standaard webservices, de API strategie en design rules: Consultatie API design rules en update API strategie | Geonovum                                                                        |
| | * Geografische data passen we de open standaarden toe WMS & WFS; NEN 3610 Basismodel Geoinformatie; ISO 19136: GML en voor 3D data: CityGML en CityJSON                                                                                                    |
| | * De ontwikkelde services/API's zijn vindbaar (Github) en herbruikbaar middels de actuele documentatie.            |

| Principe 12 | We hanteren uniforme begrippen & definities voor gegevens.                   |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Om het delen en hergebruiken van gegevens mogelijk te maken worden voor zowel gestructureerde- als ongestructureerde gegevens uniforme definities gebruikt. Iedere bedrijfsobject en onderliggend data object heeft een definitie die eenduidig is beschreven en vastgelegd. Door eenduidige definities van bedrijfs- en data objecten in datamodellen wordt het mogelijk om de informatie correct uit te wisselen op zowel syntactisch als semantisch niveau, zonder interpretatie verschillen. Bij het ontwikkelen van rapportages en van registratiesystemen voorkomt bedrijfs- en data objecten met een eenduidige definitie misvattingen en misinterpretaties.                                                                            |
| implicatie  | * We maken in het ontwerp van de services en registraties in de informatiesystemen gebruik van de landelijk vastgestelde informatiemodellen en standaarden. Zoals het landelijk bedrijfsobjectenmodel GEMMA en standaard informatiemodellen zoals ZTC 2.0, RSGB, RGBZ, IMRO, IMWA, IMKICH.                                                                |
| | * Voor maximale interoperabiliteit is het van belang dat structuur en syntax gestandaardiseerd zijn |
| | * We standaardiseren de semantiek van gegevens conform de werkelijkheid                             |
| | * Bij uitwisseling van gegevens maken we ook de context van het gebruik van gegevens inzichtelijk   |
| | * We gebruiken gegevens volgens een eenduidige landelijke taxonomie                                 |
| | * We passen typering van gegevens toe volgens uniforme landelijke bedrijfs- en data objecten met een eenduidige in de dataobjectmodellen in de landelijke repository/ datacatalogus                                           |
| |                                                                                                     |

| Principe 13 | We borgen de beschikbaarheid, vertrouwelijkheid en integriteit van gegevens (BIV).      |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Gegevens die binnen digital twin ecosysteem en organisaties worden gegevens verwerkt worden, worden conform de overeengekomen kaders beschikbaar gesteld en beveiligd tegen ongeautoriseerde toegang, frauduleus gebruik of mutatie en gegevensverlies. De eigenaar van digital twin, informatiesysteem dan wel registratie zorgt ervoor dat afnemers van vertrouwelijke gegevens enkel de gegevens verstrekt krijgen waar ze conform hun doelbinding recht op hebben.           |
| implicatie  | * We voldoen aan wet- en regelgeving nemen organisatorische-, procedurele- en technische maatregelen in  het beschikbaar stellen van data, bewerkingen en transformaties.                                            |
| | * We voeren Data Protection Impact Assessment (DPIA)3 uit op bestaande & nieuwe dataverwerkingen    |
| | * We voldoen aan de Baseline informatiebeveiliging Overheid (BIO) in data services, transformaties  |
| | * Toegang tot privacygevoelige gegevens wordt alleen geboden aan afnemers met doelbinding. Een gebruiker heeft toegang tot de data waarvoor hij/ zij geautoriseerd is. Dit wordt vastgelegd in de gegevens-leveringsovereenkomsten (GLO)   |
| | * Alle bedrijfsobjecten en onderliggende dataobjecten, hebben een eigenaar die verantwoordelijk is voor de integriteit, vertrouwelijkheid, kwaliteit en beschikbaarheid van de data.                                                                                                    |
| | * Auditing vindt plaats op het gebruik van persoonsgegevens conform vastgestelde protocollen en gegevensbeveiliging |

### Laag 1. Registratie laag
In deze paragraaf zijn de constructieprincipes beschreven die van toepassing zijn op de capabilities/ bouwblokken in de service laag.
De capabilities, bouwstenen in deze laag 1 zijn:
* *###* Infrastructuur
* *####* Datacenter
* *####* Cloud
* *#####* Public
* *#####* Private
* *####* Netwerk
* *#####* Public
* *#####* Private
* *###* Internet of Things
* *####* Sensoren
* *####* Scada
* *####* Remote sensing
* *####* Edge computing
* *###* Dataopslag
* *####* Traditioneel registratie
* *####* In memory

| Principe 14 | We borgen de duurzame toegankelijkheid van gegevens daar waar het vereist is.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Gegevens worden conform de geldende bewaar- en vernietigingstermijnen uit de vigerende wet- en regelgeving behandeld (Archief Wet). Zowel gestructureerde als ongestructureerde gegevens worden duurzaam toegankelijk gehouden. |
| implicatie  | * We voldoen aan wet- en regelgeving zoals de Archiefwet                                   |
| | * Verantwoording kunnen afleggen over uitgevoerde acties en transparantie                              |
| | * We zorgen er voor dat de opslag van gegevens duurzaam is                                             |
| | * We bewaren gegevens niet langer dan nodig is                                                         |
| | * We nemen maatregelen voor tijdige en volledige archivering van gegevens.                             |

| Principe 15 | We beheren de kwaliteit van gegevens actief middels continue verbetering en communiceren de kwaliteit.     |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | De kwaliteit van de gegevens die worden verwerkt binnen de gemeente wordt actief gemonitord en continu verbeterd en op een niveau gehouden wat in overeenstemming is met de eisen die daar vanuit de wetgeving en de afnemers aan gesteld worden. Datakwaliteit sluit aan op het proces waarbinnen het gebruik gegenereerd wordt. De kwaliteit wordt gepubliceerd.           |
| implicatie  | * Processen die het kwaliteitsbeheer en continu verbeteren borgen zijn ingericht                           |
| | * De kwaliteit van gegevens zijn van alke databron vastgelegd als metadata                                             |
| | * Buiten de syntactische correctheid van gegevens bewaakt men ook de integriteit over gegevens- verzamelingen heen     |
| | * Afnemers dienen aan te geven wat hun eisen zijn ten aanzien van de kwaliteit en actualiteit van gegevens. Datakwaliteit wordt afgesproken en vastgelegd de GLO gegevens levering overeenkomst                                                            |
| | * Datakwaliteit wordt geoptimaliseerd voor het proces waarbinnen het gebruikt wordt. De broneigenaar (en proceseigenaar) is verantwoordelijk voor de optimalisatie.                                                                                    |
| | * Proceseigenaren zien erop toe dat de data, de data die binnen een proces worden ingewonnen of geactualiseerd. Datakwaliteit wordt door proceseigenaren voortdurend gerapporteerd en datakwaliteit inzichtelijk aangeboden in datacatalogus, aangeduid met een kwaliteitslabel op een duidelijke schaal conform de handreiking gegevenskwaliteit.                                         |

| Principe 16 | Alle databronnen zijn een logisch onderdeel van digital twin ecosysteem die onderling samenhang en uniform zijn in het gegevenslandschap van ecosysteem.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Alle binnen digital twin ecosysteem aanwezige databronnen hebben een logische functie in het totaal aan beschikbare bronnen, vastgelegd in gemeenschappelijke datamodellen. We maken afspraken over datamodelleren in een afspraken document (bijvoorbeeld Waterschappen DAMO Data Afspreken Model Ondersteunend). We hergebruiken bestaande generieke landelijke informatie modellen en standaarden en wijken af of voegen data objecten toe daar waar het werkproces dit bepaald. |
| implicatie  | * Vastleggen data- & informatiemodellen met bedrijfs-/ data objecten/begrippen en definities in landelijke UML repository  |
| | * We hergebruiken landelijke datamodellen zoals IMRO, BRK, NEN3620, IMBOR, IMGeo, IMSW, IMKL, IMVG, etc.                              |
| | * Modelleren van datamodellen in UML conform conventies van MIM standaard (Metamodel voor Informatiemodellering)                |
| | * We documenteren het gebruik van datamodellen en stellen het vrij toegankelijk  |
| | * We registeren objecten (‘begrippen’) en definities in objectenhandboek van digital twin ecosysteem  |
| | * Logisch datamodel is het beschrijvende datamodel met alle definities van de objecten en attributen en is als dit objectenhandboek beschikbaar voor iedereen  |
| | * Fysiek datamodel is de vertaling van het logische datamodel naar een fysieke realisatie inclusief de benodigde installatie- en upgrade procedure  |

| Principe 17 | Alle databronnen, informatie producten en digital twins in digital twin ecosysteem zijn vindbaar en zijn voorzien van metadata.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Alle binnen digital twin ecosysteem aanwezige databronnen, informatie producten en digital twins zijn vindbaar. |
| implicatie  | * Er is een federatief stelsel van landelijke datacatalogi met daarin geregistreerd alle binnen het digital twin ecosysteem gebruikte databronnen, databestanden, informatie producten en digital twins met de relevante metadata conform DCAT standaard en DMTO Duurzaam Toegankelijke Overheidsinformatie voor archivering en vernietiging in de Datacatalogus. Data Catalog Vocabulary (DCAT) is een metadata-standaard en is ontworpen om interoperabiliteit tussen gegevenscatalogi te vereenvoudigen  |
| | * We hergebruiken landelijke datacatalogi                              |
| | * Geografische metadata wordt vastgelegd conform ISO 19115 metadata standaard.               |
| | * Er is een integrale zoekmachine voor het vinden van gegevens in het federatief stelsel van catalogi.               |

| Principe 18 | <<under construction>> Linked data is een manier om informatie te structureren en te delen met behulp van links. Deze links maken gegevens zinvoller en nuttiger in diverse toepassingen.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Linked Data is een manier om gestructureerde data te publiceren zodanig dat data met elkaar verbonden kan worden. Het is gebaseerd op de fundamenten van het World Wide Web en is in grote mate gestandaardiseerd met open W3C standaarden. Data krijgt betekenis (semantiek), waardoor de data beter ingezet (hergebruik) kan worden. Dit zal resulteren in innovatie en betere dienstverlening, waarmee economische en maatschappelijke waarde wordt gecreëerd. Linked Data is gebaseerd op de gedachte dat bij het verbinden van inhoud met inhoud de relatie betekenisvol gemaakt moet worden. |
| implicatie  | * Geef alle dingen waaraan je wilt kunnen linken, een uniek adres op internet (Uniform Resource Identifiers; URIs), conform de Nederlandse URI-strategie  |
| | * Gebruik HTTP-URI’s zodat er naar deze dingen kan worden verwezen en ze kunnen worden opgezocht door mensen en machines                              |
| | * GLeg de informatie over het concept vast in een ‘triple’ (subject-predicaat-objectrelatie). Leg die triple vast en maak het beschikbaar op basis van standaarden, zoals RDF of OWL. Presenteer linked data middels een endpoint in SPARQL of JSON-LD. Gebruik SKOS (Simple Knowledge Organization System) voor het maken van taxonomieen en thesauri, het is een internationale standaard.               |
| | * Neem links naar andere gerelateerde, open data - concepten op in de beschrijving om het ontdekken van gerelateerde informatie op het web te verbeteren.               |

Algemene capabilities waar nog constructieprincipes toegevoegd moeten worden zijn (under construction):
### Beveiliging
.
##### Identity catalogus
.
##### Identity check

##### Identity federation (bijv. SAML)
.
#### Autorisatie
.
##### Autorisatie register
.
##### Autorisatie check
.
##### Autorisatie federatie
.
### Ontwikkeling
.
#### Building
.
##### Development tooling
.
#### Testing
.
##### Test procedures

##### Test tooling
.
### Beheer
.
#### ASL
.
#### Console
.
#### ITIL
.
