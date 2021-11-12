## Constructie Principes

### Inleiding
Dit hoofdstuk gaat over het daadwerkelijk construeren van een samenhangende architectuur voor digital twinning. Op basis van de hoofdlijnen van de architectuur ontwerpprincipes en de referentie architectuur worden in dit hoofdstuk de constructie principes en de daarbij behorende standaarden beschreven.

#### Wat is het doel van constructie principes?
De constructie principes zijn de voorschriften van de pilots, de innovaties en andere ontwikkelingen in het digital twin ecosysteem om de visie, publieke waarden & doelstellingen van het programma NL-DFTL te behalen.
De constructie principes zijn de kaders waarbinnen de innovaties, de pilots en andere ontwikkelingen zich moeten begeven, tenzij een tijdelijke afwijking noodzakelijk is. Hierop wordt gestuurd in het landelijke programma NL-DFTL.

#### Hoe worden constructie principes toegepast?
De constructie principes worden in de pilots opgenomen in de Project Start Architecturen (PSA's) en toegepast in de solutions van de pilot. Het is niet een eenmalig proces, er vindt regulier afstemming plaats over het toepassen van de constructie principes in de PSA's. 
De feedbackloop is de afstemming tussen het team architectuur en de medewerkers van de pilots over het toepassen van de constructie principes en het gesprek indien men noodzakelijk tijdelijk moeten afwijken. Ook kan het zijn dat een pilot leidt tot een nieuw constructieprincipe die toegevoegd wordt aan de referentie architectuur. Het is ook mogelijk dat de pilots aanvullende domein specifieke constructie principes & open standaarden moeten hanteren specifiek voor een domein of thema.

#### Constructieprincipes in relatie tot andere architectuurproducten
De constructie principes zijn een onderdeel van de NL-DFTL referentiearchitectuur en de andere architectuurproducten die gerealiseerd worden. In onderstaand figuur is de samenhang weergegeven met de pilots en de architectuurproducten. 

<figure id="duiding constructieprincipes">
    <img src="media/duiding constructie principes.jpg" alt="duiding constructieprincipes">
    <figcaption>De constructie principes in samenhang met de referentie architectuur en de pilots</figcaption>
</figure>

#### Waarop zijn de constructie principes gebaseerd?
De constructie principes zijn gebaseerd op:
* De ontwerpprincipes van het programma NL-DFTL
* Europese wetgeving: Implementatiewet EG-richtlijn infrastructuur ruimtelijke informatie (INSPIRE) https://www.geonovum.nl/geo-standaarden/inspire-europese-leefomgeving en Minimal Interoperability Mechanisms https://oascities.org/minimal-interoperability-mechanisms/
* Nederlandse Wetgeving: 
    * Wet Open Overheid
    * Wet Hergebruik Overheidsinformatie
    * Archiefwet
    * Wet digitale toegankelijkheid
    * Wet Basisadministraties zoals bijvoorbeeld BAG; BGT; BRO
    * Omgevingswet
    * Wet Ruimtelijke Ordening
* Landelijke richtlijnen voor architectuur: NORA
* Landelijke richtlijnen voor gegevensbescherming: AVG & GDPR
* Landelijke richtlijnen voor software ontwikkeling: Common Ground
* overig <>...

#### Constructie principes hebben als scope het NL-DFTL fundament
De constructie principes zijn van toepassing op het digital twins ecosysteem, het fundament. Een toepassing in het digital twin ecosysteem zoals bijvoorbeeld een landelijke geluidsmodelsimulatie, kan aanvullende specifieke domein constructie principes hebben, bijvoorbeeld gebaseerd op de wet Geluidhinder (binnenkort Omgevingswet). Of te wel een toepassing moet minimaal voldoen aan de constructie principes maar kan aanvullende domein specifieke constructies principes hebben waaraan moet worden voldaan.

Onderstaand figuur een overzicht van de capabilities
<figure id="overzicht capabilities">
    <img src="media/infographic capabilities NLDFTL 3.jpg" alt="overzicht capabilities">
    <figcaption>Overzicht capabilities</figcaption>
</figure>

<aside class='note'>
    <p> * FdW: functies toevoegen zoals ; Data markt plaats; enterprise search; data bevragingen/query; visualisatie/model/informatie abonnement; catalogi? 
    * FdW: én BIM gerelateerd werken functionaliteit? </p>
</aside> 

### 1.1 Presentatie

| Principe 0x | Digitale toegankelijkheid - De presentatie van data- & informatie voldoet aan digitale toegankelijkheid.|
|-------------|------------------------------------------------------|
| referentie  | https://www.digitoegankelijk.nl/wetgeving/beleid-nederland-en-europa                                                   |
| rationale   | We toetsen of de digitale informatie en diensten in het digital twin ecosysteem voldoet aan de digitale toegankelijkheid zodat de data- & informatie zowel bruikbaar is voor mensen met een functiebeperking als voor mensen zonder functiebeperking. Overheidsinstanties zijn bij wet verplicht om alle websites van de organisatie, websites, (mobiele) apps en digitale documenten waar de organisatie aan meebetaalt of medeopdrachtgever voor is, toegankelijk(er) te maken.                         |
| implicatie  | * We passen bij het maken van digitale informatie de standaarden toe: EN 301 549; WCAG 2.1 en WCAG-EM          | 
| | * We toetsen publicatie van digitale informatie op digitale toegankelijkheid en zorgen voor een toegankelijkheidsverklaring. Deze verklaring moet gemaakt zijn volgens het officiële model en geaccordeerd zijn door een bestuurder of tekenbevoegde medewerker                                           |
| | * We publiceren de actuele toegankelijkheidsverklaring(en) online. Dit is verplicht                        |
| | * Het is niet zo zwart-wit dat men op elk moment 100% aan de standaard voor digitale toegankelijkheid moet voldoen. Wel moet men als overheidsinstantie ‘in control’ zijn. Dat betekent dat men weet, ook als bestuurder, voor welke digitale communicatie de overheidsinstantie verantwoordelijk is, dat men de status weet en maatregelen benoemt met een planning om de toegankelijkheid te vergroten en grip te krijgen          |

#### 1.1.1 User interface
tekst

#### 1.1.2 Customer Experience
tekst

##### 1.1.4 [Welk gebruiksdoel (= user story) wordt door de software geleverd?]
tekst

### 1.2 Analytics
tekst

#### 1.2.1 Algoritmen
<aside class='note'>
    <p> FdW: To do: aanvullen met de nieuwe richtlijnen van de Europese Unie (EU) voor de inzet van kunstmatige intelligentie? </p> 
</aside> 

| Principe 0x | We ontwikkelen algoritmen die voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (FAIR). |
|-------------|------------------------------------------------------|
| referentie  | AP25 https://www.noraonline.nl/wiki/Transparante_dienstverlening  AP15 https://www.noraonline.nl/wiki/Doelbinding_(AP)                                                 |
| rationale   | We toetsen de ontwikkeling en het gebruik van algoritmen op het risico van oneerlijke, bevoordeelde of discriminatoire uitkomsten. We houden toezicht op algoritmes wat betreft de beginselen van ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (fairness). Bij het ontwerpen en bij het gebruik van algoritmen nemen we gepaste waarborgen en maatregelen: dataprotection by design. |
| implicatie  | * We toetsen de algoritme op rechtmatigheid, transparantie en behoorlijkheid middels ethisch assesment https://dataschool.nl/deda/ en wetmatigheid https://ec.europa.eu/futurium/en/ai-alliance-consultation.1.html |
| | * We hebben transparantie en verklaarbaarheid geborgd, we hebben de werking van het algoritme in begrijpelijke taal uitgelegd en gecommuniceerd met medewerkers en de burgers in een algoritme register |
| | * We hebben de menselijke controle en toezicht geborgd. Dit houdt in dat AI-systemen menselijke autonomie en beslissingen moeten ondersteunen, en niet zonder toezicht mogen opereren of grondrechten negeren |
| | * We ontwikkelen het algoritme zodanig dat er gelijkwaardige uitkomsten gerealiseerd worden |
| | * We hebben diversiteit, non-discriminatie en rechtvaardigheid geborgd. Bij ontwerp en inzet van algoritme wordt rekening gehouden met inclusie en diversiteit, inclusief gelijke toegang via inclusieve ontwerpprocessen, alsook voor gelijke behandeling. Dit betekent er worden maatregelen genomen tegen bias (vooringenomenheid) die kan leiden tot directe of indirecte discriminatie en uitsluiting. We weten met welke data het algoritme getraind en ontwikkeld is, wat de data kwaliteit is en de eventueel gebreken in de trainingsdata en de bias. |
| | * We voeren bij aansluiting een assessment van de fairness van het machine-learning algoritme en testen op basis van de maatstaven die belangrijk worden geacht. Deze maatstaven dienen gemonitord te worden zolang het algoritme wordt ingezet. Alle intenties, motivatie en potentiële gevaren van algoritme is gedocumenteerd  |
| |                                                                   |

| Principe 0x | Hergebruik van algoritmen in digital twin ecosysteem.                                |
|-------------|------------------------------------------------------|
| referentie  | NORA AP07 https://www.noraonline.nl/wiki/Gebruik_de_landelijke_bouwstenen NORA AP08 https://www.noraonline.nl/wiki/Gebruik_open_standaarden                                             |
| rationale   | Voor een nieuwe toepassing hergebruiken we algoritme, de programmacode, die al binnen het ecosysteem beschikbaar is. We publiceren de ontwikkelde programmacode incl. documentatie zodat andere ontwikkelaars daarop verder kunnen ontwikkelen. Een voorbeeld is het hergebruik van het rekenmodel Groene Baten planner. Indien van toepassingen spreken we organisatorische samenwerkingsverbanden af in ontwikkeltrajecten. |
| implicatie  | * we maken gebruik van algoritme programmacode onafhankelijke software   |
| | * We herbruiken beschikbare algoritme programmacode die software- en platform agnostic ontwikkeld is                  |
| | * We publiceren ontwikkelde algoritme programmacode op GitHub (public tenzij private) incl. documentatie voor herbruikbaarheid.                                                              |
| | * We documenteren algoritme programmacode volgens de voorgeschreven standaarden      |
| | * We beheren de algoritme programmacode in een community, samenwerkingsverbanden     |
| | * We publiceren algoritmen incl. metadata in een landelijk register zodat ze eenvoudig vindbaar zijn voor hergebruik |
| |                                                                   |

| Principe 0x | Integriteit van algoritme is gewaarborgt in het digital twin ecosysteem.                                                      |
|-------------|------------------------------------------------------|
| referentie  | https://www.noraonline.nl/wiki/Integriteit      |
| rationale   | De gebruiker van een gegeven moet erop kunnen vertrouwen dat de werking van het algorime correcte, complete en actuele resultaten levert. |
| implicatie  | * De integriteit van algoritme en AI functies wordt gegarandeerd door reguliere validatie en beheersing van gegevensverwerking en geautoriseerde toegang tot algoritme functies, door scheiding van functie, door controle op de werking van het algoritme en gegevensuitwisseling |
| | * Uitvoeren van auditing op nieuwe en bestaande werking en data verwerkingen van het algoritme|
| | * De criteria voor juistheid, en tijdigheid en volledigheid van algoritme zijn vastgesteld en worden regulier gecontroleerd |
| | * controleren vanuit nieuwe ontwikkelde algoritme of veranderende gegevensverwerking van algoritme op juistheid, tijdigheid en volledigheid, voordat verdere verwerking plaatsvindt |
| |                                                                   |

| Principe 04 | vertrouwelijkheid - Algoritme is open tenzij alleen voor geautoriseerde afnemers toegankelijk in het digital twin ecosysteem.                                                      |
|-------------|------------------------------------------------------|
| referentie  | AP43  https://www.noraonline.nl/wiki/Vertrouwelijkheid_(principe)   |
| rationale   | De ontwikkelaar moet erop kunnen vertrouwen dat het algoritme niet wordt misbruikt. |
| implicatie  | * De vertrouwelijkheid van algoritme wordt gegarandeerd door scheiding van systeemfuncties, door controle en validatie op toegang tot algoritme  |
| | * Uitvoeren van de Data Protection Impact Assessment (DPIA) nieuwe en bestaande verwerkingen door algoritme |
| | * Voor het algoritme zijn de mate van vertrouwelijkheid en de bijbehorende identificatie-eisen vastgesteld |
| | * In geval van vertrouwelijkheid van het algoritme wordt de gebruiker voor toegangsverlening geauthenticeerd.  |
| | * Bij authenticatie dwingt het systeem toepassing van sterke wachtwoordconventies af. |
| | * De instellingen van het aanmeldproces voorkomen dat een gebruiker werkt onder een andere dan de eigen identiteit. |
| | * Om de mogelijkheden van misbruik te beperken, hebben gebruikers van algoritmen niet méér rechten dan zij voor hun werk nodig hebben (autorisatie). Daarbij zijn maatregelen getroffen om een onbedoeld gebruik van autorisaties te voorkomen|
| | * Verleende toegangsrechten zijn inzichtelijk en beheersbaar.               |
| | * De identificatie-eis voor een samengestelde dienst wordt bepaald door de dienst met de hoogste identificatie-eis |

#### 1.2.2 (Big data) analyse tools
tekst

#### 1.2.3 Self learning systems
<aside class='note'>
    <p> FdW: toevoegen: * In het Self learning systeem wordt ervoor gezorgd dat mensen op een verantwoorde wijze taken aan self learning-systeem kunnen toevertrouwen zonder daarbij de controle te verliezen.
* Self learning systeem is controleerbaar door de mens
* Self learning systeem is transparant en uitlegbaar
* Ethisch assesment is verricht voor Self learning systeem  </p> 
</aside> 

#### 1.2.4 Artificial Intelligence

### 1.3 Visualisatie componenten
<aside class='note'>
    <p> FdW: is het gebruik van open source software ook een constructie principe? </p>  
</aside>

| Principe 0x | Standaard - We standaardiseren maximaal in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  | AP08  https://www.noraonline.nl/wiki/Gebruik_open_standaarden ;  https://www.forumstandaardisatie.nl/open-standaarden/verplicht                                                |
| rationale   | Het gebruik van open standaarden bevordert de interoperabiliteit en moet door alle partijen worden toegepast. Er zijn geen door private partijen afgedwongen beperking aan het gebruik. Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang. We maken gebruik van software voor visualisatie, simulatie, dashboards, monitors op basis van open standaard webservices, data formaten, datamodellen en ontologiën.                         |
| implicatie  | * Met ontwikkelaars aan het digital twin ecosysteem zijn afspraken gemaakt over de te gebruiken open standaarden. Hierbij wordt tijdig geanticipeerd op de ontwikkeling van de open standaarden. |
| | * we maken visualisatie zónder kennisregels en transformaties zodat we visualisatie tool onafhankelijk blijven |
| | * Deelnemers digital twin ecosysteem werken verplicht volgens open standaarden op een uniforme wijze. Een overzicht van vastgestelde open standaarden waarvoor het 'pas toe - of leg uit' - regime geldt, is te vinden op Lijst https://www.noraonline.nl/wiki/Gebruik_open_standaarden |
| | * We gebruiken open standaard: SLD voor visualisatie geografische informatie https://forumstandaardisatie.nl/open-standaarden/sld |
| | * We gebruiken open standaard: Open Geospatial Consortium OGC Web Map Service WMS https://www.ogc.org/standards/wms |
| | * We gebruiken open standaard: Open Geospatial Consortium OGC Web Feauture Service WFS https://www.ogc.org/standards/wfs |
| | * We gebruiken open standaard: Open Geospatial Consortium OGC CityGML https://www.ogc.org/standards/citygml |
| | * We gebruiken open standaard: Open Geospatial Consortium OGC CityJSON https://docs.ogc.org/cs/20-072r2/20-072r2.html |
| | * We gebruiken open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc                                  |
| | * We gebruiken open standaard: Open Geospatial Consortium OGC 3D Tiles https://www.ogc.org/standards/3DTiles |
| | * We maken gebruik van API strategie en design rules: API design rules en [NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)         |
| | * We gebruiken de INSPIRE Europese richtlijnen: INSPIRE - Europese leefomgeving  https://wetten.overheid.nl/BWBR0026158/2009-09-01                      |
| | * We gebruiken de NEN 3610 Basismodel Geoinformatie https://www.nen.nl/nen-3610-2011-nl-156811     | 
| | * ISO 19136: Geography Markup Language  GML https://committee.iso.org/sites/tc211/home/projects/projects---complete-list/iso-19136-1.                    |
| | * We gebruiken de Europese richtlijnen Minimal Interoperability Mechanisms en Synchronicity architectuur                                                                     |

#### 1.3.1 2D afbeeldingen (data statisch)

#### 1.3.2 3D afbeeldingen (data statisch)

| Principe 0x | Standaard - We standaardiseren maximaal voor Bouw Informatie Modellen (BIM) in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  |                                                 |
| rationale   | Het toepassen van open standaarden van BIM in het digital ecosysteem bevordert de interoperabiliteit en moet door alle partijen worden toegepast. Er zijn geen door private partijen afgedwongen beperking aan het gebruik. Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang.                         |
| implicatie  | * Met afnemers zijn afspraken gemaakt over de te gebruiken open standaarden. Hierbij wordt tijdig geanticipeerd op de ontwikkeling van de open standaarden. 
| | * Deelnemers digital twin ecosysteem werken verplicht volgens open standaarden op een uniforme wijze. Een overzicht van vastgestelde open standaarden waarvoor het 'pas toe - of leg uit' - regime geldt, is te vinden op Lijst https://www.noraonline.nl/wiki/Gebruik_open_standaarden |
| | * We gebruiken open bestands formaat: IFC 2.0 https://www.forumstandaardisatie.nl/open-standaarden/ifc . IFC is een neutraal en open bestandsformaat voor het uitwisselen van BIM-specifieke informatie (modelobjecten en hun eigenschappen). | 
| | * We gebruiken Nederlandse open standaard CAD: NLCS https://www.forumstandaardisatie.nl/open-standaarden/nlcs |
| | * We gebruiken internationale open standaard: BIm Collaboration Format BCFhttps://www.buildingsmart.org/standards/bsi-standards/bim-collaboration-format-bcf/  |
| | * We gebruiken open standaard: 3D vector tiles https://www.ogc.org/standards/3DTiles | 
| | * We gebruiken de Nederlandse Revit open standaard: NLRS https://www.bimloket.nl/p/225/NLRS |
| | * We gebruiken open standaard: NL/Sfb https://www.bimloket.nl/p/107/NL-SfB. NL/SfB is een classificatie van bouwdelen en installaties (‘elementen’ genoemd). In de bouw- en installatiebranche wordt deze standaard veel toegepast bij het ontwerpen, realiseren en beheren van gebouwen. |
| | * We gebruiken open standaard: COINS2 https://www.bimloket.nl/p/100/COINS. Met COINS (Constructieve Objecten en de Integratie van Processen en Systemen) kunnen partijen die betrokken zijn bij bouwprojecten digitale informatie uitwisselen. |
| | * We gebruiken open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc                                  |
| | * We gebruiken open standaarden voor Common Data Environment CDE conform ISO 19650  https://www.bimloket.nl/p/269/NEN-EN-ISO-19650 en NEN2660 https://www.nen.nl/nen-2660-1-2020-ontw-nl-278048 . NEN 2660-1  biedt een raamwerk voor het ontwikkelen van samenhangende conceptuele modellen en -views, die betrekking hebben op het gebruik van, en de gehele levenscyclus van de gebouwde omgeving, en elementen uit deze omgeving.                 |

#### 1.3.3 Dashboards
tekst

#### 1.3.4 Grafieken
tekst

#### 1.3.5 Monitors (data dynamisch)
tekst

#### 1.3.6 Simulaties (manipuleerbare data en modellen)
tekst

#### 1.3.7 Rekenmodellen
tekst

#### 1.3.8 Simulatiemodellen
tekst

### 2.1 Business logic

| Principe 0x | Hergebruik businesslogica en business logica visualisatie tooling onafhankelijk ontwikkelen in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  |                                                 |
| rationale   | Door business logica los van visualisatie tooling te ontwikkelen zijn we flexibel in keuze software en leveranciersonafhankelijk zowel voor businesslogica als visualisatie software. Dit geldt tevens zoor informatie- en datamodellen en ontologiën.                         |
| implicatie  | * We maken gebruik van open source software voor BPMN workflow en DMN decision automation zoals bijvoorbeeld Camunda. |
| | * We ontwikkelen businesslogica in een taal die software onafhankelijk is zoals bijvoorbeeld BPMN, Python, Django en Go |
| | * Businesslogica ondersteunt API REST OPEN APIspecification https://swagger.io/specification/ |
| | * We publiceren ontwikkelde business logica op GitHub (public tenzij private) incl. documentatie.                                 |
| | * We borgen dat business rules voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (FAIR). |
| | * Note: voor BIM software is de praktijk dat functionaliteit workflow, issue management veelal wél geïntegreerd zijn met de visualisatie en de Common Data Environment en aan dit principe in de praktijk niet wordt voldaan. Richtlijn is in ieder geval van toepassing voor aanvullende specifieke business logica. |

### 3.1 Gateway
<aside class='note'>
    <p> FdW: er zijn meerdere API gateway toepassingen voor voor API REST en geo-webservices maar ook API gateway voor streaming data. </p>   
</aside>

| Principe 0x | Standaard - We standaardiseren maximaal in open source API Gateway oplossingen in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  |                                                 |
| rationale   | Het toepassen van open standaarden en open source API gateway referentie model bevordert de interoperabiliteit en hergebruik van kennis en moet door alle partijen worden toegepast. Er zijn geen door private partijen afgedwongen beperking aan het gebruik. Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang.                         |
| implicatie  | * Met afnemers zijn afspraken gemaakt over de te gebruiken open standaarden. Hierbij wordt tijdig geanticipeerd op de ontwikkeling van de open standaarden. 
| | * Deelnemers digital twin ecosysteem werken verplicht volgens open standaarden op een uniforme wijze. Een overzicht van vastgestelde open standaarden waarvoor het 'pas toe - of leg uit' - regime geldt, is te vinden op Lijst https://www.noraonline.nl/wiki/Gebruik_open_standaarden |
| | * We gebruiken open source NLX als referentie model voor API gateway API REST en geo-webservices https://nlx.io/.                 |

### 4.1 Datacommunicatie
tekst

#### 4.1.1 Semantiek / ontologie

| Principe 09 | Verbinden digital twins in ecosysteem - We maken gebruik gemeenschappelijkelandelijke- en smart city-ontologieen.              |
|-------------|------------------------------------------------------|
| referentie  | AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven                                                 |
| rationale   | We maken gebruiken van gemeenschappelijke landelijke- en smart city-ontologieen die visualisatie tool onafhankelijk zijn en platform agnostisch. De gemeenschappelijke ontologie is een kennisgraaf met samenhang tussen de ontologieën van digital twins waarmee cross-domein data analyse mogelijk is. We relateren digital twins aan elkaar daar waar nuttig voor analyse en visualisatie.         |
| implicatie  | * We gebruiken de smart city-ontologie ETSI CIM NGSI-LD Saref4City:  https://www.etsi.org/deliver/etsi_gs/CIM/001_099/006/01.01.01_60/gs_CIM006v010101p.pdf                                |
| | * We gebruiken ontologie IMBOR Informatie Model Openbare Ruimte https://github.com/Stichting-CROW/imbor                                  |
| | * We gebruiken ontologie Gegevenswoordenboek Stedelijk Water (GWSW) https://data.gwsw.nl/ |
| | * We gebruiken W3C/OGC GeoSparql ontologie https://www.ogc.org/projects/groups/geosparqlswg  |
| | * We maken gebruik van Linked data open standaarden: JSON-LD, SparQL en RDF of OWL voor ontwikkelen ontologie | 
| | * Note: Microsoft maakt gebruik van smart city-ontologie ETSI CIM NGSI-LD en en heeft het geïmplementeerd op Micrsoft Azure Digital twin software middels een specifieke Microsoft taal: open source DTDL-based Smart Cities ontology  https://techcommunity.microsoft.com/t5/internet-of-things/smart-cities-ontology-for-digital-twins/ba-p/2166585. Het is niet volledig leveranciersonafhankelijk.     |

#### 4.1.2 Dataobjectmodellen

| Principe 09 | Verbinden digital twins in ecosysteem - We maken gebruik canonieke data-objecten om digital twins met elkaar te kunnen verbinden en gemeenschappelijke smart city-ontologieen.              |
|-------------|------------------------------------------------------|
| referentie  | AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven                                                 |
| rationale   | We gebruiken afgesproken canonieke data objecten. Dit betekent dat elk 3D visualisatie, simulatiemodel etc. uniforme data objecten heeft. We relateren digital twins aan elkaar daar waar nuttig voor analyse en visualisatie.         |
| implicatie  | * We gebruiken afgesproken canonieke data object: Rijksdriehoekscoördinaten “RD- coördinaten” https://www.nsgi.nl/geodetische-infrastructuur/referentiestelsels/rdinfo      |
| | * We gebruiken afgesproken canonieke data object: “NAP” https://www.rijkswaterstaat.nl/zakelijk/open-data/normaal-amsterdams-peil#:~:text=Om%20binnen%20Nederland%20hoogtes%20te,6%2C78%20m%20onder%20NAP.    |
| | * We gebruiken afgesproken canonieke data object:  “Nederlandse tijd” https://24timezones.com/Nederland/tijd    |
| | * We gebruiken afgesproken canonieke data object:  “geografisch middelpunt van Nederland”   https://nl.wikipedia.org/wiki/Geografisch_middelpunt_van_Nederland                                  |
| | * We datamodelleren conform de MIM standaard  https://www.forumstandaardisatie.nl/open-standaarden/mim                                             |
| | * We ontwikkelen datamodellen die uitwisselbaar zijn in een open standaard formaat UML eXchange Format (UXF) https://en.wikipedia.org/wiki/UXF
| |                                                                                       |

#### 4.1.3 Metadata

| Principe 0x | Alle databronnen, informatie producten en digital twins in digital twin ecosysteem zijn vindbaar en zijn voorzien van metadata.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Alle binnen digital twin ecosysteem aanwezige databronnen, informatie producten en digital twins zijn vindbaar. |
| implicatie  | * Er is een federatief stelsel van landelijke datacatalogi met daarin geregistreerd alle binnen het digital twin ecosysteem gebruikte databronnen, databestanden, informatie producten en digital twins met de relevante metadata conform DCAT standaard en MDTO Duurzaam Toegankelijke Overheidsinformatie voor archivering en vernietiging in de Datacatalogus. De W3C Data Catalog Vocabulary (DCAT) is een metadata-standaard en is ontworpen om interoperabiliteit tussen gegevenscatalogi te vereenvoudigen  |
| | * We passen DCAT toe: https://www.w3.org/TR/vocab-dcat-2/ |
| | * We passen MDTO toe: https://www.informatiehuishouding.nl/actueel/nieuws/2021/10/13/definitieve-versie-mdto-nu-online-beschikbaar |
| | * We hergebruiken landelijke datacatalogi                              |
| | * Geografische metadata wordt vastgelegd conform ISO 19115 metadata standaard https://docs.geostandaarden.nl/md/mdprofiel-iso19115/ .               |
| | * Er is een integrale zoekmachine voor het vinden van gegevens in het federatief stelsel van catalogi.               |

#### 4.1.4 Attribuutbeveiliging
tekst

#### 4.1.5 Masterdata / begrippen & definities

| Principe 0x | We hanteren uniforme begrippen & definities voor gegevens.                   |
|-------------|------------------------------------------------------|
| referentie  | AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven                                                  |
| rationale   | Voor de interoperabiliteit van gegevensuitwisseling en hergebruik worden voor zowel gestructureerde- als ongestructureerde gegevens uniforme definities gebruikt. Iedere bedrijfsobject en onderliggend data object heeft een definitie die eenduidig is beschreven en vastgelegd. Door eenduidige definities van bedrijfs- en data objecten in datamodellen wordt het mogelijk om de informatie correct uit te wisselen op zowel syntactisch als semantisch niveau, zonder interpretatie verschillen. We passen typering van gegevens toe volgens uniforme landelijke bedrijfs- en data objecten met een eenduidige in de dataobjectmodellen.                                                                            |
| implicatie  | * We maken gebruik van de landelijk vastgestelde bedrijfsobjecten, informatiemodellen en standaarden. Zoals het landelijk bedrijfsobjectenmodel GEMMAhttps://www.gemmaonline.nl/index.php/GEMMA2/0.9/id-85853310-d375-4c9d-ae7a-46dcd0906996 en standaard informatiemodellen zoals RSGB https://www.gemmaonline.nl/index.php/Informatiemodel_Basis-_en_Kerngegevens_%28RSGB%29, IMRO https://www.geonovum.nl/geo-standaarden/ro-standaarden-ruimtelijke-ordening/informatiemodel-ruimtelijke-ordening-imro2012, IMWA, IMKICH.                                                                |
| | * Voor maximale interoperabiliteit is het van belang dat structuur en syntax gestandaardiseerd zijn |
| | * We standaardiseren de semantiek van gegevens conform de werkelijkheid                             |
| | * Bij uitwisseling van gegevens maken we ook de context van het gebruik van gegevens inzichtelijk   |
| | * We gebruiken gegevens met een eenduidige landelijke taxonomie, classificatie van begrippen. We maken gebruik van Samenhangende Objecten Registratie SOR begrippenkader                                 |
| | * We publiceren in de landelijke repository/ datacatalogus                                           |
| |                                                                                                     |

<aside class='note'>
    JvG: Data Uitwisseling? 
    JvG: én Data Uitwisselingsstandaarden. 
</aside> 

<aside class='note'>
    JvG: Authenticatie noemen? zie ook [NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)
</aside> 

<aside class='note'>
    JvG: Vallen hier ook de informatiemodellen onder zoals de [NEN3610](https://www.geonovum.nl/geo-standaarden/nen-3610-basismodel-voor-informatiemodellen)? 
</aside> 

#### 4.1.6 Berichtformaat
tekst

### 4.2 Communicatieprotocol
tekst

#### 4.2.1 Service/ API

| Principe 0x | We hanteren wij een service-georiënteerde architectuur.      |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | We hanteren wij een service-georiënteerde architectuur. Interactie tussen de registraties waarin de data opgeslagen is en de proceslogica- en gebruikersinterface componenten vindt plaats op basis van gestandaardiseerde services om flexibiliteit en koppelbaarheid te vergroten. Deze services kunnen andere services aanroepen waardoor een gelaagde service-architectuur ontstaat.                                                                            |
| implicatie  | * Data in authentieke registers wordt via gestandaardiseerde- en beschreven services ontsloten.        |
| | * Service georiënteerd werken heeft altijd de voorkeur boven andere manieren van koppelen. Dit is enerzijds door het ontmoedigen van "silo-applicaties" en leverancier specifieke integraties                                                           |
| | * Servicegerichte architectuur betekent gebruik maken van standaard webservices, de design rules[NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)                                                                        |
| | * De ontwikkelde services/API's zijn vindbaar (Github) en herbruikbaar |
| | * We documenteren t.b.v. herbrukbaarheid programmeertaal onfahnakelijk volgens de OpenAPI Specification (OAS) standaard.  https://swagger.io/specification/          |

| Principe 0x | Standaard - We standaardiseren maximaal in open source API Management oplossingen in digital twin ecosysteem.|
|-------------|------------------------------------------------------|
| referentie  |                                                 |
| rationale   | Het toepassen van open standaarden en open source API Management bevordert de interoperabiliteit en hergebruik van functionaliteit en moet door alle partijen worden toegepast. Er zijn geen door private partijen afgedwongen beperking aan het gebruik. Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang.                         |
| implicatie  | * Met afnemers zijn afspraken gemaakt over de te gebruiken open standaarden. Hierbij wordt tijdig geanticipeerd op de ontwikkeling van de open standaarden. 
| | * Deelnemers digital twin ecosysteem werken verplicht volgens open standaarden op een uniforme wijze. Een overzicht van vastgestelde open standaarden waarvoor het 'pas toe - of leg uit' - regime geldt, is te vinden op Lijst https://www.noraonline.nl/wiki/Gebruik_open_standaarden |
| | * We gebruiken open source API Management producten WSO2 https://wso2.com/api-manager/ en Tyke:  https://tyk.io/price-comparison/?utm_term=api%20management&utm_campaign=Price+Comparison+-+Best+2020+-+High+GDP+-+Search&utm_source=adwords&utm_medium=ppc&hsa_acc=4132762899&hsa_cam=14671572690&hsa_grp=134153488304&hsa_ad=546341718447&hsa_src=g&hsa_tgt=kwd-300455415258&hsa_kw=api%20management&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQjw8p2MBhCiARIsADDUFVF1YNJlQhNFs4cC4XU23KeWej2cStH7PD0xFurB9j4PhOo16RB4p-gaAlDsEALw_wcB en               |


#### 4.2.2 Verwijsindex
tekst

### 4.3 Transformaties
tekst

#### 4.3.1 Transformatieregels
tekst

#### 4.3.2 Transformatiecomponent
tekst

### 4.4 Databewerking
tekst

#### 4.4.1 Dataverrijking
tekst

### 5.1 Data verwerving

| Principe 0x | Eenmalige vastlegging - Gegevens worden eenmalig vastgelegd, rechtstreeks bij de bron bevraagd en meervoudig gebruikt.                                                            |
|-------------|------------------------------------------------------|
| referentie  | AP13 https://www.noraonline.nl/wiki/Bronregistraties_zijn_leidend  CG: Eenmalige vastlegging We leggen gegevens eenmalig vast en vragen op bij de bron                                               |
| rationale   | We voorkomen duplicatie (kopieën) van gegevens in de cloud omgeving van de aanbieder van visualisatie- dashboard-, simulatie tooling. Dit ten behoeve van leveranciersonafhankelijkheid en ter voorkoming van verouderde kopiegegevens die gebruikt worden. Het bronsysteem is een administratie, (basis)registratie, een documentregistratie, sensor en kan ook een digital twin of BIM zijn.                                                                |
| implicatie  | * Gegevens worden gescheiden van visualisatie- dashboard-, simulatie tooling bewaard, zodat opslag van gegevens onafhankelijk is van de gebruikte applicaties & softwareleveranciers en gegevens te (her)gebruiken zijn in verschillende applicaties voor verschillende doeleinden.                                       |
| | * Ieder gegeven wordt op precies één plek bijgehouden, zodat altijd duidelijk is wat het actuele brongegeven is en waar dat wordt beheerd. Dubbele opslag betekent synchroniseren, zodat partijen altijd naar dezelfde gegevens kijken. Dit geldt zowel binnen als buiten de oplossing, dus ook voor eventuele afgeleide opslag die geoptimaliseerd is ten behoeve van verstrekking.                                                        |
| | * Gegevens zijn alleen te registreren, wijzigen en raadplegen via dataservices, zodat de registratieservices kunnen garanderen dat de gegevens en metagegevens altijd voldoen aan de eisen en dat logging altijd plaatsvindt.                                       |
| | * Gegevens worden op betrouwbare en veilige wijze beheerd, zodat aangetoond kan worden dat gegevens niet bedoeld of onbedoeld gemanipuleerd zijn.                                                  |
| | * Samenhangend gebruik van gegevens is makkelijk mogelijk, zodat gegevens uit verschillende gegevensverzamelingen te combineren zijn.                                                                |
| |                                                                  |

| Principe x | We borgen de beschikbaarheid, vertrouwelijkheid en integriteit van registratie van gegevens (BIV).      |
|-------------|------------------------------------------------------|
| referentie  | AP44  https://www.noraonline.nl/wiki/Controleerbaarheid  AP40 https://www.noraonline.nl/wiki/Onweerlegbaarheid_(principe)  AP41  https://www.noraonline.nl/wiki/Beschikbaarheid  AP42 https://www.noraonline.nl/wiki/Integriteit  AP43 https://www.noraonline.nl/wiki/Vertrouwelijkheid_(principe)                                               |
| rationale   | Gegevens die binnen digital twin ecosysteem en organisaties worden gegevens verwerkt worden, worden conform de overeengekomen kaders beschikbaar gesteld en beveiligd tegen ongeautoriseerde toegang, frauduleus gebruik of mutatie en gegevensverlies. De eigenaar van digital twin, informatiesysteem dan wel registratie zorgt ervoor dat afnemers van vertrouwelijke gegevens enkel de gegevens verstrekt krijgen waar ze conform hun doelbinding recht op hebben.           |
| implicatie  | * We voldoen aan wet- en regelgeving nemen organisatorische-, procedurele- en technische maatregelen in  het beschikbaar stellen van data, bewerkingen en transformaties.                                            |
| | * We voeren Data Protection Impact Assessment (DPIA)3 uit op bestaande & nieuwe dataverwerkingen    |
| | * We voldoen aan de Baseline informatiebeveiliging Overheid (BIO) in data services, transformaties  |
| | * Toegang tot privacygevoelige gegevens wordt alleen geboden aan afnemers met doelbinding. Een gebruiker heeft toegang tot de data waarvoor hij/ zij geautoriseerd is. Dit wordt vastgelegd in de gegevens-leveringsovereenkomsten (GLO)   |
| | * Alle bedrijfsobjecten en onderliggende dataobjecten, hebben een eigenaar die verantwoordelijk is voor de integriteit, vertrouwelijkheid, kwaliteit en beschikbaarheid van de data.                                                                                                    |
| | * Auditing vindt plaats op het gebruik van persoonsgegevens conform vastgestelde protocollen en gegevensbeveiliging |


| Principe x | We borgen de duurzame toegankelijkheid van gegevens daar waar het vereist is.            |
|-------------|------------------------------------------------------|
| referentie  | NTB                                                  |
| rationale   | Gegevens worden conform de geldende bewaar- en vernietigingstermijnen uit de vigerende wet- en regelgeving behandeld (Archief Wet). Zowel gestructureerde als ongestructureerde gegevens worden duurzaam toegankelijk gehouden. |
| implicatie  | * We voldoen aan wet- en regelgeving zoals de Archiefwet                                   |
| | * Verantwoording kunnen afleggen over uitgevoerde acties en transparantie                              |
| | * We zorgen er voor dat de opslag van gegevens duurzaam is                                             |
| | * We bewaren gegevens niet langer dan nodig is                                                         |
| | * We nemen maatregelen voor tijdige en volledige archivering van gegevens.                             |

| Principe x | We beheren de kwaliteit van gegevens actief middels continue verbetering en communiceren de kwaliteit.     |
|-------------|------------------------------------------------------|
| referentie  |  AP31 https://www.noraonline.nl/wiki/PDCA-cyclus_in_besturing_kwaliteit  AP32  https://www.noraonline.nl/wiki/Sturing_kwaliteit_op_het_hoogste_niveau  AP33  https://www.noraonline.nl/wiki/Baseline_kwaliteit_diensten  AP34 https://www.noraonline.nl/wiki/Verantwoording_besturing_kwaliteit                                               |
| rationale   | De kwaliteit van de gegevens die worden verwerkt binnen de gemeente wordt actief gemonitord en continu verbeterd en op een niveau gehouden wat in overeenstemming is met de eisen die daar vanuit de wetgeving en de afnemers aan gesteld worden. Datakwaliteit sluit aan op het proces waarbinnen het gebruik gegenereerd wordt. De kwaliteit wordt gepubliceerd.           |
| implicatie  | * Processen die het kwaliteitsbeheer en continu verbeteren borgen zijn ingericht                           |
| | * De kwaliteit van gegevens zijn van alke databron vastgelegd als metadata                                             |
| | * Buiten de syntactische correctheid van gegevens bewaakt men ook de integriteit over gegevens- verzamelingen heen     |
| | * Afnemers dienen aan te geven wat hun eisen zijn ten aanzien van de kwaliteit en actualiteit van gegevens. Datakwaliteit wordt afgesproken en vastgelegd de GLO gegevens levering overeenkomst                                                            |
| | * Datakwaliteit wordt geoptimaliseerd voor het proces waarbinnen het gebruikt wordt. De broneigenaar (en proceseigenaar) is verantwoordelijk voor de optimalisatie.                                                                                    |
| | * Proceseigenaren zien erop toe dat de data, de data die binnen een proces worden ingewonnen of geactualiseerd. Datakwaliteit wordt door proceseigenaren voortdurend gerapporteerd en datakwaliteit inzichtelijk aangeboden in datacatalogus, aangeduid met een kwaliteitslabel op een duidelijke schaal conform de handreiking gegevenskwaliteit.                                         |

#### 5.1.1 Toegang
tekst

### 5.2 Infrastructuur
tekst

#### 5.2.1 Datacenter
tekst

#### 5.2.2 Cloud
tekst

#### 5.2.3 Public
tekst

#### 5.3.4 Private

##### 5.3.4.1. Personal Data Pods (SOLID)

### 5.4 Netwerk
tekst

##### 5.4.1 Public
tekst

##### 5.4.2 Private
tekst

### 5.5 Internet of Things
tekst

#### 5.5.1 Sensoren
tekst

#### 5.5.2 Actuatoren
tekst

#### 5.5.3 Scada
tekst

#### 5.5.4 Remote sensing
tekst

#### 5.5.5 Edge computing
tekst

#### 5.5.6 Fog computing
tekst

### 5.6 Dataopslag
tekst

#### 5.6.1 Traditioneel registratie
tekst

#### 5.6.2 In memory
tekst

### 6.1 Beveiliging
tekst

#### 6.1.1 Identity catalogus
tekst

#### 6.1.2 Identity management
tekst

#### 6.1.3 Identity check
tekst

#### 6.1.4 Identity federation (bijv. SAML2 of OpenID Connect)
tekst.

### 6.2 Autorisatie
tekst.

#### 6.1.1 Autorisatie register
tekst.

#### 6.1.2 Autorisatie check
tekst.

#### 6.1.3 Autorisatie federatie
tekst.

### 6.2 Ontwikkeling
tekst.

#### 6.2.1 Building
tekst.

#### 6.2.2 Development tooling
tekst.

#### 6.2.3 Testing
tekst.

#### 6.2.4 Test procedures
tekst

##### 6.2.5 Test tooling
tekst.

### 6.3 Beheer
tekst.

#### 6.3.1 ASL
tekst.

#### 6.3.2 Console
tekst.

#### 6.3.4 ITIL
tekst.

## BIJLAGEN

