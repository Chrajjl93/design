---
Title: Kmom02
Description: This is a page for Kmom02.
---


Kmom02
=======================

<h4>Vad tycker du om SASS än så länge?</h4>
Det verkar vara ett användbart verktyg, jag gillar tanken om att skapa variabler som direkt går in och ändrar värden på style-referenser i en 'gemensam' css-fil men att stylingen ändå blir dynamisk pga att man gör detta för varje fil man vill designa unikt. När man inte har stora CSS filer så känns det svårare att se det direkta värdet med SASS (SASS ska tydligen motverka komplexitet i stora CSS filer) men jag tror att i.o.m. att man kan skapa CSS filer mer dynamiskt med mer inbyggd funktionalitet, så underlättar detta mycket vid ett senare tillfälle.

<h4>Är du bekant med Node, npm eller npm scripts (t.ex. npm run lint) sedan tidigare? Vad anser du om det?</h4>
Jag är bekant med Node och npm sedan tidigare till viss mån, jag har inte riktigt förstått vad Node.js egentligen är och vad dennas generella syfte är, men har vetat hur man använder npm för att installera paket i tidigare projekt. Jag har arbetat på applikationer för mobil med React-Native samt webbapplikationer med React, och har då använt npm för att utnyttja bibliotek som andra användare skapat. Jag tycker detta är genialiskt då man ofta slipper spendera en vecka på att bygga en komplex komponent som någon annan redan gjort, och värdet för personen som byggt en komponent som andra använder är också stor - det kan användas i arbetet för att lyfta upp din kompetens. Jag brukar främst utgå från bibliotek som har kontinuerligt underhåll samt har laddats ner ett par tiotusen gånger.

<h4>Hur kändes det att kompilera SASS till CSS, var det något du reflekterade över?</h4>
Det fungerade rätt smidigt. Jag tänkte på att det ingår en automatisk kontroll av din CSS när SASS kompilerar till CSS. 'Dålig' CSS brukar inte lyftas upp av webbläsaren och jag visste inte ens (innan förra kursen) att det fanns dålig CSS, men när vi började validera mot dbwebb eller köra CSS validatorn så fick man ganska många anmärkningar. SASS ser ju nu till att CSS alltid är clean.

<h4>Kommentera ditt tema, hur kan man beskriva dess design och hade du några planer på “design” när du byggde ditt tema?
</h4>
Jag gillar mer stilren design och uppskattar webbsidor som arbetar för att deras UX & UI ska kännas lättanvänt och att designen känns fin och avskalad. Just den färgkombinationen som jag använt för header & footer i kontrast med textfärgen tycker jag ser bra ut, jag la till några ikoner för meny-valen för att det (enligt min mening) är roligare. Jag är inte nöjd med flash-region och image, jag brukar inte ha någonting sådant när jag själv designar men det är en artefakt från förra uppgiften eftersom det är obligatoriskt (?). Den är i alla fall responsiv mot fönstrets storlek och med object-fit: cover så har den en zoomande effekt vilket jag tycker ser bra ut. Textens storlek och 'tyngd' är rimlig, menyval och text som ska kunna klickas på är tjockare för att indikera sådan funktionalitet, text som bara är läsbar är smalare.

<h4>Valde du att dela upp din kod? Vilka uppdelningar valde du att göra?</h4>
Jag delade först upp koden i ett test-tema för att se till så att koden fungerade innan jag flyttade över den till temat 'Christian'. Jag har fortfarande styling för navigation bar separat från övrig layout, jag har även 3 separata filer i mappen 'shared': base, layout, variables. Jag valde att använda den uppdelningen som vi gick igenom på övningen då det är smidigt att ha variabler för sig och sedan styling för layout för sig. När filerna blir större tänker jag att denna uppdelning blir ännu viktigare. Att man importerar dessa i 'base' och sedan bara importerar 'base' som styling-fil är smart!

<h4>Vilken är din TIL för detta kmom?</h4>
Min TIL är allt vi lärt oss om SASS egentligen, jag hade inte använt det tidigare. Men denna gång har jag lärt mig om hur jag kan använda den tekniken för att skapa återanvändbara designteman, hur man kan bygga ut CSS funktionalitet med SASS genom att nesta funktioner och t.ex. skapa variabler. 
