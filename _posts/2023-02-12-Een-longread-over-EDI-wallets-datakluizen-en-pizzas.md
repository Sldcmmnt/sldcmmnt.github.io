---
layout: post
title: "Een longread over EDI-wallets, datakluizen en pizza’s"
categories: misc
---

# Een longread over EDI-wallets, datakluizen en pizza’s
<sub>_12-2-2023 <br>
door Gijs van den Beucken <br>
Leestijd ca. 15 minuten_  </sub><br>


Er zijn steeds meer ontwikkelingen die je in staat stellen om regie op je digitale leven te nemen. 
Door zelf controle te krijgen over (onderdelen van) je identiteit, data, en betalingen wordt een mensgericht wereldwijd web en een digitale publieke ruimte steeds concreter.
Concrete ontwikkelingen hierin zijn bijvoorbeeld de Europese Digitale Identiteit, datakluizen en persoonlijke assistenten.

Deze longread schetst een beeld hoe deze ontwikkelingen met elkaar samenhangen om zo uitwisseling van kennis, ideeën en onderzoek te stimuleren.

Het doel van deze ontwikkelingen is om jou als mens zoveel mogelijk te ondersteunen op het digitale web.
Om deze ontwikkelingen een overkoepelende naam te geven gebruiken we in deze blog daarom de naam digitaal ondersteuningssysteem.

Vaak zijn de ontwikkelingen nog sterk gefocust op het technnische onderdeel, dat natuurlijk belangrijk is maar niet als enige onderdeel zorgt voor een gezond digitaal web. 

Onderdelen zoals de **gebruikerservaring**, het financieel model, wettelijke kaders en governance, zijn net zo belangrijk voor een succesvolle ontwikkeling van een digitaal ondersteuningssysteem.  

Omdat het (technisch) jargon vaak een drempel is om zaken uit te leggen kiezen we in deze blog zo veel als mogelijk voor eenvoud en beschrijven we zaken vanuit het perspectief van de gebruiker.

In deze blog over een digitaal ondersteuningssysteem leggen we de gebruikerservaring uit beginnend met een pizza.



## Een pizza serveren
Wanneer je als gebruikerservaring een knapperige pizza met verse ingrediënten wilt serveren is er een proces nodig om te komen tot die ervaring.

Je koopt de ingrediënten voor de pizza, en wilt deze samenstellen tot een samenhangend geheel.
Wanneer je alleen het gebakken deeg zou serveren ontstaat er geen volledig gerecht. 
Wanneer je de ingrediënten allemaal los van elkaar bereidt ontstaat ook niet het gewenste resultaat.
De verschillende ingrediënten moeten dus een gebalanceerde samenhang vormen wil er een soepele ervaring ontstaan.

Als een soepele gebruikerservaring in de digitale ruimte het doel is, is het belangrijk om samenhang te creëren in de ingrediënten die een rol spelen bij die ervaring.  
Daarbij is de ervaring van de gebruiker ook nog eens mede beslissend voor de adoptie van nieuwe mogelijkheden.

Wanneer we als maatschappij allemaal ingrediënten van die gebruikerservaring apart gaan bereiden, zonder samenhang of samenwerking, dan eindigen we mogelijk met een set aan gefragmenteerde oplossingen waarbij de gebruikservaring, en mogelijk ook de adoptie, alsnog in de kou staat.

Om de samenhang van deze ingrediënten beter te gaan begrijpen volgt onderstaand een uitleg van de nieuwe ingrediënten die in je digitale ruimte een rol kunnen gaan spelen. 



## 1. Data die iets bewijzen
Dit zijn persoonlijke gegevens over jou die niet met hoge frequentie veranderen, dus min of meer statisch zijn en verbonden zijn aan jou. Denk hierbij aan je naam, de plek waar je woont, of je inwoner bent van Nederland, of je een diploma bezit etc.
Wanneer je in interactie treedt met de buitenwereld wordt vaak gevraagd om te bewijzen dat deze beweringen kloppen, dus te verifiëren zijn. In de digitale wereld daarom ook wel verifieerbare beweringen (Verifiable Credentials) genoemd. 

Aan het gebruik van verifieerbare digitale gegevens zijn verschillende voordelen verbonden. Bijvoorbeeld dat je bepaalde onderdelen kunt bewijzen zonder direct je hele set aan gegevens over jou te delen. Daarnaast hoef je geen scan van een document meer op te sturen die fraudegevoelig kan zijn.

