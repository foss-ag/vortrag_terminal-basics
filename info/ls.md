ls

Listet die Informationen aller Ordner und Dateien in einem gegebenen Verzeichnis auf.
Dabei ist das aktuelle Verzeichnis das default verzeichnis.
Die sortierung ist dabei immer alphabetisch, es sei denn es wird über --sort anders spezifiziert

Interessante Argumente:
-a   (all) listet auch die versteckten Verzeichnisse (mit . vor dem Namen gekennzeichnet) auf
alternativ kann man auch -A machen um die Verzeichnisse . und .. nicht mit aufzulisten
-c   (ctime) listet die Zeit der letzten modifikation mit auf, wird allerdings dann nach dieser sortiert
es sei denn l wird mit angegeben
-f   gibt die Inhalte in unsortierter Reihenfolge aus
-g   listet wie l aber ohne owner Name, -G lässt dann auch die Gruppen weg
-h   (human readable) fasst die Größen der Dateien als leserlicher für Menschen auf
-l   (long listing format) gibt Informationen wie Rechte, den Owner, die Gruppe, die Größe, letzte modifikationszeit und Name
-m   gibt die Liste durch Kommata getrennt an
-o   gibt selbe Ausgabe wie l, aber ohne Gruppen
-r   Rekursive Auflistung
-s   (size) gibt Größe der Dateien
--sort=(var)    mit (var)= none			 , size			      , time			  , version			 , extension
			   -U (keine Sortierung) , -S (Sortierung nach Größe) , -t (Sortierung nach Zeit) , -v (Sortierung nach Version) , -X (Sortierung nach Anhang)

-1   Auflistung Zeilenweise
