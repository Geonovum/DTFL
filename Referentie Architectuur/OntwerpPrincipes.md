## Ontwerp Principes

### Inleiding

In dit hoofdstuk worden de ontwerpprincipes beschreven. Ook wordt de link gelegd met de principes uit NORA, DisGeo en Common Ground.

De ontwerpprincipes zijn te plotten op 3 lagen:
* **Laag 1** – Toepassingen laag van Digital twins waarin functionaliteit aanwezig is zoals bijvoorbeeld: 3D visualisatie, simulatie, what-if scenario, tijdreizen, gamification, BIM gerelateerd werken.
* **Laag 2** – Transformatie laag waarin functionaliteit aanwezig is om allerlei soorten data (bijvoorbeeld procesdata uit taakapplicatie, sensor data , streaming data) uit bronsystemen beschikbaar wordt gesteld aan de toepassingen middels open standaard services, datatransformatie functionaliteit en datamodel mapping, etc.
* **Laag 3** – Registraties laag waarin bijvoorbeeld taakapplicaties, (basis)administraties, sensoren, complex event processing, maar ook digital twins als een bronsysteem, etc. aanwezig zijn.

De ontwerpprincipes zijn afgeleid van:
* NORA
* Common Ground
* Wetgeving (Wet Open Overheid; Wet Hergebruik Overheidsinformatie, Archiefwet)
* AVG & GDPR
* Doelstellingen & visie
* overig

### Principes

<aside class='note'>
   JvG: Hoofdstuk over "by design", zoals security by design.
</aside>

<aside class='note'>
   TZ:  En onderstaande principes telkens ook meeformuleren in andere functionele blokken.
</aside>

<aside class='note'>
   GT:  Onderstaande principes in template ontwerpprincipe opnemen en linken aan gerelateerde constructieprincipes
</aside>

Overzicht eerste aanzet ontwerpprincipes:
* Overzicht en verantwoording herkomst, door datahouder toegestane gebruikscondities, en gebruiksnut gebruikte datasets
(**Ton, obv EU digital rights/principles**)
* Aansluiting op dataspaces tbv het ophalen van data (**Ton, obv EU dataspaces**)
* Aansluiting op dataspaces tbv het herbruikbaar delen van uitkomsten, (**Ton, obv EU dataspaces**)
* Bij delen van uitkomsten naar een dataspace het meegeven van eventuele gestelde condities/voorwaarden voor hergebruik, en 'geërfde' voorwaarden obv gebruikte ingangsdata zoals share-alike voorwaarden (**Ton, obv dataspaces**)
* Aansluiting op dataspaces tbv het in de DT gebruiken v data terwijl die data niet verkregen/gedeeld kan/mag worden
(**Ton, obv EU dataspace / Data governance Act**) (denk aan het trainen van een model / simulatie in de DT met CBS microdata,
terwijl de microdata zelf niet in de DT zit: dit is het soort gebruik dat de DGA mogelijk maakt terwijl de data niet gedeeld wordt, en vergt dus een 'live' manier om buiten de DT met zulke data te interacteren, zodat de resultaten wel in de DT zitten telkens.
* Verantwoording t.a.v. toetsbaarheid en uitlegbaarheid van gebruikte rekenmodellen / algoritmes / AI toepassingen (**Ton, obv EU AI Verordening**)
* Federatie  (in- en aansluiting van / door andere DTs) (**Ton, obv EU Digital Twin plannen**)
* Het tijdelijk/kortstondig gebruiken (en daarna verwijderen) van persoonlijke gegevens (bijv mobliteitsdata) voor een specifieke
gerichte context/vraag (**Ton, obv personal dataspaces, data-altruisme, AVG**)
* Het alleen voor een specifieke vraag in de DT gebruiken van een dataset, en verantwoording daarvan (**Ton, obv EU data altruisme**)
(data altruisme is persoonsgebonden of bedrijfsvertrouwelijke data die van een daartoe erkende tussenpersoon komt en voor een specifiek publiek belang kan worden ingezet, onder tevoren bepaalde gebruikscondities
* Databronnen kunnen verwijderen (en aantoonbaar, e.g. door logs) (**Ton, obv EU AVG, digital principles, data minimalisatie**)

#### Template Ontwerpprincipe

##### naamOntwerpprincipe1

Referentie:
: tekst [link](url)

Rationale:
: tekst

Constructieprincipe(s):
: [naamConstructieprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamconstructieprincipe1)
: [naamConstructieprincipe2](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamconstructieprincipe2)

##### naamOntwerpprincipe2

Referentie:
: tekst [link](url)

Rationale:
: tekst

Constructieprincipe(s):
: [naamConstructieprincipe1](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamconstructieprincipe1)
: [naamConstructieprincipe2](https://geonovum.github.io/DTFL/Referentie%20Architectuur/#naamconstructieprincipe2)