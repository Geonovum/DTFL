## Constructieprincipes
In hoofdstuk XXX [Inleiding] staat een schets van het digitale tweeling  stelsel. We zagen al eerder dat dit opgebouwd is op basis van een combinatie van federatieve opslag van gegevens, modellen en bewerkingsfunctionaliteit, aangevuld met een aantal essentiële centrale, federatieve componenten, waardoor gegevens, modellen en bewerkingsfunctionaliteit over en weer gebruikt kunnen worden.

In het vorige hoofdstuk staan algemene uitgangspunten of principes waaraan het stelsel moet voldoen. In dit hoofdstuk gaan we weer een laagje dieper. We gaan kijken naar de wijze waarop digitale tweeling mogelijk wordt voor deelnemende organisaties. Dit verwoorden we in constructie principes. De constructie principes worden toegepast in meerdere typen ontwerpdocumenten, zoals projectstartarchitecturen, solution architecturen, datacommunicatie architecturen, infrastructuur architecturen, etc.

Digitale tweeling kent immers veel componenten, die met elkaar het stelsel vormen. Elk van de hierbinnen toegepaste componenten, worden bij voorkeur in lijn met de constructieprincipes uit gdit hoofdstuk ontworpen en gerealiseerd, waardoor zij inpasbaar zijn in het totale stelsel. Toepassing van ontwerpprincipes kan dus ook gezien worden als het zorgen voor een hoge mate van interoperabiliteit binnen het stelsel. 
Voordat we naar de constructieprincipes gaan staan we eerst stil bij het construct zelf. 

### Het construct

Hoe ziet het construct eruit waar heel veel verschillende stakeholders met elkaar werken vanuit verschillende domeinen en waar de infrastructuur dient te faciliteren om met behulp van data gedreven werken allerlei maatschappelijke opgaven integraal te ondersteunen? Hoe zetten we de kracht van data, analyse en visualisatie optimaal en verbindend in? In deze paragraaf geven we hier een antwoord op.

Op allerlei plaatsen zijn er initiatieven rond digitale tweelingen, waarin naast meer statische data ook nadrukkelijk gebruik gemaakt wordt van rekenmodellen, dynamische data en visualisatie-services. Digitale tweelingen richten zich niet alleen op de vastlegging van de fysieke leefomgeving, maar met name op processen in die fysieke leefomgeving: denk bijvoorbeeld aan verkeersstromen, stikstofdistributie, geluidsbelasting of de drukte in de stad. Daarvoor is niet alleen statische data over de fysieke leefomgeving zelf nodig, maar juist ook dynamische data (waarnemingen uit sensoren) over hoe die processen zich afspelen in tijd, ruimte en in combinatie met sociale aspecten.

De architectuur van de Nationale digitale tweeling infrastructuur kenmerkt zich door een enorme hoeveelheid stakeholders die werken in verschillende domeinen. Er is niet een digitale tweeling maar een zeer grote diversiteit aan digital tweelingen in de verschillende domeinen voor zeer veel toepassingen in Nederland (en daarbuiten). De digitale tweelingen zijn verbonden met elkaar daar waar nuttig. De verbonden digitale tweelingen noemen we het digitale tweeling eco-systeem of digitale tweeling stelsel. De architectuur van Nationale digitale tweeling infrastructuur die we ontwerpen is geen ontwerp van één digitale tweeling maar van een stelsel aan digitale tweelingen.

Het stelsel kan niet gerealiseerd worden door barrières op te werken waarbij het tempo van de stakeholders wordt bepaald door de randvoorwaarden van de architectuur. De architectuur moet faciliteren dat de stakeholders duizend bloemen kunnen laten bloeien. Dit vraagt gedecentraliseerde oplossingen als basis voor democratisering van iedere stakeholder. Alleen in een federatieve  architectuur met federatieve governance kan de complexiteit van Nationale digitale tweeling infrastructuur worden gerealiseerd.

In onderstaand figuur is een globale schets van de architectuur van de Nationale digitale tweeling infrastructuur weergegeven.

<m>AFBEELDING 1</m>

De architectuur bestaat uit generieke componenten die FAIR  ondersteunen, de vindbaarheid, toegankelijkheid, interoperabiliteit en herbruikbaarheid.

Om er voor te zorgen dat de Nationale digitale tweeling infrastructuur voldoet aan de FAIR richtlijnen introduceren we een nieuw concept “data mesh” waarmee we tevens ook de complexiteit ordenen.

