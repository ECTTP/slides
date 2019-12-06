### Eindtoetsopdracht ECTTP

### Algemeen
Het spel dat je tot op heden gemaakt hebt bestaat uit enemies die van boven naar beneden bewegen (en links en rechts tegen de randen van het venster botsen en van richting veranderen) en een player die van links naar rechts beweegt.

De code van dit spel gaan we nu ombouwen tot een andere spelvorm;
- Het nieuwe spel bestaat uit cijfers van 1 tot 10 die aan de linker en de rechterkant van het scherm op en neer bewegen en tegen de onderkant en de bovenkant van het venster botsen en van richting veranderen.
- De player kan door heel het venster bewegen.
- De bedoeling van het spel is dat de player het laagste cijfer dat nog in beeld is te pakken krijgt. Dus de player moet eerst met de 1 botsen (die na de botsing verdwijnt), daarna met 2 botsen, etc.
- Botsen met een ander cijfer dan het laagste cijfer geeft een minpunt.

### Basic
- Zorg dat je player door heel het venster kan bewegen (je mag zelf kiezen of je de muis of toetsen gebruikt (1 punt)

- Zorg dat cijfers van 1 t/m 10 verticaal door het beeld gaan bewegen en tegen de boven en de onderkant van het venster bouncen. (2 punten)

- De cijfers moeten tegen de linkerkant van het venster of tegen de rechterkant van het venster op en neer bewegen. De keuze of een cijfer links of rechts in het venster op en neer beweegt is random (1,5 punten)

- zorg dat de collision-berekening tussen de player en de cijfer-enemies alleen uitgevoerd wordt als de player positie ver genoeg naar links of rechts in het venster is.
Je hoeft hier niet de feitelijke collision te berekenen, maar alleen te berekenen of de player ver genoeg naar links of rechts is om de collision-berekening uit te gaan voeren. Doe een prinln(“botsen maar…”) als de player een positie heeft om de collision te berekenen. De feitelijke collision komt bij de Advanced. (1 punt)

- Zorg dat snelheid van de cijfers en de player dusdanig is dat er een uitdagend spel (niet te makkelijk en niet te moeilijk) ontstaat (0,5 punt)

### Advanced
- Bereken de collision tussen de player en de cijfer-enemies. In dit stadium mag de player nog alle cijfers raken en maakt de volgorde nog niet uit. Bij een collision verdwijnt het cijfer dat geraakt is. (1,5 punten)

### Expert
- Zorg dat de player alleen de cijfers op volgorde mag raken. Een punt toevoegen bij raken van het juiste cijfer, een punt aftrekken voor het raken van een verkeerd cijfer.

### Structuur
- gebruik functies en classes op de juiste plekken (1 punt)
 

### INLEVEREN
Maak een zip van de map waarin je sketch en de overige files die nodig zijn om de sketch te laten werken zich bevinden. Zorg dat je voornaam, achternaam en ecttp_eindtoets in de naam van je sketch staan. Je opdracht kun je mailen naar je Lab docent (vincent.booman@hku.nl, ton.markus@hku.nl, valentijn.muijrers@hku.nl of aaron.oostdijk@hku.nl) en inleveren.gi@hku.nl. Mail je opdracht voordat je het lokaal verlaat.