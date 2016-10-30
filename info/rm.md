# `rm`
#### Flutsch! Und weg!

Immer wieder im Leben kommt eine Zeit in der man etwas Ballast abwerfen möchte.  
`rm` hilft dabei.

-----
##### In Kürze:
* `rm` entfernt Dateien und Ordner.

-----
##### Wichtige Parameter:

* `-f, --force` es wird nicht nachgefragt und versucht alles zu löschen
* `-i` bei jeder Löschung einzeln nachfragen
* `-r` Löschung rekursiv vornehmen (Löscht Ordner und Unterordner/-dateien)
* `-d` löscht leere Verzeichnisse

-----
#### Achtung!
`rm` löscht die Dateien aus dem Verzeichnis (Ein sogenannter Unlink). Die Dateien werden damit aber **nicht** unlesbar und können wiederhergestellt werden!  
Zum Überschreiben von Dateien siehe [shred](shred.md)