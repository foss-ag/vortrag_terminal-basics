stdin (Standard Input)  stdout (standard Output)  stderr (Standard Error Output)
number: 0               number: 1                 number: 2

Jedes Programm, dass ausgeführt wird hat automatisch 3 Datenströme, die damit verbunden sind (s.o.).
Standard Input ist die Eingabe des Programmes
Standard output ist die Ausgabe des Programmes (default: Konsole)
Standard error ist die Fehler Ausgabe (default: Konsole)

Input und Output können mit >,< und | verwändert werden

Um die Ausgabe der Fehler umzuleiten muss die Nummer des Streams mit angegeben werden also statt > wird dann geschrieben 2>

Wenn wir die Fehlerausgabe und die Standardausgabe in einer Datei haben wollen, dann muss die Fehlerausgabe auf die Standardausgabe geleitet werden:
process > output_file 2>&1  Zuerst wird die Ausgabe des processes wie immer auf die Datei gelegt, dann wird die Ausgabe des Streams 2 auf den Stream 1 gelegt
dies geschieht durch angeben des & vor der Stream Nummer.
