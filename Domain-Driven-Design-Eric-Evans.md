# Domain-Driven Design (Tackling Complexity in the Heart of Software, 2004)

## Preface

  - The author has more than 10 years experience in development of complex systems.
  - The book provides a framework for making design descisions.

## Contrasting Three Projects

  - The author remembers 3 projects:
    1. A project that failed because it was completely missing a design model thus becoming a swamp of code.
    2. A project that emphasized on domain design that had been a great success. Through the model the team and the software stayed alive and responsive to clients needs. The model improved, so did the count of opportunities for the project grow.
    3. A project that emphasized on domain design at first, but then lost its focus, then its vision, and ended up as a modest, conventional project with modest success.
  
## The Challenge of Complexity

  - Bei den meisten Projekten sollte der Fokus auf der Domäne und der Domain Logic liegen.
  - Komplexe Designs sollten auf Modellen basieren.

## Design Versus Development Process

Softwaredesign wird normalerweise entweder unterschätzt oder übertrieben. 
Auch Extreme Programming hat Definitionsschwächen. So ist es den Entwicklern erlaubt, immer die "einfachste Lösung" für die Erfüllung einer Anforderung zu wählen.
Erfahrungsweise funktioniert XP am Besten bei Entwicklern, die für Software-Design sensibilisiert sind.
Das Buch soll im weiteren Design und den agilen Entwicklungsansatz miteinander verzahnen.

# Putting the domain model to work

Ein Modell zu designen ist wie Filme machen: Ein Teil der Realität wird abstrahiert um etwas bestimmtes darzustellen.

## The utility of a model in domain driven design

  - Das Modell und das Herz der Software beeinflussen einander.
  - Das Modell ist das Rückrad der Sprache, die von allen Team-Mitgliedern genutzt wird.
  - Das Modell ist konzentriertes Wissen.
  
Dem Autor geht es nicht um eine bestimmte Design-Methodik, er mag aber agile Vorgehensweisen.

Daher: 
  1. Entwicklung ist ein iterativer Prozess
  2. Entwickler und Domänen-Experten stehen in enger Beziehung zueinander.
  
Der Autor nutzt Extreme Programming. Die Leichtigkeit von Extreme Programming steht im Kontrast zu Designansätzen wie dem Wasserfallmodell in denen zunächst Design stark übergewichtet wird, ohne dann Bezug zur Entwicklung zu haben. Das führt zu unnötigen Problemen.

## The Heart of Software

Das Herz der Software ist ihre Fähigkeit Herausforderungen für den Benutzer zu lösen. Dennoch sind die meisten talentierten Entwickler nicht gewillt sich mit der Domäne ihrer Kunden auseinanderzusetzen. Stattdessen beschäftigen sie sich lieber mit rein technischen Problemen und überlassen die Analyse der Domäne anderen.

Der Autor erläutert als Beispiel einen Vorfall bei den Dreharbeiten eines Monty Python Films, bei dem ein Film-Editor eine lustige Aufnahme einer komplizierten Szene verworfen hatte, weil sie nicht technisch perfekt war. Sie erfüllte aber den Zweck des Regisseurs hervorragend, weil die Szene dort lustig herüberkam, was in etlichen anderen Aufnahmen nicht gelungen war.

Das Buch befasst sich mit Arten zu Denken, die Entwickler anwenden können, um Domänen zu verstehen und passende Modelle zu entwickeln.

# Crunching Knowledge

Der Autor beschreibt in der Einleitung, wie er in einem vergangenen Projekt mit den Domänen Experten zusammen saß und wie sie zusammen in ihren Besprechungen ein Modell für eine komplexe Anwendung entwickelten. Hierbei profitierte er vom Einblick in die Domäne und die Experten profitierten ebenfalls, weil die systematische Denkweise des Entwicklers ihnen half, herauszufinden, was das Herz ihrer Software eigentlich ist und sein sollte. Er zeigt hierbei, wie Sprache sehr bewusst als Modellierungswerkzeug eingesetzt wurde. Und wie dies letztlich zum Erfolg der Software beitrug.

## Ingredients of effective Modeling

Folgende Zutaten haben zu dem zuvor beschriebenen Erfolg :

  1. Die Verbindung von Modell und Implementation.
  2. Das kultivieren einer Sprache, die auf dem Modell basiert.
  3. Entwicklung eines wissenstragenden Modells
  4. Verschlankung / Kristallisierung des Modells
  5. Brainstormen und experimentieren

Es ist die Kreativität von Brainstorming und intensiven Experimenten mit einer modellbasierten Sprache, diszipliniert durch den Feedback-Loop der Implementation, welche es ermöglicht ein wissensintensives Modell zu finden und es treffender zu gestalten.

## Knowledge Crunching

Effektive Domänen-Modellierer prüfen viele unterschiedliche Organisationsideen um die einfachste Option zu finden, die im Großen und Ganzen Sinn ergibt.
Das Knobeln zum Finden des Modells ist eine Team-Aktivität von Entwicklern und Domänenexperten. Die Aufgabe der Entwickler ist dabei der Entwurf von Zeichnungen und Mitschriften und das Führen des Gesprächs. Die Domänenexperten bringen ihr Wissen und ihre Anforderungen mit ein.

