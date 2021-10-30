## Constructie Principes

### Inleiding

Dit hoofdstuk gaat over het daadwerkelijk construeren van een samenhangende architectuur voor digital twinning. Op basis van de hoofdlijnen van de architectuurprincipes worden in dit hoofdstuk de constructieprincipes en de daarbij behorende standaarden beschreven.

Voor de ordening van de ontwerpprincipes wordt het overzicht van de capabilities of te wel "bouwblokken" gebruikt. De ontwerpprincipes zijn direct te relateren aan capabilities.
Voor een bepaalde digital twin toepassing te realiseren, bijvoorbeeld een geluid simulatiemodel, is een combinaties van capabilities/ bouwblokken nodig. Doordat de ontwerpprincipes gerelateerd zijn aan de capabilities/ bouwblokken is inzichtelijk welke ontwerpprincipes op de realisatie van toepassing zijn.  

De ontwerpprincipes zijn te plotten op 5 lagen van capability overzichtsplaat:
* Laag 1 - interactie-laag met de gebruikersinterface van Digital twins waarin functionaliteit aanwezig is zoals bijvoorbeeld: 3D visualisatie, simulatie, what-if scenario, tijdreizen en gamification 
* Laag 2 - proces-laag met daarin functionaliteit voor bijvoorbeeld BIM gerelateerd werken.
* Laag 3 – integratie-laag met functionaliteit voor data uitwisseling in digital twin ecosysteem
* Laag 4 - service laag met functionaliteit om allerlei soorten data uit laag 1 registratie-laag beschikbaar te stellen aan de boven liggende lagen middels open standaard services, datatransformatie en datamodel mapping, etc.
* Laag 3 – Registraties laag met datareristraties zoals bijvoorbeeld taakapplicaties, (basis)administraties, sensoren, complex event processing, maar ook digital twins als een bronsysteem.

De ontwerpprincipes zijn afgeleid van
* NORA
* Common Ground
* Wetgeving: Wet Open Overheid; Wet Hergebruik Overheidsinformatie, Archiefwet
* AVG & GDPR
* Doelstellingen & visie
* overig

<figure id="infographic capabilities">
    <img src="media/infographic bedrijfsarchitectuur NLDFTL.jpg" alt="infographic capabilities">
    <figcaption>Dit is de plaat van het capability overzicht</figcaption>
</figure>

### Laag 1. Interactie- & business laag
Ontwerppricipes die van toepassing zijn op de capabilities/ bouwblokken in de interactie- en business laag
De interactie- & business laag bestaat uit de volgende capabilities, bouwstenen:
#### Algoritmen
tekst.
#### Business logic
tekst.
##### [Welk gebruiksdoel (= user story) wordt door de software geleverd?]
tekst.
### Analytics
tekst.
#### (Big data) analyse tools
tekst.
#### Self learning systems
tekst.
#### Artificial Intelligence
tekst.
### Presentatie
tekst.
#### User interface
tekst.
#### Customer Experience
tekst.
#### Visualisatie componenten
tekst.
##### 2D afbeeldingen (data statisch)
tekst.
##### 3D afbeeldingen (data statisch)
tekst.
##### Dashboards
tekst.
##### Grafieken
tekst.
##### Monitors (data dynamisch)
tekst.
##### Simulaties (manipuleerbare data en modellen)
tekst.

| Principe 01 | We ontwikkelen open source en publiceren de code die herbruikbaar en vrij toegankelijk is, dashboard-, monitor-, visualisatie- & simulatie tool en platform agnostic is, tenzij                                |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We maken gebruik van de programmacode en (deel)producten die al in de markt beschikbaar zijn. We publiceren de eigen ontwikkelde programma code en producten/kennis, stellen het beschikbaar zodat andere daarop verder kunnen ontwikkelen. Een voorbeeld van programmacode is een simulatie model voor mobiliteit. Indien wenselijk spreken we samenwerkingsverbanden af. |
| implicatie  | * we maken gebruik van programmacode onafhankelijke software   |
| | * We maken gebruik van beschikbare programmacode                   |
| | * We publiceren programmacode op GitHub (public tenzij private)    |
| | * We documenteren programmacode volgens de voorgeschreven standaarden |
| | * We beheren de programmacode in een community                     |
| | * We gebruiken software (dit kan betaalde software zijn met een licentie) die open source ontwikkelen ondersteunt |
| | * We ontwikkelen op infrastructuur die agnostisch is                |
| | * We ontwikkelen op infrastructuur die voldoet aan Common Ground richtlijnen, is “haven-compliant” |
| |                                                                   |

