## Opdracht (Level 4 -> 5)
Voor deze opdracht was er een folder met verschillende files erin.
1 van deze files bevatte normale "human-readable" tekst en de rest 
bevatte allemaal andere tekens. Het doel was om de file te vinden die het
wachtwoord bevatte. 

## Stappen ondernomen
- Eerst probeerde ik de eerste file te openen door "cat -file00" te doen. Dit werkte niet.
- Hierna probeerde ik de file te openen door "cat -- -file00" te doen. Dit werkte wel.
- Toen probeerde ik dit bij elke file te doen. Dit werkte wel, maar dit zorgde voor
  veel herhaling en dat is niet efficiënt.
- Ik deed hierna "file *" om te zien wat alle files bevatte kwa inhoud. Dit werkte ook
  niet, omdat die nu files zag als "ile00" inplaats van "-file00".
- Toen ik "file ./*" deed werkte die wel en zag van elke file wat voor soort inhoud erin stond.
- Ik zag dat file07 ASCII text bevatte als enige dus wist dat dit de file moest zijn.
- Toen "cat -- -file07" gedaan en toen had ik het wachtwoord succesvol ontvangen

## Commands die ik heb gebruikt
Niet werkende:
- cat -file00
- file *

Wel werkende:
- find ./*
- cat -- -file07"


## Screenshot
![Level 3->4](Media/level3-4.png)

## Wat ik heb geleerd
Ik heb dit level niks nieuws geleerd, want ik wist al dat je verborgen files 


## Skills die ik heb geoefend

