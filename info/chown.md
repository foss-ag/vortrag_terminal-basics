## chown
wird benutzt, um Besitzer von Dateien/Ordnern zu verändern. Zu jeder Datei gehören zwei Besizter: 
- einer vom Typ Nutzer
- einer vom Typ Gruppe
Wie bei normalen Rechten für die Datei selbst muss auch hier das Schreibrecht für den Ordner oder die Datei vorhanden sein.
#### Bespiel
chown *Nutzer* *datei* # datei gehört jetzt dem Nutzer *Nutzer*
chown *Nutzer*:*Gruppe* *datei*

#### Parameter
- -R Alle Dateien und Ordner rekursiv ändern. Ohne wechselt nur der entsprechende Ordner den Besitzer / Gruppe
