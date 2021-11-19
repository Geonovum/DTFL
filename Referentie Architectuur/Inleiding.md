## Inleiding

Deze referentie architectuur bevat afspraken en principes voor een digitaal twinstelsel voor de fysieke leefomgeving. Deze referentie architectuur is bedoeld voor iedereen die een rol speelt bij het tot stand brengen van een digital twin of digitale tweeling voor de fysieke leefomgeving. De afspraken, uitgangspunten , principes en standaarden die in dit document worden gepresenteerd, dragen bij aan het tot stand brengen van een stelsel dat bestaat uit vele toepassingen van het idee van digitale tweelingen.

Dit document bevat een "open" architectuur. Dat wil zeggen: de architectuur kan door iedereen, overheid en bedrijfsleven, toegepast worden. Toepassing van de afspraken, principes en standaarden uit dit document draagt bij aan het tot stand brengen van een "ecosysteem", dat bestaat uit veel te verbinden databronnen en rekenmodellen. Hierdoor wordt het mogelijk om data en modellen uit uiteenlopende sectoren en kennisgebieden met elkaar te verbinden en daarmee twee- of driedimensionale beelden samen te stellen van de fysieke leefomgeving, beleidsvorming te ondersteunen met beslismodellen en simulaties of real time besturingsmogelijkheden voor operationele processen mogelijk te maken.

U leest de eerste versie van deze referentie architectuur. Het onderwerp 'digital twinning' is relatief nieuw. Op veel fronten wordt gewerkt aan de verdere ontwikkeling van het idee van digital twinning. Daardoor bestaan momenteel vaak nog vele oplossingen naast elkaar en is er nog geen dominante aanpak of zijn er nog geen dominante standaarden die de interoperabiliteit eenduidig mogelijk maken. Anderzijds zijn er ook nog onopgeloste vraagstukken. Tegen deze achtergrond is deze referentie architectuur opgesteld; zoekend naar zo breed mogelijk gedragen uitgangspunten, principes en standaarden voor het ontwikkelen van digital twins. Zoekend naar een samenhangend pakket van principes en standaarden en daarmee soms ook bepaalde principes en standaarden uitsluitend. De keuzes die in dit document gemaakt worden, kunnen dan ook discussie uitlokken. Dat past bij de fase waarin deze ontwikkeling zich bevindt. Na deze eerste versie zullen dan ook nieuwe versies volgen, die ons weer een stap dichterbij een compleet stelsel voor digital twinning van de fysieke leefomgeving zullen brengen.

### Toepassingsgebied

Deze referentie architectuur beperkt zich tot de fysieke leefomgeving. Daarbij wordt onder meer gedacht aan de gebouwde omgeving, ruimtelijke ordening, verkeersstromen, luchtsamenstelling, geluid, temperatuur, openbaar vervoer, watersystemen en infrastructuren voor energie, data, water, riolering en datacommunicatie.

Binnen dit domein kan digital twinning bijdragen aan het in kaart brengen van de actuele situatie, zoals de plaats en afmetingen van gebouwen, bruggen, tunnels en dergelijke. Of het bijeen brengen van gegevens op basis van metingen van verkeersstromen, fijnstof, geluid of temperatuur. Het kan gaan over statische of dynamische gegevens. Inzet van een digital twin kan onderzoekers en beleidsmakers ondersteunen bij het maken van afwegingen in het ontwerp van aspecten van de fysieke leefomgeving, zoals het ontwerp van nieuwe woonwijken, infrastructuur of het doorrekenen van effecten van maatregelen in het kader van de energietransitie. Digital twinning kan ook een krachtig hulpmiddel zijn bij het dagelijks sturen van processen, zoals verkeersstromen of het opvangen van negatieve gevolgen van voor ons land exeptionele regenval.

