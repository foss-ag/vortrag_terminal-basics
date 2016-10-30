# `mkdir.md`
#### Wie man einen Ordner erstellt

`mkdir` erstellt auf Anforderung Ordner auf dem Rechner.  
Standard ist es `mkdir` den Ordnernamen als Parameter mit anzugeben um im aktuellen Verzeichnis einen Unterordner zu erstellen. Aber auch ganze Pfadstrukturen kann `mkdir` erstellen wenn man möchte.

-----
##### In Kürze:
* `mkdir` erstellt Ordner.

-----

##### Wichtige Parameter
* `<Directory>` der zu erstellende Ordner/Pfad
* `-p, --parent` erstellt auch Überordner, falls sie nicht existieren
* `-m, -mode=` der Modus unter dem der Ordner erstellt wird, siehe [`chmod`](chmod.md) 