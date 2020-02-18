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

Succes met het doornemen van les02!
