# `grep`
### Schnapp dir den String!

-----
##### In Kürze:
* Durchsucht eine Eingabe nach einem regulären Ausdruck (RegEx) oder Wort
* Ohne Parameter wird die gesamte Zeile in der ein Ausdruck vorkam ausgegeben.

-----
##### Die wichtigsten Parameter:
* **Matcher Selektoren**
    * `-E` Interpretiert das Suchwort als erweiterten regulären Ausdruck
    * `-F` Interpretiert das Suchwort als fixed Strings
    * `-G` Interpretiert das Suchwort als basic regular Expression
    * `-P` Interpretiert das Suchwort als Perl-kompatiblen RegEx

* **Matching Kontrolle**
    * `-f FILE` Liest die RegEx aus einer Datei aus
    * `-v` Invertiert das Matchmaking und gibt daher alle Zeilen **ohne** den RegEx aus
    * `-w` Gibt nur Zeilen aus, in denen ganze Worte dem RegEx entsprechen
    * `-x` Gibt nur Zeilen aus, welche komplett dem RegEx entsprechen

* **Output Kontrolle**
    * `-c` Unterdrückt die normale Ausgabe und zählt stattdessen die Aufkommen der RegEx
    * `-o` Gibt allein die gematchten Teile einer Zeile statt der ganzen Zeile aus
    * `-q` Still; Keine Ausgabe; Das Programm terminiert mit ExitCode 0 sobald ein Match gefunden wurde.

-----
Besonders gern beim Piping verwendet.  
Die Auflistung der Parameter ist nicht erschöpfend. `grep` beherrscht noch viele weitere Parameter und Anzeige/Suchmöglichkeiten. Dazu bitte eigenständig das Manual oder Tutorials konsultieren.