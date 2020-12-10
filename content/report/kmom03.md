---
Title: Kmom03
Description: This is a page for Kmom03.
Template: kmom
---

# Kmom03

<h2>Hur har det gått att jobba med CSS-Grid/Flexbox?</h2>
Det gick bra, har använt flexbox sedan tidigare så det var inga konstigheter. Det var kul att lära sig CSS-grid dock, har inte vetat om att det funnits som alternativ. Flexbox blir mer endimensionellt att man antingen lägger in columns eller rows, medan grid känns mer tvådimensionellt i att man kan lägga ut hela matrisen på en gång. Jag lärde mig samtidigt lite mer om hur man lägger ut elementen enligt dessa två tekniker.

<h2>Har du jobbat med dessa tekniker sedan tidigare? Vad anser du om det?</h2>
Jag har arbetat med flexbox ganska mycket och jag tycker tekniken fungerar väldigt bra. Det är väldigt logiskt i hur man lägger ut element i vyerna, jag brukar också lägga på olika bakgrundsfärger på elementen så att man kan säkerställa att de renderas korrekt, att marginalerna stämmer osv. Det som är bra med flex är att vyernas storlekar blir dynamiska samtidigt som de är väldigt lätta att sätta med flex 1,2,3 etc, då man minskar webbsidans fönster så minskar även vyerna i takt med detta. Denna teknik plus att sätta en min width på element brukar fungera tillräckligt för att ge en professionell känsla.

<h2>Har du försökt dela upp din SASS-kod i olika moduler? Kanske har du skapat en ny modul som är din layout?</h2>
SASS koden är uppdelad i 3 filer, en som är style.scss som står för layouten för majoriteten av webbsidan, en report.scss som bestämmer layouten för report landing page, och en kmom.scss som bestämmer layouten och utseendet för kursmomentens detaljerade vyer. Kmom och report importeras i style.scss vilket är den fil som körs och genererar den aktiva css-filen vid scriptet npm run style.

<h2>Valde du att göra om din sidas layout eller nöjde du dig med report sidan?</h2>
Jag nöjde mig med att göra report sidan och sidorna för kursmomenten i detta kmom.

<h2>Vilken är din TIL för detta kmom?</h2>
Min TIL för detta kmom är att grid finns som alternativ till flex, samt de olika tillvägagångssätten för att lägga ut element på rätt plats inom griden (men faktiskt också inom flex, visste inte tidigare att justify-content: space-evenly kunde användas, jag brukar lägga divs med flex:1 där det behöver finnas ett mellanrum i kanterna men det skapar mer svårläst kod). Display: grid verkar ha stor flexibilitet i hur man lägger ut element och det är samtidigt lättförståeligt, bra teknik!
