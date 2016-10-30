# `shred`
#### RRRRRRRRRRRRRTTZZZZZZZZZZ! Und ganz weg!

Immer wieder im Leben kommt eine Zeit in der man etwas Ballast abwerfen möchte und dabei sicher sein will dass niemand mehr mitlesen kann.  
`shred` hilft dabei.

-----
##### In Kürze:
* `shred` überschreibt Dateien.

-----
##### Wichtige Parameter:

* `-f, --force` es wird versucht Schreibrechte zu erlangen, falls nötig
* `-n` die Anzahl der Schreibvorgänge pro Datei
* `-u` Löschung nach dem Überschreiben vornehmen
* `-z` Nullen beim letzten Vorgang verwenden um das Überschreiben zu verbergen.

-----
#### Achtung!
`shred` stellt nicht sicher dass Backups von Dateien mitgelöscht werden. Dies kann auch bei Journaling (Wie bei ext3/4 verwendet) dazu führen dass die Dateien wiederhergestellt werden können obwohl das Shredding erfolgreich war!
Zum einfachen Löschen von Dateien siehe [rm](rm.md)