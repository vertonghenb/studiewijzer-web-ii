# Studiewijzer Web II

De te kennen leerstof zijn de slides en de oefeningen die gebruikt worden tijdens de reguliere lessen (academiejaar 2019-20). Je vindt deze per hoofdstuk op [https://web-ii.github.io/OverViewCourse/](https://web-ii.github.io/OverViewCourse/). Het is ook belangrijk dat je de inleidende [slides](https://web-ii.github.io/OverViewCourse/docs/Inleiding1920.pdf) doorneemt. Deze bevatten onder andere info over het examen. 

Momenteel is via bovenstaande link [https://web-ii.github.io/OverViewCourse/](https://web-ii.github.io/OverViewCourse/) enkel Hoofdstuk 1 beschikbaar, maar deze website zal regelmatig aangevuld worden. Daar de slides dit jaar niet veel zullen wijzigen, geef ik alvast een download-link naar de slides van vorig academiejaar mee [Slides_2018-19.zip](docs/Slides_2018-19.zip). Wie nieuwsgierig is naar de komende hoofdstukken kan dan alvast eens door de slides bladeren.

Analoog als bij Webapplicaties 1 kan je de repo's downloaden van GitHub als zip-files of je kan gebruikmaken van een Git client. Indien je je repo's nog steeds download als zip-files is het wellicht een goed moment om eens een Git client te installeren ([https://git-scm.com/downloads](https://git-scm.com/downloads)) zodat je de repo's kan downloaden met behulp van het **git clone**-commando. De slides van Hoofdstuk 1 JavaScript (dia 18 en 19) bevatten instructies over hoe je het git clone-commando kan gebruiken in Visual Studio Code. Het creëren van een Github-account is hiervoor niet noodzakelijk. 

Daar er voor Webapplicaties II geen video's beschikbaar zijn, zal ik wekelijks, op maandag of dinsdag, een studiewijzer voorzien voor de les die de reguliere studenten die week zullen zien.

Ik raad alvast als extra leermateriaal zeker het onderstaande gratis materiaal aan. Ik zal er regelmatig naar verwijzen in de studiewijzers per les.

- [https://javascript.info/](https://javascript.info/)
  <br>Zeer goede website!
- [https://developer.mozilla.org/](https://developer.mozilla.org/)
  <br>Deze website mag je als naslagwerk gebruiken op het examen.
- [https://eloquentjavascript.net/](https://eloquentjavascript.net/)
  <br>Dit boek is technischer, maar is toch interessant als je op sommige zaken wat dieper wilt ingaan. Is ook te downloaden als pdf-bestand [https://eloquentjavascript.net/Eloquent_JavaScript.pdf](https://eloquentjavascript.net/Eloquent_JavaScript.pdf)

## Les01 De bouwstenen van JavaScript


| **Leerstof:  Slides [Hoofdstuk 1: JavaScript](https://web-ii.github.io/OverViewCourse/docs/01slJavascript.pdf) dia's 1-83** |

Tenzij je reeds een voorkennis hebt van JavaScript zou ik je aanraden om vooraleer de slides te doorlopen te starten met de tutorial [https://javascript.info/](https://javascript.info/) en de volgende items door te nemen:

- **An introduction** (*1.1 An introduction to JavaScript* tot *1.4 Developer console*)
- **JavaScript Fundamentals** (*2.1 Hello, world!* tot *2.14 Functions*)
  <br>**Opmerking** *2.3 The modern mode, "use strict"* is in de slides niet vermeld, je kan dit dus overslaan, maar je mag dit wel gebruiken, moet niet.
- **Code quality** (*3.1 Debugging in Chrome*)

Alhoewel je ook op de server en desktop kan programmeren in JavaScript, bijvoorbeeld via Node.js zullen we in dit opleidingsonderdeel enkel programmeren in de Browser. Bijgevolg is het gebruik van de **Chrome Developer tools** heel erg belangrijk. Als er iets niet werkt dan moet je eerste reactie zijn om de **Chrome Developer tools** (`<F12>`) te openen en te kijken of er geen errors vermeld zijn in de **Console**.

De eerste les bevat heel veel JavaScript syntax. Veel hiervan is analoog aan hetgeen je gezien hebt in Java. Concentreer je dus vooral op de verschillen.

In de slides van Hoofdstuk 1 wordt ook reeds gesproken over de basisobjecten **Number**, **Math** en **String**. Overloop dus zeker eens de reference op MDN in verband met deze objecten, om te zien welke methoden er allemaal beschikbaar zijn voor deze objecten: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)

### **Belangrijke opmerking**

Voor Hoofdstuk 1 is er geen repo met startbestanden voor de theorie. De repo [https://github.com/Web-II/01thVoorbeelden](https://github.com/Web-II/01thVoorbeelden) bevat een website met daarin de theorie uit de slides afgewisseld met interactieve oefeningetjes. Om de code die je intypt in de tekstvakken uit te voeren moet je op `<Ctrl+ENTER>` drukken. En daarna natuurlijk nog op `<F12>`om de **Console** af te beelden.
Dit is een experiment van vorig academiejaar. Je kan via deze website de leerstof van les 01 dus nog op een derde manier ;-) doorlopen. De website staat online op [https://web-ii.github.io/01thVoorbeelden/](https://web-ii.github.io/01thVoorbeelden/) of je kan de repo ook clonen en openen met de Live server.

Bij les01 horen de volgende oefeningen:

| **Oefeningen: [(https://github.com/Web-II/01exJavaScript](https://github.com/Web-II/01exJavaScript)** |
| - **Oefening 1: Blad – steen – schaar** |
| - **Oefening 2: Dragon slayer** |    

## Les02 Arrays, objects and functions

Maak als herhaling op les01 de driloefeningen: [https://github.com/Web-II/01driloefeningen](https://github.com/Web-II/01driloefeningen)

| **Leerstof:<br>Slides [Hoofdstuk 1: JavaScript - arrays](https://web-ii.github.io/OverViewCourse/docs/01slJavascript.pdf) dia's 84-104** de rest van het hoofdstuk is ter info.<br>**Slides [Hoofdstuk 2: Objecten en functies](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) dia's 1-46** |

### Arrays

Doorloop op je eigen tempo de slides van Hoofdstuk 1: dia's 84-104 (arrays). Probeer hierbij regelmatig eens iets uit in de chrome developer console. **Dia 90** is van minder belang. Om een element te verwijderen uit een array zal je meestal de methode `.splice()` gebruiken of `.pop()` en `.shift()`.
Om bijvoorbeeld het derde element te verwijderen uit de array *pizzas* gebruik je `pizzas.splice(2,1)`. Het eerste argument is de positie waar het verwijderen moet starten, het tweede argument is hoeveel elementen er moeten verwijderd worden, hier eentje. 

Later in deze cursus komen we nog terug op het werken met arrays, maar bekijk al eens op MDN welke properties en methods er allemaal beschikbaar zijn [Array op MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array). Zie ook dia 98 en 99.

Op dia 100 en 101 wordt **Array destructuring** besproken en op dia 102 wordt gebruikgemaakt van de spread syntax. De uitleg op deze drie dia's is heel kort en al komt men later in de cursus nog hierop terug. Ik zou toch aanraden om nu al de volgende artikels te lezen: 

- [Destructuring assignment op MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
tot juist voor 'Unpacking values from a regular expression match'.
- [Rest parameters and spread syntax op javascript.info](https://javascript.info/rest-parameters-spread)

| **Oefeningen:** |
| Als oefening op arrays kan je op de website [https://web-ii.github.io/01thVoorbeelden/](https://web-ii.github.io/01thVoorbeelden/) bij Arrays > Eenvoudige operaties, onderaan de pagina de oefening maken (bestaat uit 10 vraagjes). |
| Eventueel kan je ook nog Oefening 3 en 4 van Hoofdstuk 1 maken. |

### Objecten en functies

Neem de slides door van [Hoofdstuk 2: Objecten](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) nl. dia 1 t.e.m. dia 19. **Maak daarna de oefening op dia 20**.

Neem de slides door van [Hoofdstuk 2: functies](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) nl. dia 21 t.e.m. dia 45. **Maak daarna de oefening op dia 46**.

Na het doornemen van de slides over functies ken je nu drie manieren om een functie te definiëren, alle drie hebben ze hun toepassingen. Je moet ze dus alle drie kennen.

Eventueel kan je op [https://javascript.info/](https://javascript.info/) nog de volgende items doornemen:

- **JavaScript Fundamentals** (*2.15 Function expressions* en *2.16 Arrow functions, the basics*)
  <br>**Opmerking** Eventueel kan je ook *2.17 JavaScript specials* doornemen, wat grotendeels herhaling is.
- **Objects: the basics** (*4.1 Objects*)
  <br>**Opmerking** Ben je nog niet helemaal mee met 'Destructuring assignment' dan raad ik je aan om *5.10 Destructuring assignment* door te nemen.

## Les03 Objects and functions (methods), events, closures, exceptions

In deze les wordt hoofdstuk 2 verder afgewerkt.

| **Leerstof: Slides [Hoofdstuk 2: Objecten en functies](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) dia's 47-76** |

### Objects and functions (methods)

Neem de slides door over 'methods': [Hoofdstuk 2: Objecten](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) nl. dia 47 t.e.m. dia 54.


Eventueel kan je op [https://javascript.info/](https://javascript.info/) bij PART 1 het onderdeel *[4.4 Objects methods, "this"](https://javascript.info/object-methods)* doornemen.

### Events

Neem de slides door over events [Hoofdstuk 2: Objecten](https://web-ii.github.io/OverViewCourse/docs/02ObjectenEnFuncties.pdf) nl. dia 55 t.e.m. dia 70.

De DOM wordt in de slides pas in Hoofdstuk 6 besproken, maar om te kunnen werken met events hebben we wel een beetje DOM nodig, waaronder `document.getElementByd()`. Daarom wordt in het onderdeel 'events' ook reeds gesproken over de DOM.

Eventueel kan je op [https://javascript.info/](https://javascript.info/) bij PART 2  het volgende doornemen:

- in verband met de DOM:

  - *[1.1 Browser environment, specs](https://javascript.info/browser-environment)* 
  - En bij *1.4* de sectie *[document.getElementById or just id](https://javascript.info/searching-elements-dom#document-getelementbyid-or-just-id)*.

- in verband met events:

  - *[1.2 Introduction to browser events](https://javascript.info/introduction-browser-events)*

### Closures (dia 71-75)

Closures is een niet zo eenvoudig stukje. Maar gelukkig zal je in JavaScript meestal Closures gebruiken, zonder dat je je er echt van bewust bent.

Diepgaandere info vind je op [https://javascript.info/closure](https://javascript.info/closure).


### Exceptions (dia 76)

Er is slechts één summiere dia over exceptions. `try...catch` werkt in JavaScript vrij analoog aan hetgeen je gezien hebt in java.

Meer info vind je op [https://javascript.info/try-catch](https://javascript.info/try-catch)

| **Oefeningen** | 
| Nadat je het bovenstaande hebt doorgewerkt kan je ook nog de oefeningen op Hoofdstuk 2 maken. Neem gerust de oplossing [https://github.com/Web-II/02solObjectsAndFunctions](https://github.com/Web-II/02solObjectsAndFunctions) erbij als je problemen ondervindt. | 

## Les04 Class basic syntax

In deze les starten we in hoofdstuk 3 met het werken met classes in JavaScript. Classes ken je reeds uit Java, het meeste zal je dus bekend voorkomen.

In JavaScript kan je op verschillende manieren werken met objecten en sinds ES6 kan je in JavaScript ook de class-syntax gebruiken. Daar het gebruik van de class-syntax in JavaScript meer en meer mainstream wordt, zullen we in deze cursus vooral hierop de nadruk leggen.

Voor ES6 gebruikte men in JavaScript *Constructor functions* in plaats van *Classes*. Ook al gaan we de werkwijze met de Constructor function niet echt gebruiken in deze cursus, toch is het misschien niet slecht om van het onderdeel *[4.6 Constructor, operator "new"](https://javascript.info/constructor-new)* het begin te lezen (de inleiding en de eerste sectie **Constructor function**).

| **Leerstof: Slides [Hoofdstuk 3: OOP in JavaScript](https://web-ii.github.io/OverViewCourse/docs/03OopInJavascript.pdf) dia's 1-29** |

Neem de slides door nl. dia 1 t.e.m. 29  en los ook de vragen op in blog1.js (dia 15) en blog2.js (dia 29) in de voorbeeldbestanden.

Lees op [https://javascript.info/](https://javascript.info/) eventueel *[9.1 Class basic syntax](https://javascript.info/class)* (**Class expression** en **Class properties** kan je skippen, deze zullen we niet bespreken in de cursus).

| **Oefeningen** | 
| Nadat je het bovenstaande hebt doorgewerkt, maak je best **Oefening 1: Afrikaans dobbelen**. Deze oefening bevat een stapsgewijze opgave en is een goede herhaling.

## Les05 Overerving, prototypes

Een mogelijke oplossing voor de blog-oefeningen (*blog1.js* en *blog2.js* uit de vorige les en *blog3.js* deze les) vind je in de repo [https://github.com/plauwaer/03thcompleted](https://github.com/plauwaer/03thcompleted)

In deze les bekijken we overerving en zien we hoe je in JavaScript een subklasse van een klasse kunt maken via `extends`. Dit alles is zeer analoog aan overerving in Java.

We hebben gezien dat we sinds ES6 in JavaScript de class-syntax kunnen gebruiken, maar op de achtergrond gebruikt JavaScript nog steeds het 'prototype pattern' met 'constructor functions' en de 'prototype-chain'. Regelmatig zul je dus in JavaScript in aanraking komen met prototype-objecten. Daarom bevat dit hoofdstuk ook een aantal dia's over prototypes.

Deze dia's zijn vnl. bedoeld als achtergrondinformatie. Bij het oplossen van de oefeningen en ook op het examen werken we in principe met de class-syntax en niet met prototypes.

Misschien nog even benadrukken dat naast de class-syntax ook de object literal syntax (meestal zonder methodes) belangrijk is voor de oefeningen en het examen.

De volgende les is een belangrijke les. Eén van de doelstelingen van Webapplicaties II is immers het vlot leren werken met de array-methoden `map()`, `filter()`, `reduce()` en `forEach()` en deze worden besproken in Hoofdstuk 4. Neem als introductie daarop dia's 1-22 door van **Hoofdstuk 4 Functional programming met Arrays**. Voor deze dia's is er een video 'H04 - 1 arrays herhaling' gemaakt. Je vindt de video in de map 
**[VIDEO'S Hoofdstuk 4 Theorie](https://hogent.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx#folderID=%224c0fb62e-2bad-4269-99fb-ab81009a402f%22)**

| **Leerstof: <br>Slides [Hoofdstuk 3: OOP in JavaScript](https://web-ii.github.io/OverViewCourse/docs/03OopInJavascript.pdf) dia's 30-37** - overerving<br>**Slides [Hoofdstuk 3: OOP in JavaScript](https://web-ii.github.io/OverViewCourse/docs/03OopInJavascript.pdf) dia's 38-53** - prototypes<br>**Slides [Hoofdstuk 4: Functional programming met Arrays](https://web-ii.github.io/OverViewCourse/docs/04FunctioneelProgrammeren.pdf) dia's 1-22** - inleiding en herhaling arrays |



| **Oefeningen** |
| **Oefening 2: OXO** | 

## Les06 Functional programming, Array methods

(Opmerkingen voor wie de repo **04thCollectionsStarter** gecloned heeft voor 2020-03-14: de twee oefeningen op sorteren stonden in de verkeerde .js-file. De oefeningen zijn verplaatst van **/js/herhaling.js** naar **/js/advanced.js**.  En bovenaan in **/js/advanced.js** is de array fruit toegevoegd. )

| **Leerstof: Slides [Hoofdstuk 4: Functional programming met Arrays](https://web-ii.github.io/OverViewCourse/docs/04FunctioneelProgrammeren.pdf) dia's 23-33** |

In deze dia's worden de array-methoden `arr.map()`, `arr.filter()` en `arr.reduce()` besproken. Voor deze dia's is er een video 'H04 - 2 map/filter/reduce' gemaakt. Je vindt de video in de map 
**[VIDEO'S Hoofdstuk 4 Theorie](https://hogent.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx#folderID=%224c0fb62e-2bad-4269-99fb-ab81009a402f%22)**.

Doorloop niet alleen de video, maar maak (zoals gevraagd in de video) Oefening 1, achteraan in **js/mapFilterReduce.js** . Deze oefening bevat zeven driloefeningen. Vooraleer je Oefening 1 probeert te maken is het misschien nuttig om op http://developer.mozilla.org de methodes die beschikbaar zijn voor String en Array nog eens kort te overlopen. Maak eventueel voor jezelf hiervan een samenvatting.

Nog enkele extra links:

- Wie na het doornemen van **/js/herhaling.js** graag nog een beetje extra herhaalt, kan de basis in verband met arrays nog eens nalezen op 
[https://javascript.info/](https://javascript.info/) nl. *[5.4 Array](https://javascript.info/array)*. Ook de eerste taak 'Is array copied?' is een goede herhaling.
- De moeilijkste methode is wellicht `arr.reduce()`. Je kan de werking van deze methode nalezen op [MDN: Array.prototype.reduce()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce). Ook de eerste voorbeeldjes zijn een goede herhaling.

|  **Oefeningen Hoofdstuk 4**  |
|  **Oefening 1: 1. Caesarcijfer, 2 Camelize, 3. Buren en 4. Morse**<br>Met uitzondering van de functie zijnBuren() is het de bedoeling dat je in deze oefening geen gebruikmaakt van de klassieke for-lus. Tip Je moet onder andere gebruikmaken van `str.split()`, `str.join()` en `arr.map()`, `arr.reduce()`.<br>Voor deze oefening zijn er video's gemaakt. Je vindt de video's in de map **[VIDEO'S - H04ex](https://hogent.cloud.panopto.eu/Panopto/Pages/Sessions/List.aspx?folderID=d3f69ef3-9beb-4742-b2ce-ab81009a8c2c)**, maar probeer eerst zelf de oefeningen te maken.  |
|  Dit academiejaar is de Canvas API geen leerstof. Bijgevolg zijn 'Oefening 2: Snake' en 'Oefening 3: Doolhof' geen verplicht te maken oefeningen. Indien je deze leuke oefeningen wenst te maken, lees je best eerst een inleiding op de Canvas API. Suggestie: lees op MDN in de [Canvas tutorial](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) minstens '1. Basic usage' en het begin van '2. Drawing shapes'.  |

## Les07 Array methodes: forEach(), sort(), ...

| **Leerstof: Slides [Hoofdstuk 4: Functional programming met Arrays](https://web-ii.github.io/OverViewCourse/docs/04FunctioneelProgrammeren.pdf) dia's 34-39** |

In deze dia's worden de array-methoden `arr.forEach()`, `arr.find()`, `arr.findIndex()` en `arr.sort()`besproken.

Onthou dat:

- in tegenstelling tot de andere methodes, de methode `arr.forEach()`, geen waarde (undefined) teruggeeft
- en dat de methode `arr.sort()` geen nieuwe array teruggeeft, zoals `arr.map()` en `arr.filter()`, maar de array zelf wijzigt.

Neem niet alleen de theorie door, maar maak ook de twee driloefeningen op sorteren (sorteren array animals en sorteren array shapes) achteraan in **js/advanced.js** . 

Voor meer info over `.sort()` zie [Array.prototype.sort() op MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort).

Eventueel kan je nog eens de geziene array-methodes, uit deze en de vorige les herhalen op [https://javascript.info](https://javascript.info) nl. *[5.5 Array methods](https://javascript.info/array-methods)* (het laatste item nl. **Most methods support “thisArg”** kan je skippen, dit wordt niet besproken in de cursus).

| **Oefeningen Hoofdstuk 4** | 
| Maak nadat je het bovenstaande hebt doorgewerkt **Oefening 4: Array Cardio**. Een stapsgewijze oplossing van 1. t.em. 7 kan je bekijken in de video [https://youtu.be/HB1ZC7czKRs](https://youtu.be/HB1ZC7czKRs) (6. in de video komt niet voor in de oefening omdat deze gebruikmaakt van DOM, wat pas in Hoofdstuk 6 besproken wordt). De oplossing van 8., 9. en 10. kan je bekijken in de video [https://youtu.be/QNmRfyNg1lw](https://youtu.be/QNmRfyNg1lw). | 

## Les08 De datastructuren **Map** en **Set** en het gebruik van de rest en de spread operator 

| **Leerstof: Slides [Hoofdstuk 4: Functional programming met Arrays](https://web-ii.github.io/OverViewCourse/docs/04FunctioneelProgrammeren.pdf) dia's 40-65** |

Alhoewel 'Objects' en 'Arrays' als datastructuren meestal volstaan, zijn de datastructuren 'Map' en 'Set' soms geschikter voor het oplossen van een bepaald probleem (we moeten niet telkens opnieuw het wiel uitvinden).

Map- en Set-objecten hebben echter minder methodes dan een Array-object. Wensen we dus bijvoorbeeld `.filter()` te gebruiken op een Map-object, dan zullen we het Map-object eerst moeten omzetten naar een Array-object. Dit kan onder andere met de spread operator. Eventueel zal je daarna het Array-object terug omzetten naar een Map-object. 

Maak bij het doornemen van **js/maps.js**, **js/sets.js** en **restAndSpread.js** ook telkens de twee oefeningen die onderaan in de files vermeld zijn.

