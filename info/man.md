man page

Die man page ist im Prinzip eine Benutzeranleitung für das System. Es bietet zu fast allen Programmen eine kurze Erklärung.
Die Einträge sind unter /etc/manpage.config gespeichert.
Bei der Suche nach einem Programm durchsucht man alle Klassen, die wie folgt definiert sind:

       1   Executable programs or shell commands
       2   System calls (functions provided by the kernel)
       3   Library calls (functions within program libraries)
       4   Special files (usually found in /dev)
       5   File formats and conventions eg /etc/passwd
       6   Games
       7   Miscellaneous (including macro packages and conventions), e.g. man(7), groff(7)
       8   System administration commands (usually only for root)
       9   Kernel routines [Non standard]

Dabei besteht ein Eintrag einer man page immer aus unterschiedlichen Sektionen:
NAME, SYNOPSIS, CONFIGURATION, DESCRIPTION, OPTIONS, EXIT STATUS, RETURN VALUE, ERRORS, ENVIRONMENT, FILES, VERSIONS, CONFORMING TO, NOTES, BUGS, EXAMPLE, AUTHORS und SEE ALSO.

Dabei sind die für den Benutzer wohl wichtigsten Sektionen folgende: NAME (Name des Programms), SYNOPSIS (die Syntax des Programms), DESCRIPTION (Beschreibung des Programms),
OPTIONS (die Optionen, die beim Aufruf mit angegeben werden können), EXAMPLE (Beispiele; allerdings nicht immer vorhanden) und evtl BUGS (bekannte Fehler)
Die anderen Einträge haben auch ihre Relevanz, sind aber meist für den normalen gebrauch nicht ganz so interessant.

Es gibt einige Optionen, allerdings benötigt man in der Regel nur die default Einstellungen.

Es gibt sogar eine man-page für die man-page :D 

Die man-page ist ein guter Begleiter und sehr hilfreich, wenn man mal nicht weiß, wie man mit einem Befehl umgehen soll, bzw was dieser tut. Allerdings ist sie auch unglaublich
mächtig und riesig, somit kann es etwas dauern, bis man das gefunden hat, was man benötigt.
