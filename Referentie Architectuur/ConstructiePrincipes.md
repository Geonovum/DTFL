## Constructie Principes en standaarden

### Inleiding
Dit hoofdstuk gaat over het daadwerkelijk construeren van een samenhangende architectuur voor digital twinning. Op basis van de hoofdlijnen van de ontwerpprincipes uit het vorige hoofdstuk worden in dit hoofdstuk de constructie principes en de daarbij behorende standaarden beschreven.

#### Wat is het doel van constructie principes?
Constructieprincipes zijn te beschouwen als richtlijnen voor het ontwikkelen van bijdragen aan het Nederlandse digital twinstelsel. Veel gespecialiseerde architecten, ontwerpers, ontwikkelaars en beheerders spelen hierbij een rol, zoals user interface experts, solution architects, softwareontwikkelaars, informatie-analisten, data-specialisten, IT-architecten, informatiebeveilingsdeskundigen, etc. etc. In dit hoofdstuk vinden zij toe te passen ontwerpprincipes en daarbij behorende standaarden.

#### Hoe worden constructie principes toegepast?
De constructie principes worden toegepast in meerdere typen ontwerpdocumenten, zoals projectstartarchitecturen, solution architecturen, datacommunicatie architecturen, infrastructuur architecturen, etc. etc. Digital twinning kent immers veel componenten, die met elkaar het stelsel vormen. Elk van de hierbinnen toegepaste componenten, worden bij voorkeur in lijn met de constructieprincipes uit dit hoofdstuk ontworpen en gerealiseerd, waardoor zij inpasbaar zijn in het totale stelsel. Toepsassing van deze ontwerpprincipes kan dus ook gezien worden als het zorgen voor een hoge mate van interoperabiliteit binnen het stelsel.

#### Constructieprincipes in relatie tot andere architectuurproducten
De constructie principes zijn een onderdeel van deze NL-DFTL referentiearchitectuur en de andere architectuurproducten die gerealiseerd worden. 
<aside class='note'>
    <p> * GB: Ik zou de plaat niet opnemen. De structuur ervan loopt niet meer helemaal parallel met onze inhoudsopgave. De relatie met pilots maakt deze R.A. erg tijdgebonden en legt het onderhoud ervan al te zeer vast. De suggestie dat er ook al documenten zijn met beschrijvingen vsan bouwblokken, de IST en SOLL architectuur roept verwachtingen op die we met de huidige versie van de R.A. nog zeker niet kunnen waarmaken. Sterker nog: Ik denk niet dat we ooit een IST of een Doelarchitectuur zullen beschrijven. De vele partijen die deze R.A. hopelijk gaan gebruiken, zorgen immers voor een voortdurende beweging binnen het stelsel, waardoor we hiervna nooit een afgeronde doelarchitectuurbeschrijving kunnen maken. . </p>
</aside> 

In onderstaand figuur is de samenhang weergegeven met de pilots en de architectuurproducten. 

<figure id="duiding constructieprincipes">
    <img src="media/duiding constructie principes.jpg" alt="duiding constructieprincipes">
    <figcaption>De constructie principes in samenhang met de referentie architectuur en de pilots</figcaption>
</figure>

#### Waarop zijn de constructie principes gebaseerd?
<aside class='note'>
    <p> * GB: Binnen deze paragraaf moeten we ons beperken tot het noemen van de belangrijkste bronnen die we gerbuikt hebben voor standaarden en richtlijnen, zoals W3C, de PTOLU-lijst van het Standaardisatieforum, etc. De hieronder genoemde wetten zouden we in hoofdstuk 4 moeten plaatsen, als verantwoording van de ontwerpprincipes die we hebben opgesteld. </p>
</aside> 

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
<aside class='note'>
    <p> * GB: Het zal de lezer duidelijk zijn wat de scope van de nDTFL is. We maken een open architectuur. Dat impliceert dat er ruimte is voor verdere 'vertakkingen' binnen extra domeinen of thema's. Dit moeten we goed in de gaten houden bij de verdere ontwikkeling van deze R.A. Als er vnauit de DTFL-community nieuwe zaken naar boven komen, kunnen we die toevoegen aan de volgende versie van deze R.A. Concreet: Geluidsmodelsimulatie kunnen we misschien nu al opnemen. Zo niet, dan in een volgende versie van deze R.A. M.i. kan de onderstaande alinea dus vervallen. </p>
</aside> 

De constructie principes zijn van toepassing op het digital twins ecosysteem, het fundament. Een toepassing in het digital twin ecosysteem zoals bijvoorbeeld een landelijke geluidsmodelsimulatie, kan aanvullende specifieke domein constructie principes hebben, bijvoorbeeld gebaseerd op de wet Geluidhinder (binnenkort Omgevingswet). Of te wel een toepassing moet minimaal voldoen aan de constructie principes maar kan aanvullende domein specifieke constructies principes hebben waaraan moet worden voldaan.

<aside class='note'>
    <p> * GB: De onderstaande figuur gaat over capabilities. Dat 'past' hier niet lekker. Laten we eerst maar eens de ontwerp- en constructieprincipes en standaarden tot een consistent geheel te vormen. Dan kunnen we later wellicht nog iets gaan doen met de toepassing ervan via de capability-insteek. </p>
