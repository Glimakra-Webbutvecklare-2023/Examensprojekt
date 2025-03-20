# Examensprojekt

Examensprojektet är den avslutande modulen på kursen Webbutvecklare. Projektets omfattning är ca 8 veckor (vecka 14-22). Studerande på kursen Webbutvecklare kan påbörja arbetet med projektet innan modulen startar.

Handledning av ditt arbete med examensprojektet sker inom modulens tidsramar.

Syftet med examensprojektet är att du på egen hand ska få möjligheten att fokusera på ett område inom webbprogrammering som du vill fördjupa dig inom. Du arbetar med ditt examensprojekt på heltid, och under eget ansvar. Det är viktigt att du väljer ett ämne som du tycker är intressant.

### Vad kan examensprojektet handla om?

Vårt tips är att du använder programspråk som du lärt dig under kursen. Det kan vara en ny webbapplikation som du utvecklar från grunden, eventuellt en webbapplikation där du utgår från delar av ett arbete som du tidigare programmerat under kursen. 

Väljer du det sista alternativet ska en större del av koden skapas under avslutande projektperioden. Det måste finnas ny funktionalitet i ett projekt som baseras på kod du arbetat med tidigare.

Ditt examensprojekt kommer vara möjligt att arbeta med om vi lärare ser att någon av oss kommer kunna handleda dig. Väljer du nya programspråk eller ramverk som vi inte behandlat under kursen kan ditt förslag nekas.

#### Exempel på examensprojekt

Ett exempel på examensprojekt kan vara att hjälpa ett företag eller kund med en applikation. Applikationen ska vara lagom utmanande och omfatta färdigheter som du har lärt dig under kursen. Applikationen kan baseras på ett CMS (som ex Wordpress) förutsatt att du utvecklar funktionalitet som du själv kodar.  

Andra förslag för projekt som kan passa: 

- Socialt nätverk: Skapa en social nätverksplattform där användare kan registrera sig, skapa profiler, posta inlägg, kommentera och gilla inlägg från andra användare.

- Bloggplattform: Skapa en bloggplattform där användare kan skapa egna bloggar, publicerar inlägg och länka till andra bloggar.

- Onlinekursplattform: Skapa en plattform där användare kan registrera sig, ta kurser och få certifieringar. Plattformen skulle också kunna innehålla funktioner som att visa kursmaterial, ställa frågor till lärare och interagera med andra elever.

- E-butik: Skapa en applikation där användare kan köpa produkter. Webbplatsen skulle innehålla en katalog över produkter, produktbeskrivningar, en varukorg och en check-out-process.

- Realtidsapplikation: Skapa en websocket baserad applikation, med backend och frontend. Gör det möjligt för en administratör att skapa innehåll i applikationen, hantera ett resultat som baseras på applikationens funktionalitet. 

### Handledare

Handledning kommer att finnas under tiden som du arbetar med examensprojektet. Du kommer att få en huvudsaklig handledare, men givetvis med möjlighet att samråda med andra lärare på kursen.

### Loggbok

Under arbetet med examensprojketet ska ni skriva en loggbok där ni kort beskriver ert arbete **varje vecka**

Exempel på hur loggboken kan se ut initiellt är

```md
# Loggbok

## Vecka 14
Presenterat projektet för handledare och skapat en första kravspecifikation

- Figmalänk:
- Gitrepo till projekt:

## Vecka 15
...

```


### Redovisning vid halvtid 

*preliminärt datum*

När du arbetat med examensprojektet i ca 4 veckor redovisar du ditt projekt i form av ett pågående arbete. Här du delar du med dig av utmaningar och kan få feedback. Visa skisser, din applikation och ditt Git repo.  

- Tisdag 29 april 

### Slutlig redovisning

*preliminära datum*

- Måndag 26 maj 10:30 
- Onsdag 28 maj 10:30

Redovisningen av projektet förväntas innehålla

- ett versionshanterat Git repo
- en inspelad video (5-7 minuter) där applikationens funktionalitet demonstreras
- en presentation av designskisser
- en kort redogörelse för val av språk och eventuella ramverk
- en länk till fungerande applikation på publik webbserver
- en loggbok med veckovisa (*minst*) uppdateringar av vad som har arbetats på och eventuella utmaningar


Ditt examensprojektet kommer att framgå av slutgiltigt kursintyg.

---

### Att göra innan perioden startar - beskriv ditt förslag till examensarbete 

**Vi vill att din beskrivning av projektet ska finnas tillgänlig i ett git repo senast 28 mars**. 

Skapa ett Git repo för projektarbetet. 

I README.md anger du följande rubriker:
- Översiktlig beskrivning: I korthet vad ska applikationen göra?
- Tekniker och programspråk: Punktform vilka programspråk och applikationer ska användas
- Samarbeten: Om ni ska göra detta i grupp eller tillsammans med ett företag skriv det här och hur ni har tänkt samarbeta
- Kravspecifikation: I punktform skriv ner funktionalitet som ska finnas implementerad inom projektets tidsram (den här punkten kan behöva preciseras mer när projektet startats upp i samråd med lärare)

---

#### Exempel på kravspecifikation - här för en tänkt Bloggplattform

**Vi vill att en kravspecifikation utformas (godkänd av handledare) under första veckan - vecka 14**. 

En kravspecifikation är ngt du ska ha som mål att arbeta med under projektet. Det innebär att du kanske inte hinner med alla punkter. Det kan oxå innebära att du omprioriterar vissa punkter.*      

Applikationen ska
- [x] lagra data i en databas
- [x] använda tabeller som relateras till varandra: user, blogg, comment
- [x] hantera 2 användarroller: admin, user
- [x] hantera vy för mobil och skärm
- [x] hantera sessioner 
- [x] finnas publicerad på en publik webbplats

En användare (user) ska kunna: 
- [x] registrera sig / logga in / logga ut
- [x] redigera inloggningsuppgifter
- [x] skapa och tagga blogginlägg
- [x] ladda upp bild till blogginlägg
- [x] redigera blogginlägg
- [x] ta bort blogginlägg
- [x] gilla andra användares blogginlägg
- [x] kommentera andra användares blogginlägg

En besökare (utan inloggning)
- [x] ska kunna läsa publika blogginlägg 

En administratör (admin) ska kunna
- [x] redigera användares roller
- [x] skapa, redigera taggar för blogginlägg
- [x] radera användare


Andra delar som kan ingå i en kravspecifikation kan ex vara
- hantera cookies
- visa användare online
- ta bort / avpublicera blogginlägg
- få länk med inloggningsuppgifter om lösenordet är fel
- applikationen ska kunna installeras genom att följa en guide

---

**Bjud in oss lärare till ditt repo för examensprojektet senast fredagen den 28:e mars i vecka 13**

*andsju, addkolon, frozenbanana*

---