In der klassischen Wasserfallmethode sprechen die Domänenexperten mit Analysten, die dann das Ergebnis ihrer Analyse an Softwareentwickler übergeben, welche dann die Software schreibeb. Es gibt kein Feedback und keine Möglichkeit für die Entwickler zu lernen.

Iterativ entwickelte Projekte können ebenfalls Probleme haben, wenn sie kein Modell aufbauen, sondern einfach nur Anforderungen erfüllen. In einem solchen Projekt stehen die Anforderungen dann nebeneinander, ohne ein Modell zu bilden.

Großartige Softwareentwickler werden automatisch beginnen ein Modell aufzustellen, in das sich die aktuellen und kommenden Anforderungen natürlich einfügen. Aber auch das wird nur teilweise erfolgreich sein, wenn das Modell keine tiefe Verbindung zur Domäne aufweist.

## Continuous Learning

Wenn wir beginnen, Software zu schreiben, wissen wir niemals genug. Und das Wissen um ein Projekt nimmt aus vielen Gründen über die Zeit auch noch ab.
Hochproduktive Teams pflegen und erweitern ihr Wissen bewusst, z.B. in dem sie "continuous learning" (Kerievski 2003) anwenden.
Für Entwickler bedeutet das sowohl technische Fortbildung als auch intensive Fortbildung im Bereich der Domäne.
Diese autodidaktisch arbeitenden Team-Mitglieder bilden einen stabilen Kern, der in den kritischsten Bereichen eingesetzt werden kann.

## Knowledge Rich Design

In Modellen geht es nicht nur darum, die richtigen Substantive zu finden. Auch Aktivitäten und Geschäftsregeln bilden einen wichtigen Anteil. 
Domänen-Experten sind sich oft der Komplexität ihrer Domäne nicht bewusst, weil sie ihr Wissen leben und fließend Widersprüche und Lücken situationsbedingt auffüllen. 
Das kann Software nicht leisten. Diese Erkenntnisse müssen in einer Kooperation zwischen Entwicklern und Domänenexperten herausgearbeitet werden.

(Es folgt ein Beispiel zur Extraktion eines versteckten Konzepts.)

## Deep Models

Nützliche Modelle findet man nicht so einfach. Das Container-Liefersystem wird im Buch als Beispiel verwendet. 

Das Modell, das entwickelt wurde, hat zwar die näheren Anforderungen erfüllt, aber dennoch waren die Domänenexperten nicht wirklich zufrieden. Etwas hat gefehlt. Nach Monaten fanden wir heraus, dass Belade-, Entlade- und Bewegungsaufträge hauptsächlich von Unterauftragnehmern erledigt wurden. D.h. es fanden aus Sicht der Domänenexperten ständig Verantwortungswechsel statt. 
Oftmals fanden wichtige Schritte statt, während sich das Transportgut überaupt nicht bewegte. 

Auf der anderen Seite fanden manchmal komplexe physikalische Schritte statt, ohne dass dies für unseren Kunden interessant gewesen wäre. 

Es ging hier hauptsächlich um Verträge und Rechnungen sowie Zahlungsprozesse. Das veränderte das Modell tiefgreifend. 
Daher bedenke: Du weißt nie, wo du landen wirst.

# Communication and the use of Language

Ein Modell kann der Kern einer gemeinsamen Sprache eines Softwareprojektes werden. Diese Modellelemente sind auf der einen Seite an die Domäne gebunden und auf der anderen Seite genau genug für eine technische Implementation. 

Diese Sprache verbessert die Kommunikation über dne Code und die Tests.

Wie Sprache in einem Projekt verwendet wird ist sehr wichtig.

## Ubiquitous Lanugage (Allgegenwärtige Sprache)

Domänenexperten und Entwickler sprechen unterschiedliche Sprachen, auch wenn sie sich intensiv darum bemühen, den jeweils anderen zu verstehen.

In einem Projekt ohne eine gemeinsame Sprache wird stetig hin- und her übersetzt, was zu Informationsverlust, Missverständnissen, mehrdeutigen Begriffen und Begriffen, die unterschiedliche Teammitglieder unbewusst anders verstehen, führt.
Das wiederum führt zu Quelltext-verschlechternden Refactorings.

Benutze das Modell als Rückrad einer Sprache. Bringe das Team dazu, die Sprache rücksichtslos in Gesprächen und Quelltext zu verwenden. Glätte Schwierigkeiten durch Experimente mit alternativen Ausdrücken, die zu alternativen Modellen gehören.
Dann refaktoriere den Code, benenne Klassen, Methoden und Module um, damit sie mit dem neuen Modell übereinstimmen.
Löse Missinterpretationen in den Begriffen auf. 
Bemerke, dass eine Änderung in der Sprache automatisch eine Änderung im Modell bewirkt.

(Aktueller Stand : S. 27 / 506)