Het concept data mesh  heeft een architectuur die gebaseerd is op federatieve oplossingen  waar de data en het ondersteunen van opschalen centraal staat. Deze architectuur is gebaseerd op grote complexe domeinen, organisaties en stakeholders.

Voor de architectuur van de Nationale digitale tweeling infrastructuur voegen we een aantal onderdelen toe aan het data mesh concept of vullen we het iets anders in maar in essentie hanteren we de data mesh architectuur als basis.

De data mesh architectuur gaat uit van een viertal primaire uitgangspunten, dit zijn:

<m>AFBEELDING 2</m>

1.	Domein eigenaarschap
De infrastructuur ondersteunt een federatieve aanpak met een verdeling van verantwoordelijkheid naar mensen die het dichtst bij de gegevens staan. We hebben al zoveel werkende domeinen met een eigen dynamiek en governance die we nog beter en in samenhang waar relevant willen laten werken.

2.	Data als een product
Met data als een product stellen we het dataproduct centraal. Het dataproduct is een ‘atomaire’ eenheid en heeft de metadata, ontstaansgeschiedenis, kwaliteit, e.d. allemaal bij het product zelf staan en heeft mechanismen om afnemers te informeren en consulteren.

<m>AFBEELDING 3</m>

3.	Basis data infrastructuur
Ook een federatieve structuur heeft basisvoorzieningen nodig om dataproducten, modellen, e.d. te kunnen vinden. De inrichtingswijze wordt wel een andere omdat de metadata bij de data staat. Basisvoorzieningen voor mensen en machines maken gebruik van federatieve indexen en dit kan niet zonder afsprakenstelsels.

4.	Federatieve governance
Afsprakenstelsels zijn nodig om het geheel te kunnen laten werken. Dit betreft niet alleen standaarden voor het delen van data, data-producten, modellen maar ook ethiek, privacy, transparantie, e.d. Governance vraagstukken liggen op de gedeelde voorzieningen, in een federatief stelsel zijn de overige governance vraagstukken voor de domeinen. 

Met het datamesh concept passen we een mesh topologie  toe. Dit is een vermaast netwerk waarin de dataproducten de nodes zijn van waaruit de data wordt doorgestuurd naar gebruikers, afnemende applicaties of andere dataproducten.

<m>AFBEELDING 4</m>

Om onderdeel te kunnen zijn van de Nationale Digitale Tweeling infrastructuur dienen de volgende constructie principes gevolgd te worden.

### Domein eigenaarschap

Data mesh is in de kern gebaseerd op decentralisatie en verdeling van verantwoordelijkheid naar mensen die het dichtst bij de gegevens staan om continue verandering en schaalbaarheid te ondersteunen. Een domein  heeft de verantwoordelijkheid voor data-producten. Degene die de verantwoordelijkheid over de data-producten hebben moeten in dialoog kunnen zijn met de afnemers. Dit lukt niet als de data vele malen wordt gekopieerd en binnen allerlei systemen een eigen context krijgen.

#### Duidelijk eigenaarschap data

De dataproducten hebben een eigenaar en deze is hierop aanspreekbaar. Een dataproduct zonder duidelijk eigenaarschap is geen onderdeel van de nDTFL.

#### We gebruiken data vanuit de bron

Om een dataproduct te maken gebruiken we de data uit de bron waarbij op basis van services. Alleen de bron heeft de juiste, meest actuele versie van de data en bevat alle context. De eigenaar van de data wijst afnemers de juiste weg en faciliteert ze, waar nodig, bij het benaderen van de bron.

#### 	De brondata past op de afnemersbehoeften 

De eigenaar van dataproduct heeft de zorgplicht dat de output data continu geleverd wordt conform de afspraken (SLO) zodat deze door andere dataproducten gebruikt kan worden. Dit vraagt een continue dialoog tussen de data product-eigenaar en afnemers cq. afnemende dataproducten. 

<m>AFBEELDING 5</m>

Domeinen kunnen op verschillende manieren georganiseerd zijn. Dit is vrij en naar behoefte van het werkveld. Denk bv. aan verticale kennisdomeinen zoals luchtverontreiniging of horizontale domeinen als sensoren. De DTFL schrijft de inrichting niet voor dit is een sociaal maatschappelijk proces dat continue in beweging zal zijn en alleen kan bestaan als dit waarde toevoegt voor de betrokken stakeholders en daarmee verbonden is met lange termijn eigenaarschap vanuit het domein. In de praktijk bestaan de meeste domeinen al. In de DTFL brengen we deze in beeld.

#### 	We schrijven geen domeinen voor

