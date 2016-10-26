cd  - change directory

Der wohl am meisten Benutzte Command in der Konsole. Mit diesem Befehl ist es möglich sich durch die Dateistruktur des Systems zu navigieren.

eigenes home directory wird durch ~ abgekürzt. Allerdings ist es nicht nötig diese zu benutzen, wenn man in das home directory zurück kehren möchte, es reicht cd
Ist das erste Zeichen nach dem cd ein / dann wird vom root Verzeichnis begonnen. wird das / weg gelassen und gibt direkt den Ordner an, in den man möchte, so wird
ausgehend von der aktuellen Position verfahren.

Will mann in der Ordnerstruktur eine Ebene in das parent directory aufsteigen, so kann man dies via cd ../ tun das ../ kann bis zur root Ebene beliebig oft verwendet werden

cd hat Attribute(Optionen), die allerdings so gut wie nie benutzt werden:

-L   will man über einen symbolischen Link in einen Ordner navigieren, so wird dies über diese Option ermöglicht. Dies ist default Einstellung.
-P   hierbei wird symbolischen Verlinkungen nicht gefolgt
-e   kann nur in Verbindung mit -P verwendet werden und sagt dem System, dass wenn etwas beim Navigieren schief geht, gebe Fehler aus

funfact: cd .     wechselt uns in unser aktuelles Verzeichnis. Es ändert sich also nichts. Es tut praktisch nichts, aber dafür sehr gut