</aside> 

Onderstaand figuur een overzicht van de capabilities
<figure id="overzicht capabilities">
    <img src="media/infographic capabilities NLDFTL 3.jpg" alt="overzicht capabilities">
    <figcaption>Overzicht capabilities</figcaption>
</figure>

<aside class='note'>
    <p> * FdW: functies toevoegen zoals ; Data markt plaats; enterprise search; data bevragingen/query; visualisatie/model/informatie abonnement; catalogi? 
    * FdW: én BIM gerelateerd werken functionaliteit? </p>
</aside> 

#### Template Constructieprincipe

##### naamConstructieprincipe1

Referentie:
: tekst [link](url)

Rationale:
: tekst

Ontwerpprincipe(s):
: [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

##### naamConstructieprincipe2

Referentie:
: tekst [link](url)

Rationale:
: tekst

Ontwerpprincipe(s):
: [naamOntwerpprincipe2](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe2)

### Presentatie

##### naamConstructieprincipe1
Digitale toegankelijkheid van de digitale informatie

###### Referentie:
tekst [link]https://www.digitoegankelijk.nl/wetgeving/beleid-nederland-en-europa    

###### Rationale:
We toetsen of de digitale informatie en diensten in het digital twin ecosysteem voldoet aan de digitale toegankelijkheid zodat de data- en informatie zowel bruikbaar is voor mensen met een functiebeperking als voor mensen zonder functiebeperking. 
* We passen bij het maken van digitale informatie de standaarden toe: EN 301 549; WCAG 2.1 en WCAG-EM.
* We toetsen publicatie van digitale informatie op digitale toegankelijkheid en zorgen voor een toegankelijkheidsverklaring. Deze verklaring moet gemaakt zijn volgens het officiële model en geaccordeerd zijn door een bestuurder of tekenbevoegde medewerker.
* We publiceren de actuele toegankelijkheidsverklaring(en) online. Dit is verplicht 
* Het is niet zo zwart-wit dat men op elk moment 100% aan de standaard voor digitale toegankelijkheid moet voldoen. Wel moet we als overheidsinstantie ‘in control’ zijn. Dat betekent dat we maatregelen benoemen met een planning om de digitale toegankelijkheid te vergroten en grip te krijgen.

<aside class='note'>
    GT: URL opnemen naar genoemde standaarden
</aside>

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1) Digitale toegankelijkheid
  
<aside class='note'>
    <p> * GB: De vraag is of dit een eis is die we aan het stelsel stellen of dat dit een eis is die we aan websites / portalen stellen. In het eerste geval moeten we ons afvragen hoe diep deze eis ingrijpt in de aard en het modelleren van gegevens, in de modellen en wellicht ook in de uitwissleingsstandaarden. In het tweede geval is het 'slechts' een eis die we stellen aan de presentatielaag. </p>
</aside> 

#### User interface
tekst

#### Customer Experience
tekst

##### [Welk gebruiksdoel (= user story) wordt door de software geleverd?]
tekst

### Analytics
tekst

#### Algoritmen
<aside class='note'>
    <p> FdW: To do: aanvullen met de nieuwe richtlijnen van de Europese Unie (EU) voor de inzet van kunstmatige intelligentie? </p> 
</aside> 

##### naamConstructieprincipe1
FAIR algoritmen

###### Referentie:
tekst [link] AP25 https://www.noraonline.nl/wiki/Transparante_dienstverlening ; AP15 https://www.noraonline.nl/wiki/Doelbinding_(AP)

###### Rationale:
* We toetsen de ontwikkeling en het gebruik van algoritmen op het risico van oneerlijke, bevoordeelde of discriminatoire uitkomsten. We houden toezicht op algoritmes wat betreft de beginselen van ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (fairness) middels ethisch assesment https://dataschool.nl/deda/ en wetmatigheid https://ec.europa.eu/futurium/en/ai-alliance-consultation.1.html.
* We ontwerpen algoritmen met gepaste waarborgen en maatregelen: dataprotection by design.
* We hebben transparantie en verklaarbaarheid geborgd, we hebben de werking van het algoritme in begrijpelijke taal uitgelegd en gecommuniceerd met medewerkers en de burgers in een algoritme register 
* We hebben de menselijke controle en toezicht geborgd. Dit houdt in dat AI-systemen menselijke autonomie en beslissingen moeten ondersteunen, en niet zonder toezicht mogen opereren of grondrechten negeren 
* We ontwikkelen het algoritme zodanig dat er gelijkwaardige uitkomsten gerealiseerd worden 
* We hebben diversiteit, non-discriminatie en rechtvaardigheid geborgd. Bij ontwerp en inzet van algoritme wordt rekening gehouden met inclusie en diversiteit, inclusief gelijke toegang via inclusieve ontwerpprocessen, alsook voor gelijke behandeling. Dit betekent er worden maatregelen genomen tegen bias (vooringenomenheid) die kan leiden tot directe of indirecte discriminatie en uitsluiting. We weten met welke data het algoritme getraind en ontwikkeld is, wat de data kwaliteit is en de eventueel gebreken in de trainingsdata en de bias en hebben dit vastgelegd. 
* We voeren bij aansluiting een assessment van de fairness van het machine-learning algoritme en testen op basis van de maatstaven die belangrijk worden geacht. Deze maatstaven dienen gemonitord te worden zolang het algoritme wordt ingezet. Alle intenties, motivatie en potentiële gevaren van algoritme is gedocumenteerd.  

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1) algoritmen voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (FAIR)

