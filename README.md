YADM - Yet Another Disposable Mail (Service)
====

Der YADM wurde mit dem Play Framework 2.0 erstellt (http://www.playframework.org/).
Bevor die Serverumgebung gestart wird, sollten die Domain/Host Namen unter denen der MailServer arbeiten soll, gesetzt werden.
Hierf�r muss in der Datei conf/initdata.conf der folgende Eintrag gesetzt werden:
yadm.domains=test1,test2

Desweiteren muss noch f�r die Versendung von internen Mails wie z.b. 'Forgoten Password' die Dom�ne gesetzt werden:
yadm.domain=localhost

Um die Serverumgebung zu start, muss aus dem Ordner 'yadm' das 'play' Kommmondo aufgerufen werden (http://www.playframework.org/documentation/2.0.4). 