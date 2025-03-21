# agile-method-examination
## Länk till Kanban Commandos grupprepo
https://github.com/Welene/kanban-commandos

## Individuella reflektioner
## Frågor
### Inledning
#### Vad var ditt mål med projektet initialt?
Att få en förståelse för hur agil metod fungerar samt se vilka möjligheter man har att påverka tidigt hur strukturen ska se ut när det är ett nytt team som ska samverka med varandra. Målet var att skapa bra förutsättningar för att undvika att det blir två veckor av hell med konflikter gällande t ex git, planering, buggar pga misskommunikation etc.
Vad var din känsla inför att arbeta i ett team när du gick in i uppgiften?
Att mina övriga kollegor är engagerade och hade samma mål om att göra vårt bästa. Sedan kändes uppgiften som att det var många moment som vi behövde gå igenom och att vi inte hade så mycket tid på oss då gruppen hade ambitioner att leverera en produkt med alla krav utförda.

### Planering och genomförande
#### Hur tycker du att planeringen inför projektet fungerade?
Den fungerade väldig väl då vi la 1,5 dag på planeringen. Vi gick igenom så att alla förstod hur git fungerade med brancher och hur man mergade dev till sin pågående branch. Vi skrev även innehållet och riktlinjer till varje user story samt placerade i figma för att lättare se vilka userstorys som tillhörde till olika sidor.