De inrichting van de domeinen is een sociaal maatschappelijk proces gebaseerd op de behoeften van stakeholders.
In de domeinen bestaat enorm veel data. Hoe houden we dit bij elkaar in een wereld van decentralisatie en domeinen die hun eigen context(en) van de gegevens nodig hebben? De data mesh hanteert hiervoor de volgende aanpak:

1.	Objecten hanteren een globaal uniek extern gericht identifier systeem
2.	De mogelijkheid om modelmatig dezelfde data (begrippenkader) aan elkaar te verbinden
3.	De mogelijkheid om data aan elkaar te verbinden

#### Verbinden in plaats van verzamelen

Tussen of binnen een domein wordt brondata niet met elkaar verbonden in een datawarehouse, datalake of andere omgeving. De data wordt op bovenstaande wijze (1. t/m 3.) verbonden zodat een verbonden stelsel van data ontstaat gericht op herbruikbaarheid (in plaats van specifieke oplossingen).

Data Mesh onderkent Domain driven design (DDD)  als een manier om domeinen te modelleren. Business-vertegenwoordigers en software-ontwikkelaars spreken dezelfde eenduidige taal (‘ubiquitous language’) die de kernbegrippen binnen het domein bevat. DDD onderkent het feit dat standaardisatie van modellen en taal slechts tot op zeker hoogte mogelijk én wenselijk is binnen een divers systeem, zeker wanneer daarbij meerdere organisaties betrokken zijn.

Domeinen gebruiken, vanwege het taak-specifieke karakter vaak om goede redenen, verschillende begrippen in een andere betekenis of dezelfde begrippen met een verschillende betekenis. Zo kan een ‘klant’ in het ene domein vergelijkbaar zijn met wat in een ander domein ‘cliënt’ wordt genoemd. Andersom kan het begrip ‘klant’ in meerdere domeinen worden gebruikt maar een, ietwat of sterk, verschillend betekenis hebben. DDD hecht daarom veel belang aan het zorgvuldig afbakenen van wat wel en niet tot een domein behoort (‘bounded context’) en benadrukt dat begrippen een domein gebonden betekenis hebben.

#### 	Er bestaan meerdere contexten van de werkelijkheid

De data heeft binnen het domein waarin ze zijn ontstaan een specifieke betekenis. Binnen de DTFL hebben we een bijzonder domein. Dit is het domein van de basisregistraties. Basisregistraties zijn context onafhankelijk en zijn het fundament onder de data uit de domeinen. Zonder fundament hanteren de domeinen verschillende referenties en kunnen we de resultaten niet meer met elkaar vergelijken. Denk aan het gebruik van topografie die op een andere plek ligt dan de Basisregistratie Grootschalige Topografie (BGT).

#### De domeinen hanteren de basisregistraties en relaties tussen de basisregistraties als fundament

De (basis)registraties bestaan uit de Basisregistratie Grootschalige Topografie (BGT), Basisregistratie Topografie (BRT), Basisregistratie Adressen en Gebouwen (BAG), Basisregistratie Ondergrond (BRO), Basisregistratie Kadaster (BRK), Landelijke Voorziening Beeldmateriaal, 3D Basisvoorziening

Het onderscheid dat we van oudsher hebben tussen operationele (veelal transactie-gebaseerde) en analytische data zal steeds meer vervallen. Analytische data maakt direct gebruik van de operationele data en levert vaak ook weer feedback op de operationele data. Analytische data kan weer operationele data zijn voor een ander DTFL proces. We brengen data naar de modellen en modellen naar de data. Dit organisch stromen van data faciliteren we door de domein-structuur. We hanteren hier het concept van data als een product, zie volgende paragraaf.

### Data als een product

Data als een product lijkt vanzelfsprekend omdat we dit naar ons gevoel al doen. Echter in de huidige infrastructuren beschouwen we data en techniek als 2 aparte dingen terwijl bij data als een product dit een is. Data als een product heeft daarnaast nog een subtiel maar essentieel verschil. Nu leveren we data, denk aan grote bestanden waar de gegevensgebruiker, gegevensanalist, etc. zelf zijn relevante gegevens maar moet uithalen en vaak zelf moet omzetten naar werkbare formaten. Met data als een product voegen we product denken (product thinking) toe. De gebruikers moeten als klant worden behandeld en wel op zo’n manier dat de klant gelukkig wordt van de wijze waarop de data geconsumeerd kan worden. Succesvolle producten  zijn waardevol, eenvoudig bruikbaar en haalbaar om te maken. Het concept van succesvolle producten is ook toegepast op data als een product.

