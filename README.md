# Projektmall

Nyckelord: Filhantering, stränghantering, tid och datum

## Uppgiften

### Lydelse

Du ska skriva ett program som hanterar konton och inloggning. Programmet ska kunna:

- Skapa konton
- Logga in på konton och därefter byta lösenord

Programmet ska simulera inloggning enligt exemplet nedan.

![image](https://user-images.githubusercontent.com/101513815/224575617-1aea14db-fd1e-461b-bb76-13d37fd0f73c.png)

Lösenorden måste kodas med någon metod som du själv får uppfinna, du ska alltså göra en egen krypteringsalgoritm av något slag, som även ska gå att avkryptera. Dessa krypterade lösenord ska skrivas ner på fil med användarnamnet. Användaren ska även kunna ändra sitt lösenord genom att ange komandet "passwd". Det ska då fungera som nedan.

![image](https://user-images.githubusercontent.com/101513815/224575680-4b872db8-9460-4e2c-96b4-1c63f310513e.png)

Skriver användaren fel vid upprepningen av ett nytt lösenord ska ett felmeddelande skrivas ut och bytet av lösenord verkställs ej. Om lösenordet ändras ska det även ändras på den sparade filen.

### Krav för olika betyg

För bedömningen C så finner du kraven här ovan.

För bedömningen A behöver du lägga till följande:

Alla inloggningsförsök (både lyckade och misslyckade) samt lösenordsbyten (tidpunkt för bytet, om det lyckades eller misslyckades samt vilket konto det gällde) ska skrivas ner på fil i en log.

## Dokumentation & Planering

### Loggbok

Under arbetet förväntas du föra loggbok. Varje inlägg bör innehålla vad du gjort under passet och hur det gått. Skriv även gärna om du uppnått någon av milstolparna i projektplaneringen, använd gärna då ID:n för referens. Få gärna med eventuella problem du stött på och hur du löst dem (ifall du gjort det).

### Projektplan

Du påbörjar ditt projekt med att planera. Detta görs genom en projektplan med milstolpar och grindhål som ska uppnås under arbetets gång. Din projektplan bör revideras minst tre gånger under arbetet för att nå högsta bedömning. Projektplanen ska vara utförlig med detaljerade mål och uppgifter samt när deadline för dessa sker och vad som ska göras.

Projektplanen är det Google Sheet-arket som finns på classroom.

### Flödesschema

I första stadiet av projektet bör du även skissa upp ett flödesschema i förslagsvis draw.io som ska tillhöra ditt program. Tänk på vad de olika symbolerna betyder, samt att du inte har överflödiga punkter i schemat, eller att det är oläsbart.

## Författare

Niclas Lund

## Disclaimer

Uppgiften (eller inspiration till den) är ärligt stulen från EECS-skolan (gamla CSC) och kursen DD1314.