Binnen de genoemde domeinen zijn vaak al uitgebreide databestanden en meetgegevens voorhanden. Om gegevens inzichtelijk te maken zijn modellen ontwikkeld. Modellen zijn ook noodzakelijk om "what if" analyses te kunnen doen of simulaties uit te kunnen voeren waarmee betrouwbare voorspellingen kunnen worden gedaan. Er is al veel en er liggen vaak verchillende disciplines en uitgangspunten aan ten grondslag. Digital twinning is te zien als een volgende stap in deze ontwikkeling. Het gaat om het bij elkaar brengen van data en resultaten van modellen om op die wijze een multidimensionaal model van (een deel van) de werkelijkheid samen te stellen. Een voorbeeld: Wat is het effect op de verkeersdoorstroming van een tijdelijke wegafsluiting en wat betekent dit voor de milieubelasting (CO2-uitstoot, geluid) van de alternatieve routes waarvan het verkeer gebruik zal gaan maken en welke aanpassingen in het verkeersbegeleidingssysteem zullen hierbij nodig zijn om een verkeersinfarct te voorkomen? De gecombineerde inzet van rekenmodellen biedt inzicht in dergelijke complexe vraagstukken.

Deze referentie architectuur bevat daarom afspraken, principes en standaarden die relevant zijn voor digital twinning binnen het genoemde gebied. 

### Doelgroep

Dit document is gericht op iedereen die betrokken is bij het ontwikkelen van vormen van digital twinning binnen het fysieke domein. Dit betreft uiteraard bedrijfs-, informatie-, data- en infrastructuur-architecten, maar ook model- en dataspecialisten, ontwikkelaars, user interface- en beveiligingsexperts en beheerders. Voor personen die iets verder van de techniek afstaan zijn de hoofdstukken over het klantperspectief, de publieke waarden en de stelselafspraken mogelijk ook van belang.

### Leeswijzer

<aside class='note'>
GB: Lijkt me niet nodig. ER is een overzichtelijke inhouidsopgave en in de vorige paragraaf staat ook al welk deel van het document voor wie bedoeld is.
</aside> 


### Het proces

Dit document is eind 2021 tot stand gekomen door samenwerking van architecten van onder meer Geonovum, TNO, Kadaster, Gemeente Utrecht en Gemeente Rotterdam. Er is gebruik gemaakt van een grote hoeveelheid recente literatuur over dit onderwerp. Daarnaast is gebruik gemaakt van voorbeelden uit de praktijk, aangevuld met de vaak jarenlange betrokkenheid van de leden van de werkgroep op het gebied van digital twinning, geo-informatie, modelleringstechnieken, data-analyse, referentie architecturen, etc. Via personele unies, gezamenlijke besprekingen en reviewwerkzaamheden hebben deskundigen uit andere werkgroepen binnen het programma Digital Twin van de Fysieke Leefomgeving invloed uitgeoefend op het eindresultaat. Dit geldt ook voor leden van de werkgroep met vertegenwoordigers uit het bedrijfsleven (nader te specificeren).

<!--figure id="voorbeeld plaatje">
    <img src="media/voorbeeldplaatje.jpg" alt="voorbeeldplaatje">
    <figcaption>Dit is een voobeeld van een plaatje</figcaption>
</figure -->

### Architectuur producten

<aside class='note'>
GB: Deze paragraaf strookt niet helemaal met de inhoudsopgave van ons document. Een deel van de informatie staat (nu) in de voorgaande paragrafen.Daarnaast wordt veel gesproken over de bouwblokken, maar we hebben deze voorlopig even voor ons uitgeschoven. De informatie over de pilots zal snel leiden tot veroudering van het document. Ik stel voor deze paragraaf niet op te nemen.
</aside> 

Het team architectuur ontwikkeld de volgende architectuur producten:
* NL-DFTL Referentie architectuur bestaande uit:
    * Capabilities/ bouwblokken
    * ontwerp principes
    * constructie principes
* NL-DFTL doelarchitectuur waarin de generieke "bouwblokken/solutions" zijn opgenomen die landelijk hergebruikt kunnen (moeten) worden
* NL-DFTL roadmap met daarin de geplande realisatie van de generieke herbruikbare "bouwblokken/solution"

