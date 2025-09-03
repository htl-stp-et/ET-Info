# allgemeine Grundlagen

3D-Druck gehört zu den additiven Fertigungsverfahren und diente ursprünglich als Rapid-Prototyping-Verfahren.
Der VDI hat eine ganze Richlinienfamilie VDI 3405 zu additiven Fertigungsverfahren veröffentlicht und auch internationale Normungen 
werden derzeit ausgearbeitet.

Durch die mittelerweile sehr günstigen Anschaffungskosten kleinerer 3D-Drucker für Kunststoffe sind diese auch zunehmend in privat 
Haushalten anzutreffen. Um diese Klasse der 3D-Drucker bzw. der Umgang mit diesen ist das Hauptaugenmerk dieses Wiki-Beitrages. 
Dabei soll auch auf die in der Schule frei zugänglichen Drucker (Servicecenter) eingegangen werden.

3D-Drucker sind heutzutage aber mittelerweile weit mehr als nur Geräte zur Herstellung von einfachen Kunststoffeinzelteilen. 
So können neben unterschiedlichen Materialien von eben Kunststoffbasis bis hin zu Metallen auch Kombinationen von solchen in einem 
Gerät gemeinsam verarbeitet werden. Soche Geräte sind jedoch derzeit meist jenseits der € 50.000,00 angesiedelt.

Auch verlässt der 3D-Druck zunehmend die kleinen Dimensionen von einigen Zentimetern, so wurden mittelerweile auch schon ganze Häuser mittels 3D-Druckverfahren hergestellt.

# 3D-Druck im privat Bereich

## 3D-Druckverfahren

Beim 3D-Druck kommen je nach Werkstoff unterschiedliche Techniken zum Einsatz. Das derzeit häufigste im beschrieben Bereich angewendete 
Verfahren ist das sogenannte Schmelzschichtverfahren (Fused Deposition Modeling (FDM) oder Fused Filament Fabrication (FFF)).

Dabei wird das Rohmaterial des Werkstücks als Faden - das sogenante Filament - einer beheizten Düse (Nozzle), welche auch als Hot-End 
bezeichnet wird, zugeführt (extrudiert). Durch die Bewegung der Düse bzw. der Druckfläche im Raum, entsteht Schicht um Schicht das Werkstück. 
Überhänge sind daher nur bis zu einem gewissen Winkel möglich bzw. durch die Verwendung von Stützstrukturen, welche auch von 3D-Drucker 
mitgefertigt werden können.

Die Schichtdicken sind dabei in gewissen Grenzen je nach Drucker (üblich 0.1mm bis 0.3mm) bei der Erzeugung der Steuerungsdaten wählbar. 
Die Wandstärken ist jedochabhängig von der verwendeten Nozzle und kann nur durch einen mechanischen Umbau (Austausch) verändert werden. 
Da die Nozzle regelmässig getauscht werden muss um eine gleichbleibende Qualität der Objekte zu gewährleisten, ist ein solcher Austausch 
meist ohne größere Schwierigkeiten möglich. Eine Kalibrierung mit der neuen Nozzle ist jedoch unumgänglich. Übliche Durchmesser der Nozzle 
liegen bei 0.4mm. Die verwendete Nozzle sollte daher schon bei der Erstellung des 3D-Objekts in der CAD-Software berücksichtigt werden. 
Daher legt man oft schon bei der Konstruktion die Ausrichtung bei der Fertigung fest!

## Filamente

Die folgende Auflistung soll nur überblicksmässig die derzeit üblichsten Filamente mit deren grundlegenden Eigenschaften und 
Verarbeitungsanforderungen zeigen:

 **Name**  | **Hot-End Temperatur** | **Heatbed** | **Glastemperatur** | **besondere Eigenschaften**                           
-----------|------------------------|-------------|--------------------|-------------------------------------------------------
 PLA       | 190°C - 220°C          | optional    | 45°C –  65°C       | derzeit das Standard Filament                         
 PLA+      | 190°C - 230°C          | optional    | 45°C –  65°C       | nachhärtbares PLA, danach Glastemperatur bis 160°C    
 ABS       | 190°C - 220°C          | ja          | 95°C – 110°C       | uv- und formbeständig                                 
 PETG      | 190°C - 220°C          | ja          | ca. 80°C           | beständig gegen viele Chemikalien                     
 TPU/TPE   | 190°C - 220°C          | optional    | -                  | flexibele Elastoplaste                                
 PVA       | 190°C - 220°C          | ja          | ca. 55°C           | wasserlöslich                                         
 ASA       | 190°C - 220°C          | ja          | 110°C – 125°C      | extrem witterungsbeständig                            
 Green-Tec | 190°C - 200°C          | ja          | 120°C lt. Hst.     | 100% recycelbar, bzw. kompostierbar, lebensmittelecht 

Die Glastemperatur beschreibt bei amorphen Werkstoffen jene Temperaturschwelle ab welche diese beginnen weich zu werden, 
daher häufig auch Erweichungstemperatur genannt.