De data als een product is een atomaire eenheid. Het is niet zo dat op andere plekken ‘metadata’ wordt opgeslagen van het dataproduct maar bij data mesh is al deze informatie aanwezig bij het dataproduct zelf. Dit past bij de federatieve aanpak. Een dataproduct  kan bestaan uit:

 * Transactie data – data in transactionele werkprocessen zoals bijvoorbeeld financiële transacties, maar ook sensor data of events
 * Analytische data – dit is transactionele data dat gecombineerd, bewerkt, verrijkt en/of geaggregeerd is uit verschillende bronsystemen. Analytische data biedt nieuwe kennis en inzichten.
 * Combinatie van beiden

 Dataproducten bieden output data aan gebruikers of afnemende applicaties zoals bijvoorbeeld een viewer of een dashboard tool en is softwareproduct (tool) onafhankelijk.

<m>AFBEELDING 6</m>

Een dataproduct bestaat uit:

Code

 * API’s, notificaties of andere wijzen waarop je de data kunt benaderen of verkrijgen 
 * Code om van de input data nieuwe output data te maken, data transformatie. Dit kan een ETL zijn, maar ook een algoritme, streaming data-analyse 
Polyglot input- en output data: 
 * De input én output is in verschillende open standaard dataformaten (graph’s, JSON, XML, etc.) waarbij de semantiek hetzelfde is uitgedrukt 
 * De input en output is op basis van open standaard mechanisme zoals: batch; streaming data; SQL; API; geo-webservices; Query 
 * De input en output is transactionele- en/of analytische data 
Dataproduct ontwikkeling:  
 * Op basis van de input wordt output data ontwikkeld op basis van diverse (moderne) technieken zoals pipelines voor data transformatie, algoritmen voor data transformatie, streaming data-analyse, etc.; Op basis van de technieken worden dataproduct ontwikkelt en beheerd.  

<m>AFBEELDING 7</m>

De dataproducten bestaan uit verschillende typen informatie. Operationele data of een model, het informatiemodel, begrippen of andere typen zoals ontstaansgeschiedenis, tijdslijnen, kwaliteit, etc. De typen variëren op basis van de aard van het dataproduct.

<m>AFBEELDING 8</m>

Van een of meerdere dataproducten kan ook een nieuw dataproduct gemaakt worden. Dit kan een samenstelling zijn of het resultaat van een algoritme zoals een tijdelijke analyse, voorspelmodel, e.d. Dit nieuwe product kan ook weer een dataproduct worden dat door andere stakeholders gebruikt kan worden in hun ecosysteem. De dataproducten zijn permanent verbonden (vanuit de bron). Voor dataproducten geldt dat ze moeten voldoen aan constructieprincipes van het ecosysteem.

<m>AFBEELDING 9</m>

Een dataproduct wordt ontwikkeld in een domein en heeft één product eigenaar. Een domein heeft een of meerdere dataproducten en eigenaren. 

<m>AFBEELDING 10</m>

Informatie vraagstukken kunnen betrekkingen hebben om meerdere dataproducten van verschillende domeinen (afdelingen, organisatieonderdelen cq. organisaties). Ter illustratie een voorbeeld voor verkeersregel installaties.
Hierin worden dataproducten in een keten gebruikt waarin een dataproduct een algoritme als transformatie technologie inzet.

<m>AFBEELDING 11</m>

Dit kunnen we ook toepassen op een overkoepelend vraagstuk waarbij verschillende dataproducten zijn gebruikt. Bijvoorbeeld het vraagstuk of Nederland voldoende beschermd is tegen het water in geval van enorme regenval en smeltwater in de grote rivieren zoals de Maas en de Rijn. De dataproducten worden dan gebruikt in het domein water risico’s.

<m>AFBEELDING 12</m>

Dataproducten hebben kenmerken of te wel constructie principes die toegepast moeten worden in de ontwikkeling van het dataproduct om te kunnen (mogen) aansluiten op het landelijke digitale tweeling eco-systeem nDFTL.

<m>AFBEELDING 13</m>

Ontwerpprincipes dataproduct

#### Vindbaar

Vindbaarheidsinformatie wordt verstrekt door het dataproduct zelf.

