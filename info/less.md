# `less`
### Even more than `more`

`less` ist der intelligentere Nachfolger des Textreaders `more`.  
Neben einer Anzeige in der eigenen Ausgabe, beherrscht `less` zudem das Scrolling. Weiterhin kann das Dokument durchsucht werden und man wird nun gewarnt wenn man binaries zu lesen versucht und kann den Vorgang frühzeitig abbrechen.  

-----

##### In Kürze:  
* `less` ist eine Kreuzung aus `more` und `vi`
* `less` ist intellligent und warnt den Benutzer
* Beherrscht das freie Scrolling durch Textdateien

-----

##### Wichtige Optionen und Inline-Befehle

* `less` verwendet Pfeiltasten und Bildlauftasten zur Navigation im Dokument
* `/pattern` Durchsucht das Dokument nach dem angegebenen Muster
* `?pattern` Durchsucht das Dokument rückwärts
* `&pattern` Zeigt nur die Zeilen an in denen das gesuchte Muster vorkommt
* `n` ermöglicht das Aufrufen des nächsten Aufkommens des gesuchten Musters
* `:n` ermöglicht das Aufrufen des nächsten Textfiles wenn `less` mehrere files übergeben wurden

-----

`less` ist der Nachfolger des Programms [`more`](more.md)