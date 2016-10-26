htop

htop ist ein interaktiver Prozess Viewer

-ist meist nicht standardmäßig installiert
-es gibt eine nicht interaktive Alternative, die immer installiert ist:  top
-htop zeigt an: Auslastung der einzelnen CPU kerne und Arbeitsspeicher, Anteil des Swap, bisherige Laufzeit des PCs
-für Prozesse wird angegeben: Prozess ID (PID), der zugehörige Benutzer (User), Priorität: Nice-Wert + 20 (PRI), Nice Wert (NI), VIRT genutzter Virtueller Speicher,
    RES genutzter physischer Speicher, SHR größe der Prozess geteilten Pages, S ist der State (S=Sleeping, R=Running, D=Disk Sleep, Z=Zombie, T=Traced/Suspended, W=Paging),
    CPU% Anteil an genutzter CPU Zeit, MEM% Anteil an genutztem Speicher, TIME+ ist die Zeit, die das Programm bisher läuft, Command ist das Programm selber gegeben als Kommando

Aktionen in htop:
	-Help selbsterklärend ;)
	-Setup Modifizieren der Anzeige (Farbe, was angezeigt werden soll, etc.)
	-Search Suche nach Prozess, dabei wird die Auswahl entsprechend beim Tippen angepasst
	-Filter Filtern der Ansicht nach Prozessen, die dem Filter entsprechen
	-Tree Anzeige als Baum, mit entsprechender Hiarchie
	-SortBy Sortieren der Prozesse
	-Nice- Prozess höhere Relevanz geben (nur super user)
	-Nice+ Prozess niedrigere Relevanz geben
	-Kill ausgewähöten Prozess beenden
	-Quit selbsterklärend ;)

Options:

	-d --delay=DELAY Delay zwischen dem Updaten
	-C --no-color htop ohne Farbe
	-h (Help) zeigt mögliche Optionen
	-p --pid=PID,PID,...   zeigt nur Prozesse mit gegebener PID an
	-u --user=USERNAME  zeigt nur Prozesse des gegebenen Benutzers  
