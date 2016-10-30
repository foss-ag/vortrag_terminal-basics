# `mv` & `cp`
### Die Macht verwenden, und: Wie man Klone erstellt

`mv` und `cp` sind nach `cd` eure Lieblingsprogramme im Umgang mit Dateien und Ordnern. Sie ermöglichen es euch, Dateien zu verschieben oder sie zu kopieren.  
Dabei sind die Beiden echte Tausendsassa, denn es steckt noch mehr unter der Haube.

-----
##### In Kürze:
* `mv` verschiebt Dateien und Ordner und kann sie auch umbenennen
* `cp` kopiert Dateien, Ordner und ganze Ordnerstrukturen

-----
##### Die wichtigsten Parameter:
* `mv`
    * `<Quelle> <Ziel>` die geforderten Parameter von mv
    * `-i, --interactive` fragt vor dem Überschreiben
    * `-f, --force` überschreibt **immer**
    * `-n, --no-clobber` überschreibt **niemals**
    * `--backup` erstellt Backups von bestehenden Zieldateien bevor sie überschrieben werden
    * `-S, --suffix=` gibt ein alternatives Suffix für backup-Dateien an. (Standard: "~" )

* `cp`
    * Dieselben wie `mv`
    * `-r, --recursive` ermöglicht es, Ordner zu kopieren
    * `-s, --symbolic-link` erstellt symbolische Links anstatt Dateien