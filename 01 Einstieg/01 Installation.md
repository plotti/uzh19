## 02 Installs

Hier installieren wir Zusatzprogramme und bereiten den Computer darauf vor, dass er in Zukunft einfacher Zusatzpakete installieren kann. Den Terminal öffnen und mit folgenden Befehlen die Software installieren. Manchmal dauern die Installs etwas lange. Geduld. Es funktioniert alles richtig. Und all das müssen wir nur einmal machen. Nicht mehr, aber auch nicht weniger.

### Weitere Install-Programme, jetzt auch für Linux

 ```pip3 install -U pip``` zur Sicherheit installieren wird noch ```pip install -U pip```. Wenn das nicht funktioniert hat versuche es mit ```sudo pip install -U pip```.


### Brew Installieren

**Mac OS X** (auf Linux sollte Python 3 schon installiert sein)

- Diese Install-Programme sind auf manchen Macs bereits vorinstalliert. Auf
anderen nicht. Zur Sicherheit einfach diesen Befehl eingeben: ```xcode-select --install```

- Mit **Homebrew** ist es einfacher, Pakete zu installieren. Der Befehl zum
Initialsetup ist etwas kompliziert. Müssen wir aber nur einmal
eingeben. ```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

- Und, damit alles etwas runde läuft, diesen Befehl:
- ```echo 'export PATH=/usr/local/bin:$PATH' >> ~/.bash_profile```
- ```source ~/.bash_profile```

- Und jetzt können wir mit Befehl Python 3 installieren: ```brew install python3```

### Git Installieren

Was ist git? Git hilft uns code von github zu ziehen. Die installation läuft einfach wenn wir erstmal brew haben.

```
brew install git
```

- Detaillierte Anleitung für Windows/Mac/Linux zur [Github-Installation](https://gist.github.com/derhuerst/1b15ff4652a867391f03). Wer mehr dazu lesen will wie git funktioniert, der findet [hier eine gute Einführung](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control).

### Unterrichtsmaterialien ziehen

Die Unterrichtsmaterialien liegen auf github. Was ist eigentlich github? Es handelt sich bei Github um die wohl grösste Ansammlung von offenem Code, den es auf der Welt gibt. Die Plattform ist so etwas wie das Facebook für Programmierer. Nur, dass hier ein System entwickelt wurde, das dafür sorgt, dass ihre Nutzer kreativ sind.  

Wie zieht man die Materialien? In die Kommandozeile gehen und dann einfach im Ordner in dem ihr es ablegen wollt wechseln 
- ```mkdir kurs```
- ```cd kurs```
- ```git clone https://github.com/plotti/uzh19.git```

### Pip Installieren

- **Pip3** ist das gängigste Install-Modul, das wir verwenden werden. Damit lassen sich python Bibliotheken installieren. Es lässt sich folgendermassen installieren:
```sudo easy_install pip```

### Jupyter Notebook installieren

- Jetzt wo wir pip haben, installieren wir noch Jupyter Notebook: ```pip install jupyter notebook```.
- Jupyter notebook ist die Umgebung in der wir unseren Code schreiben werden. 