<aside class='note'>
    <p> * GB: Het onderstaande principe is een variant van de 'open source' gedachte. Naar de letter toegepast zou dit principe betekenen dat alle deelnemers in het DT-stelsel hun volledige code moeten publiceren. Dat zal de meeste private partijen doen afhaken. Ik ben er niet zeker van dat we dit principe in deze vorm moeten handhaven. Het omgekeerde kan wel: Partijen die dat wensen, kunnen via een gemeenschappelijke repository code aan anderen beschikbaar stellen. Dit zou een federatieve voorziening kunnen zijn. </p>
</aside> 

##### naamConstructieprincipe1
Hergebruik van algoritmen

###### Referentie:
tekst [link]NORA AP07 https://www.noraonline.nl/wiki/Gebruik_de_landelijke_bouwstenen NORA AP08 https://www.noraonline.nl/wiki/Gebruik_open_standaarden

###### Rationale:
* we maken gebruik van algoritme programmacode onafhankelijke software  
* We herbruiken beschikbare algoritme programmacode die software- en platform agnostic ontwikkeld is
* We publiceren ontwikkelde algoritme programmacode op GitHub (public tenzij private) incl. documentatie voor herbruikbaarheid. 
* We documenteren algoritme programmacode volgens de voorgeschreven standaarden 
* We beheren de algoritme programmacode in een community, samenwerkingsverbanden 
* We publiceren algoritmen incl. metadata in een landelijk register zodat ze eenvoudig vindbaar zijn voor hergebruik

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

<aside class='note'>
    <p> * GB: De uitwerking van dit integriteitsprincipe omvat feitelijk een breed doorgevoerd stelsel van kwaliteitsborging. Er staan dan ook vooral activiteiten in die onder auspicien van een gezaghebbend lichaam in dit kader zouden moeten worden uitgevoerd. Als we dit willen, hoort dit onderwerp meer in het hoofdstuk over stelselafspraken. Denk ook aan certificering en code-inspectie. </p>
</aside> 

#### naamConstructieprincipe1
Integriteit van algoritme

###### Referentie:
tekst [link]https://www.noraonline.nl/wiki/Integriteit

###### Rationale:
De gebruiker van een gegevens moet erop kunnen vertrouwen dat de werking van het algoritme correcte, complete en actuele resultaten levert. 
* De integriteit van algoritme en AI functies wordt gegarandeerd door reguliere validatie en beheersing van gegevensverwerking en geautoriseerde toegang tot algoritme functies, door scheiding van functie, door controle op de werking van het algoritme en gegevensuitwisseling. 
* Uitvoeren van auditing op nieuwe en bestaande werking en data verwerkingen van het algoritme en vastlegging van resultaten audit.
* De criteria voor juistheid, en tijdigheid en volledigheid van algoritme zijn vastgesteld en worden regulier gecontroleerd. 
* controleren vanuit nieuwe ontwikkelde algoritme of veranderende gegevensverwerking van algoritme op juistheid, tijdigheid en volledigheid, voordat verdere verwerking plaatsvindt.

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

<aside class='note'>
    <p> * GB: In het onderstaande principe worden veel, belangrijke beveiligingseisen 'opgehangen' aan het onderwerp algoritme. Het lijkt me beter om dit principe meer algemeen te formuleren en dan verder de concretisering ervan op te nemen onder hetr kopje informatiebeveiliging en privacyborging. </p>
</aside> 

#### naamConstructieprincipe1
vertrouwelijkheid algoritme 

###### Referentie:
tekst [link]AP43  https://www.noraonline.nl/wiki/Vertrouwelijkheid_(principe) 

###### Rationale:
De ontwikkelaar moet erop kunnen vertrouwen dat het algoritme niet wordt misbruikt. 
* De vertrouwelijkheid van algoritme wordt gegarandeerd door scheiding van systeemfuncties, door controle en validatie op toegang tot algoritme 
* Uitvoeren van de Data Protection Impact Assessment (DPIA) nieuwe en bestaande verwerkingen door algoritme 
* Voor het algoritme zijn de mate van vertrouwelijkheid en de bijbehorende identificatie-eisen vastgesteld 
* In geval van vertrouwelijkheid van het algoritme wordt de gebruiker voor toegangsverlening geauthenticeerd.  
* Bij authenticatie dwingt het systeem toepassing van sterke wachtwoordconventies af. 
* De instellingen van het aanmeldproces voorkomen dat een gebruiker werkt onder een andere dan de eigen identiteit. 
* Om de mogelijkheden van misbruik te beperken, hebben gebruikers van algoritmen niet méér rechten dan zij voor hun werk nodig hebben (autorisatie). Daarbij zijn maatregelen getroffen om een onbedoeld gebruik van autorisaties te voorkomen|
* Verleende toegangsrechten zijn inzichtelijk en beheersbaar.               
* De identificatie-eis voor een samengestelde dienst wordt bepaald door de dienst met de hoogste identificatie-eis 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### (Big data) analyse tools
tekst

