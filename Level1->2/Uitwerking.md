## Opdracht (Level 0 -> 1)
De opdracht van dit level was om het wachtwoord te achterhalen dat in de file "-"
verstopt zou zitten.

## Stappen ondernomen
- Eerst wilde ik weer zien welke files er allemaal waren. (Door "ls" te doen)
- Ik wilde toen de file openen met "cat -", maar dit lukt niet.
- Ik heb op google gezocht hoe je een "dashed filename"kan openen.
- Hierna heb ik de goede commando uitgevoerd en toen kreeg ik het wachtwoord te zien.

## Commands die ik heb gebruikt
- cat ./-

## Screenshot
![Level 0->1](Media/level0-1.png)

## Wat ik heb geleerd
Linux hanteert een "-"als een commando optie en niet als pad. Vandaar dat "cat -" niks terug geeft.
Linux wacht namelijk op een optie. De oplossing is om "./" ervoor te zetten, zodat Linux
het ziet als een pad in de huidige directory. 

## Skills die ik heb geoefend
- Ik heb geoefend om bestanden te openen die beginnen met een "-"
