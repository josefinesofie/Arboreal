# Arboreal
Inlämning HTML/CSS

Vi fick i uppgift att bygga en hemsida baserad på förbestämt innehåll.

"Startup-företaget Arboreal behöver en ny hemsida för sin affärsidé. Ni har fått i uppdrag att skapa denna sida.""

"Arboreal är en prenumerationstjänst för företag. Tjänsten innebär att man får sitt kontor inrett med växter med hjälp av experter från Arboreal. Sedan betalar man en månadskostnad för att få nya växter levererade och placerade på kontoret varje månad eller vecka beroende på vilken prisplan man har valt. Arboreal har sin kundgrupp bland små till medelstora IT-företag i stockholmsområdet."

Innan jag skickade vidare hade jag tre fel i validatorn som sa "Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.", jag valde att bortse från detta då jag inte fick det att fungera på något snyggt sätt.

FEEDBACK
Den feedback jag fick av Jonas:

HTML
-Felen som uppstår i validatorn tror jag går att ändra om du byter ut de sektioner på rad 50, 57 och 64 till divar, eftersom det endast är till för styling syfte.
-Formuläret går inte att fylla i(iaf på min dator).

CSS
-Tycker du hade hittat fina bilder till elementen, dock blir din background-image i headern lite skev. Längst till höger slutar bilden och börjar igen.
-Gränssnittet är stilrent och tydligt på de flesta ställen, kanske lite otydligt i footern på informationen. Jag tycker texten smälter in lite för mycket i bakgrunden. Kan tänka mig att folk som har svårt att se skulle ha svårt att läsa informationen.
-Bakgrunden tycker jag är snygg i sig men hade varit intressant att se om man piffade till den med lite färg. Kanske med nåt som matchar bilderna.

----||----

Ändringar:
Headerbilden vet jag inte hur jag ska fixa eftersom den ser bra ut på min skärm och jag antar att det är så lång som bilden är. Jag vill helst inte behöva byta bild, återkommer till detta.
Bakgrundsbild vet du Jesper att jag har haft problem att lägga in. Den kom fram först när man hovrade, hittade inte någon lösning. Nu när man lägger in en bakgrundsbild så finns det inget fören man hovrar och sedan scrollar upp så långt att man "går utanför bodyn". Så väljer att ha vit bakgrund.
Ändrade mina sections på rad 50, 57 och 64 till divar och nu är det inga problem i validatorn.
Jag la till en bakgrundsfärg på kontaktinformationen så den syns bättre.
Jag ändrade färgen på input till svart vilket jag missat innan, den var vit när Jonas försökte skriva.

----||----

Responsivitet:
Jag har valt brytpunkten 960px för tablet även om den inte är så bred eftersom att elementen i themes flyttade sig utanför diven. Sedan ändrade jag padding på några och flyttade in kontaktinformationen till sin mitt.

Till mobil satte jag brytpunkt 380px eftersom det är fem pixlar över en vanlig iphone6 vilket bör vara en okej marginal. 
Jag förminskade loggan, minskade textstorlek på slogan och förlängde headern en bit så det får plats. Jag la även offers övanpå varandra och ändrade höjd på diven themes. Jag la in padding där det krävdes och la kontaktinformationen ovanpå formuläret.

Jag har tittat på vilket responsive pattern jag efterliknat och det skulle kunna vara "Responsive UI Examples" eftersom det exemplet har flera divar bredvid varandra och på höjden som sen lägger sig ovanpå varandra eftersom man förminskar skärmen.
"3 equal-width columns" är också likt på samma sätt att divarna lägger sig på varandra eftersom.
Jag har också kört css:en grenom autoprefixer men inga övriga ändringar efter det.