#### Self learning systems
<aside class='note'>
    <p> FdW: toevoegen: * In het Self learning systeem wordt ervoor gezorgd dat mensen op een verantwoorde wijze taken aan self learning-systeem kunnen toevertrouwen zonder daarbij de controle te verliezen.
* Self learning systeem is controleerbaar door de mens
* Self learning systeem is transparant en uitlegbaar
* Ethisch assesment is verricht voor Self learning systeem  </p> 
</aside> 

#### Artificial Intelligence

### Visualisatie componenten
<aside class='note'>
    <p> FdW: is het gebruik van open source software ook een constructie principe? 
    GB: Zie mijn eerdere comment over open source. We kunnen zeker in hoofdstuk 4 een paragraaf opnemen over onze voorkeur voor open source. Maar niet dwingend voorschrijven, zou ik zeggen.</p>  
</aside>

#### naamConstructieprincipe1
Gebruike open standaarden

###### Referentie:
tekst [link]AP08  https://www.noraonline.nl/wiki/Gebruik_open_standaarden ;  https://www.forumstandaardisatie.nl/open-standaarden/verplicht

###### Rationale:
* we maken visualisatie zónder kennisregels en transformaties zodat we visualisatie tool onafhankelijk blijven 
* We gebruiken open standaard: SLD voor visualisatie geografische informatie https://forumstandaardisatie.nl/open-standaarden/sld 
* We gebruiken open standaard: Open Geospatial Consortium OGC Web Map Service WMS https://www.ogc.org/standards/wms 
* We gebruiken open standaard: Open Geospatial Consortium OGC Web Feauture Service WFS https://www.ogc.org/standards/wfs 
* We gebruiken open standaard: Open Geospatial Consortium OGC CityGML https://www.ogc.org/standards/citygml 
* We gebruiken open standaard: Open Geospatial Consortium OGC CityJSON https://docs.ogc.org/cs/20-072r2/20-072r2.html 
* We gebruiken open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc                                  
* We gebruiken open standaard: Open Geospatial Consortium OGC 3D Tiles https://www.ogc.org/standards/3DTiles 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### naamConstructieprincipe1
Open Source functionaliteit ontwikkelen in visualisatie tooling

###### Referentie:
tekst [link](url)

###### Rationale:
* We ontwikkelen functionaliteit op basis van open source in visualisatie tooling. Dit bevordert hergebruik van functionaliteit en moet door alle partijen worden toegepast.
* we maken gebruik van programmacode onafhankelijke visualisatie software  
* We publiceren ontwikkelde functionaliteit/ programmacode op GitHub (public tenzij private) incl. documentatie voor herbruikbaarheid. 
* We documenteren functionaliteit/ programmacode volgens de voorgeschreven standaarden 
* We beheren de functionaliteit/  programmacode in een community, samenwerkingsverbanden 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### 2D afbeeldingen (data statisch)

<aside class='note'>
    <p> * GB: Waarom deze VIP-behandeling voor BIM-modellen? ER zijn nog tal van andere modellen van belang binnen het DT-stelsel. Ook voor die modellen geldt dat we streven naar standaardisatie. Als 'zelfstandig' principe, kan deze er m.i. uit. </p>
</aside> 

#### 1.3.2 3D afbeeldingen (data statisch)

#### 3D afbeeldingen (data statisch en dynamisch)

#### naamConstructieprincipe1
Open standaarden voor Bouw Informatie Modellen (BIM)

###### Referentie:
tekst [link](url)

###### Rationale:
* We passen open standaarden voor BIM in het digital ecosysteem toe om de interoperabiliteit te bevorderen en voor een optimale werking gegevensuitwisseling.                        
* We gebruiken open bestands formaat: IFC 2.0 https://www.forumstandaardisatie.nl/open-standaarden/ifc . IFC is een neutraal en open bestandsformaat voor het uitwisselen van BIM-specifieke informatie (modelobjecten en hun eigenschappen). 
* We gebruiken Nederlandse open standaard CAD: NLCS https://www.forumstandaardisatie.nl/open-standaarden/nlcs 
* We gebruiken internationale open standaard: BIM Collaboration Format BCFhttps://www.buildingsmart.org/standards/bsi-standards/bim-collaboration-format-bcf/  
* We gebruiken open standaard: 3D vector tiles https://www.ogc.org/standards/3DTiles  
* We gebruiken de Nederlandse Revit open standaard: NLRS https://www.bimloket.nl/p/225/NLRS 
* We gebruiken open standaard: NL/Sfb https://www.bimloket.nl/p/107/NL-SfB. NL/SfB is een classificatie van bouwdelen en installaties (‘elementen’ genoemd). In de bouw- en installatiebranche wordt deze standaard veel toegepast bij het ontwerpen, realiseren en beheren van gebouwen. 
* We gebruiken open standaard: COINS2 https://www.bimloket.nl/p/100/COINS. Met COINS (Constructieve Objecten en de Integratie van Processen en Systemen) kunnen partijen die betrokken zijn bij bouwprojecten digitale informatie uitwisselen. 
* We gebruiken open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### Dashboards
tekst

