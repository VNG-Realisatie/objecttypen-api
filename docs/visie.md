Visie
=====

Voor het opslaan en ontsluiten van allerlei domein specifieke gegevens zijn 
registraties en bijbehorende API's nodig. Een domein specifiek gegeven kan een 
"melding", "hond", "boom", "parkeervergunning", "klacht", "trouwambtenaar", 
etc. zijn.

Typisch willen gemeenten, maar soms ook externe partijen, toegang krijgen tot 
deze domein specifieke gegevens. Vanuit een Zaak moet kunnen worden verwezen 
naar zo'n object en sommige type objecten moeten bijvoorbeeld in bulk op een 
kaart of overzicht getoond worden.

Deze object registraties zijn nodig in het gegevenslandschap om domein 
specifieke applicaties te realiseren volgens de Common Ground principes. 
Standaardisatie is nodig om wildgroei en uiteenlopende invulling van 
objecttypes te voorkomen.

Aanpak
======

Het is bijna onmogelijk om elk objecttype vooraf te kennen, definiëren en vast 
te leggen in een API standaard. Daarnaast is het ook niet praktisch dat voor 
elke objecttype een eigen registratie en bijbehorende API ontstaat omdat 
daarmee het gegevenslandschap vervuild wordt. Echter, er moet geen belemmering 
zijn om, indien dat nodig is, een objecttype uiteindelijk toch zijn eigen 
registratie en API te geven, bijvoorbeeld omdat het objecttype te complex 
wordt.

We introduceren daarom 2 API's:

**Landelijke Objecttypen API**

Op landelijk niveau moet er een catalogus komen voor allerlei objecttypen. 
Hierin worden objecttypen gedefinieerd die in de loop der tijd ontstaan. Deze 
catalogus moet ondersteuning krijgen voor versies van objecttypen. De definitie 
van zo'n objecttype kan worden voorgesteld aan een werkgroep en als deze 
akkoord is wordt deze opgenomen. Belangrijk is wel dat dit een vrij kort proces 
is zodat objecttypen snel kunnen worden gestandaardiseerd.

**Objecten API**

Een gemeente kan hier één of meerdere instanties van opzetten, voor de 
registratie van allerlei objecten, behorende bij een objecttype uit de 
Objecttypen API. Meerdere registraties zijn interessant om bijvoorbeeld 
met dezelfde API-specificaties zowel openbare objecten (denk aan open data, 
zoals lantaarnpalen of bomen) als meer gevoelige objecten op te slaan (denk aan 
klachten of vergunningen). De openbare objecten zijn middels een publieke API 
toegankelijk terwijl de andere objecten alleen binnen de organisatie 
toegankelijk zijn. Alle objecten volgen zo een vast formaat, vastgelegd in het 
landelijke objecttype, en zijn dus eenvoudig te gebruiken in allerlei 
applicaties.
