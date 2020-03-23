# M300
Dokumentation des Modul 300 Plattformübergreifende Dienste in ein Netzwerk integrieren

## Inhaltsverzeichnis
* KN 01 - [KN01](## KN1)
* KN 02 - [KN02](KN2)
* KN 03 - [KN03](KN3)
* KN 04 - [KN04](KN4)
* KN 05 - [KN05](KN5)

## KN1
### Umgebung auf eigenem Notebook eingerichtet und funktionsfähig:

Zu erfüllende Kriterien:
* Virtualbox
* Vagrant
* Visualstudio-Code
* Git-Client
* SSH für Client erstellt

#### Dokumentation der Tool installationen 
##### 1. Virtualbox:
Virtual Box ist eine Virtualisierungssoftware von Oracle. Wir benutzen dieses PrograSoftware, um damit Vagrant VMs zu erstellen und zu betrieben.

VirtualBox ist sehr einfach, aber auch sehr leistungsfähig. Es kann überall laufen gelassen werden, von einem kleinen Embedded-Systemen oder Desktop-Computern bis hin zu Rechenzentrumsbereitstellungen und sogar Cloud-Umgebungen.

Auf jeder einzelnen virtuellen Maschine kann mittels Vagrant bei der automatischen Einrichtung die Software installiert werden.

Auf folgender Seite kann VirtualBox installiert werden: https://www.virtualbox.org/wiki/Downloads

![VirtualBox-InstallationBild](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/VirtualBox.PNG)

![VirtualBox-directory](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/VirtualBox_dir.PNG)

##### 2. Vagrant:
Vagrant ist ein Tool zum Erstellen und Verwalten von Umgebungen virtueller Maschinen in einem einzigen Workflow.

Vagrant bietet einfach zu konfigurierende Arbeitsumgebungen, die auf einem einzigen Workflow gesteuert werden, um die Produktivität und Flexibilität eines wiederholendes Vorgehen zu automatisieren.

Auf folgender Seite kann Vagrant installiert werden: https://www.vagrantup.com/downloads.html

Wie installiert man Vagrant?

* Die Installationsdatei muss ausgewählt und ausgeführt werden.
* Danach kann man die normale Installation durchführen und wählt den Pfad aus, wo Vagrant installiert werden soll

![VagrantImg](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/vagrant.PNG)

#### 3. Virtualstudio-Code
Visualstudio Code ist ein Editor für verschiedene Programmiersprachen. Es können Externsions installiert werden, um weitere Sprachen darin zu programmieren.

Mit dem Editor kann man eine beliebige Anzahl von Erweiterungen von Drittanbietern installieren. Während die meisten Szenarien "out of the box" ohne Konfiguration funktionieren, ist es möglich die Programme auf seine eigene individuellen Erlebnisse anzupassen. VS Code ist ein Open-Source-Projekt, so dass man auch vieles auf Github mit beitragen kann.

Auf der folgender Seite kann Visualstudio Code installiert werden: https://code.visualstudio.com/

![VScode](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/VScode.PNG)

![VScodeDir](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/VScodeDir.PNG)

#### 4. Git-Client


![GitStartmenu](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/Git_Directory.PNG)

![GitDir](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/GItWindows.PNG)

#### 5. SSH für Client erstellt

Mittels eines SSH-Keys ist es möglich auf einem Server zuzugreifen. Heute wird das SSH-Protokoll häufig verwendet, um sich von einem System in ein anderes einzuloggen, und seine starke Verschlüsselung macht es ideal, um Aufgaben wie die Ausgabe von Remote-Befehlen und die Remote-Verwaltung der Netzwerkinfrastruktur und anderer wichtiger Systemkomponenten auszuführen. Um das SSH-Protokoll verwenden zu können, müssen einige Softwarekomponenten installiert werden. Dazu führt man folgende Schritte aus.

![SSH Key](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K1/SSHkeyyGITHUB.PNG)

## KN2 
### Eigene Lernumgebung (PLE) ist eingerichtet:

Zu erfüllende Kriterien:
* GitHub oder Gitlab-Account ist erstellt
* Git-Client wurde verwendet
* Dokumentation ist als Mark Down vorhanden
* Mark down-Editor ausgewählt und eingericht
* Mark down ist strukturiert
* Persönlicher Wissenstand im Bezug auf die wichtigsten Themen sind dokumentiert (Linux, Virtualisierung, Vagrant, Versionsverwaltung / Git, Mark Down, Systemsicherheit)
* Wichtige Lernschritte sind dokumentiert

#### Dokumentation der Lernumgebung
##### 1. GitHub oder Gitlab-Account ist erstellt:
Die Leistung von Git sind im Vergleich zu vielen Alternativen sehr stark. Das Einbringen neuer Änderungen, das Branchen, Merging und Vergleichen vergangener Versionen sind leistungsoptimiert.

Um einen GitHub Account zu erstellen, öffnet man die Seite https://github.com/join?source=header-home und folgt dort die einzelnen Steps:

* Username auswählen
* Eine gültige E-Mailadresse eingeben
* Passwort eingeben
* Verifizieren, dass man kein Roboter ist

![Githubaccounterstellen](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/CreateGitHubAccount.png)

![Gihubaccount](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K2/Githubaccount.PNG)

##### 2. Git-Client wurde verwendet
Der Git-Installer kann unter folgender Seite installiert werden: https://git-scm.com/downloads

Hier eine übersicht der Commands welche für Git wichtig sind:

| Commands      | Bedeutung                                                                                                                                                        |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| git branch    | Mit diesem Befehl listet man alle Branches im eigenem Repo auf. Ebenfalls ist es möglich eigene Branches zu erstellen oder zu dem genannten Branch zu wechseln   |
| git checkout  | Mit diesem Befehl wechselt man einen Branch                                                                                                                      |
| git commit    | Damit ruft man eine Bestätigung für eine gespeicherte Aktion aus                                                                                                 |
| git clone     | Mit diesem Befehl klont man lokal ein Repository aus einem Git                                                                                                   |
| git add       | Mit diesem Befehl kann man eine Datei zum Upload hinzufügen                                                                                                      |
| git push      | Mit Git Push wird ein Upload bzw. ein Push durchgeführt                                                                                                          |

##### 3. Dokumentation ist als Mark Down vorhanden
Hier können Sie sehen dass die Dokumentation in Mark Down geschrieben wurde. 

![DokumentationMD](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/NEW_Dokumentation.PNG)

Die Dokumentation wird am Ende wenn ich sie fertig geschrieben habe auf mein Repository geladen

![DokumentationGIT](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/NEW_DoklumentationGIT.PNG)

##### 4. Markdown-Editor ausgewählt und eingerichtet
Das Markdown ist eine zusätzliche Extension, um Git Dokumentationen zu schreiben. Die Extension kann im VisualStudio Codes installiert werden.

![Markdowneditor](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K2/Markdowneditor.PNG)

##### 5. Markown ist Strukturiert

Hier sehen wir die Struktur der Mark Down Dokumentation am Anfang haben wir ein Inhaltsverzeichnis welches auf die richtigen Kapitel verlinkt in denen man am anfang die Kriterien aufgelistet sieht und darunter die dazugehörige Dokumentation mit untertiitel.

![DokumentationMD](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/NEW_Dokumentation.PNG)

##### 6. Persönlicher Wissenstand im Bezug auf die wichtigsten Themen sind dokumentiert (Linux, Virtualisierung, Vagrant, Versionsverwaltung / Git, Mark Down, Systemsicherheit)

##### Linux
Im bereich Linux habe ich bis jetzt nur private Erfahrung und das Wissen der Schule. Im Betrieb habe ich noch nie mit Linux gearbeitet. Jedoch habe ich seit langem auf meinem Notebook Linux installiert und arbeite seit je her fast täglich damit. Somit kenne ich einige Ticks und kenn mich gut in der Umgebung aus. Da ich Parrot Linux habe, habe ich auch etwas übung in der Systemsicherheit mit Linux

##### Virtualisierung
Mit Virtualisierung habe ich noch nicht oft gearbeitet im Betrieb aber dafür oft in der Schule und  auch etwas im privaten Umfeld. Somit habe ich auch dort etwas Erfahrung welche aber bei weitem noch nicht alles abdeckt und sich noch entwickelt.

##### Vagrant
Mit Vagrant habe ich bisher noch nie gearbeitet und ich tue mich sehr schwer mich mit dem Thema anzufreunden. Es ist sehr kompliziert aber ich versuche mich langsam ran zu tasten. Leider habe ich keine Möglichkeit gehabt im Betrieb Vagrant noch anzusehen wegen einer Menge Arbeit. In der Schule hatten wir auch noch nie Vagrant und ich finde es sollte schon früher den Schülern beigebracht werden da es sehr kompliziert ist.

##### Versionsverwaltung / Git
Mit Git habe ich erst einmal gearbeitet. Dies war ein kleines Projekt in der Firma wo wir einige Befehle in Git umsetzen mussten. Dazu musste ich privat mal darüber einen SSH key erstellen dies war jedoch anfangs Lehre.

##### Mark Down
Mit Mark Down habe ich etwas mehr Erfahrung da ich im Betrieb oft damit arbeite um Dokumentationen zu schreiben. Ich habe vor ungefähr einem halben Jahr das erst mal Mark Down gehabt und schreibe seit dem öfters im Betrieb damit.

##### Systemsicherheit
In der Systemsicherheit habe ich etwas mehr Erfahrung da ich in der als Security Analyst arbeite. Ich habe vor einem halben Jahr in der Abteilung angefangen und arbeite auf meinen Lehrabschluss in der Security hin. Deshalb bin ich nicht schlecht in diesem Bereich unterwegs was die Erfahrung angeht.


##### 7. Wichtige Lernschritte sind dokumentiert


## KN3
### Vagrant:

Zu erfüllende Kriterien:
* Bestehende vm aus Vagrant-Cloud einrichten
* Kennt die Vagrant-Befehle
* Eingerichtete Umgebung ist dokumentiert (Umgebungs-Variablen, Netzwerkplan gezeichnet, Sicherheitsaspekte)
* Funktionsweise getestet inkl. Dokumentation der Testfälle
* andere, vorgefertigte vm auf eigenem Notebook aufgesetzt
* Projekt mit Git und Mark Down dokumentiert

#### Dokumentation 
##### 1. Bestehende vm aus Vagrant-Cloud einrichten:
1. Um die bestehende Vagrant VM zu starten muss man zuerst den Repo vom Modul klonen


```
git clone https://github.com/YongYong01/M300-1.git
```


2. Danach exploriert man in das Verzeichnis der VM


```
cd D:\M300_LokalesRepository\VagrantBoxVM
```


3. Die Vagrant VM startet man mit folgendem Befehl


```
vagrant up
```


![vagrantup](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/VagrantupUnbenannt.PNG)

4. Man kann auf die VM per SSH zugreifen


```
vagrant ssh
```


![vagrantssh](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/VagrantSSh.PNG)

 #### 2. Kennt die Vagrant-Befehle

Hier sind die Vagrant Befehle welche man häufig benötigt und wärend dem projekt braucht:

| Commands            | Bedeutung                                           |
|---------------------|-----------------------------------------------------|
| vagrant box add	  | fügt eine Vagrant Box dazu                          |
| vagrant box list    | listet alle verfügbaren Vegrant Boxen auf           |
| vagrant init        | erstellt ein neues Vagrant File in dem Verzeichnis  |
| vagrant up          | erstellt mit dem Vagrant File im Verzeichnis die VM |
| vagrant ssh         | mit diesem Befehl greift man mit SSh auf die VM zu  |
| vagrant halt        | stoppt die VM                                       |
| vagrant destroy     | stppt und zerstört die Vm                           |

##### 3. Eingerichtete Umgebung ist dokumentiert (Umgebungs-Variablen, Netzwerkplan gezeichnet, Sicherheitsaspekte)



##### VM mit eigenem Vagrant Fileaufsetzen
Hier dokumentiere ich wie ich mene eigene VM-Umgebung aufgesetzt habe. Ich möchte mit einemVagrantfile einige VMs erzeugen, welche auch miteinander kommunizieren können. Dies alles wird im Netzwerkplan ersichtlich dieser befindet sich am Ende dieses Abschnitts.

1. Gehen wir in dir directory meines Repositorys


```
D:\M300_LokalesRepository\eigenesprojekt\VM2
```


2. Danach erstellt man ein leeres Vagrantfile und gibt ein Betriebssystem an


```
vagrant init debian/jessie64
```


##### Vagrantfile

Nun muss man die Konfigurationen und Modifikationen der VM im Vagrantfile definieren und coden. Hier werde ich mein Vagrantfile zur selbst erstellten VM websrv01 etwas ausführen.

Das erst im Vagrantfile ist der anfang der Konfigurationsdatei. Dieser sieht so aus:


```
Vagrant.configure("2") do |config|
```


Als nächstes folgt diese definiert eine virtuelle Maschine in diesem Fall "websrv01"


```
config.vm.define "websrv01" do |websrv01|
```


Jetzt kommt die definierung des Hostnamens der VM. Danach folgen noch weitere konfigurationen der VM, diese sind im Vagrantfile oben ersichtlich.


```
websrv01.vm.hostname = "websrv01"
```


Weiter unten finden wir dann noch den Parameter nmit dem wir die freigegebenen Ports bestimmen können in diesem Fall jeglichen HTTp/HTTPS-Traffic


```
web01.vm.network "forwarded_port", guest:80, host:8080, auto_correct: true?
```



```
web01.vm.network "forwarded_port", guest:443, host:4343, auto_correct: true
```


Normalerweise wird bei jeder VM ein NAT-Adapter eingerichtet. Man kann auch mit Netzwerk Parametern zusäziche Netzwerkadapter einrichten.hier habe ich es mit einer C Klasse IP erstellt. Somit können die VMs auch untereinannder kommunizieren.


```
web01.vm.network "private_network", ip: "192.168.1.10"
```


Mit dem Provider-Parameter können wir den Namen & Memory angeben.


```
web01.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
    vb.name = "web01"
end
```

Mit dem Provider-Parameter können wir aber auch die VM weiter Konfigurieren so wie ich. Das Script (werbsrv01) mit dem ich dies gemacht habe sehen sie oben im Repository.

```
web01.vm.provision "shell", path: "web01.sh"
``` 

Das Vagrantfile mit "end" am schluss speichern und schliessen.

##### Netzwerkplan

##### Umgebungsvariabeln

Hier ganz unten sehen wir die Umgebungsvariabeln und welche hinzugefügt wurden.

![umgebugsvariabeln](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K2/Umgebungsvariable.PNG)

##### 4. Funktionsweise getestet inkl. Dokumentation der Testfälle



##### 5. andere, vorgefertigte vm auf eigenem Notebook aufgesetzt

Man kann von der Seite https://app.vagrantup.com/boxes/search?utf8=%E2%9C%93&sort=downloads&provider=&q= verschiedene VM Boxen herunterladen, um einzelne Vagrantmaschinen zu installieren und einzurichten.

1. Mit dem folgenden Befehl kann man die Debian Box installieren

![Debianinstall](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/Debian1.PNG)

2. Nun erstellt man ein eigenes Vagrantfile damit man die VM einrichten kann

![Debianvagrantfile](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/Debian2.PNG)

3. Wenn man dies gemacht hat kann man nun das Vagrantfile anpassen und somit die Konfiguration anpassen

![Debianfiledir](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/Debian3.PNG)

##### 6. Projekt mit Git und Mark Down dokumentiert
YES!

## KN4
### Sicherheitsaspekte sind implementier:

Zu erfüllende Kriterien:
* Firewall eingerichtet inkl. Rules
* Reverse-Proxy eingerichtet
* Benutzer- und Rechtevergabe ist eingerichtet
* Zugang mit SSH-Tunnel abgesichert
* Sicherheitsmassnahmen sind dokumentiert
* Projekt mit Git und Mark Down dokumentiert

#### Dokumentation 
##### 1. Firewall eingerichtet inkl. Rules

##### Was ist eine Firewall?

Eine Firewall ist nichts weiter als eine Netzwersicherheitsvorrichtung, die den ein- und ausgehenden Netzwerkverkehr überwacht und darauf hin bestimmt ob der Datenverkehr zugelassen oder abgeblockt werden soll.

##### Was ist ufw

ufw ist das Standard-Firewall-Konfigurationstool für Ubuntu. Es wurde entwickelt umd die Kofiguration von iptables und Firewalls zu erleichtern und man kann damit eine IPv4 und/oder eine IPv6 Host basierte-Firewalls erstellen.

Hier eine Übersicht über die ufw Commands:

| Commands            | Bedeutung                                           |
|---------------------|-----------------------------------------------------|
| ufw status	      | zeigt den Status der Firewall an                    |
| ufw enable          | Aktiviert die Firewall                              |
| ufw disable	      | 	Deaktiviert die Firewall                        |
| ufw allow           | Öffnet einen Port                                   |
| ufw deny            | Blockiert einen Port                                |
| ufw reject          | Blockiert einen Port ausserhalb (Absender)          |


##### 2. Reverse-Proxy eingerichtet
Ein Reverse Proxy holt Ressourcen von einem oder mehreren Servern. Ein Reverse-Proxy verbirgt sich normalerweise hinter der Firewall und leitet Anfragen von außen an die Backend-Server des internen Netzwerkes weiter. 

Der Proxy wurde so eingerichtet:
```
#Configure Reverse-Proxy
sudo apt-get install libapache2-mod-proxy-html -y
sudo apt-get install libxml2-dev -y

sudo a2enmod proxy
sudo a2enmod proxy_html
sudo a2enmod proxy_http

sudo service apache2 restart
```
![ReverseProxy]()

##### 3. Benutzer- und Rechtevergabe ist eingerichtet
um einen User zu beidenen benötigen wir einige Commands welche für die Benutzereinrichtung. Hier sehen wir einen Überblick über die wichtigsten

| Commands            | Bedeutung                                           |
|---------------------|-----------------------------------------------------|
| id	              | Informationen über User                             |
| adduser             | Einen User erstellen und zu einer Gruppe hinzufügen |
| usermod	          | 	Einen User zu einer Gruppe hinzufügen           |
| groupmod            | Gruppe modifizieren                                 |
| deluser             | Einen User von einer Gruppe entfernen               |
| addgroup            | Gruppe erstellen                                    |

Arbeitet man in einem Team mit mehreren Funktionen auf einem System kann es durchaus Sinn ergeben einge gewisse Gruppe zu ertellen. Dafür kann man beim Apache die Dateo www-data Group. Diese wird automatisch installiert. Diese Gruppe kann man anwenden um vollen Zugriff auf alle Apache Konfigurationsdateien zu vergeben.

Die Berechtigungen können wir nomal verteilen. Dabei helfen uns die Basics

Lesen (R): Die Leseberechtigung ermöglicht es eine Datei zu öffnen und zu lesen. Diese Berechtigung für ein Verzeichnis ermöglicht es den Inhalt aufzulisten

Schreiben (W): Lässt den Benutzer den Inhalt der Datei zu ändern. Diese Berechtigung in einem Verzeichnis  erlaubt es gespeicherte Dateien hinzuzufügen, entfernen und umzubenennen.

Ausführen (X): Mit dieser Berechtigung lässt sich ein Script oder ein Programm ausführen. 

| Commands            | Bedeutung                                           |
|---------------------|-----------------------------------------------------|
| chmod	              | Dateirechte anpassen                                |
| chown               | Dateibesitzer ändern                                |
| chgrp	              | Dateigruppe ändern                                  |

Ordner und Files hatben jeweils verschiedene Berechtigungsgruppen. Der erste Buchstabe definiert den Dateity. Die nächsten Drei sind für User Group und arndere. Hier noch ein Bild zur erklärung. 

![Rechte](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/222_ReverseProxy.PNG)

##### 4. Zugang mit SSH-Tunnel abgesichert
Damit SSH funktioniert benötigt man einen SSH Server. diesen installiert man wie folgt:

1. Server installieren
```
sudo apt-get install openssh-server
```

2. Firewall auf SSH überprüfen
```
Netstat -tulpn
``` 
3. danch Port 22 auf Listen überprüfen

![Port](https://github.com/crigcsus2001/M300_TBZ/blob/master/images/K3/222_Port.PNG)

4. Zuletzt noch den Service starten
```
service ssh start
```

Diese Einstellungen kann man im Vagrant vordefinieren.

##### 5. Sicherheitsmassnahmen sind dokumentiert


##### 6. Projekt mit Git und Mark Down dokumentiert
YES!

## KN5
### Zusätzliche Bewertungspunkte:

Umsetzung eigener Ideen:
* Übungsdokumentation als Vorlage für Modul-Unterlagen 
* Authentifizierung und Autorisierung via LDAP
* Cloud-Integration (Einsatz einer IaaS-Umgebung)
Persönliche Lernentwicklung:
*  Vergleich Vorwissen - Wissenszuwach
*  Reflexion

#### Dokumentation 
##### Vergleich Vorwissen - Wissenszuwachs
##### Linux
Vorher:     Im bereich Linux habe ich bis jetzt nur private Erfahrung und das Wissen der Schule. Im Betrieb habe ich noch nie mit Linux gearbeitet. Jedoch habe ich seit langem auf meinem Notebook Linux installiert und arbeite seit je her fast täglich damit. Somit kenne ich einige Ticks und kenn mich gut in der Umgebung aus. Da ich Parrot Linux habe, habe ich auch etwas übung in der Systemsicherheit mit Linux

Jetzt: Mein Linux wissen hat sich nicht besonders stark verändert. Vielleicht sind einige Befhele wieder aufgefrischt geworden.

##### Virtualisierung
Vorher:     Mit Virtualisierung habe ich noch nicht oft gearbeitet im Betrieb aber dafür oft in der Schule und  auch etwas im privaten Umfeld. Somit habe ich auch dort etwas Erfahrung welche aber bei weitem noch nicht alles abdeckt und sich noch entwickelt.

Jetzt: Jetzt kann ich durchaus stellung nehmen zur Virtualisierung und konnte durch die ganzen Erfahrungen kahm ich sehr viel weiter und kann nun gut mit der Virtualisierung arbeiten

##### Vagrant
Vorher:     Mit Vagrant habe ich bisher noch nie gearbeitet und ich tue mich sehr schwer mich mit dem Thema anzufreunden. Es ist sehr kompliziert aber ich versuche mich langsam ran zu tasten. Leider habe ich keine Möglichkeit gehabt im Betrieb Vagrant noch anzusehen wegen einer Menge Arbeit. In der Schule hatten wir auch noch nie Vagrant und ich finde es sollte schon früher den Schülern beigebracht werden da es sehr kompliziert ist.

Jetzt: Vagrant finde ich immernoch sehr schwer aber mit der Zeig kommt es immer besser 

##### Versionsverwaltung / Git
Vorher:     Mit Git habe ich erst einmal gearbeitet. Dies war ein kleines Projekt in der Firma wo wir einige Befehle in Git umsetzen mussten. Dazu musste ich privat mal darüber einen SSH key erstellen dies war jedoch anfangs Lehre.

Jetzt: Mit Git kenne ich mich sehr gut aus mittlerweile. Aber das liegt auch daran, dass es auch an Linux angelehnt ist. 

##### Mark Down
Vorher:     Mit Mark Down habe ich etwas mehr Erfahrung da ich im Betrieb oft damit arbeite um Dokumentationen zu schreiben. Ich habe vor ungefähr einem halben Jahr das erst mal Mark Down gehabt und schreibe seit dem öfters im Betrieb damit.

Jetzt: Mark Down fällt mir jetzt sehr leicht ich kann die meisten Dinge auswendig und hatte nie grosse Probleme damit.

##### Systemsicherheit
Vorher:     In der Systemsicherheit habe ich etwas mehr Erfahrung da ich in der als Security Analyst arbeite. Ich habe vor einem halben Jahr in der Abteilung angefangen und arbeite auf meinen Lehrabschluss in der Security hin. Deshalb bin ich nicht schlecht in diesem Bereich unterwegs was die Erfahrung angeht.

Jetzt: Gleich wie zuvor, kurze Auffrischung von Themen und praktische Umsetzung konnten mir noch das ein oder andere codestück helfen.

##### Reflexion

In diesen Punkten konnte ich mich sehr gut verbessern in diesem Projekt:
* Linux-Services
* Shell Scripts
* Vagrant
* Umgang mit der CLI
* GIT Bash

Ich habe noch nie mit Vagrant gearbeitet. und Darum fand ich diese LB sehr schwer alleine zu machen aber auch sehr interessant und ich bin Froh dass ich meine Erkenntnisse so aufbessern konnte. Dieses Projekt hat nicht Spass gemacht, im gegenteil ich fand es zu mühsam und zu langweilig aufgebaut. Ich hoffe die LB 3 wird interessanter und weniger. Denn es war sehr viel arbeit.