#### Grafieken
tekst

#### Monitors (data dynamisch)
tekst

#### Simulaties (manipuleerbare data en modellen)
tekst

#### Rekenmodellen
tekst

#### Simulatiemodellen
tekst

### Business logic

#### naamConstructieprincipe1
business logica is onafhankelijk visualisatie tooling 
###### Referentie:
tekst [link](url)

###### Rationale:
* Er wordt geen business logica los in de visualisatie tooling. Dit geldt ook voor de informatie- en datamodellen en ontologiën.                         |
* We maken gebruik van open source software voor BPMN workflow en DMN decision automation zoals bijvoorbeeld Camunda. 
* We ontwikkelen businesslogica in een taal die software onafhankelijk is zoals bijvoorbeeld BPMN, Python, Django en Go 
* Businesslogica ondersteunt API REST OPEN APIspecification https://swagger.io/specification/ 
* We publiceren ontwikkelde business logica op GitHub (public tenzij private) incl. documentatie.                                
* We borgen dat business rules voldoen aan ‘rechtmatigheid’, ‘transparantie’ en ‘behoorlijkheid’ (FAIR). 
* We gebruiken Common Data Environment CDE conform ISO 19650  https://www.bimloket.nl/p/269/NEN-EN-ISO-19650 en NEN2660 https://www.nen.nl/nen-2660-1-2020-ontw-nl-278048 . NEN 2660-1 biedt een raamwerk voor het ontwikkelen van samenhangende conceptuele modellen en -views, die betrekking hebben op het gebruik van, en de gehele levenscyclus van de gebouwde omgeving, en elementen uit deze omgeving.                 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)


### Gateway
<aside class='note'>
    <p> FdW: er zijn meerdere API gateway toepassingen voor voor API REST en geo-webservices maar ook API gateway voor streaming data. </p>   
</aside>

#### naamConstructieprincipe1
standaardiseren in open source API Gateway oplossingen
###### Referentie:
tekst [link](url)

###### Rationale:
* Het toepassen van open standaarden en open source API gateway referentie model bevordert de interoperabiliteit en hergebruik van kennis en moet door alle partijen worden toegepast.  
* Deelnemers digital twin ecosysteem werken verplicht volgens open standaarden op een uniforme wijze. Een overzicht van vastgestelde open standaarden waarvoor het 'pas toe - of leg uit' - regime geldt, is te vinden op Lijst https://www.noraonline.nl/wiki/Gebruik_open_standaarden 
* We gebruiken open source NLX als referentie model voor API gateway API REST en geo-webservices https://nlx.io/. 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

### Datacommunicatie
tekst

#### Semantiek / ontologie

#### naamConstructieprincipe1
gebruik gemeenschappelijkelandelijke- en smart city-ontologieen om digital twins met elkaar te kunnen verbinden

###### Referentie:
tekst [link]AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven  

###### Rationale:
* We gebruiken van gemeenschappelijke landelijke- en smart city-ontologieen die visualisatie tool onafhankelijk zijn en platform agnostisch. De gemeenschappelijke ontologie is een kennisgraaf met samenhang tussen de ontologieën van digital twins waarmee cross-domein data analyse mogelijk is. We relateren digital twins aan elkaar daar waar nuttig voor analyse en visualisatie.         
* We gebruiken de smart city-ontologie ETSI CIM NGSI-LD Saref4City:  https://www.etsi.org/deliver/etsi_gs/CIM/001_099/006/01.01.01_60/gs_CIM006v010101p.pdf                               
* We gebruiken ontologie IMBOR Informatie Model Openbare Ruimte https://github.com/Stichting-CROW/imbor                                 
* We gebruiken ontologie Gegevenswoordenboek Stedelijk Water (GWSW) https://data.gwsw.nl/
* We gebruiken W3C/OGC GeoSparql ontologie https://www.ogc.org/projects/groups/geosparqlswg 
* We maken gebruik van Linked data open standaarden: JSON-LD, SparQL en RDF of OWL voor ontwikkelen ontologie
* Note: Microsoft maakt gebruik van smart city-ontologie ETSI CIM NGSI-LD en en heeft het geïmplementeerd op Micrsoft Azure Digital twin software middels een specifieke Microsoft taal: open source DTDL-based Smart Cities ontology  https://techcommunity.microsoft.com/t5/internet-of-things/smart-cities-ontology-for-digital-twins/ba-p/2166585. Het is niet volledig leveranciersonafhankelijk

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### Dataobjectmodellen

#### naamConstructieprincipe1
canonieke data-objecten om digital twins met elkaar te kunnen verbinden

###### Referentie:
tekst [link]AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven 

