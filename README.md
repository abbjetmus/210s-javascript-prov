# 210s-javascript-prov
## Regler
* Inte tillåtet att hjälpa varandra på något sätt, räknas som fusk.
* Det är tillåtet att använda internet hur mycket man vill.
* Efter provet kan ni skicka in era svarsfiler som DM till mig via Teams.
Vet ni hur man zippar så får ni gärna zippa mappen med filerna.<br><br>

Börja med att klona eller ladda ner projektet.
<br>
`git clone https://github.com/abbjetmus/210s-javascript-prov.git`
<br>
## Att tänka på

Varje fråga består av en html fil med uppgiftsnumret.<br>
Html filen innehåller en html mall med nödvändiga taggar och en ```script``` tagg där ni ska lägga in er javascript kod.<br>
För att starta programmet dubbel-klickar du bara på html filen i filutforskaren och den öppnas i webbläsaren. Sedan när du gör ändringar i filen laddar du om webbläsaren för att dina ändringar ska synas.
Du får använda valfri editor för att koda men rekommenderar Visual Studio Code.

## Fråga 1 - Variabler
1. Skapa två variabler en som heter <b>height</b> som du tilldelar ett valfritt tal/nummer, och en som heter <b>width<b> som du också tilldelar ett tal till.
2. Skapa sedan en variabel <b>area</b> som tilldelas multiplikationen av variablerna height och width.<br>
3. Skriv ut area variabeln till konsolen.

## Fråga 2 - HTML/CSS
1. Skapa en div-tagg och ange den en klass med namnet **rectangle**. Definera klassen rectangle i *style* taggen innan för head.
2. Rectangle klassen ska ha följande egenskaper:
* height: 300px;
* width: 300px;
* margin: 20px;
* padding: 20px;
* background-color: green;

## Fråga 3 - Array/lista
1. Skapa en array/lista med siffrorna 1 till 5 och tilldela den till en variabel tal.
2. Skriv ut till konsolen med hjälp av listan första talet i listan, dvs tal 1.

## Fråga 4 - If-satser
Läs in ett namn på bilmärke med <i>prompt()</i> och lagra det i en variabel som heter <b>brand</b>.
Använd if-satser för att kontrollera ifall märket är:<br> 1. <i>Audi</i> - Är fallet sådan skriver du ut "Det är ett tyskt bilmärke".<br>
2. <i>Fiat</i> - Är fallet sådan skriver du ut "Det är ett italienskt bilmärke".
3. Annars skriver du ut "Känner inte till märket".


## Fråga 5 - For-loopen
 
Skapa en for-loop som loopar igenom talen 0 till 18 och skriver ut talet till konsolen.


## Fråga 6 - For-loop på lista med objekt

Du har en lista nedan med objekt som innehåller information om politiker.

```
[{id: 1, firstName: 'Stefan', lastName: 'Löven'},
{id: 2, firstName: 'Annie', lastName: 'Lööv'},
{id: 3, firstName: 'Nyamko', lastName: 'Sabuni'},
{id: 4, firstName: 'Jimmie', lastName: 'Åkesson'},
{id: 5, firstName: 'Per', lastName: 'Bolund'},]
```
1. Skapa en data variabel med namnet **politiker** som tilldelas listan med fem objekt med politiker:

2. Loopa sedan igenom listan och skriv ut information om varje list-objekt på följande format:
**firstName - lastName**, för första objektet skulle det se ut så här **Stefan - Löven**.

## Fråga 7
1. Skapa två funktioner **area** och **volume** för beräkning av area och volym. Area ska ta in två parametrar **x** och **y** och returnera arean av dem dvs multiplikationen. <br>Volume ska ta in 3 parametarar **x**, **y** och **z** och returnera volymen av dem dvs multiplikationen.
2. Anropa sedan varje funktion med valfria värden på parametrarna och skriv ut resultatet till konsolen.


## Fråga 8 (lite svårare) - Filtrering med Callback
Du har en lista nedan med objekt som innehåller information om politiker.

```
[{id: 1, firstName: 'Stefan', lastName: 'Löven'},
{id: 2, firstName: 'Annie', lastName: 'Lööv'},
{id: 3, firstName: 'Nyamko', lastName: 'Sabuni'},
{id: 4, firstName: 'Jimmie', lastName: 'Åkesson'},
{id: 5, firstName: 'Per', lastName: 'Bolund'},]
```
1. Tilldela listan till en variabel som heter **politiker**.

2. Skapa en funktion som heter findPolitiker(), findPolitiker tar in en parameter på ett Id,
använd Id't för att filtrera ut objektet med det Id't från politiker och returnera det.

Använd inbyggda find funktionen för att filtrera: <https://www.w3schools.com/jsref/jsref_find.asp>

3. Anropa findPolitiker med ett Id som finns i listan och tilldela det till en variabel **p**, använd **p** och skriv ut namnet på objektet på formatet: 
**firstName - lastName**, för första objektet med id=1 skulle det se ut så här **Stefan - Löven**.


## Fråga 9
1. Skapa en input-tagg med **id="adress"** som tar in en bild-adress dvs text.
2. Skapa en knapp-tagg (button) bredvid input-taggen som när man klickar på den ska köra en funktion som heter *showImage()* som du definerar i script-taggen.
3. Skapa under dessa en img-tagg med **id="bild"** som du ändrar *src*-attributet på från din showImage() funktion till det som kopierades in i input-taggen.

Notera att i resultatet så finns inte knappen med med som ni ska klicka på utan bara fältet och bilden.
### Resultat
![](./uppgift3.gif)