| Principe 02 | Vertrouwd - Privacy & security worden integraal meegenomen in het ontwerp van de 3D visualisatie (simulatie, voorspelmodel)                                                      |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We houden ons aan wettelijke richtlijnen, nemen maatregelen om risico’s te minimaliseren, en verantwoorden naar betrokkenen wat we doen. We zorgen voor een goede beveiliging van gegevens en garanderen privacy. We ontwikkelen en borgen technische, organisatorische, fysieke en procedurele maatregelen voor privacy en informatiebeveiliging. |
| implicatie  | * Vanuit de informatiebeveiliging worden eisen gesteld aan de integriteit en vertrouwelijkheid van gegevens |
| | * Uitvoeren van de Data Protection Impact Assessment (DPIA) nieuwe en bestaande verwerkingen |
| | * Burgers hebben vanuit de Algemene Verordening Gegevensbescherming (AVG) het recht om op te vragen welke persoonsgegevens door de gemeente zijn verwerkt (inzagerecht) |
| | * Het hebben van een verwerkingsregister |
| | * 3D visualisaties, informatieproducten en data worden beveiligd afhankelijk van hun gevoeligheid |
| | * Vastleggen wie, wanneer en waarom welke persoonsgegevens heeft verwerkt |
| | * Inrichting monitoring en controle op gebruik van 3D visualisaties, informatieproducten en data |
| | * Auditing op het gebruik van persoonsgegevens conform vastgestelde protocollen |
| | * Auditing op gegevensbeveiliging |
| | * De data en informatie zijn alleen inzichtelijk voor die personen die het betreft en op zo'n wijze dat deze het inzicht bieden dat past bij de rol van de medewerker binnen de organisatie               |
| |                                                                   |

| Principe 03 | We ontwikkelen algoritmen die voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’. |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We toetsen de ontwikkeling en het gebruik van algoritmen op het risico van oneerlijke, bevoordeelde of discriminatoire uitkomsten. We houden toezicht op algoritmes wat betreft de beginselen van ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (fairness). Bij het ontwerpen en bij het gebruik van algoritmen nemen we gepaste waarborgen en maatregelen: dataprotection by design. |
| implicatie  | * We toetsen de algoritme op rechtmatigheid |
| | * We hebben de werking van et algoritme in begrijpelijke taal uitgelegd en gecommuniceerd met medewerkers en de burgers in een algoritme register ten behoeve van transparantie |
| | * Weten met welke data het algoritme getraind en ontwikkeld is. We kunnen de data kwaliteit en de gebreken ervan. We letten op de vooroordelen en de bias die erin kunnen zitten |
| | * We voeren assessment uit op zoek naar eventueel bias en minderheden in de data |
| | * We ontwikkelen het algoritme zodanig in om gelijkwaardige uitkomsten in de hand te werken |
| | * We voeren een assessment van de fairness van het machine-learning algoritme. Een controle waarbij getest wordt op de maatstaven die belangrijk worden geacht. Deze maatstaven dienen gemonitord te worden zolang het algoritme wordt ingezet. Alle intenties, motivatie en potentiële gevaren van algoritme is gedocumenteerd  |
| |                                                                   |

| Principe 04 | Taken, bevoegdheden en verantwoordelijkheden in het gebruik van digital twins is in de organisatie belegd en werkafspraken zijn gemaakt.                                          |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We maken afspraken over het eigenaarschap van digital twins en diverse rollen en verantwoordelijkheden die nodig zijn in het ontwikkelen, onderhouden, data- en informatie delen en beheren van digital twins. |
| implicatie  | * We hebben nieuwe rollen van medewerkers belegd in de Organisatie. Men is getraind en geïnstrueerd op de nieuwe taken te kunnen uitvoeren:                                                 |
| | * Digital twin eigenaar                                          |
| | * Digital twin coordinator                                       |
| | * Digital twin regisseur                                         |
| | * Digital twin analist                                           |
| | * Digital twin modelleur/ beheerder                              |
| | * Digital twin engineer                                          |
| | * Datasteward                                                    |
| |                                                                  |

| Principe 05 | Standaard - We standaardiseren maximaal in digital twin ecosysteem.|
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

| Principe 06 | Digitale toegankelijkheid - De presentatie van data- & informatie voldoet aan digitale toegankelijkheid.|
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We toetsen of de digitale informatie en diensten in het digital twin ecosysteem voldoet aan de digitale toegankelijkheid zodat de data- & informatie zowel bruikbaar is voor mensen met een functiebeperking als voor mensen zonder functiebeperking. Overheidsinstanties zijn bij wet verplicht om alle websites van de organisatie, websites, (mobiele) apps en digitale documenten waar de organisatie aan meebetaalt of medeopdrachtgever voor is, toegankelijk(er) te maken.                         |
| implicatie  | * We passen bij het maken van digitale informatie de standaarden toe: EN 301 549; WCAG 2.1 en WCAG-EM                                  |
| | * We toetsen publicatie van digitale informatie op digitale toegankelijkheid en zorgen voor een toegankelijkheidsverklaring. Deze verklaring moet gemaakt zijn volgens het officiële model en geaccordeerd zijn door een bestuurder of tekenbevoegde medewerker                                           |
| | * We publiceren de actuele toegankelijkheidsverklaring(en) online. Dit is verplicht                        |
| | * Het is niet zo zwart-wit dat men op elk moment 100% aan de standaard voor digitale toegankelijkheid moet voldoen. Wel moet men als overheidsinstantie ‘in control’ zijn. Dat betekent dat men weet, ook als bestuurder, voor welke digitale communicatie de overheidsinstantie verantwoordelijk is, dat men de status weet en maatregelen benoemt met een planning om de toegankelijkheid te vergroten en grip te krijgen          |


