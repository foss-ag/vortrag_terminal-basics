tar

tar wird genutzt um Archive anzulegen bzw zu entpacken.

tar [Option] [path]

Optionen:
	-A  (Concatenate) fügt .tar Dateien einem Archiv hinzu
	-c  (create) erzeugt ein neues Archiv
	-d  (difference) Sucht Unterschiede zwischen zwei Archiven
	-r  (append) fügt Dateien an das Ende einer .tar Datei an
	-t  (list) Listet die Inhalte einer .tar Datei auf
	-x  (extract) extrahiert eine .tar Datei
	-j  (bzip2 format) 
	--overwrite Überschreiben der bereits existierenden Dateien beim extrahieren
	-v  (verbose) Listet den Vortschritt beim Extrahieren auf
	-z  (gzip format) im Prinzip komprimieren der Dateien
	-f  erzeugt Ordner mit Namen von Archiv und entpackt dort
