## Projektuppgift: DummyForum
Du ska använda DummyApi-webbtjänsten för att bygga diskussionsforum.
Denna applikation ska byggas med hjälp av AngularJS, Bootstrap och jQuery UI.

Inlägg (posts) kommer finnas tillgängliga här: http://dummyapi.kodalagom.se/api/posts<br>
Trådar (threads) kommer finnas här: http://dummyapi.kodalagom.se/api/threads

DummyApi docs: https://github.com/JohnFChas/DummyApi/wiki

## Uppgifter
Följande är minimum för godkänt betyg.

- Använd AngularJS med routing
- Använd bootstraps grid för layout och responsivitet
- Skapa en service som hanterar alla HTTP-requests
- Navigation
	- Använd till exempel bootstrap navbar eller tabs
- "Home"-view
	- Skapa nya trådar
	- Ta bort trådar
	- Lägg till favorit-trådar
- "Thread"-view
	- Visa alla posts som tillhör tråden
	- Skriva nya inlägg
	- Se till att dina nya inlägg och trådar dyker upp i webbläsaren utan att man behöver ladda om sidan
	- Formatera datumen på alla inlägg med ett filter eller directive  
  
Det är tillåtet att skapa fler/färre/andra views om man anser det nödvändigt

## Extrauppgifter
Följande uppgifter ger poäng mot betyget väl godkänt, för väl godkänt betyg krävs minst 8 VG-poäng.

Utöver dessa uppgifter kommer jag dessutom att titta på kodstruktur och design av gränssnitt för högre betyg.
När det gäller design är det först och främst struktur och användarvänlighet jag är ute efter.

- Skriv väl strukturerad och genomtänkt kod (0-4 VG-poäng)
- Användarvänligt och strukturerat gränssnitt (0-4 poäng)
- Skapa components eller directives för: (1-5 VG-poäng)
	1. Länkar till trådar
	2. Input-fält
  3. Formulär
	3. Alternativt andra valfria saker
- Använd jQueryUI draggable och droppable för att: (1-2 VG-poäng)
	1. Flytta trådar till favoriter
	2. Ta bort trådar
- Använd någon cool jQueryUI effekt när: (1-2 VG-poäng)
	1. När man tar bort trådar med draggable/droppable
  2. Andra valfria saker
- Skapa valfria directives, components, filters och/eller services (0-5 VG-poäng)
- Skapa valfri widget med widget factory eller AngularJS component/directive (och använd den på något meningsfullt sätt) (0-5 VG-poäng)
- Labbar/inlämningar som lämnades in under kursens gång (0-2 VG-poäng)

## Inlämning
Det är individuell inlämning för detta projekt.
Deadline för inlämning: 1 januari 2017, kl 23:59

- Skapa ett GIT repository, till exempel på github.com.
- Pusha upp ert projekt till ert repository.
- Maila länken till repositoryt till mig på john.fristedt@chas.se.

Vet ni inte hur man gör detta så hör av er till mig så ska jag förklara.