###### Rationale:
* We gebruiken afgesproken canonieke data object: Rijksdriehoekscoördinaten “RD- coördinaten” https://www.nsgi.nl/geodetische-infrastructuur/referentiestelsels/rdinfo      
* We gebruiken afgesproken canonieke data object: “NAP” https://www.rijkswaterstaat.nl/zakelijk/open-data/normaal-amsterdams-peil#:~:text=Om%20binnen%20Nederland%20hoogtes%20te,6%2C78%20m%20onder%20NAP.    
* We gebruiken afgesproken canonieke data object:  “Nederlandse tijd” https://24timezones.com/Nederland/tijd    
* We gebruiken afgesproken canonieke data object:  “geografisch middelpunt van Nederland”   https://nl.wikipedia.org/wiki/Geografisch_middelpunt_van_Nederland                                  
* We datamodelleren conform de MIM standaard  https://www.forumstandaardisatie.nl/open-standaarden/mim                                             
* We ontwikkelen datamodellen die uitwisselbaar zijn in een open standaard formaat UML eXchange Format (UXF) https://en.wikipedia.org/wiki/UXF

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### Metadata

#### naamConstructieprincipe1
Vindbaarheid data

###### Referentie:
tekst [link](url)

###### Rationale:
* Er is een federatief stelsel van landelijke datacatalogi met daarin geregistreerd alle binnen het digital twin ecosysteem gebruikte databronnen, databestanden, informatie producten en digital twins met de relevante metadata conform DCAT standaard en MDTO Duurzaam Toegankelijke Overheidsinformatie voor archivering en vernietiging in de Datacatalogus. De W3C Data Catalog Vocabulary (DCAT) is een metadata-standaard en is ontworpen om interoperabiliteit tussen gegevenscatalogi te vereenvoudigen  
* We passen DCAT toe: https://www.w3.org/TR/vocab-dcat-2/ 
* We passen MDTO toe: https://www.informatiehuishouding.nl/actueel/nieuws/2021/10/13/definitieve-versie-mdto-nu-online-beschikbaar 
* We hergebruiken landelijke datacatalogi                              
* Geografische metadata wordt vastgelegd conform ISO 19115 metadata standaard https://docs.geostandaarden.nl/md/mdprofiel-iso19115/              
* Er is een integrale zoekmachine voor het vinden van gegevens in het federatief stelsel van catalogi.

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)


#### Attribuutbeveiliging
tekst

#### Masterdata / begrippen & definities

#### naamConstructieprincipe1
uniforme begrippen & definities

###### Referentie:
tekst [link]AP17 https://www.noraonline.nl/wiki/Informatie-objecten_systematisch_beschreven

###### Rationale:
* We maken gebruik van de landelijk vastgestelde bedrijfsobjecten, informatiemodellen en standaarden. Zoals het landelijk bedrijfsobjectenmodel GEMMAhttps://www.gemmaonline.nl/index.php/GEMMA2/0.9/id-85853310-d375-4c9d-ae7a-46dcd0906996 en standaard informatiemodellen zoals RSGB https://www.gemmaonline.nl/index.php/Informatiemodel_Basis-_en_Kerngegevens_%28RSGB%29, IMRO https://www.geonovum.nl/geo-standaarden/ro-standaarden-ruimtelijke-ordening/informatiemodel-ruimtelijke-ordening-imro2012, IMWA, IMKICH.                                                                
* Voor maximale interoperabiliteit is het van belang dat structuur en syntax gestandaardiseerd zijn 
* We standaardiseren de semantiek van gegevens conform de werkelijkheid                             
* Bij uitwisseling van gegevens maken we ook de context van het gebruik van gegevens inzichtelijk   
* We gebruiken gegevens met een eenduidige landelijke taxonomie, classificatie van begrippen. We maken gebruik van Samenhangende Objecten Registratie SOR begrippenkader                                 
* We publiceren in de landelijke repository/ datacatalogus 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

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

#### Berichtformaat
tekst

### Communicatieprotocol
tekst

#### Service/ API

#### naamConstructieprincipe1
Gebruik open standaarden

###### Referentie:
tekst [link]AP08  https://www.noraonline.nl/wiki/Gebruik_open_standaarden ;  https://www.forumstandaardisatie.nl/open-standaarden/verplicht

###### Rationale:
* We gebruiken open standaard: Open Geospatial Consortium OGC Web Map Service WMS https://www.ogc.org/standards/wms 
* We gebruiken open standaard: Open Geospatial Consortium OGC Web Feauture Service WFS https://www.ogc.org/standards/wfs 
* We gebruiken open standaard: Open Geospatial Consortium OGC CityGML https://www.ogc.org/standards/citygml 
* We gebruiken open standaard: Open Geospatial Consortium OGC CityJSON https://docs.ogc.org/cs/20-072r2/20-072r2.html 
* We gebruiken open standaard data uitwissel formaten: usd; .dwg; .fbx; .nwd; .nwc                                  
* We gebruiken open standaard: Open Geospatial Consortium OGC 3D Tiles https://www.ogc.org/standards/3DTiles 
* We maken gebruik van API strategie en design rules: API design rules en [NL-GOV API Strategie](https://docs.geostandaarden.nl/api/API-Strategie-ext/#authentication)  
* De ontwikkelde services/API's zijn vindbaar (Github) en herbruikbaar 
* We documenteren t.b.v. herbrukbaarheid programmeertaal onfahnakelijk volgens de OpenAPI Specification (OAS) standaard.  https://swagger.io/specification/     
* We gebruiken de INSPIRE Europese richtlijnen: INSPIRE - Europese leefomgeving  https://wetten.overheid.nl/BWBR0026158/2009-09-01                    
* ISO 19136: Geography Markup Language  GML https://committee.iso.org/sites/tc211/home/projects/projects---complete-list/iso-19136-1.                   
* We gebruiken de Europese richtlijnen Minimal Interoperability Mechanisms en Synchronicity architectuur 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### naamConstructieprincipe1
Open Source API Management

###### Referentie:
tekst [link](url)

###### Rationale:
Het toepassen van open source API Management bevordert hergebruik van functionaliteit en moet door alle partijen worden toegepast. Er zijn geen door private partijen afgedwongen beperking aan het gebruik. Voor een optimale werking van het digital twin ecosysteem is een uniforme gegevensuitwisseling van belang

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)


