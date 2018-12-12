# 1397 Building better C# Docs with Bill Wagner

Bill Wagner beschreibt die neue Microsoft Dokumentation unter http://docs.microsoft.com . 
Diese ist komplett in Markdown geschrieben und über github verfügbar. Jeder kann sich daran 
beteiligen und senden (über den üblichen Weg), wenn er möchte, einen Pull-Request.

Die Quelltextschnipsel kommen alle aus laufenden Projekten, die in der Dokumentation hinterlegt
sind, die mit Unit Tests ausgestattet ist. D.h. sie werden alle regelmäßig erneut gebaut um sicherzustellen, 
dass sie funktionieren und funktional bleiben. 

  - C#7 Pattern Matching: So eine Art Routing funktioniert damit wohl gut.

Eine weitere Methode sind "live code environments" die in der Cloud übersetzt werden.
Also eine Art jsFiddle für C# z.B. ist eingebaut.

# 1400 Rewriting Critical Code with Phil Haack

Code rewrites sollten nur dann stattfinden, wenn absehbar ist, dass die Beschaffung neuer Entwickler
immer schwieriger wird, die Wartungskosten steigen - und absehbar ist, dass dieser Trend weiter geht 
und sich verschärfen wird. 

Wenn die Wartungskosten die vorraussichtlichen Kosten der Reimplementation und dann der neuen 
Wartungskosten übersteigen lohnt es sich darüber nachzudenken. 

Eine Bibliothek zum Vergleich von Implementierungen in der produktiven Anwendung:
https://github.com/github/Scientist.net 

Über Scientist.net ist es möglich, an einer bestimmten Stelle die alte und die neue Implementation gleichzeitig 
auszuführen. Die Biblithek loggt die zeitlichen Verhalten, Exceptions, Abweichungen sowie gibt die Möglichkeit
dafür, dass sich alt und neu in bestimmten Aspekten systematisch unterscheiden dürfen.

https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/

http://githubengineering.com
