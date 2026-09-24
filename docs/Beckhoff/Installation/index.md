# Beckhoff
## Installation Übersicht
In diesem Abschnitt wird gezeigt wie an der HTL St.Pölten:
* der TwinCAT Package Manager bezogen wird ([Abschnitt Download](download-twincat-package-mamager))
* die Registrierung bei Beckhoff erfolgt ([Abschnitt Registrierung](registrierung-bei-beckhoff))
* der Packagemanger installiert wird ([Abschnitt Packagemanger installieren](installation-packagemanger))
* und welche Pakete von TwinCAT installiert werden sollen ([Abschnitt TwinCAT installieren](installation-von-twincat))
* ([Hinweise](hinweise))

## Download TwinCAT Package Manager
Der TwinCAT Package Manager kann direkt über das ET-Wiki bzw. ET-EDV sharepoint heruntergeladen werden.
Dazu am einfachsten in der Übersicht des ET-Wiki auf Beckhoff TwinCAT klicken:

    <img src="TwinCAT_install_001.jpg" alt="TwinCAT-Verlinkung im ET-Wiki">

Dabei wird (wenn nicht bereits im Browser ein Office-Login aktiv ist) zum Login am HTL-Sharepoint aufgefordert:

    <img src="TwinCAT_install_002.jpg" alt="HTLSTP Sharepoint login">

Nun wir der Download angezeigt und der INstaller kann lokal abgespeichert werden:

    <img src="TwinCAT_install_004.jpg" alt="Installer abspeichern">

## Registrierung bei Beckhoff
Während der Download läuft, kann man sich bei Beckhoff mit der Schulemailadresse registrieren.
Dazu auf der Site[www.beckhoff.com/de-at](https://www.beckhoff.com/de-at) rechts oben auf "Jetzt anmelden myBeckhoff" klicken:

    <img src="TwinCAT_install_011.jpg" alt="Beckhoff-Website">

und Registriern auswählen:

    <img src="TwinCAT_install_012.jpg" alt="Beckhoff-Website Registrieren">

oder direkt den Link [myBeckhoff](https://www.beckhoff.com/de-at/mybeckhoff-registrierung/index.aspx) nutzen.

Jetzt noch mindestens die Pflichtfelder ausfüllen:

    <img src="TwinCAT_install_013.jpg" alt="Beckhoff Registrierung">

Wenn alles notwendige ausgefüllt ist, bekommt man den Hinweis, dass die eMail noch bestätigt werden muss:

    <img src="TwinCAT_install_014.jpg" alt="Beckhoff Registrierung eMail Hinweis">

Im eMail mit dem Klick auf "myBeckhoff aktivieren" ist die Registrierung abgeschlossen

    <img src="TwinCAT_install_015.jpg" alt="Beckhoff eMail-Aktivierung">

## Installation Packagemanger
Nun sollte der Download abgeschlossen sein und der Installer des Packagemanagers kann gestartet werden:

    <img src="TwinCAT_install_005.jpg" alt="Beckhoff Packagemanger install 1">

Als Abschluss der Installation muss der PC möglicherweise neu gestartet werden:

    <img src="TwinCAT_install_006.jpg" alt="Beckhoff Packagemanger install 2">

## Installation von TwinCAT
Am System ist nun der "TwinCAT Package Manager" (Startmenü oder Desktop), welcher zu starten ist. Während des Starts werden unterschiedliche Abschnitte geladen:

    <img src="TwinCAT_install_007.jpg" alt="Beckhoff Packagemanger start">
    
Der erste Bereich im Erststartfenster Fenster "Introduction" kann mit "Next" bestätigt werden

    <img src="TwinCAT_install_008.jpg" alt="Beckhoff Packagemanger Introduction">

Im zweiten Bereich "Feeds" müssen die Quellen aktiviert werden damit Produkte installiert werden können. Dazu rechts oben "+Add new feed" auswählen:

    <img src="TwinCAT_install_009.jpg" alt="Beckhoff Packagemanger Feeds">

Wir benötigen aktuell nur einen Feed, nämlich den stable:

    <img src="TwinCAT_install_010.jpg" alt="Beckhoff Packagemanger Feed stable">

Wer auf älterer Hardware arbeiten muss, benötigt eventuell noch den "outdated" dies kann aber zu Komplikationen führen -> für die Schule nicht notwendig!
Nun muss der aktivierte myBackhoff-Account von der Registrierung auf der Homepage ([Abschnitt Registrierung](registrierung-bei-beckhoff)) eingetragen werden:

    <img src="TwinCAT_install_016.jpg" alt="Beckhoff Packagemanger Feed Account">

Nach dem Speichern ist man wieder in der vorherigen Maske, hier sollte nun der stable-feed sichtbar sein und Aktiv (Hacken bei enable). Durch die Bestätigung auf "Finish" kann der Ersteinstieg abgeschlossen werden:

    <img src="TwinCAT_install_017.jpg" alt="Beckhoff Packagemanger Feed fertig">

Das folgende willkommens Fenster kann mit "Skip" übersprungen werden:

    <img src="TwinCAT_install_019.jpg" alt="Beckhoff Packagemanger welcome skip">

Als Entwicklungsumgebung nutzen wir in der Schule die Standardumgebeung 4026.26.0. Dazu einfach auf die blaue Schaltfläche zum Download klicken:

    <img src="TwinCAT_install_020.jpg" alt="Beckhoff Packagemanger TwinCAT Standard">

Nach der Hinweismeldung "Workload selected",

    <img src="TwinCAT_install_021.jpg" alt="Beckhoff Packagemanger TwinCAT Standard ausgewählt">

kann mittels "Apply modifications":

    <img src="TwinCAT_install_022.jpg" alt="Beckhoff Packagemanger Apply modifications">

der Download- und Installationsvorgang gestartet werden:

    <img src="TwinCAT_install_023.jpg" alt="Beckhoff Packagemanger Modifications">

Der folgende Hinweis muss mit "Accept" bestätigt werden:

    <img src="TwinCAT_install_024.jpg" alt="Beckhoff Packagemanger Modification finish">

damit der eigentliche Download und die folgende Installation startet:

    <img src="TwinCAT_install_025.jpg" alt="Beckhoff Packagemanger Modification download/install">

Nach dem alle Produktteile heruntergeladen und erfolgreich installiert wurde muss das entsprechende Hinweisfenster bestätigt werden:

    <img src="TwinCAT_install_026.jpg" alt="Beckhoff Packagemanger Modification complete">

und das Download-/Installationsfenster mittels "close" geschlossen werden:

    <img src="TwinCAT_install_027.jpg" alt="Beckhoff Packagemanger Modification close">

Der Package Manager sollte nun wie folgt aussehen:

    <img src="TwinCAT_install_028.jpg" alt="Beckhoff Packagemanger fertig">

Damit ist die Installation von TwinCAT abgeschlossen.

## Hinweise
* Gestartet wird die IDE über den Eintrag "TwinCAT XAE Shell 64-bit" im Startmenü.
* Damit der Hauptspeicher nicht permanent belastet wird, kann der Eintrag "TcSysUI.exe" im Autostart deaktiviert werden.

[zurück zur Beckhoff Übersichtsseite](../index.md)