#### Verwijsindex
tekst

### Transformaties
tekst

#### Transformatieregels
tekst

#### Transformatiecomponent
tekst

### Databewerking
tekst

#### Dataverrijking
tekst

### Data verwerving

#### naamConstructieprincipe1
Eenmalige vastlegging meervoudig gebruik

###### Referentie:
tekst [link]AP13 https://www.noraonline.nl/wiki/Bronregistraties_zijn_leidend  

###### Rationale:
* We voorkomen duplicatie (kopieën) van gegevens in de cloud omgeving van de aanbieder van visualisatie- dashboard-, simulatie tooling. 
* Gegevens worden gescheiden van visualisatie- dashboard-, simulatie tooling bewaard. Opslag van gegevens is onafhankelijk van de Visualisatie software, gebruikte app's.  
* Ieder gegeven wordt op precies één plek bijgehouden, zodat altijd duidelijk is wat het actuele brongegeven is en waar dat wordt beheerd. Dubbele opslag betekent synchroniseren, zodat partijen altijd naar dezelfde gegevens kijken. Dit geldt zowel binnen als buiten de oplossing, dus ook voor eventuele afgeleide opslag die geoptimaliseerd is ten behoeve van verstrekking.                                                        
* Gegevens zijn alleen te registreren, wijzigen en raadplegen via dataservices, zodat de registratieservices kunnen garanderen dat de gegevens en metagegevens altijd voldoen aan de eisen en dat logging altijd plaatsvindt.      
* Gegevens worden op betrouwbare en veilige wijze beheerd, zodat aangetoond kan worden dat gegevens niet bedoeld of onbedoeld gemanipuleerd zijn.    
* Samenhangend gebruik van gegevens is makkelijk mogelijk, zodat gegevens uit verschillende gegevensverzamelingen te combineren zijn.     

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### naamConstructieprincipe1
beschikbaarheid, vertrouwelijkheid en integriteit van registratie van gegevens (BIV)

###### Referentie:
tekst [link]AP44  https://www.noraonline.nl/wiki/Controleerbaarheid  AP40 https://www.noraonline.nl/wiki/Onweerlegbaarheid_(principe)  AP41  https://www.noraonline.nl/wiki/Beschikbaarheid  AP42 https://www.noraonline.nl/wiki/Integriteit  AP43 https://www.noraonline.nl/wiki/Vertrouwelijkheid_(principe)

###### Rationale:
* We voldoen aan wet- en regelgeving nemen organisatorische-, procedurele- en technische maatregelen in  het beschikbaar stellen van data, bewerkingen en transformaties.                                           
* We voeren Data Protection Impact Assessment (DPIA)3 uit op bestaande & nieuwe dataverwerkingen   
* We voldoen aan de Baseline informatiebeveiliging Overheid (BIO) in data services, transformaties 
* Toegang tot privacygevoelige gegevens wordt alleen geboden aan afnemers met doelbinding. Een gebruiker heeft toegang tot de data waarvoor hij/ zij geautoriseerd is. Dit wordt vastgelegd in de gegevens-leveringsovereenkomsten (GLO)  
* Alle bedrijfsobjecten en onderliggende dataobjecten, hebben een eigenaar die verantwoordelijk is voor de integriteit, vertrouwelijkheid, kwaliteit en beschikbaarheid van de data.                                                                                                    
* Auditing vindt plaats op het gebruik van persoonsgegevens conform vastgestelde protocollen en gegevensbeveiliging 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### naamConstructieprincipe1
duurzame toegankelijkheid van gegevens

###### Referentie:
tekst [link](url)

###### Rationale:
* We voldoen aan de Archiefwet 
* Verantwoording kunnen afleggen over uitgevoerde acties en transparantie    
* We zorgen er voor dat de opslag van gegevens duurzaam is   
* We bewaren gegevens niet langer dan nodig is       
* We nemen maatregelen voor tijdige en volledige archivering van gegevens. 

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)

#### naamConstructieprincipe1
continue verbetering van de kwaliteit van gegevens

###### Referentie:
tekst [link]AP31 https://www.noraonline.nl/wiki/PDCA-cyclus_in_besturing_kwaliteit  AP32  https://www.noraonline.nl/wiki/Sturing_kwaliteit_op_het_hoogste_niveau  AP33  https://www.noraonline.nl/wiki/Baseline_kwaliteit_diensten  AP34 https://www.noraonline.nl/wiki/Verantwoording_besturing_kwaliteit

