# Programmeren2

## Oefeningen op Klassen

1. Sommige stereoversterkers hebben een display dat veranderingen in het 
geluidsvolume laat zien. De uitslag van de indicator in het display wordt groter
en kleiner afhankelijk van het volume op elk tijdstip. Sommige displays 
hebben indicatoren die de maximum en minimumwaarden tonen vanaf het moment dat
de versterker wordt aangezet. Schrijf een programma dat in tekstvakken de 
numerieke waarden van de maximum-en minimumwaarden laat zien waarop een schuif
regelaar was ingesteld. De schuif kan je nabootsen door een tekstvak. Schrijf
een klasse dat deze waarden onthoudt en kijkt of je waarde niet de min en max 
zal overschrijden.

2. Maak een schermlayout voor een ballonprogramma. De bedoeling is dat je 
een form aanmaakt met allerlei knoppen die een ballon kunnen besturen. De 
ballon tekenen (op een picturebox: zoek uit hoe je een cirkel kan tekenen),
de ballon verplaatsen, van grootte of kleur veranderen. De ballon op een 
willekeurige positie tekenen. Je maakt in je winform project een klasse ballon
aan met de nodige properties, methodes, constructors,...



3. Schrijf een klasse Wekker. Je kunt de huidige tijd opvragen, een alarmtijd 
instellen wanneer de wekker moet aflopen en controleren of de alarmtijd al dan niet is 
verstreken. Verder kun je instellen hoelang de wekker moet aflopen (in seconden)
. Default is deze waarde 10 seconden. Denk zelf na over publieke en private 
methodes en properties. 
Ontwerp vervolgens een formulier waarin je een Wekker object instantieert. Gebruik labels
tekstvelden en knoppen om de huidige tijd te tonen en om een alarmtijd in te 
stellen. Het afgaan van de wekker kun je simuleren door het knipperen van een label of door het afspelen
van een geluid, vb.: 

My.Computer.Audio.PlaySystemSound(
        System.Media.SystemSounds.Asterisk)



![oef1](/oef1.PNG)


4. Ontwerp en schrijf een klasse die handelt als een dobbelsteen die bij een 
worp een waarde tussen 1 en 6 krijgt. 
Schrijf een programma dat een dobbelsteenobject maakt en gebruikt.
Het scherm laat een knop zien die, wanneer erop gedrukt wordt, ervoor zorgt dat
de dobbelsteen gegooid wordt en het aantal ogen op het scherm te zien is.

**Uitbreiding**
Kan je de dobbelsteen klasse gebruiken voor het spelletje craps?

Maak het spelletje CRAPS
Een speler gooit met 2 dobbelstenen. Als de som bij de eerste worp 7 of 11 is wint de speler. Als de som 2,3 of 12 is tijdens eerste worp (=craps) verliest hij. Als
de som 4,5,6,8,9,10 is dan wordt deze som de speler zijn punten, en probeert vanaf dan met de dobbelstenen te gooien totdat hij deze som opnieuw heeft gesmeten. Maar smijt
hij vanaf dan een 7 verliest hij.

(Misschien kan je al proberen om "craps" in een klasse te gieten, op die manier kan je een multiplayer game maken..