Vindbaarheid van dataproducten binnen het DTFL-stelsel gebeurt aan de bron. Het is aan de individuele dataproducten om hun vindbaarheidsinformatie op een standaard manier te delen. Elk dataproduct deelt continue zijn oorsprong, eigenaren, runtime-informatie zoals tijdigheid, kwaliteitsstatistieken, voorbeeldgegevenssets en vooral informatie die is bijgedragen door hun consumenten, zoals de belangrijkste gebruiksscenario's en toepassingen die door hun gegevens mogelijk worden gemaakt. 
Via een centrale mogelijkheid worden deze federatieve indexen bevraagt voor een totaaloverzicht.

#### Begrijpelijk

Het dataproduct is zelfbeschrijvend.

Uit welke begrippen, definities, relaties, waardelijsten, e.d. – de semantiek - bestaat het dataproduct? Naast begrip van de semantiek, moeten datagebruikers begrijpen hoe de gegevens aan hen worden gepresenteerd. Hoe hebben ze toegang? Hoe kunnen ze de data syntactisch opvragen? Wat voor soort SQL-query's kunnen ze uitvoeren? Hoe lees je de data-objecten? Dit gaat idealiter vergezeld van voorbeelddatasets en voorbeeldcodes.

Dataschema’s helpen om de datagebruiker te ondersteunen. Dit geldt ook voor computational notebooks  die het verhaal van een dataproduct helpen vertellen. Computational notebooks bevatten documentatie van de data, evenals code om het te gebruiken en het visueel demonstreren van de code in actie.

Ten slotte is begrijpbaarheid een sociaal proces. Wij leren van elkaar. Het moet eenvoudig zijn om als datagebruiker ervaringen te delen die weer zorgen voor betere ondersteuning op bruikbaarheid.

#### Betrouwbaar en waarheidsgetrouw

