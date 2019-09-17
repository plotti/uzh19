# Setup

## 01 Command Line Intro

### Start

Bevor wir loslegen, müssen wir die Commandline kennenlernen. Sie ist so etwas wie unsere Hauptsteuerungszentrum und unsere neue Maus. Von hier aus starten wir Programme, auch unsere eigenen, wir halten unsere Software uptodate und installieren neue Software.

In dieser Erklärung braucht ihr [] nicht anzuschrieben. Also ```cd [dirname]```
bedeutet, dass ihr einfach ```cd dirname```schreibt.

### Wir sind faul

* ↑ und ↓ scrollen uns zu alten Eingaben. Sehr nützlich.
* Mit ```Tab``` können Sachen autocompleted werden. Probiert es aus.
* Auf einem Mac könnte ihr auch mit Drag und Drop arbeiten, um Files und Folders hin und her zu bewegen.

### Navigation

* ```pwd```: prints working directory — zeigt uns an, wo wir uns gerade befinden.
* ```cd [dirname]```: changes directory, bewegt uns ins jeweilige Directory.
* ``cd ..``: Bewegt uns eine Stuff rauf.
* ``ls``: zeigt alle subdirectories an. ``ls -lah`` zeigt uns alles an.
* ```mv [source] [destination]``` bewegt eine Datei von A nach B
* ```cp [source] [destination]``` kopiert eine Datei an einen anderen Ort, nun habt ihr also zwei identische Kopien derselben Datei.
* ```rm [file] deletes``` zerstört eine Datei, ihr findet sie auch nicht mehr im Papierkorb
* ```mkdir [directoryname]``` Baut ein neues Verzeichnis

### Individuelle Files

* ```cat [filename]```: displays the contents of a file
* ```head -n 10 [filename]```: displays the first 10 lines of a file
* ```tail -n 20 [filename]```: displays the last 20 lines of a file

* Und **wichtig**: Mit diesem wunderbaren Zeichen kann man Befehle kombinieren: ```|```

### Escaping commands

Hat etwas nicht funktioniert? Dauert es zu lange? Dann drückt Ctrl+C, das unterbricht jeden Prozess in der Commando zeile. 