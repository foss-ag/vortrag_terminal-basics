# `head` & `tail`
### Von Kopf bis Fuß
`head` und `tail` sind interessante kleine Ergänzungen zu `cat`.  
Sie beschränken sich auf bestimmte Teile von Textfiles und eignen sich besonders zur Beobachtung von Logfiles und anderen Dateien in denen aktiv geschrieben wird.

-----
##### In Kürze:
* `head` gibt die ersten 10 Zeilen eines Textfile aus.
* `tail` gibt die letzten 10 Zeilen eines Textfile aus.

-----
##### Die wichtigsten Parameter
* `head`
    * `-n` gibt die ersten *n* Zeilen aus. (Statt 10)
    
* `tail`
    * `-n` siehe `head`
    * `-f` füge weitere Zeilen zur Ausgabe hinzu wenn das File anwächst

-----
Insbesondere `tail` beherrscht noch weitere Parameter, welche das Verhalten von `-f` beeinflussen können. Hierzu das Manual konsultieren.