NL-DFTL referentiearchitectuur is het kader, de ontwerp- & constructie principes en richtlijnen, waaraan elke pilot, innovatie, projecten binnen het digital twin ecosysteem moet houden zodat de visie, publieke waarden & doelstellingen van het ecosysteem gerealiseerd worden, het ecosysteem goed blijft functioneren en toekomstig bestendig blijft. De NL-DFTL referentie architectuur is gebaseerd op wetgeving, landelijk beleid, referentie architecturen, etc.

De (nationale) ontwerp- & constructie principes geven richting aan de pilots, innovaties, projecten zodat de landelijke doelstellingen & publieke waarden behaald worden. De constructieprincipes worden in de pilots opgenomen in de Project Start Architecturen en toegepast in de solutions van de pilot. Het is niet een eenmalig proces, er vindt regulier afstemming plaats over het toepassen van de constructieprincipes in de PSA’s. 
De feedbackloop is de afstemming tussen het team architectuur en de medewerkers van de pilots over het toepassen van de constructieprincipes en het gesprek indien men noodzakelijk tijdelijk moeten afwijken. Ook kan het zijn dat een pilot leidt tot een nieuw constructieprincipe die toegevoegd wordt aan de referentie architectuur. Het is ook mogelijk dat de pilots aanvullende domein specifieke constructieprincipes & open standaarden moeten hanteren specifiek voor een domein of thema.

De generieke (herbruikbare) bouwblokken/ capabilities zijn de verzameling van functionaliteiten die nodig zijn in het digital twin ecosysteem om de werking van de toepassingen te ondersteunen die de publieke waarden realiseren.

De NL-DFTL doelarchitectuur is het vergezicht met de generieke (herbruikbare) bouwblokken/ solutions die nodig in het digital twin ecosysteem om de werking van de toepassingen te ondersteunen die de publieke waarden realiseren.

Voorbeelden van de generieke (herbruikbare) bouwblokken solutions in het digital twin ecosysteem zijn:
* Toepassingen, bijvoorbeeld een geluidsimulatie model; crowd-monitor; landelijke fijnstof voorspelmodel
* Software componenten, bijvoorbeeld: 3D viewer, identificatie component, API management & gateway, data opslag, etc.
* Infrastructuur componenten, bijvoorbeeld fysieke connectiviteit en dataverbindingen

De generieke bouwblokken/solutions in het digital twin ecosysteem worden zo veel mogelijk hergebruikt  in nieuwe toepassingen die publieke waarden realiseren. 

Met de NL-DFTL doelarchitectuur is het mogelijk om de strategische dialoog te kunnen voeren welke extra investeringen in de landelijke ICT-voorzieningen nodig zijn voor de nationale doelstellingen en publieke waarden te realiseren en met welke prioriteit. Dit resulteert in aanvullende ontwikkeling op de NL-DFTL roadmap. 

De pilots ontwikkelen de bouwblokken solutions die opgenomen zijn (worden) in de roadmap van de NL-DFTL doelarchitectuur. 
De pilot hebben eigen business wensen en publieke waarden die gerealiseerd worden, maar dragen met generieke bouwblokken solutions die hergebruikt kunnen worden, bij aan de realisatie van de NL-DFTL doelarchitectuur en daarmee de nationale doelstellingen en publieke waarden. 

De bouwblokken/ solutions op de roadmap is de basis voor de NL-DFTL doelarchitectuur met de prioriteiten pilots. Hiermee wordt het goed in samenhang functioneren en optimaal hergebruik van de ICT middelen bereikt en daarme voor optimaal rendement van de landelijke investeringen.

In onderstaand figuur zijn de architectuurproducten weergegeven met een rode stip die in het programma gerealiseerd worden:
<figure id="Architectuur producten">
    <img src="media/Architectuur producten NL DFTL v02.jpg" alt="Architectuur producten">
    <figcaption>Architectuur producten</figcaption>
</figure>