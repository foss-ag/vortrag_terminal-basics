#mount umount
Geräte manuell einhängen. Der Ordner, in den eingehängt werden sollen. Der Ornder muss existieren.
Sollte der Ordner nicht leer sein, kann in der Zeit nicht darauf zugegriffen werden. 
Erst, wenn mit umount der entsprechende Teil ausgehängt wurde, ist der alte Inhalt wieder sichtbar.

### Beispiel:
mount /dev/sdb1 /media/backup  #die erste Partition vom Gerät sdb in Ordner /media/backup hängen
