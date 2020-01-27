### Eindtoetsopdracht ECTTP

### Algemeen
Het spel dat je tot op heden gemaakt hebt bestaat uit enemies die van boven naar beneden bewegen (en links en rechts tegen de randen van het venster botsen en van richting veranderen) en een player die van links naar rechts beweegt.

De code van dit spel gaan we nu ombouwen tot een andere spelvorm;
- Het nieuwe spel bestaat uit 10 vierkantje blokjes die diagonaal door het venster bewegen en tegen de onder-, boven-, linker- en rechterkant van het venster botsen en van richting veranderen.

- de blokjes vormen qua grootte en reeks. De kleinste is 5x5 pixels, de op één na kleinste is 10x10 pixels, de op twee na kleinste is 15x15 pixels etc, tot het grootste blokje dat 50x50 pixels is.

- De player kan alleen verticaal bewegen en bevindt zich horizontaal midden in het venster.

- De bedoeling van het spel is dat de player het kleinste blokje dat nog in beeld is te pakken krijgt. Dus de player moet eerst met de kleinste (5x5 px) botsen (die na de botsing verdwijnt), daarna met de op 1 na kleinste (10x10px) botsen, etc.

- Botsen met een ander blokje dan het nog kleinst zichtbare blokje geeft een minpunt.

### Basic
- Zorg dat je player alleen vertikaal door het venster kan bewegen, horizontaal in het midden van het venster (je mag zelf kiezen of je de muis of toetsen gebruikt (1 punt)

- Zorg dat een reeks van 10 vierkante blokjes diagonaal door het beeld gaan bewegen en tegen de boven en de onderkant van het venster bouncen. (2 punten)

- De blokjes vormen qua grootte een reeks. De kleinste is 5x5 pixels, de op één na kleinste is 10x10 pixels (2x5), de op twee na kleinste is 15x15 pixels (3x5) etc, tot het grootste blokje dat 50x50 pixels is (10x5) (1,5 punten)

- zorg dat de collision-berekening tussen de player en de blokjes alleen uitgevoerd wordt als de blokjes zich (horizontaal) in het midden van het venster bevinden, met een strook van 10 pixels links en 10 pixels rechts van het midden.
Je hoeft hier niet de feitelijke collision te berekenen, maar alleen te berekenen of een blokje zich in de juiste positie bevindt om de collision-berekening uit te gaan voeren. Doe een println(“botsen maar…”) als een blokje een positie heeft om de collision te berekenen. De feitelijke collision komt bij de Advanced. (1 punt)

- Zorg dat snelheid van de blokjes en de player dusdanig is dat er een uitdagend spel (niet te makkelijk en niet te moeilijk) ontstaat (0,5 punt)


### Advanced
- Bereken de collision tussen de player en de blokjes. In dit stadium mag de player nog alle blokjes raken en maakt de volgorde nog niet uit. Blokjes verdwijnen bij botsen. (1,5 punten)

### Expert
- Zorg dat de player alleen de blokjes op volgorde van klein naar groot mag raken. Een punt toevoegen bij raken van het juiste blokje, een punt aftrekken voor het raken van een verkeerd blokje. Alleen de juiste blokjes verdwijnen bij botsing. De overige blokjes blijven bestaan bij botsen (1,5 punten)

### Structuur
- gebruik functies en classes op de juiste plekken (1 punt)
 

### INLEVEREN
Maak een zip van de map waarin je sketch en de overige files die nodig zijn om de sketch te laten werken zich bevinden. Zorg dat je voornaam, achternaam en ecttp_eindtoets in de naam van je sketch staan. Je opdracht kun je mailen naar je Lab docent (vincent.booman@hku.nl, ton.markus@hku.nl, valentijn.muijrers@hku.nl of aaron.oostdijk@hku.nl) en inleveren.gi@hku.nl. Mail je opdracht voordat je het lokaal verlaat.