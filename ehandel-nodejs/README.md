# Inlämningsuppgift 1

## Instruktioner

I denna inlämningsuppgift ska du bygga en Node.JS-applikation för en e-handelssida. Du ska skapa upp ett API samt en databas med lowdb som ska hantera din e-handelssida. Denna inlämningsuppgift ska **dock inte** ha någon HTML, CSS eller JavaScript (i klienten). Utan det kommer i nästa inlämningsuppgift där du ska använda dig av ditt API från denna uppgift.

**Krav på funktionalitet**
* Endpoint:s för följande:
    * Hämta alla produkter (sedan nedan på vad en produkt ska innehålla).
    * Kunna lägga till produkter i en varukorg.
    * Kunna ta bort produkter i varukorgen.
    * Hämta varukorgen med alla tillagda produkter.
* Man ska inte kunna lägga till samma produkt i varukorgen igen.
* Man ska få ett felmeddelande om man försöker lägga till en produkt som inte finns.
* Man ska få ett felmeddelande om man försöker ta bort en produkt som inte finns.

**En produkt ska innehålla följande:**
* Namn
* Pris
* En bild-url (Använd exempelvis denna sida för att generera bild-url:er https://placeimg.com/)

**För Godkänt krävs:**
* Att du uppfyller alla krav på funktionalitet.
* Innehåller en package.json med alla dependencies som behövs för att köra projektet.
* Genomtänkta namn på variabler, funktioner etc.
* En genomtänkt namnsättning på dina endpoints avseende ditt API.
* Att du använder GET, POST etc vid rätt tillfälle (eller kan argumentera för ditt val).

**För Väl Godkänt krävs:**
* Allt i Godkänt.


* Att din kod är indelad i moduler (finns inget krav på antal).
* Att du har gjort en code review på en annan klasskamrats kod. Du ska i din inlämning bifoga ett dokument med namnet på personen du har gjort
din code review på och tre saker som du tycker är bra samt en sak som kan förbättras.

Inlämning sker via Github och Learnpoint. Ladda upp ditt projekt på Github inklusive din databas (d.v.s din JSON-fil). Gå sedan in på Learnpoint och under innehåll finns det en inlämningsuppgift där du ska posta din länk till ditt repo. Bifoga även med ditt dokument gällande code review om du satsar på Väl Godkänt.

**Inlämning senast**: 22/4 23:59 


**DONN'T forget:**
* cd folder !
* -> npm run watch ....(using nodemon) /OR
* -> node BASIC-server.js
* -> use Postman as client-side...
