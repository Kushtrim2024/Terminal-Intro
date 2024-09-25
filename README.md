# Terminal-Intro

|**Linux Terminal Befehl**|**Erklärung**|
|-------------------------|-------------|
|rm                       |Der Befehl rm löscht **unwiderruflich** Dateien. 
Nützliche Flags:

    -f steht für force (erzwingen) und erzwingt etwas. Im Fall von rm -f das Löschen der Datei
    -r steht für recrusive (rekrusiv) und muss beim Löschen von Ordnern angegeben werden, damit wird gesagt, dass alles, auch im Ordner gelöscht werden soll. Beispiel: rm -r ordnerA löscht alles im OrdnerA inklusive diesen.

Beispiel Kombination Flag -r und -f

In diesem Beispiel lösche ich ein Verzeichnis rekursiv (-r) UND bestätige (-f) das alles im Ordner gelöscht werden soll.

    rm -rf /home/marcuswoy/dasVerzeichnisLoeschen