In Vlaanderen werkt de overheid met deze zogenoemde verifiable credentials bij het bewijzen dat je een diploma hebt.
Deze <a href="https://assets.vlaanderen.be/video/upload/c_scale,f_mp4,q_90,w_1280/Sander_-_diploma_case_vfbdxe" target="_blank">video</a> geeft meer uitleg daarover. 
Meer toelichting bij onderstaande video vind je op de website van het Vlaams DataNutsbedrijf onder projecten.
[link](https://assets.vlaanderen.be/video/upload/c_scale,f_mp4,q_90,w_1280/Sander_-_diploma_case_vfbdxe){:target="_blank"}


<p ><a href="https://www.vlaanderen.be/digitaal-vlaanderen/het-vlaams-datanutsbedrijf/projecten-vlaams-datanutsbedrijf" rel="noopener noreferrer" target="_blank" style="color: rgb(143, 143, 143);">Bron</a></p>
    


In Nederland is een bekend initatief IRMA die daarbij verschillende risico’s rond het delen van attributen adresseert. 

Het zou interessant kunnen zijn om te verkennen hoe deze twee voorbeelden zich tot elkaar verhouden. 

Op de IRMA Meetup is Laurens de Backere namens Vlaanderen op bezoek geweest om uit te leggen hoe zij in Vlaanderen hiermee werken. 

De ontwikkeling van een WebId
Bij het inloggen op een website of applicatie komt het bewijzen van wie je bent ook terug. 

Op het wereldwijde web moet je vaak voor iedere applicatie een nieuw account aanmaken om in te loggen. Dit levert het risico en nadeel op dat je een hele set aan wachtwoorden moet onthouden, of vaak op ‘I forgot my password’ mag klikken.

Bedrijven zijn hierop ingesprongen door inloggen makkelijker te maken: Log overal in met je account van bedrijf y. 
Echter je zit daarmee ook direct ingesloten bij de diensten van bedrijf y. 
Als dat bedrijf verbonden is aan een sociaal medium en je zou stoppen met het afnemen van die service, dan ben je direct ook al je inlogmogelijkheden én contacten kwijt want die zitten in die dienst ingesloten.

Willen we in de digitale ruimte de ‘log-in lock-in’ bevrijden en meer onafhankelijkheid bieden dan hebben we een log-in nodig die wel vaker gebruikt kan worden voor het gemak, maar niet direct aan een bedrijf toebehoort. 

Een mogelijkheid die daarvoor nu wordt ontwikkeld is een WebID.  Dit is een manier om in te loggen bij applicaties en organisaties op het wereldwijde web zonder dat je vastzit aan één bedrijf en zonder dat je voor iedere service een apart account hoeft aan te maken.

Een WebID is daarnaast ook een manier om in contact te kunnen blijven met alle mensen die je in je sociale netwerk hebt, los van of zij op sociaal medium x,y,z, zitten, omdat deze link wordt gelegd buiten de services om. 

Waarom loggen we in bij applicaties, organisaties of websites?
Het inloggen is vaak nodig omdat je een service of omgeving krijgt aangeboden die specifiek voor jou bedoeld is en vanuit daar kunt beheren.
Inloggen is dus een middel om die service te kunnen gebruiken. 
Wat die data in jouw account inhouden en hoe die op een nieuwe manier georganiseerd zou kunnen worden beschrijven we in het volgende onderdeel.

## 2. Gebruikersdata en gebruiksdata
Het volgende ingrediënt gaat over gebruiksdata.

Dit zijn data over jou die nu (nog) verspreid staan opgeslagen op de servers van organisaties en bedrijven. Denk aan je lijstje met favoriete boeken of films, je posts op een social medium etc.  
Deze data kunnen in plaats van statisch ook dynamischer zijn: denk hierbij aan nummers die je luistert bij een muziekstreaming-dienst. Terwijl je muziek luistert worden de geluisterde nummers live in je historie opgeslagen. 

Wanneer je deze data zelf zou kunnen beheren op één plek onder jouw controle, in plaats van verspreid op de verschillende servers van de organisaties en bedrijven ontstaan er verschillende voordelen: 

Een eerste voordeel is dat je de controle krijgt over wie deze data uitleest, voor hoelang en voor welk doel.

Omdat de data over jou op één plek staan onder jouw controle zijn die data daarnaast gemakkelijker actueel te houden.  
Als jij verhuist, dan hoef je niet meer bij allerlei webwinkels apart aan te geven wat je nieuwe adres is voor pakketbezorging, maar pas je je adres alleen aan op de plek waar jij jouw adres beheert en lezen de organisaties dat uit.

Een derde belangrijk voordeel van data onder jouw controle is dat je deze data kunt hergebruiken in verschillende apps en stoppen met- en wisselen van applicaties als je dat wilt, zonder daarbij alles kwijt te raken.
Je favoriete boekenlijst van webwinkel 1 kun je zo ook gebruiken bij webwinkel 2.
Je krijgt dus meer keuzevrijheid en bent minder afhankelijk van applicaties. 

Immers, applicaties, services en organisaties komen en gaan, maar de mens of gebruiker is de constante en het scharnierpunt in die processen. Het lijkt dus relevant om data over jou dan ook rondom jou te organiseren in plaats van per applicatie. ‘Bring your own data’.

Om dit te realiseren zullen we applicaties en data van elkaar moeten scheiden.
Een plek waar je deze data beheert wordt een datakluis genoemd.

Solid en datakluizen
Het zet in feite het huidige internet op zijn kop, omdat data niet meer in applicaties staan, maar uitgelezen worden vanuit je datakluis.

Om dit technisch te realiseren is de grondlegger van het wereldwijde web, Tim Berners Lee, enkele jaren geleden begonnen met het ontwikkelen van deze uitbreiding op het internet.
De naam van dit initiatief is Solid, afkomstig van Social Linked Data.

Een datakluis die gebruikt maakt van de open specificaties van Solid wordt ook wel een Personal Online Datastore genoemd, oftewel Pod of SolidPod. Het is gebaseerd op open specificaties waardoor je er geen lock-in ontstaat bij één datakluis aanbieder.

Een onderdeel van Solid is het eerder genoemde WebId, bedoeld om gemakkelijk in te kunnen loggen op websites en applicaties. 

Deze WebId is gekoppeld aan je datakluis waardoor de services en applicaties weten waar de data kan worden neergezet en uitgelezen. 
Deze WebId kan gekoppeld worden aan bijvoorbeeld je DigiD om in de overheidssector je overheidsdatakluis te bezoeken. Of in andere sectoren zoals de zorgsector je zorgdatakluis, of datakluizen. Een WebId kan namelijk gekoppeld worden aan meerdere datakluizen. Als je inlogt ontstaat dan vervolgens één overzicht. 
Wanneer je datakluizen gescheiden wilt houden, bijv. zorggegevens en vrije tijd dan kan dat natuurlijk ook.

Meer achtergrond-informatie en uitleg vind je in deze blog van Ruben Verborgh, professor en verbonden aan het Solidlab in Vlaanderen.
Meer uitleg in de vorm van een video kun je hier vinden.

Nieuwe technieken vragen om nieuwe regels, vooraf ontwikkeld
Deze techniek alleen volledig technisch (door)ontwikkelen is niet voldoende. 
Nieuwe technieken vragen ook om nieuwe regels. 
Open standaarden, governance en wettelijke regels zorgen voor de kaders van een gezonde digitale ruimte waarin keuzevrijheid, transparantie, privacy en gebruiksgemak voorop staan.

Er zijn bijvoorbeeld regels nodig om te voorkomen dat mensen door services overvraagd worden en alleen toegang krijgen tot een dienst wanneer ze meer data delen dan echt nodig is. Om dit soort situaties te voorkomen moet er duidelijke regelgeving komen rondom het ‘voor wat hoort wat’ principe. 

Omdat deze techniek nog tot wasdom moet komen biedt het ook kansen. Nieuwe regelgeving kan ontwikkeld worden vóórdat een nieuwe techniek volledig in gebruik is, in plaats van achteraf de gaten dichten. 

Het ontwikkelen van nieuwe processen biedt ook kansen om oude drempels aan te pakken: door samenwerkingsprocessen te organiseren kunnen bijvoorbeeld cookies en ‘accept our terms’ met lange juridische teksten langzaamaan gaan verdwijnen en plaats maken voor gezondere en meer gebruikersvriendelijkere alternatieven.



3. Financiële data
Het derde ingrediënt van jouw digitale wereld, toegang tot je financiële data, lichten we uit omdat deze sector meer gereguleerd is. 

Je betalingen en bijbehorend rekeningoverzicht worden beheerd door commerciële banken. Met de invoering van een wet om de financiële wereld meer open te stellen (PSD2) kun je sindsdien andere partijen toegang geven tot je bankrekening om deze in te zien.

Het voordeel daarvan is volgens de De Nederlandse Bank: “Al uw betaalrekeningen en betaaltransacties bij verschillende banken verzamelen in een overzicht is een voorbeeld. Zo ontstaat een slim huishoudboekje dat met eerdere betaaltransacties voorspellingen kan doen.”

Daarnaast kan er met de inzage in je bankrekening ook advies over hypotheken en pensioenen worden gegeven. Het gemakkelijk kunnen gebruiken van je rekening-informatie in andere applicaties is volgens de huidige gebruikelijke werkwijze alleen mogelijk via derde partijen. 

Vanuit de visie van controle over eigen gegevens en het scheiden van data en applicaties kan dat als een nadeel worden ervaren. Je hebt wel invloed maar geen directe controle om transactiegegevens automatisch op te slaan in je datakluis en te hergebruiken in applicaties zoals een huishoudboekje. 

Een ander nadeel dat de inzage bij derde partijen is belegd, is dat een dienstverlener zoals een hypotheekverstrekker bij toegang tot je bankrekening de transacties van je bankrekening kan inzien. Daarbij mag de dienst van hypotheken verstrekken geweigerd worden wanneer je geen toestemming geeft voor inzage in je bankrekening.

Om ervoor te zorgen dat je alleen die betalingen deelt die relevant zijn is er ook een mogelijkheid om een betaling te laten bewijzen vanuit de betalende partij.

De loon-afschriften van je werkgever bijvoorbeeld, kunnen als beweringen die te verifiëren zijn (Verifiable Credential) in je SolidPod (datakluis) worden gezet. Zo kun je aan een hypotheekverstrekker bijvoorbeeld alleen die relevante gegevens aanreiken zonder dat ze alle transacties hoeven in te zien.

Tegelijkertijd kunnen deze bewezen betalingen ook gebruikt worden om inkomenstoeslagen te berekenen en daarmee deze berekeningen meer actueel te maken op basis van je situatie.

Voorbeeld Vlaanderen
Deze twee scenario’s worden al door de Vlaamse overheid ontwikkeld. In de volgende video worden deze toegelicht.

Meer toelichting bij onderstaande video vind je op de website van het Vlaams DataNutsbedrijf onder projecten.

Bron

Nederlandse ontwikkeling
Een soortgelijk concept in Nederland wordt voor een Nederlandse gemeentelijke use case ontwikkeld als eerste stap. Hierbij wordt de aanvraag van burgers voor een inkomenstoeslag gecheckt vanuit een SolidPod (datakluis) van een burger.

Hierdoor kun je gemakkelijker en veiliger de juiste gegevens delen. Ook wordt het mogelijk om automatisch te gaan checken of je in aanmerking komt voor regelingen, of dat deze niet meer van toepassing zijn omdat je bijvoorbeeld meer bent gaan verdienen.



Fictief voorbeeld Belastingdienst
Wanneer je bijvoorbeeld jouw vermogen of inkomen moet opgeven zou het mogelijk zijn dat vanuit de Belastingdienst een verifieerbare bewering kan worden uitgegeven over je vermogen of inkomen. Deze kun je vanuit je SolidPod (datakluis) vervolgens delen met andere organisaties die willen weten of je boven of onder een bepaalde inkomens vermogensgrens zit.
Zo kan er, én een betere dienstverlening ontstaan die ervoor zorgen dat de burger ondersteund wordt om gemakkelijk de juiste toeslagen te ontvangen, en wordt ook GDPR-compliant delen van data met ketenpartners mogelijk.

Bovenstaande gaat natuurlijk over digitale dienstverlening. Door dit aspect slimmer en efficiënter te organiseren ontstaat er ruimte om middelen en aandacht voor offline dienstverlening en menselijk contact in te zetten.



4. Rekenkracht onder jouw controle voor inzicht en ondersteuning
Een vierde ingrediënt van je digitale ondersteuningssysteem is rekenkracht.
Wanneer rekenkracht wordt toegevoegd aan de data over jou kun je allerlei extra inzichten op basis van jouw data genereren.
Bijvoorbeeld inzichten over je locatiedata, de input van je gezondheidsmetingen analyseren etc. 

Een concreet voorbeeld hierbij is dat momenteel wetgeving leesbaar wordt gemaakt voor machines. Als bijvoorbeeld de regels voor de eerder genoemde inkomenstoeslag openbaar toegankelijk zijn, kun je dus laten berekenen of je in aanmerking komt voor een toeslag, of bij een verandering van je situatie je juist wel of juist niet meer in aanmerking komt voor een toeslag.

Als rekenkracht onderdeel kan zijn van jouw digitale wereld, met de juiste regelgeving, hoeft geen derde partij met jouw gegevens en de uitkomsten aan de haal te gaan.



5. Data combineren terwijl je privacy gewaarborgd blijft
Een vijfde ingrediënt is samenwerken en data combineren met de digitale buitenwereld. 
Wanneer jij je data over jou meebrengt naar een service of applicatie, en je wilt bekijken hoe dit matcht met het aanbod van die service of applicatie, bijvoorbeeld in het geval van aanbevelingen dan ontstaat er interactie tussen twee soorten data: Data over jou en data van de service. 
Bijvoorbeeld: welke artikelen kan een service je aanbevelen op basis van je favoriete boeken en de artikelen die je afgelopen maand hebt gelezen. 
Wat die service vervolgens op basis van de uitkomst van die combinatie van beide datasets over jou kan weten, en hoe die data worden gebruikt is belangrijk om goed te reguleren.



Verder met de ingrediënten voor een samenhangende gebruikerservaring
Nu deze ingrediënten meer zijn toegelicht is de vraag:

Kunnen we een optimale gebruikerservaring ontwikkelen die jou ondersteunt in de digitale wereld.
Een gebruikerservaring die de voordelen van een datakluis en een WebId meeneemt, de veiligheidsaspecten die IRMA adresseert, met rekenkracht onder jouw controle, gebaseerd op open standaarden? 

Er ontstaan steeds meer voorbeelden dat dit mogelijk is. Om deze stapsgewijs te ontwikkelen tot een samenhangend geheel lijken in elk geval de volgende punten nodig om te komen tot een succesvol bereidingsproces:

de gebruikservaring van de mens in de digitale ruimte centraal stellen.

een onderzoeksfase bestaande uit proeftuinen waarin niet alleen naar de technische aspecten gekeken wordt, maar ook proeftuinen waarin de wettelijke kaders, governance en financiële modellen worden verkend.

De verschillende scenario’s en contexten onderzoeken waarin data delen voorkomt, en deze stapsgewijs ontwikkelen.
Er zijn namelijk allerlei scenario’s mogelijk waarin je meer of minder privacy wilt of kunt verkrijgen. Dit is vaak afhankelijk van de sector en specifieke dienstverlening, zoals bijvoorbeeld de gezondheidszorg, overheid, vrijetijdsbranche etc.
Het is daarom belangrijk de specifieke context mee te nemen: waar, welke functies nuttig, nodig en mogelijk zijn om te komen tot een optimale gebruikerservaring.



Stichting Solid Community
Wij zijn Stichting Solid Community.

We werken aan een gezonde digitale ruimte met een groeiende coalitie van partijen die een veilig, vriendelijk en innovatief web belangrijk vinden.

Werk je bij een organisatie en is er concrete interesse om aan de slag te gaan met projecten rondom veilig en verantwoord data delen, mogelijk in samenwerking met ketenpartners?
Neem dan contact op via: samenwerken@solidcommunity.nl

We werken doelgericht en stapsgewijs aan prototypes die breder in de maatschappij toegepast kunnen worden en zo als voorbeeld en inspiratie kunnen dienen om veilig en verantwoord data delen te realiseren en verder onder de aandacht te brengen.
<video src="https://user-images.githubusercontent.com/28604639/146938627-beb71c68-b6d6-4d9f-a7eb-2d23c5b95e14.mov" controls="controls" style="max-width: 730px;">
</video>