Elk dataproduct heeft Service Level Objectives (SLO's) die een acceptabel kwaliteitsniveau garanderen en worden nageleefd door de dataproduct eigenaar.

Een SLO omvat onder meer:

 * Interval van verandering
 * Actualiteit
 * Volledigheid
 * Statistische vorm van gegevens
 * Ontstaansgeschiedenis – de datareis
 * Precisie en nauwkeurigheid in de loop van de tijd
 * Operationele kwaliteiten

Hoe beter de data-eigenaar deze gegevens bij zijn dataproduct vastlegt, bijhoudt en beheert, hoe meer vertrouwen de datagebruikers zullen hebben in het dataproduct zelf.

#### Adresseerbaar

Een dataproduct moet een vast en uniek adres hebben voor de datagebruiker om het handmatig of vanuit software te kunnen openen.

Een uniek adresseringssysteem moet de dynamische aard van de data en de mesh-topologie ondersteunen. Het moet aspecten omvatten van dataproducten die continu kunnen veranderen en tegelijkertijd de continuïteit van het gebruik ondersteunen. Het adresseringssysteem moet de volgende continu veranderende aspecten van de dataproducten accommoderen:

 * Voortdurende verandering in de semantiek van het dataproduct, versies
 * Continue release van nieuwe data-time slices (gekoppeld aan een bepaalde tijds(duur)
 * Nieuwe ondersteunde syntaxis van de onderliggende data: nieuwe manieren van serialiseren, het verzenden en opvragen van de gegevens
 * Continu veranderende runtime gedragsinformatie: b.v. SLO's (als code)
Een uniek adresseringssysteem moet een wereldwijde conventie volgen zodat de data-producten een consistente toegang hebben voor mensen en machines. Dit is ook nodig om gevonden te kunnen worden door de discover-oplossing <m>(1.2.1 Vindbaar)</m>.

#### Semantische interoperabiliteit

De dataproducten moeten zoveel als mogelijk met elkaar inhoudelijk combineerbaar kunnen worden.

Een van de belangrijkste zorgen in een gedistribueerde data-architectuur is de mogelijkheid om data te correleren/in samenhang over domeinen heen te gebruiken.
De sleutel voor semantische interoperabiliteit van data tussen domeinen is het volgen van standaarden en harmonisatieregels, die het mogelijk maken om gegevens over domeinen heen zinvol in samenhang te bevragen. Hiervoor zullen we een aantal zaken moeten standaardiseren die de interoperabiliteit van de dataproducten vergemakkelijken:

 * Volgen van Metamodel informatiemodellering (MIM) voor informatiemodellen ,  
 * Gestandaardiseerde metadata
 * Geharmoniseerde begrippen en definities
 * (knowledge) graphs
 * Mogelijkheid tot hergebruik en koppeling aan begrippen, informatiemodellen, graphs, etc.
 * naar schema's - typen - gedefinieerd door andere dataproducten.

#### Toegankelijk en veilig

Gegevensgebruikers moeten op een veilige en vertrouwelijke manier toegang krijgen tot het gegevensproduct.

Veilige toegang is een must of de architectuur nu gecentraliseerd of gedistribueerd is. In de wereld van gedecentraliseerde architectuur zoals Data Mesh wordt de toegangscontrole tijdens runtime gevalideerd door het dataproduct. Het toegangscontrolebeleid wordt centraal gedefinieerd (design time). Denk hierbij aan:

 * Toegangscontrole
Wie, wat en hoe hebben systemen toegang tot het dataproduct?
 * Encryptie
Welke soorten versleuteling ondersteunen we?
 * Vertrouwelijkheidsniveaus
Welke soorten vertrouwelijke informatie, denk aan persoonsinformatie, draagt het dataproduct?
 * Dataretentie
Hoe lang de informatie moet worden bewaard?
 * Regelgeving en overeenkomsten
AVG, domeinspecifieke regelgeving, contractuele overeenkomsten
 * Doelbinding
Voor welke doelen mag het dataproduct worden gebruikt.

#### Waardevol

Het dataproduct moet inherente waarde voor de datagebruikers en klanten toevoegen (anders hoeft het niet te bestaan). Publieke waarden en business waarden.
En ergens opnemen dat de data op verschillende technische manieren te benaderen is op ‘API’ manieren. Data en techniek zijn 1.
Datakwaliteit toevoegen inzichtelijk volgens een generiek (landelijk) datakwaliteit framework

### Basisinfrastructuur

Om het stelsel goed te laten werken zijn enkele basiscomponenten van belang. Een datacommunicatie-infrastructuur is uiteraard essentieel voor het transporteren van data. Deze basisinfrastructuur bestaat op zijn beurt weer uit verschillende componenten en werkt op basis van veelal mondiale afspraken over toe te passen standaarden. Delen van deze infrastructuur vallen onder verantwoordelijkheid van private partijen, delen onder samenwerkingsverbanden en weer andere delen vallen onder de overheid. Digitale tweelingen maken gebruik van deze infrastructuur.
Toelichting van de basiscomponenten:

#### Dataproduct catalog (service)

De data-producten moeten vindbaar zijn en exploratief verkend kunnen worden.
De data catalog werkt met federatieve indexen of anderszins omdat de relevante informatie bij het data-product zelf staat. 

De ontstaansgeschiedenis (pipelines), kwaliteit, SLO’s, wat wel of niet mag met de data, privacy, etc. is informatie van het data-product dat in de data catalog of in aparte catalogi wordt geëtaleerd maar wel als eenheid functioneert. 

Dataproducten kunnen zoals eerder aangegeven operationale data, modellen, informatiemodellen, etc. zijn. 
Het model kan een reken-, machine learning, deep learning of ander model zijn. De aard van het model bepaalt ook welke informatie nodig is om de transparantie te kunnen bieden zodat de uitkomsten herleidbaar zijn. Dit is niet altijd een eenvoudige opgave omdat bij bv deep learning neurale technieken gebruikt worden.

#### Standaarden

Inhoudelijke en technische standaarden om het stelsel van domeinen te laten werken.
Inhoudelijk: Hoe beschrijven we modellen? Hoe beschrijven we data-kwaliteit? Etc.
Technisch: Hoe notificeren we ons op wijzigingen aan dataproducten? Hoe notificeren we ons op wijzigingen van modellen? Hoe bouwen we de federatieve indexen op? Aan welke voorwaarden moeten API’s voldoen ? frameworks, etc.

#### Communities

We faciliteren communities voor het delen van kennis, gebruikservaringen, tooling, code, e.d.

#### Knowledge Graphs

Semantische samenhang over de domeinen heen drukken we uit in knowledge graphs voor het borgen van de onderlinge samenhang en hergebruik.

#### Monitoring

Met monitoring monitoren we de runtime van data-producten, modellen en andere essentiële onderdelen van de DT’s.
IAM

### Federatieve governance 

Dataproducten worden autonoom ontwikkeld en beheerd en de dataproducten zijn breder in de organisatie te gebruiken (cross domain). Er is decentrale autonomie en met centrale richtlijnen, beleid en standaarden t.b.v. data uitwisseling in de organisatie.

Een gefedereerde besluitvormings- en verantwoordingsstructuur, wordt geleid door de federatie van eigenaren van domein dataproducten en producteigenaren van dataplatforms, met autonomie en domein-lokale beslissingsbevoegdheid, terwijl een reeks generieke organisatie brede regels wordt gecreëerd en nageleefd - regels die worden toegepast op alle dataproducten en hun interfaces - zorgen voor een gezond en interoperabel nDFTL digital twin ecosysteem.  
Het creëert een stimulans- en verantwoordingsstructuur die in evenwicht is de autonomie en wendbaarheid van de domeinen, en de organisatie brede conformiteit, interoperabiliteit en veiligheid van data mesh t.b.v. data uitwisseling.

Om het geheel mogelijk te maken, vereist een datamesh-implementatie een bestuursmodel dat decentralisatie en zelfsoevereiniteit van het domein, interoperabiliteit door organisatiebrede standaardisatie en een dynamische topologie.

De uitdaging is het handhaven van een evenwicht tussen centralisatie en decentralisatie.  
Welke beslissingen moeten worden gelokaliseerd voor elk domein en welke beslissingen moeten globaal worden genomen voor alle domeinen? Uiteindelijk hebben organisatie brede beslissingen maar één doel, namelijk het creëren van interoperabiliteit en een versterkend netwerkeffect met het samenstellen van dataproducten.

De prioriteiten van de governance in data mesh zijn anders dan de traditionele governance. Hoewel ze allebei waarde uit data wilden halen, probeert traditioneel databeheer dat te bereiken door de besluitvorming te centraliseren en een canonieke representatie van data tot stand te brengen. De federatieve governance van Data Mesh daarentegen omarmt verandering met de federatie bestaande uit data product- en platform eigenaren.

### De werking in samenhang beschreven 

De nationale Digitale Tweeling bestaat niet 1 digitale tweeling maar uit een stelsel van digitale tweelingen. Deze digitale tweelingen zijn georganiseerd per domein. In een domein vinden stakeholders van bedrijfsleven, wetenschap, kenniscentra, overheid en burgers elkaar rondom bepaalde vraagstukken zoals luchtverontreiniging of leefbaarheid van de omgeving. De meeste domeinen bestaan al, nieuwe domeinen zullen ontstaan terwijl huidige domeinen veranderen of in een ander opgaan of verdwijnen. Dit is een sociaal maatschappelijk proces gebaseerd op waarde. Ieder domein is federatief van opzet en heeft zijn eigen afspraken, governance en financiering.

We hebben een bijzonder domein. Dit is het domein van de geo(basis)registraties. Dit domein biedt de referentiegrondslag. Door gebruik te maken van de Basisregistratie Grootschalige Topografie (BGT), Basisregistratie Adressen en Gebouwen (BAG), 3D bestand van Nederland gebaseerd op de BGT en puntenwolken en andere referentieregistraties  hanteren de domeinen dezelfde referentiegrondslag waardoor de resultaten uit de domeinen met elkaar te vergelijken zijn. 

<m>AFBEELDING 14</m>

Deze – vaak relatief statische – gegevens vormen een robuust fundament, waaraan dynamische informatie kan worden toegevoegd. Zo is een 3D referentie van een nieuwe stadswijk met hoog- en laagbouw een stevige basis voor dynamische analyses van te verwachten luchtstromen op straatniveau.

 
Door de federatieve opzet zal iedere organisatie zelf moeten zorgen voor het ontsluiten van de data producten die ze willen delen met anderen. Dit delen gebeurt met services vanuit de bron. Voorwaarden hierbij zijn dat het vindbaar, begrijpelijk, betrouwbaar en waarheidsgetrouw, adresseerbaar, semantisch interoperabel, toegankelijk en veilig en natuurlijk waardevol is voor de gebruikers. De voorwaarden worden bij een federatieve opzet ingevuld door de bronhouder of aanbieder namens de bronhouder. Het is hierdoor zeer decentraal van opzet. Aan de bron worden de privileges toegekend wie wat mag. Deze federatieve aanpak kan alleen werken als we ons houden aan bepaalde afspraken. Deze worden met elkaar gemaakt en beheerd. 

<m>AFBEELDING 15</m>

In bovenstaande figuur zien we dat binnen een domein organisatie A het data platform X hanteert en hetzelfde platform ook gebruikt wordt door andere organisaties. Dit kan een samenwerking zijn op basis van open source, closed software of een combinatie. Hier doen we geen uitspraken over, dit is aan het domein.

Organisatie A heeft een data product gepubliceerd. Dit kan van alles zijn, van statische gegevens tot bijvoorbeeld een continue stroom van meetgegevens. Het data product voldoet aan de eerder gestelde voorwaarden. Omdat andere organisaties deze gebruiken helpt organisatie A de gebruikers met events op veranderingen op data en het informatiemodel. Ze hebben ook documentatie hoe het data product snel gebruikt kan worden en voor welke doeleinden. De gebruikers komen bij deze informatie door aan te sluiten op de node.

Organisatie B gebruikt een ander data platform en gebruikt het data product in de organisatiewebsite. 
Organisatie C maakt downstream gebruik van de data producten van organisatie A en B. Deze worden met een Machine Learning model (groen) verwerkt, en dit leidt tot een nieuw product dat upstream voor hergebruik beschikbaar wordt gesteld. Het ML model is tevens volgens de randvoorwaarden gepubliceerd. Tenslotte maakt een andere organisatie weer gebruik van het ML model van organisatie C dat als service beschikbaar is en laat dit los op het data product (blauw). Dit wordt gecombineerd met het paarse interne data product en leidt tot een nieuw samengesteld data product (grijs) dat voor hergebruik beschikbaar wordt gesteld. 

Bovenstaande manier van werken is recursief. Het werkt ook zo voor de andere domeinen, organisaties, afdelingen, etc. 

Met de data mesh view hebben we een stuk basisinfrastructuur waarmee we binnen een domein en tussen de domeinen het makkelijker maken om data producten te kunnen vinden, semantiek samenhang beter kunnen duiden en hergebruiken, op kwaliteit van services wordt gemonitord of op het gebruik van de standaarden. Ook een centrale trustvoorziening kan nodig zijn om toegangsaspecten binnen het stelsel goed te kunnen inrichten of andere dingen waarvan we met elkaar vinden dat deze nodig zijn.

Samenwerkende organisaties binnen het stelsel, of beter nog, samenwerkende computers, dienen te weten bij welke organisatie bepaalde data, modellen en verwerkingscapaciteit aanwezig zijn. Daarvoor hebben we centrale wegwijzers of indexen nodig want bij een federatief stelsel zal de data product eigenaar metadata niet opnieuw opvoeren op de basisinfrastructuur. De metadata staat bij het data product en we maken geen onderscheid meer tussen metadata en data. Het is allemaal data geworden die via indexen gevonden wordt. Dergelijke indexen kunnen ook informatie bevatten over de toegankelijkheid van bepaalde dataproducten, modellen of verwerkingscapaciteit.
Dit geeft wel aan dat het niet voldoen aan de randvoorwaarden ook zorgt voor het niet vindbaar zijn van het data product. Een federatieve infrastructuur kan niet zonder volwassen eigenaarschap.

Een datacommunicatie-infrastructuur is uiteraard essentieel voor het transporteren van data. Deze infrastructuur bestaat op zijn beurt weer uit verschillende componenten en werkt op basis van veelal mondiale afspraken over toe te passen standaarden. Delen van deze infrastructuur vallen onder verantwoordelijkheid van private partijen, delen onder samenwerkingsverbanden en weer andere delen vallen onder de overheid. Digitale tweelingen maken gebruik van deze infrastructuur.  

Hoe werkt dit dan voor een organisatie die een vraagstuk heeft en gebruik wil maken van de nationale digitale tweeling stelsel?
Een organisatie beschikt over de nodige hulpmiddelen, tooling, voor het manipuleren van data, het ontwikkelen van (nieuwe) modellen, het uitvoeren van simulaties en het doen van voorspellingen. Zij gebruiken hiervoor een combinatie van dataproducten die ze zelf heeft laten ontstaan of verworven (sensoren, apparaten) en dataproducten die via het digitale tweeling stelsel zijn verkregen. Hiermee wordt het mogelijk om bijvoorbeeld geografische informatie te combineren met resultaten van milieumetingen, verkeersgegevens en meteorologische modellen.

Deze gecombineerde modellen kunnen het resultaat zijn van bepaalde momentopnamen, maar in toenemende mate zijn we in staat om ook met direct aan de werkelijkheid ontleende data (realtime) te werken, waardoor een digitale tweeling van dit deel van de fysieke leefomgeving ontstaat. Met de data producten is het dus mogelijk om complexe modellen en visualisaties samen te stellen. Denk hierbij aan het samenstellen van dynamische modellen die het gedrag van verkeersdeelnemers voorspellen in geval van een wegafsluiting of de gevolgen voor fijnstof en geluid bij de verbreding van een weg.

De organisatie kan dit zelf gebruiken en is vrij om het dataproduct weer beschikbaar te stellen voor hergebruik indien andere gebruikers hierom vragen.