| Principe 07 | Eenmalige vastlegging - Gegevens worden eenmalig vastgelegd en rechtstreeks bij de bron bevraagd.                                                            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We voorkomen duplicatie (kopieën) van gegevens in de cloud omgeving van de aanbieder van visualisatie- dashboard-, simulatie tooling. Dit ten behoeve van leveranciersonafhankelijkheid en ter voorkoming van verouderde kopiegegevens die gebruikt worden. Het bronsysteem is een administratie, (basis)registratie, een documentregistratie, sensor en kan ook een digital twin of BIM zijn.                                                                |
| implicatie  | * Gegevens worden gescheiden van visualisatie- dashboard-, simulatie tooling bewaard, zodat opslag van gegevens onafhankelijk is van de gebruikte applicaties & softwareleveranciers en gegevens te (her)gebruiken zijn in verschillende applicaties voor verschillende doeleinden.                                       |
| | * Ieder gegeven wordt op precies één plek bijgehouden, zodat altijd duidelijk is wat het actuele brongegeven is en waar dat wordt beheerd. Dubbele opslag betekent synchroniseren, zodat partijen altijd naar dezelfde gegevens kijken. Dit geldt zowel binnen als buiten de oplossing, dus ook voor eventuele afgeleide opslag die geoptimaliseerd is ten behoeve van verstrekking.                                                        |
| | * Gegevens zijn alleen te registreren, wijzigen en raadplegen via dataservices, zodat de registratieservices kunnen garanderen dat de gegevens en metagegevens altijd voldoen aan de eisen en dat logging altijd plaatsvindt.                                       |
| | * Gegevens worden op betrouwbare en veilige wijze beheerd, zodat aangetoond kan worden dat gegevens niet bedoeld of onbedoeld gemanipuleerd zijn.                                                  |
| | * Samenhangend gebruik van gegevens is makkelijk mogelijk, zodat gegevens uit verschillende gegevensverzamelingen te combineren zijn.                                                                |
| |                                                                  |

### Infrastructuur

tekst.

#### Datacenter

tekst.

#### Cloud

tekst.

##### Public

tekst.

##### Private

tekst.

#### Netwerk

tekst.

##### Public

tekst.

##### Private

tekst.

### Internet of Things

tekst.

#### Sensoren

tekst.

#### Scada

tekst

#### Remote sensing

tekst.

#### Edge computing

tekst.

### Dataopslag

tekst.

#### Traditioneel

tekst.

#### In memory

tekst.

### Data

tekst.

#### Semantiek / ontologie

tekst.

#### Datamodellen

tekst.

#### Metadata

tekst

#### Attribuutbeveiliging

tekst.

### Modellen

tekst.

#### Objectmodellen

tekst.

<aside class='note'>
    JvG: Vallen hier ook de informatiemodellen onder zoals de [NEN3610](https://www.geonovum.nl/geo-standaarden/nen-3610-basismodel-voor-informatiemodellen)? 
</aside> 


#### Rekenmodellen

tekst.

#### Simulatiemodellen

tekst.

#### Dynamische modellen

tekst.

### Datacommunicatie

<aside class='note'>
    JvG: Data Uitwisseling? 
    JvG: én Data Uitwisselingsstandaarden. 
</aside> 

tekst

#### Berichtformaat

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Communicatieprotocol

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### API

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Service

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Gateway

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Verwijsindex

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

### Transformaties

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Transformatieregels

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Transformatiecomponent

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

### Databewerking

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Data verwerving

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Dataverrijking

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.



### Beveiliging

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Toegang

<aside class='note'>
    JvG: Authenticatie noemen? zie ook [NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)
</aside> 

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Identity catalogus

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Identity check

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Identity federation (bijv. SAML)

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Autorisatie

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Autorisatie register

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Autorisatie check

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Autorisatie federatie

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

### Ontwikkeling

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Building

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Development tooling

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Testing

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Test procedures

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

##### Test tooling

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

### Beheer

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### ASL

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### Console

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.

#### ITIL

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. 
Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, 
ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, 
aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo.