#### Vad har du bidragit med i planeringen, samt utvecklandet av applikationen.
Initialt tänkte jag mycket på vad Jesper hade berättat om vilka misstag många andra grupper hade gjort och att han hade betonat kommunikation som en vital del i projektet. Därför tog jag upp detta tidigt gällande hur vi skulle göra för att underlätta kommunikation. Våra åtgärder var en tydlig struktur i discord med olika kanaler för olika ändamål (#länkar, #ny pullrequest, #ny dev, #kod etc…)

Vidare bidrog jag med kontinuerligt att kolla av nya dev med eventuella buggar på andras uppladdade koder och rapporterade vidare i kanalen #bugg- eller förbättringar.
Beskriv med dina egna ord, er applikation
Vår applikation förenklar för kunder att kunna beställa mat via företaget Yum yum gimme sum som har foodtrucks placerade på olika ställen i Karlstad. Genom en tydlig överblick med mat/dryck så går det enkelt att göra en beställning och sedan får användaren information om när maten är redo att hämtas samt kan se orderhistorik. För admin kan man även se orderhistorik för samtliga foodtrucks och även kunna redigera menyn med mat/dryck.

### Teamets utmaningar och lösningar
#### Vilka var de största utmaningarna för dig?
Att kunna läsa och förstå andras koder samt att kunna återanvända någon annans kod. Dessutom var det en utmaning att när man själv skriver koden för sin egen branch att tänka om denna skulle kunna vara applicerbar hos någon annan och därför skriva den mer skalbar.

#### Hur löste eller hanterade du dessa utmaningar?
Kommunikation genom våra daily scrums där vi fick reda mer på vad alla hade gjort men också planerat att göra under dagen. Då vi hade gjort en bra och grundlig planering så var det lättare att kommunicera med en annan utvecklare om jag visste att vi hade några liknande funktioner och därmed ha ett videosamtal och prata om hur vi skulle kunna skriva några kodrader tillsammans.

#### Vilka kompromisser inom teamet har du fått göra under projektets gång?
Inga större kompromisser men det var vissa designval som vi behövde enas om då vi inte hade tid för att göra klart figmaskissen i detalj under planeringsstadiet. Detta gjorde att när det fanns vissa moment i designen som skulle se likadana ut på vissa sidor behövde jag kompromissa utifrån min första design, men inget som jag ansåg vara av vikt för att ha större diskussioner om.
### Individuell reflektion och utvärdering
#### Vad lärde du dig under projektets gång?
Att lägga tid på planeringen är otroligt viktigt för att ett samarbete ska flyta på bra och att agila metoder underlättar då det finns en tydlig struktur med olika saker som behöver diskuteras och alla accepterar dessa då vi utgår från metoden.
Finns det någonting du skulle velat göra annorlunda om du fick chansen igen?
Att vi fick mer tid för planeringen och prata mer om vilka funktioner som vi skulle kunna upprätta i början som underlättar sedan när vi programmerar samt prata om hur eventuell localStorage skulle kunna se ut för att underlätta när vi programmerar på olika sidor men använder oss av samma localStorage.

#### Vilka möjligheter ser du med de kunskaper du fått under arbetet med projektet?
Projektet har gett mig otrolig mycket erfarenheter på hur ett bra samarbete kan se ut och vilka viktiga delar som gjorde att det fungerade så pass bra. En kombination av engagemang, tydlig planering, tydlig struktur i discord och hur man kommunicerar och löser problem tillsammans genom t ex videosamtal istället för att skriva tar jag med mig inför framtida projekt.

## VG-frågor (minst 200 tecken)
#### Beskriv minst tre fördelar med att arbeta agilt och motivera varför de är viktiga. Använd exempel från ert projekt för att styrka dina argument.
1.	Det finns en tydlig struktur med tillvägagångssättet och att det är en metod som många använder sig av vilket gör att det är lätt för nya medlemmar att komma in snabbt i teamet.
2.	Finns klara frågor vid t ex daily scrum, sprint review/retrospective osv så att man måste diskutera saker och delge information så att alla i teamet håller sig uppdaterade.
3.	En bra överblick med vad man gjort och vad som finns att göra genom t ex att använda sig av Kanban och projekt genom backlog, sprintlog, in process, done.

#### Beskriv en konkret lösning du föreslagit under projektet. Varför ansåg du att den var bäst? Jämför med minst en annan möjlig lösning och förklara varför du inte valde den.
Jag programmerade koden för hamburgarmenynknappen där jag använde mig av buttonelement och javascript/css för att göra animering medan en annan i vår grupp hade hand om navmenyn när man tryckt på hamburgarmenyknappen men han hade gjort det med checkbox. Jag argumenterade för att det var för att Jesper inte hade lärt oss JavaScript och använde en annan metod för att göra den interaktion men nu är vi kunde JS så behövde vi inte använda oss av den metoden och därför behöll vi min lösning då min andra teammedlem förstod detta i efterhand.

#### Ge minst två exempel på lösningar ni valde bort. Analysera varför ni avstod från dem. Hur påverkade det projektet? Kunde något ha gjorts annorlunda?
Vi hade en lösning om att man skulle kunna se menyn utan att logga in men då behövde vi ta hänsyn till detta i all kod som vi redan hade gjort och då vi endast hade en vecka på oss så valde vi att ha kvar att man måste logga in för att kunna se menyn. Hade vi pratat om detta initialt så hade vi kunnat förhålla oss till detta när vi började skriva koden för applikationen.

En annan lösning vi valde bort var att göra kartbilden interaktivt så att man kunde se genom t ex google api men vi upptäckte att det kunde innebära problem med tokens samt svårigheter att lägga upp exakta locations på vart foodtruckens skulle vara. Vi tog beslutet att inte lägga större vikt vid detta då det inte var efterfrågat just denna funktion mer att man kunde se vart foodtruckens skulle vara placerade men det hade varit snyggt om vi hade fått till det mer interaktivt beroende på vart man var och kunde se närmaste foodtruck.

#### Reflektera kring hur den kod du bidragit med skulle kunna förbättras, ge konkreta exempel.
Använda mig av ternära operatorer som t ex vid if-satser så att koden blir färre rader men ändå läsbar. Ett exempel är:
```javascript
if (action === 'incrament') {
        // Adderar en till item till nuvarande siffra
        basketItemCounts++;
    } else if (action === 'decrament') {
        // Adderar en till item till nuvarande siffra
        basketItemCounts--;
    }
```
Och istället skriva: 
```javascript
basketItemCounts += action === 'incrament' ? 1 : action === 'decrament' ? -1 : 0;
```
#### Om ni hade en vecka till på er, vad skulle du ändrat? Fokusera på arbetsprocessen, samarbetet eller verktygen ni använde. Hur skulle det ha påverkat resultatet?
Då vi hann klart med alla ursprungliga user stories från PO i första sprinten så fick vi fler förslag på features som vi i andra sprinten blev klara med. Det enda vi inte hann klart var att göra denna till en desktopversion. Om vi hade haft mer tid så hade vi först och främst fokuserat på att göra klart figmaskissen för se hur det skulle kunna se ut för att senare kunna dela upp det i fler beståndsdelar med user stories.
