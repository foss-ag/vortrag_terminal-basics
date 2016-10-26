Pipes


Pipes sind ein hilfreiches mittel um die standard Ausgabe, Eingabe oder Fehlerausgabe umzulenken, bzw genauer gesagt, die Ausgabe des einen Befehls als Eingabe für einen anderen 
zu benutzen.
Als Pipes werden als | geschrieben und bewirken, dass die Ausgabe des Befehls auf der linken Seite zur Eingabe des Befehls auf der rechten Seite wird, bevor dieser ausgeführt
wird.

Eine etwas andere Umleitung der Standardausgabe und Eingabe stellen > und < dar.
Bei >  wird die Standardausgabe des Befehls auf der linken Seite in die Datei geschrieben, die auf der rechten Seite angegeben wird.
Bsp.: ls -l > ls_out.txt    Was hier geschieht, ist, dass die Ausgabe von ls nicht wie üblich auf den Bildschirm gegeben wird, sondern in die Datei ls_out.txt geschrieben wird.
Existiert diese Datei noch nicht, so wird sie angelegt.
< Funktioniert genau anders herum, hier wird der Inhalt der Datei auf der rechten Seite als Eingabe für das Programm auf der linken Seite benutzt.
Bsp.: less < nohup.out


Hilfreich kann > besonders sein, wenn man Berechnungen durchführt und die Ergebnisse sichern möchte, z.B. wenn die Berechnung mehrere Stunden beträgt und man die Auswertung des
Geschehenen erst nachträglich machen möchte.


&

Der &-Operator ist meist bekannt als mathematisches Symbol, welches in der Informatik oft für Binäre Verundung benutzt wird (Bsp. Programmiersprachen, in C ist es ein fork).
In der Konsole allerdings hat dieser Operator eine ganz andere Bedeutung. 
wird der &-Operator hinter einem Befehl angegeben, so wird dieser Befehl im Hintergrund ausgeführt, ist nicht mehr an der Konsole fixiert. Man kann also noch in der shell weiter arbeiten
Die Standardausgabe wird automatisch immer noch in die Shell geschrieben.

Achtung!! & schickt Prozesse in den Hintergrund, && hingegen verbindet 2 Prozesse. Bsp.: prozess1 && prozess2  prozess2 wird ausgeführt, sobald prozess1 beendet ist, allerdings auch nur,
wenn prozess 1 erfoglreich beendet ist. Sollen zwei Prozesse hintereinander ausgeführt werden unabhängig davon, ob sie erfolgreich sind oder nicht, werden sie durch ein ; getrennt
Bsp.: prozess1 ; prozess2
