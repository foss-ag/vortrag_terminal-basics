nice

Ausführen eines Programmes mit modifizierter sheduling Priorität. Die Nettigkeit rangiert von -20 bis 19 mit -20 als höchste Priorität und 19 als niedrigste.
Default ist 10. Erhält der Prozess eine niedrigere Priorität, benötigt aber viel Rechenleistung, können andere Benutzer an dem Gerät trotzdem noch 
ohne Beeinträchtigung arbeiten.

nice [Option] [Command] [arg] ..

interessante Argumente:

-n   (--adjustment=N) aufaddieren von Integer N auf den aktuellen Nettigkeitsgrad. Default 10

ein nachträgliches Einstellen des Nettigkeitswertes ist auch möglich

renice

renice [-n] priority [-g | -p | -u] identifier

g ist group-id, p ist process-id, u ist user-id

-n priority  ist der neue Nice-Wert, der benutzt werden soll. Wenn dieses Argument benutzt wird, muss es immer als erstes erscheinen
