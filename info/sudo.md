# `sudo`
### Aus großer Macht folgt große Verantwortung

**S**uper**U**ser**DO** ist das wohl eines der meistverwendeten Programmen in der Linuxwelt.  
Systemweite Änderungen, Manipulation von Systemdateien, Starten systemweiter Prozesse ist nur mit root-Rechten möglich. `sudo` ist hier das Mittel der Wahl.

-----
##### In Kürze:
* `sudo` erhöht die Berechtigungen des Benutzers für einen übergebenen Vorgang unter Angabe seines Passworts
* Die Einmaligkeit, dass kritische Änderungen im und am System nur mit sudo ermöglicht werden, sorgen für mehr Sicherheit
* `sudo` verleiht besondere Rechte, welche mit Vorsicht genutzt werden müssen!

-----
##### Die wichtigsten Parameter:
* `-b` führt den angegebenen Befehl im Hintergrund aus (Vorsicht mit interaktiven Programmen!)
* `-e` Kopiert das angegebene File temporär und öffnet den Standardeditor des Benutzers. Nach erfolgtem Editieren wird das neue File zurückkopiert und überschreibt das alte File
    * Diese Methode ist besonders bei Systemkonfigurationen zu empfehlen, da sie Datenverlust vorbeugt
    * Sollte ein normales File editiert werden, ist `root` danach der neue Besitzer
    * Dieser Parameter kann auch direkt mit dem Befehl `sudoedit` impliziert werden 
* `-i` Übergibt root die .profile oder .login des ausführenden Benutzers
    * Übergebene Befehle werden im Environment des ausführenden Benutzers ausgeführt
    * Ohne mit `-c` übergebenem Befehl wird eine interaktive `root`-Shell geöffnet
* `-s` öffnet eine Shell
* `-u USER` führt den Befehl als den angegebenen Benutzer aus. Mit `-i` oder `-s` wird eine Shell unter diesem Benutzer geöffnet

-----
