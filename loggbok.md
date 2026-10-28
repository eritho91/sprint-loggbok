## Sprint vecka 2

### Vad jag arbetade med

Jag hade tidigare utvecklat vår Order Service under grupparbetet med mikrotjänsterna. Under den här sprinten arbetade jag vidare med att koppla ihop backend och frontend.

Jag lade till CORS-konfiguration och arbetade med backlog-item **FE-11**, där jag skapade en grundläggande lösning för att hämta produkter från backend och visa dem i React.

### Eventuella problem och hur jag löste dem

Det tog ett tag innan jag förstod hur en separat frontend kommunicerar med flera mikrotjänster. Framför allt hade jag problem med att få miljövariabler och localhost-adresser rätt.

Jag behövde också förstå vilka tjänster som måste vara igång för att applikationen ska fungera, särskilt eftersom vi använder JWT för autentisering.

Genom att arbeta med konfigurationerna och testa kommunikationen mellan tjänsterna lärde jag mig hur Auth Server hanterar inloggning, hur JWT används för att komma åt skyddade endpoints och hur Product Service skickar produktdata till frontend.

Jag fick även en bättre förståelse för hur CORS styr vilka ursprung som får läsa svar från backend.

### Samarbete och agilt arbete

Arbetet krävde att jag förstod hur de olika gruppmedlemmarnas mikrotjänster fungerade tillsammans. Genom att integrera frontend med backend kunde jag bidra till att webbshoppen började fungera som en sammanhängande applikation.

## Sprint vecka 1

### Vad jag arbetade med

Under sprinten arbetade vi med att sätta upp frontendprojektet med React, TypeScript och Node.js. Vi skapade ett gemensamt GitHub-repository och såg till att alla gruppmedlemmar kunde klona projektet via SSH och köra det lokalt.

Vi skapade även en grundläggande mappstruktur med `components`, `pages`, `service`, `types` och `test`. React Router installerades för att kunna hantera flera sidor i applikationen utan att behöva ladda om hela sidan.

Vi konfigurerade också GitHub Actions för att automatiskt bygga och testa projektet. Vi fick workflowet att köras utan fel och satte upp rulesets så att pull requests behöver granskas och godkännas innan de kan mergas till main.

### Eventuella problem och hur jag löste dem

Det viktigaste under den här sprinten var att förstå hur frontendprojektet skulle sättas upp och hur de olika verktygen hänger ihop. Jag fick en bättre förståelse för hur Node.js används för att köra utvecklingsverktyg och hur GitHub Actions automatiserar bygg- och testprocessen.

### Samarbete och agilt arbete

Vi arbetade gemensamt med att skapa projektets grundstruktur och få en fungerande utvecklingsmiljö för hela gruppen. Resultatet blev att alla kunde arbeta lokalt mot samma repository.
