## Constructie Principes en standaarden

### Hoe worden constructie principes toegepast?

#### Toepassing
De constructie principes worden toegepast in meerdere typen ontwerpdocumenten, zoals projectstartarchitecturen, solution architecturen, datacommunicatie architecturen, infrastructuur architecturen, etc. Digital twinning kent immers veel componenten, die met elkaar het stelsel vormen. Elk van de hierbinnen toegepaste componenten, worden bij voorkeur in lijn met de constructieprincipes uit dit hoofdstuk ontworpen en gerealiseerd, waardoor zij inpasbaar zijn in het totale stelsel. Toepassing van ontwerpprincipes kan dus ook gezien worden als het zorgen voor een hoge mate van interoperabiliteit binnen het stelsel.

#### Verdieping
In het hoofdstuk [Inleiding](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#inleiding) staat een schets van het digital twin stelsel. We zagen al eerder dat dit opgebouwd is op basis van een combinatie van decentrale opslag van gegevens, modellen en bewerkingsfunctionaliteit, aangevuld met een aantal essentiële centrale, federatieve componenten, waardoor gegevens, modellen en bewerkingsfunctionaliteit over en weer gebruikt kunnen worden. In het vorige hoofdstuk staan algemene uitgangspunten of principes waaraan het stelsel moet voldoen. In dit hoofdstuk gaan we weer een laagje dieper. We gaan kijken naar de wijze waarop digital twinning mogelijk wordt voor deelnemende organisaties.

#### Opbouw van de Digital Twin
Het stelsel van digital twinning is opgebouwd uit een groot aantal componenten of bouwblokken. De onderstaande figuur geeft daarvan een vereenvoudigd overzicht.

<figure id="Dataproduct totaalview GB">
    <img src="media/Dataproduct totaalview gb.jpg" alt="duiding constructieprincipes gb">
    <figcaption><m>titel toevoegen</m></figcaption>
</figure>

De basis voor digital twinning ligt deels in het hergebruik van ontwerpdocumentatie en tal van bestaande registraties. Denk bijvoorbeeld aan geobasisregistraties, digitale bouwtekeningen (BIM-modellen) of ingemeten percelen (Kadastraal model). Deze – vaak relatief statische – gegevens vormen een robuust fundament, waaraan dynamische informatie kan worden toegevoegd. Zo is een driedimensionaal model van een nieuwe stadswijk met hoog- en laagbouw een stevige basis voor dynamische analyses van te verwachten luchtstromen op straatniveau.

#### Additioneel
Digital twinning kan echter meer bieden. Steeds vaker wordt gebruik gemaakt van dynamische en zeer uiteenlopende data die met elkaar worden gecombineerd. Laten we eens kijken hoe dit mogelijk wordt gemaakt.

##### Additioneel - uitwerking/voorbeeld
We zien een organisatie XYZ die deelneemt aan het stelsel. XYZ verkrijgt meetgegevens uit sensoren en data over het functioneren van systemen waarvoor XYZ verantwoordelijk is. Een deel van deze systemen valt in het type “[internet of things](url)”. Voorbeelden van sensoren zijn de bekende detectielussen in onze wegen die het gebruik ervan meten of satellietwaarnemingen van stofdeeltjes. Systemen kennen veelal een eigen ‘besturingssysteem’ (scada) waardoor het mogelijk is permanent of periodiek statusinformatie over de werking van een systeem naar een centrale database door te geven. Denk bijvoorbeeld aan gemalen die data over actuele stroomgegevens (debiet) of meldingen van (te verwachten) storingen doorgeven. Een voorbeeld uit de wereld van verkeersmanagement: sensoren die verkeersgegevens doorgeven, die direct gebruikt worden om verkeerslichten binnen een stad aan te sturen. Voorbeelden van Internet of Things zijn afvalcontainers die via internet doorgeven dat het tijd wordt om geleegd te worden of sensoren die het aantal passanten in een winkelstraat doorgeven.

##### Opslag bij de bron
De verkregen data wordt opgeslagen in eigen databases. Via meerdere applicaties of gegevensverwerkende systemen wordt data gebruikt om overzichten te creëren in de vorm van lijsten en modellen.

##### AI
De gegevens worden bewerkt met behulp van algoritmen, aangevuld met kunstmatige intelligentie. Hierdoor is het mogelijk complexe modellen en visualisaties samen te stellen. Denk hierbij aan het samenstellen van dynamische modellen die het gedrag van verkeersdeelnemers voorspellen in geval van een wegafsluiting of de gevolgen voor fijnstof en geluid bij de verbreding van een weg.

##### Uitwisselingsafspraken
De organisatie gebruikt ook data van andere deelnemers aan het stelsel, zoals van organisatie ABC. Daartoe wordt gebruik gemaakt van uitwisselingsafspraken die in stelselverband zijn gemaakt (inclusief ‘gebruiksrechten’). ABC levert min of meer kant-en-klare informatieproducten, die door XYZ kunnen worden ingelezen en verder verwerkt. XYZ levert daarbij ook gegevens over de kwaliteit, houdbaarheid en herkomst van de geleverde data. Medewerkers van XYZ beschikken over de nodige hulpmiddelen, tooling, voor het manipuleren van data, het ontwikkelen van (nieuwe) modellen, het uitvoeren van simulaties en het doen van voorspellingen. Zij gebruiken hiervoor een combinatie van data die XYZ zelf heeft laten ontstaan (ontwerp!) of verworven (sensoren, apparaten) en data die via het digital twinning stelsel zijn verkregen. Hiermee wordt het mogelijk om bijvoorbeeld geografische informatie (Kadaster) te combineren met resultaten van milieumetingen (RIVM), verkeersgegevens (ANWB) en meteorologische modellen (KNMI). Deze gecombineerde modellen kunnen het resultaat zijn van bepaalde momentopnamen, maar in toenemende mate zijn we in staat om ook met direct aan de werkelijkheid ontleende data (realtime) te werken, waardoor een digitale tweeling van dit deel van de fysieke leefomgeving ontstaat. In ons voorbeeld zou dat een actueel beeld kunnen zijn van de ringweg om Amsterdam, de verkeersdrukte, het fijnstof- en geluidsniveau, de omgevingstemperatuur en de windsnelheid.

##### Uitbesteden
Een bijzonder aspect gaat over het ‘uitbesteden’ van werkzaamheden. Digital twinning betekent ook dat het mogelijk is om eigen databestanden via het stelsel aan te bieden aan andere deelnemers. Deze deelnemers beschikken over gegevensverwerkende systemen, algoritmen en artificial intelligence, waarmee analyses kunnen worden uitgevoerd en modellen kunnen worden gemaakt. In dat geval maakt organisatie XYZ dus gebruik van gespecialiseerde systemen van organisatie ABC om analysewerkzaamheden uit te voeren en het resultaat daarvan terug te krijgen. Alsof je je kleding naar de stomerij (droogkuis) brengt en een keurig eindresultaat retour ontvangt. Dit kan niet alleen een probleem oplossen van een gebrek aan rekenkracht of specialistische analyse-instrumenten, maar het kan ook een oplossing bieden om privacygevoelige data bij de bron te houden – in dit voorbeeld bij ABC – en er dus geen problemen met privacyborging ontstaan. Dit zou bijvoorbeeld het leggen van een verband mogelijk maken tussen de vastgestelde isolatiewaarde van huizen in een stadsdeel te laten koppelen aan geanonimiseerde en geaggregeerde data over de sociaal-economische status van de bewoners.

##### Presentatie
Een deel van de resultaten van dit werk, wordt aan een breder publiek ter beschikking gesteld via de website van XYZ. Dit kunnen statische modellen zijn, maar het kunnen ook modellen zijn die door de bezoekers van de website gemanipuleerd kunnen worden. Een aardig voorbeeld is de “Treinrader” van de Nederlandse Spoorwegen. Een app die een actueel beeld geeft van de treinenloop in Nederland, die elke tien seconden aangeeft waar welk type trein zich bevindt. De gebruiker kan een selectie maken van intercity’s, sprinters, e.d.. 

Over de wijze waarop data en modellen aan een breder publiek gepresenteerd worden, kunnen ook nadere afspraken worden gemaakt in stelselverband. Denk bijvoorbeeld aan de richtlijnen die de overheid kent voor de toegankelijkheid van websites.

##### Polyglot
Daarnaast worden (gecombineerde) data en modellen als dataproducten, in machineleesbare vorm, ter beschikking gesteld aan andere deelnemers aan het stelsel. Hierdoor wordt het mogelijk om combinaties van data in te zetten, zoals we hiervoor al zagen met het voorbeeld van de ringweg rond Amsterdam.

##### Semantiek
Omdat data wordt uitgewisseld die vanuit verschillende achtergronden of domeinen zijn ontstaan, is het belangrijk goede afspraken te maken over de betekenis (semantiek) en samenhang (ontologische relaties) van bepaalde gegevens. Het bekende voorbeeld is informatie over een bank. Het maakt echt verschil of deze informatie van een meubelgigant afkomstig is of van het Ministerie van Financiën. Zo ook met de samenhang van de beschreven objecten. De ene bank zal gerelateerd zijn aan stoel of meubel; de andere aan spaarrekening of rentestand. Deze samenhang wordt geduid in object- en datamodellen of in een meer omvangrijke ontologie.

##### Metadata
Voor de wijze waarop data en modellen worden uitgewisseld worden binnen het stelsel afspraken gemaakt over toe te passen standaarden voor datacommunicatie, de ‘verpakking’ van data, de ‘vrachtbrieven’ bij de data (metadata) en eventuele beperkingen in het gebruik ervan. 

##### Standaarden
Het zal zeker aanvankelijk vaak zo zijn dat nog niet iedere deelnemer dezelfde standaarden hanteert. In dat geval zullen deelnemers zelf moeten zorgen voor goed koppelvlakken met vertaal- of transformatiemogelijkheden. Binnen het federatieve deel van het stelsel zullen echter eenduidige en breed geaccepteerde standaarden worden toegepast.

##### Infrastructuur
Om het stelsel goed te laten werken zijn enkele centrale componenten van belang. Een datacommunicatie-infrastructuur is uiteraard essentieel voor het transporteren van data. Deze infrastructuur bestaat op zijn beurt weer uit verschillende componenten en werkt op basis van veelal mondiale afspraken over toe te passen standaarden. Delen van deze infrastructuur vallen onder verantwoordelijkheid van private partijen, delen onder samenwerkingsverbanden en weer andere delen vallen onder de overheid. Digital twinning maakt gebruik van deze infrastructuur.

##### Indexen
Samenwerkende organisatie binnen het stelsel, of beter nog, samenwerkende computers, dienen te weten bij welke partner bepaalde data, modellen en verwerkingscapaciteit aanwezig zijn. Daarbij kan een centrale wegwijzer of index behulpzaam zijn. Een dergelijke index kan ook informatie bevatten over de toegankelijkheid van bepaalde databestanden, modellen of verwerkingscapaciteit. Ook een centrale trustvoorziening kan nodig zijn om toegangsaspecten binnen het stelsel goed te kunnen inrichten. Kortom: het federatieve deel van het stelsel fungeert als de intelligente rotonde in het dataverkeer.

Tot zover deze meer anekdotische beschrijving van de werking van het stelsel. In de rest van dit hoofdstuk worden deze componenten verder toegelicht, verdiept en van standaarden voorzien. Dit hoofdstuk kan daarmee beschouwd worden als een naslagwerk voor degene die werkt aan een of meerdere componenten van het digital twinning stelsel.

We sluiten dit hoofdstuk af met richtlijnen voor ontwikkeling van componenten en het beheren ervan.j