###### Rationale:
* Processen die het kwaliteitsbeheer en continu verbeteren borgen zijn ingericht                           
* De kwaliteit van gegevens zijn van alke databron vastgelegd als metadata                                             
* Buiten de syntactische correctheid van gegevens bewaakt men ook de integriteit over gegevens- verzamelingen heen     
* Afnemers dienen aan te geven wat hun eisen zijn ten aanzien van de kwaliteit en actualiteit van gegevens. Datakwaliteit wordt afgesproken en vastgelegd de GLO gegevens levering overeenkomst                                                            
* Datakwaliteit wordt geoptimaliseerd voor het proces waarbinnen het gebruikt wordt. De broneigenaar (en proceseigenaar) is verantwoordelijk voor de optimalisatie.                                                                                    
* Proceseigenaren zien erop toe dat de data, de data die binnen een proces worden ingewonnen of geactualiseerd. Datakwaliteit wordt door proceseigenaren voortdurend gerapporteerd en datakwaliteit inzichtelijk aangeboden in datacatalogus, aangeduid met een kwaliteitslabel op een duidelijke schaal conform de handreiking gegevenskwaliteit.                                         

###### ontwerpprincipe(s):
 * [naamOntwerpprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamontwerpprincipe1)


#### Toegang
tekst

### Infrastructuur
tekst

#### Datacenter
tekst

#### Cloud
tekst

#### Public
tekst

#### Private

##### 5.3.4.1. Personal Data Pods (Solid)
Solid, afgeleid van "social linked data", is een set van conventies en tools om het web te decentraliseren. Gebruikers slaan persoonlijke data op in "pods" (personal online data stores) die gehost worden waar de gebruiker maar wil. Applicaties die door Solid zijn geverifieerd, mogen gegevens opvragen als de gebruiker hiervoor toestemming heeft gegeven. De gebruiker behoudt volledige eigendom van en controle over de gegevens en bepaalt zelf welke toepassingen toestemming hebben om de gegevens te gebruiken.

Het doel van Solid is om de privacy van internet gebruikers te verbeteren en om individuele gebruikers volledige controle te geven over het gebruik van hun data.

### Netwerk
tekst

##### Public
tekst

##### Private
tekst

### Internet of Things
Het internet der dingen (Engels: Internet of Things, IoT) is het geheel aan kleine apparaten ("dingen") die via internetverbindingen met andere apparaten of systemen in contact staan en daarmee data uitwisselen. Alledaagse voorwerpen kunnen communiceren met met andere objecten en systemen, en op grond hiervan (autonome) beslissingen nemen of actuatoren aansturen. De mogelijkheden die ontstaan wanneer fysieke objecten en de virtuele wereld samenkomen (in de Digitale Tweeling), vormen een belangrijk aspect van het internet der dingen.

Dingen hebben beperkte berekenings, -geheugen, -batterij en communicatiecapaciteit, waarmee rekening moet gehouden worden.
Bij voorkeur communiceren dingen via een beveiligd communicatiekanaal.

Apparaten zijn zich 'bewust' van hun fysieke locatie op aarde alsook de locatie van wat geobserveerd wordt, dit is de basis van de Observations en Measurement standaard (ISO 19156)

#### Sensoren
Sensoren verzamelen data over hun omgeving (bv temperatuur, luchtdruk, beelden van een kruispunt, ...), en sturen ze door of houden ze vast tot ze doorgestuurd kunnen worden.

#### Actuatoren
Via een actuator beïnvloeden de apparaten de fysieke wereld. Een actuator zet data om in een actie, bijvoorbeeld een beweging, aan of uit zetten van een licht of het nemen van een foto.

#### Scada
tekst

#### Remote sensing 
tekst

#### Edge computing (moet dit hier staan?)
Edge computing is een gedistribueerd computerparadigma dat berekeningen en gegevensopslag dichter bij de gegevensbronnen brengt. Dit zal naar verwachting de reactietijden verbeteren en bandbreedte besparen

#### Fog computing (moet dit hier staan?)
Fog computing of fog-netwerken, ook wel fogging genoemd, is een architectuur die edge-apparaten gebruikt om een ​​aanzienlijke hoeveelheid berekeningen, opslag en communicatie lokaal uit te voeren en over de internetbackbone te leiden

### Dataopslag
tekst

#### Traditioneel registratie
tekst

#### In memory
tekst

### Beveiliging / Authenticatie
tekst

#### Identity catalogus
tekst

#### Identity management
tekst

#### Identity check
tekst

#### Identity federation (bijv. SAML2 of OpenID Connect)
tekst.

### Autorisatie
tekst.

#### Autorisatie register
tekst.

#### Autorisatie check
tekst.

#### Autorisatie federatie
tekst.

### Ontwikkeling
tekst.

#### Building
tekst.

#### Development tooling
tekst.

#### Testing
tekst.

#### Test procedures
tekst

##### Test tooling
tekst.

### Beheer
tekst.

#### ASL
tekst.

#### Console
tekst.

#### ITIL
tekst.

## BIJLAGEN

