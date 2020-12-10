---
Title: Load
Description: This is a analysis page.
Template: index
---

# Load

Syftet med denna analys är att undersöka 3 olika webbplatsers laddningstid, antalet resurser de laddar in samt hur mycket data som laddas. Detta för att analysera vilka förbättringsmöjligheter de olika webbplatserna kan implementera för att optimera laddningstiden samt för att skapa förståelse för hur de presterar i jämförelse till varandra.

## Urval

Youtube.com: En webbplats med mycket innehåll i video- och bildformat som även kräver väldigt stor användarvänlighet i att innehållet laddas snabbt. Valet grundar sig i att se hur en webbplats med dessa höga krav presterar baserat på laddningstid.

Aftonbladet.se: Även denna webbplats bygger på en stor volym av innehåll, i detta fall artiklar. Det är viktigt att de laddas snabbt för att skapa bra användarupplevelse, men de är inte lika fokuserade kring video-format, utan istället bilder och text.

Vasamuseet.se: Denna webbplats har inte lika höga krav på att innehållet är optimerat för att ladda snabbt, varför denna webbplats är vald då en jämförelse kan göras med de två tidigare valen.

## Metod

Metoden för denna analys beskrivs enligt följande. Googles verktyg, PageSpeed Insights användes för att sätta ett jämförelsebart värde på webbplatsernas laddningshastighet, både för desktop och för mobila enheter. Dessutom användes detta verktyg för att analysera vilka förbättringsåtgärder respektive webbplats kan implementera för att optimera sin laddningstid. Därefter användes Google Chromes inbyggda verktyg för utvecklare för att bedöma antalet resurser som användes av respektive webbplats, hur lång totala laddningstiden var samt hur mycket data som laddades. På varje webbplats analyserades 3 olika sidor enligt tidigare beskriven metodik, och resultatet presenterades med hjälp av Googles kalkylark.

## Resultat

<h3>Youtube:</h3>

<h4>1. Snapshots</h4>
![youtube_01](%assets_url%/img/youtube_01.png)

<h4>2. Länk till resultat i excelark</h4>
<a href="https://docs.google.com/spreadsheets/d/1FvCTE1ZBWKvU2G4NWAIZ7Vwx65XaawEJ1uFYR8HJ8ak/edit?usp=sharing">Länk till resultat</a>

<h4>3. Förbättringsmöjligheter</h4>
Större tidsbesparingar kan göras genom att ladda in viktiga resurser i förväg, ta bort JavaScript som inte används och genom att skicka bilder i mordernare bildformat.

<h3>Aftonbladet:</h3>
<h4>1. Snapshots</h4>
![aftonbladet_02](%assets_url%/img/aftonbladet_02.png)

<h4>2. Länk till resultat i excelark</h4>
<a href="https://docs.google.com/spreadsheets/d/1FvCTE1ZBWKvU2G4NWAIZ7Vwx65XaawEJ1uFYR8HJ8ak/edit?usp=sharing">Länk till resultat</a>

<h4>3. Förbättringsmöjligheter</h4>
Större tidsbesparingar kan göras genom att ta bort JavaScript som inte används, ta bort resurser som blockerar renderingen och genom att ta bort oanvänd CSS.

<h3>Vasamuseet:</h3>
<h4>1. Snapshots</h4>
![vasamuseet_01](%assets_url%/img/vasamuseet_01.png)

<h4>2. Länk till resultat i excelark</h4>
<a href="https://docs.google.com/spreadsheets/d/1FvCTE1ZBWKvU2G4NWAIZ7Vwx65XaawEJ1uFYR8HJ8ak/edit?usp=sharing">Länk till resultat</a>

<h4>3. Förbättringsmöjligheter</h4>
Större tidsbesparingar kan göras genom att ta bort resurser som blockerar renderingen, ta bort JavaScript som inte används, läsa in viktiga resurser i förväg och skicka bilder i modernare bildformat.

## Analys

Resultatet av studien är intressant. Man kan tänka sig att en webbplats som Youtube som beror väldigt mycket av video- och bildrelaterat innehåll och där användarupplevelsen är oerhört viktig (då själva webbplatsen är produkten) bör prestera mycket bra i mätningarna av laddningshastighet, speciellt när Google själva äger Youtube. Ett förväntat resultat var därför att Youtube skulle prestera bäst i mätningarna. Efter att resultaten samlats in är det dock uppenbart att så inte är fallet och anledningen till det är att jämförelsen mellan dessa webbsidor inte är rättvis då deras syfte skiljer sig åt. En webbsida för vasamuseet är relativt lättviktig då värdeerbjudandet mot kund inte direkt är webbsidan utan att besöka museet i sig, därav har de inte den massiva volym innehåll att hantera för användare. En rimligare mätning vore att jämföra Youtube med liknande webbsidor som erbjuder liknande värderbjudande för att se hur de presterar i relation till varandra. Youtube verkar å andra sidan ligga på ungefär samma nivå som resterande webbplatser på mobil-prestandan. Antalet resurser som Youtube laddar är dessutom förre än vad övriga webbsidor laddar i medel, men dessa är i regel tyngre än resurserna som övriga webbplatser laddar.

Aftonbladet har aningen bättre laddningstider men presterar inte speciellt bra med sin mobil-prestanda. De har ett stort antal resurser att ladda (förmodligen rätt mycket reklam) men resurserna väger i regel mindre. Vilket kan vara en av anledningarna till att prestandan för desktop är betydligt bättre än Youtubes.

De vanligaste förbättringsåtgärderna som verkar finnas för de analyserade webbsidorna är att 1) Ta bort JavaScript som inte används, 2) Ta bort resurser som blockerar renderingen, 3) Läsa in viktiga resurser i förväg och 4) att skicka bilder i modernare bildformat.

<h3>Rangordning av webbplatser</h3>
* 1 - Vasamuseet
* 2 - Aftonbladet
* 3 - Youtube

Vinnaren i mätningen (baserat på PageSpeed Insights) är Vasamuseet. Mätningen är som tidigare diskuterat inte representativ för att förstå om Vasamuseet har en mer optimerad snabbhet än en webbplats som Youtube. Syftet med webbplatserna skiljer sig åt och innehållet skiljer sig åt vilket påverkar resultatet nämnvärt.

<h3>Gräns för absolut laddningstid</h3>
En gräns för vad jag själv upplever som en tillräckligt snabb webbsida ligger mellan 2.5-3.5 sekunders laddningstid eller snabbare. Endast Vasamuseets webbplats ligger inom detta intervall i total laddningstid. Aftonbladets webbplats laddar dock snabbt in det viktigaste innehållet, själva artiklarna, medan mindre viktiga element laddas in betydligt långsammare.

## Övrigt

Christian Kälvegren
