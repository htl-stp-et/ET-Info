# Lizenz/Installation 
Die Lizenz wird beim Administrator beantragt ('''H. Frank Abt. ET''').
Für den Administrator folgende Information erforderlich:

    Familienname, Vorname, email-Adresse der htlstp.at-Domain.

Also beispielsweise Reschauer Erwin erwin.reschauer@htlstp.at
Falls Lizenzen für mehrere Personen (bspw. ganze Klasse) angefordert werden: Am besten eine Liste an helge.frank@htlstp.at senden, wo die Daten in oben genannter Reihenfolge eingetragen sind.

**Unbedingt die email-Adresse auf Korrektheit überprüfen.**

Der Administrator trägt die Daten im License-Center ein. Danach erhält der user, nach wenigen Minuten, automatisch ein email mit den Zugangsdaten.
Die Aktivierung sollte bald nach Erhalt der email erfolgen, da die Zugangsdaten nach einiger Zeit wieder verfallen.
Wir verfügen über die License Number 40418416 (Primary and Secondary School).
Jeder user darf Matlab auf beliebig vielen Rechnern installieren, unter Einschränkung der kommerziellen Nutzung.
Die Installation dauert, je Bandbreite der Internetverbindung etwa eine Stunde. Der Speicherbedarf auf der Festplatte beträgt, so man alle Toolboxen installiert (die gewünschten Toolboxen können bei der Installation ausgewählt werden) derzeit über 16GB.

Das Lehrpersonal empfiehlt zur Speicherplatzschonung NICHT alle Toolboxen zu installieren. Empfohlen werden die Packete
* MATLAB
* Simulink
* Audio System Toolbox
* Communications System Toolbox
* Control System Toolbox
* Curve Fitting Toolbox
* DSP System Toolbox
* Embedded Coder
* Instrument Control Toolbox
* MATLAB Coder
* MATLAB Compiler
* MATLAB Report Generator
* Simulink Coder
* Simulink Desktop Real-Time
* Simulink Report Generator
* Symbolic Math Toolbox
* System Identification Toolbox

Die Installation muss nicht notwendigerweise über Internet erfolgen. Es können auch Datenträger erstellt werden (einige DVDs erforderlich) und ein Licence-File generiert werden. Die Files können nach Einloggen auf den user-Account downgeloaded werden.

[zum Licensecenter von Mathworks](https://de.mathworks.com/licensecenter/licenses/40418416/)

## Installations-Images im lokalen Netzwerk 
<pre>
//10.32.1.20/daten/daten/software/Lizenz-SW/Matlab/R2018bDiskImages
</pre>
* Benutzer: htl
* Passwort: htl
* Die beide ISO-Images auf die lokale Festplatte kopieren und dann von dort das erste ISO-Image durch Doppelklick im Explorer öffnen
* Installation mit **setup** starten
  * Lizenz Online über Account
  * Packete auswählen (im Zweifelsfall alle)
* Wechseln der DVD im Explorer wenn das Setup-Programm dazu auffordert
  * Auswerfen der ersten DVD
  * Einlegen der zweiten DVD
  * Continue im Setup-Programm

# Tutorial 

* [Online Kurs zum Erlernen der Matlab Basics "Onramp"](https://matlabacademy.mathworks.com/)
* [Matlab Grundlagen](https://www-m11.ma.tum.de/fileadmin/w00bnb/www/people/karpfinger/MATLAB-Tutorial.pdf)

# Links 
* [https://de.mathworks.com/](https://de.mathworks.com/)

# Installation von Hardware-Support-Packages 
### Arduino Simulink im Schulnetzwerk 
* Im Explorer verbinden mit \\10.32.1.20\daten (Benutzer: htl, Passwort: htl)
* Installation in der Windows-Commandline (cmd)
<pre>
mkdir c:\\tmp
rmdir /S /Q c:\\tmp\\matlab
mkdir c:\\tmp\\matlab
xcopy /E /S /H /Y \\\\10.32.1.20\\daten\\daten\\software\\Lizenz-SW\\Matlab\\Packages\\arduino\\* c:\\tmp\\matlab
"C:\\Program Files\\MATLAB\\R2018b\\bin\\win64\\install_supportsoftware.exe" -archives c:\\tmp\\matlab

</pre>
* Nun sollte in einem Matlab-Login-Fenster nach einem gültigen Login gefragt werden
* bestätige alle auftretenden Fragen beim Installationsvorgang
* am Ende der Installation könnte noch das '''Setup''' der Arduino Hardware gestartet werden. Dies hat nur einen Sinn wenn man eine Arduino-Hardware zur Verfügung hat die konfiguriert werden soll.
* Nach erfolgreicher Installation kann das temporäre Installationsverzeichnis wieder gelöscht werden
<pre>
rmdir /S /Q c:\\tmp\\matlab
</pre>
