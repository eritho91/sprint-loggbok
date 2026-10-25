# sprint-loggbok

## Sprint 1 - v. 38

### Vad jag arbetade med:
Jag gjorde order service när vi gjorde grupparbetet med mikrotjänsterna. Jag lade senare till CORS-konfiguration och fick det att fungera tillsammans med frontend, där jag gjorde FE-11, en grundläggande setup för att hämta produkterna från backend och visa dem i frontend.

Det tog ett tag innan jag förstod hur det här konceptet fungerade, alltså att man använder sig av en separat frontend-tjänst. Mer specifikt tog det tid innan jag fick alla miljövariablerna på rätt plats i rätt service, speciellt localhost-adresserna. Det svåraste här tyckte jag var att förstå vilka services som måste vara igång och varför, speciellt samtidigt som JWT-token är implementerat, men har nu lärt mig att: 
- Auth-server måste vara igång för att man ska kunna logga in.
- Product-service måste ha JWT-token från auth-server för att frontend ska ha tillstånd att visa produkterna.
- Det är väldigt viktigt att rätt localhost-adresser finns på rätt ställen.
- Frontend får tillstånd att hämta data med mikrotjänsternas CORS-konfigurationer. 

## Sprint 2 - v. 39
Den här veckan var jag scrum master, det var svårt att hålla reda på alla termer som har med agilt arbetssätt att göra men jag fokuserade på att leda gruppen och lära mig allt eftersom och förstår nu mycket mer om hur ett utvecklarteam jobbar effektivt. Vi valde fyra punkter från backloggen att klara av för den här veckans sprint, och vi hann med alla samt ett par fler uppgifter. Vad vi kunde gjort bättre var mer effektiv delegation av arbete; efter att de första målen var uppnådda så blev arbetet en aning splittrat, men vi lärde oss av det.
