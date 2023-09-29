# Spiralboard - Lötanleitung

![alt text](Bilder/20230919_221744-removebg-preview.png)


Das Spiralboard ist eine Demoplatine, anhand der wir die Fähigkeit unserer Pick and Place Maschine demonstrieren wollen. Darüber hinaus ist sie auch sehr schön anzusehen und macht sehr viel Spaß beim zusammenbauen (Das Spiralboard, nicht die Maschine).

Folgende Schritte sind notwendig um ein Spiralboard zu fertigen:
- Auftragen der Lötpaste Oberseite
- Automatische Bestückung Oberseite
- Backen der Platine
- Handbestücken der Unterseite
- Steuern der LEDs

Je nach Kenntnisstand kannst du alle Schritte, außer der automatischen Bestückung, mithilfe dieser Anleitung selbstständig durchführen. Dabei stehen wir dir jederzeit mit Rat und Tat zur Seite.

**Wichtig:** Bitte lies jeden Schritt erst zuende und schaue dir das Bild dazu an, bevor du anfängst ihn abzuarbeiten.

Das Herz der Platine ist ein **ESP8266-Modul** mit der Open Source Software **WLED**. Mithilfe von WLED kann das Spiralboard auf jede erdenkliche Art und Weise zum Leuchten und Blinken gebracht werden.

Und das von dir! - Mit deinem Smartphone!

## Schritt 1: Auftragen der Lötpaste

### Einlegen der Platine in den Schablonenhalter
Zuerst muss die Platine in den Schablonenhalter eingelegt werden, so dass die Platine rechts und unten an den Metallstegen anliegt. Die weißen Magnetplatten müssen so gegen die Platine geschoben werden, dass sie sich nicht mehr bewegen kann.

![alt text](Bilder/IMG_8405.JPG)

### Auflegen der Lötschablone
Nun muss die Lötschablone (auch Stencil genannt) so auf die Platine aufgelegt werden, dass die Löcher in der Schablone und die silbernen Pads der Platine perfekt übereinander liegen.

![alt text](Bilder/IMG_8409.JPG)

Wenn alles perfekt passt, muss die Lötschablone mit den schwarzen Magneten am Scharnier des Schablonenhalters befestigt werden. Dabei muss darauf geachtet werden, dass die Schablone nicht wieder verrutscht. Das Scharnier beginnt erst ab ca. 2 cm von der unteren rechten Ecke. Die Magnete müssen also oberhalb platziert werden.

**Achtung**: Die Magnete sind ziemlich stark.

![alt text](Bilder/IMG_8408.JPG)

### Auftragen der Lötpaste

Am unteren Rand der Lötschablone muss eine dünne Wurst aus Lötpaste aufgetragen werden. Die Wurst muss so breit sein, dass beim Rakeln alle Löcher in der Schablone gefüllt werden können.

![alt text](Bilder/IMG_8410.JPG)

Mit zwei Fingern wird die Lötschablone am unteren Rand fixiert und mit dem Rakel wird die Lötpaste über die Schablone gezogen. Dabei muss mit dem Daumen Druck auf den Rakel ausgeübt werden, damit die Lötpaste sich gut in die Öffnungen setzen kann.

![alt text](Bilder/IMG_8411.JPG)

![alt text](Bilder/IMG_8412.JPG)

![alt text](Bilder/IMG_8413.JPG)

Zum Entfernen der Schablone wird mit dem rechten Daumen das Scharnier des Schablonenhalters blockiert und mit dem linken Zeigefinger die linke untere Ecke der Schablone angehoben. 

Hier muss darauf geachtet werden, dass die Schablone nicht zurückfällt, sonst kann die Lötpaste verschmiert werden.

![alt text](Bilder/IMG_8414.JPG)

![alt text](Bilder/IMG_8415.JPG)

Nachdem sich die Schablone komplett von der Platine gelöst hat, kann die Blockierung des Scharniers gelöst werden und das Scharnier mit der Schablone aufgeklappt werden.

![alt text](Bilder/IMG_8416.JPG)

![alt text](Bilder/IMG_8417.JPG)

Nun folgt die Kontrolle, ob die Lötpaste bündig auf den Pads aufgetragen ist. Ist dies nicht der Fall, muss die Platine zuerst komplett gereinigt und dann der ganze Vorgang wiederholt werden.

![alt text](Bilder/IMG_8418.JPG)

## Schritt 2: Automatische Bestückung

Die Oberseite der Platine wird automatisch in der Pick and Place Maschine bestückt. Dazu muss die Platine in den dafür vorgesehenen Halter eingelegt werden.

![alt text](Bilder/IMG_8419.JPG)

Auf der Oberseite werden die LEDs und 100 nF Kondensatoren platziert.

![alt text](Bilder/IMG_8420.JPG)

![alt text](Bilder/IMG_8421.JPG)

![alt text](Bilder/IMG_8422.JPG)

## Backen der Platine

Die bestückte Platine muss jetzt im Lötofen gebacken werden.

Dazu wird die Platine vorsichtig mittig in den Ofen eingelegt, die Tür geschlossen, der Timer maximal aufgezogen und der Heizvorgang mit dem grünen Taster gestartet.

![alt text](Bilder/IMG_8423.JPG)

Auf dem Display kann der Temperaturverlauf verfolgt werden.

![alt text](Bilder/IMG_8424.JPG)

Nach Beenden des Heizvorgangs verbleibt die Platine noch für 2-3 Minuten bei geschlossener Tür im Ofen, egal was das Display sagt.

Anschließend wird die Tür für ca. 1 Minute einen Spalt breit geöffnet.

![alt text](Bilder/IMG_8425.JPG)

Daraufhin wird der Ofen komplett geöffnet und die heiße Platine mit einer Pinzette entnommen.

Zum Schluss wird geprüft, ob alle Bauteile ordungsgemäß verlötet wurden.

![alt text](Bilder/IMG_8427.JPG)

## Schritt 3: Handbestückung der Unterseite
### Alle Bauteile auf einen Blick

![alt text](Bilder/IMG_8443.JPG)

### Einspannen der Platine

Damit während des Lötens die Platine nicht verrutscht, wird diese mit sogenannten PCBites auf einer magnetischen Unterlage fixiert.

![alt text](Bilder/IMG_8441.JPG)

### Widerstände - R1, R4, R5 und R6 (10 kΩ)

Die Widerstände sind in einem weißen Papiergurt verpackt, der mit der Aufschrift "10k" versehen ist.
Um die Widerstände aus dem Gurt zu lösen, muss die Plasikfolie entfernt werden. Das geht am Besten, wenn man mit der Pinzette zwischen Folie und Papier sticht und die Folie vorsichtig abzieht, so dass die Widerstände nicht wegspringen.

![alt text](Bilder/IMG_8431.JPG)

Im ersten Schritt wird das rechte Pad des mit "R1" beschrifteten Footprints verzinnt.

![alt text](Bilder/IMG_8446.JPG)

![alt text](Bilder/IMG_8447.JPG)

Anschließend wird der Widerstand mit der Pinzette aufgenommen und mit dem Lötkolben das Lötzinn wieder flüssig gemacht. Gleichzeitig muss der Widerstand in das flüssige Lötzin hineingeschoben werden.

Ist der Widerstand an der korrekten Stelle platziert, wird der Lötkolben entfernt und der Widerstand mit der Pinzette noch so lange festgehalten, bis das Lötzinn fest geworden ist.

![alt text](Bilder/IMG_8449.JPG)

Nun wird die andere Seite des Widerstands mit dem zweiten Pad verlötet.

![alt text](Bilder/IMG_8450.JPG)

Der gleiche Vorgang muss mit R4, R5 und R6 wiederholt werden.

![alt text](Bilder/IMG_8451.JPG)

![alt text](Bilder/IMG_8452.JPG)

![alt text](Bilder/IMG_8453.JPG)

### Kondensatoren - C33 und C34 (100 nF)

Die 100 nF-Kondensatoren sind ebenso wie die Widerstände in einem weißen Papiergurt verpackt, der mit der Aufschrift "100nF" versehen ist.

![alt text](Bilder/IMG_8444.JPG)

Sie werden auch in gleicher Manier wie die Widerstände verlötet. Die Richtung (welche Seite wohin) ist egal, diese Kondensatoren sind nicht gepolt.

![alt text](Bilder/IMG_8455.JPG)

![alt text](Bilder/IMG_8456.JPG)

### Kondensatoren - C35, C36 und C37 (10 µF)

Die 10 µF-Kondensatoren sind in einem transparenten Plastikgurt verpackt, der mit der Aufschrift "10u" versehen ist.
Auch hier: Gleiches Vorgehen wie bei den anderen Kondensatoren und Widerständen.

![alt text](Bilder/IMG_8432.JPG)

![alt text](Bilder/IMG_8457.JPG)

![alt text](Bilder/IMG_8458.JPG)

![alt text](Bilder/IMG_8459.JPG)

### Linearregler - U3

Der Linearregler ist in einem schwarzen Plastikgurt verpackt.

![alt text](Bilder/IMG_8433.JPG)

Auch hier wird zuerst ein Pad verzinnt und dann das Bauteil in das flüssige Lötzinn geschoben. 

![alt text](Bilder/IMG_8460.JPG)

![alt text](Bilder/IMG_8461.JPG)

Wenn das Bauteil sitzt, werden die restlichen Beine und die Kühlfahne verlötet.

![alt text](Bilder/IMG_8462.JPG)

### Schalter - SW1

Beim Schalter ist die Ausrichtung egal. 

![alt text](Bilder/IMG_8434.JPG)

Verlötet wird er, wie bisher gelernt.

![alt text](Bilder/IMG_8463.JPG)

![alt text](Bilder/IMG_8464.JPG)

![alt text](Bilder/IMG_8465.JPG)

### ESP8266-Modul - U1

Das ESP8266-Modul kann von Hand und ohne Pinzette platziert werden.

![alt text](Bilder/IMG_8435.JPG)

Wie bisher auch wird zu erst ein Pad verzinnt und das Modul in das flüssige Lötzinn geschoben. Hier ist es ganz wichtig darauf zu achten, dass das Modul ordentlich sitzt und jeder Pin über einem Pad platziert ist. 

![alt text](Bilder/IMG_8467.JPG)

![alt text](Bilder/IMG_8468.JPG)

Es genügt, nur die Pins an den beiden langen Seiten zu verlöten. Die Pinreihe an der kurzen Seite wird nicht benötigt.

![alt text](Bilder/IMG_8469.JPG)

![alt text](Bilder/IMG_8470.JPG)

### Ladereglermodul - Mod1

Für das Laderegler-Modul ist ebenfalls keine Pinzette notwendig. 

![alt text](Bilder/IMG_8436.JPG)

Routiniert wird wieder ein Pad verzinnt und das Modul ausgerichtet. Zum Verlöten muss der Lötkolben durch die Bohrung gesteckt werden um das Lötzinn auf dem vorverzinnten Pad zu verflüssigen.

![alt text](Bilder/IMG_8471.JPG)

![alt text](Bilder/IMG_8474.JPG)

Anschließend werden alle anderen Pads verlötet, indem Lötzinn in die Bohrungen gedrückt wird und alles mit dem Lötkolben erhitzt wird.

![alt text](Bilder/IMG_8475.JPG)

![alt text](Bilder/IMG_8477.JPG)

### Ladebuchse - J2

Die Ladebuchse ist ein THT-Bauteil, es muss von oben in die Platine gsteckt, aber von der Unterseite verlötet werden.

![alt text](Bilder/IMG_8437.JPG)

Das heißt die Platine muss jetzt aus den PCBites gelöst werden und andersherum wieder eingespannt werden. Die Buchse sollte von alleine halten, wenn sie doch herausfällt, muss sie mit einem Finger leicht fixiert werden.


![alt text](Bilder/IMG_8478.JPG)

![alt text](Bilder/IMG_8479.JPG)

![alt text](Bilder/IMG_8480.JPG)

### Taster - ohne Namen

Der Taster war im ursprünglichen Design nicht vorgesehen. Weil er aber so praktisch ist, wird er an der Stelle reingefuddelt, wo die optionale Programmierschnittstelle hätte hinkommen können.

![alt text](Bilder/IMG_8438.JPG)

Die Platine kann auf dem Kopf bleiben und der Taster muss von unten durchgefädelt werden.

Die Beinchen müssen durch zwei Bohrungen von J1 gesteckt werden. Vorgesehen sind dafür die mittlere Bohrung und die, die am weitesten von der Bohrung mit dem quadratischen Pad entfernt ist.
Schematisch:

|[ ]| O| O| O| O|
|-|-|-|-|-|
| | |x | | x |

Damit der Taster beim Verlöten nicht herausfällt, können die Beinchen verbogen werden.

Beim Verlöten des ersten Beinchens sollte der Taster trotzdem mit einem Finger fixiert werden, damit er anschließend ordentlich auf der Platine aufliegt.

![alt text](Bilder/IMG_8482.JPG)

![alt text](Bilder/IMG_8483.JPG)

![alt text](Bilder/IMG_8484.JPG)

Nach dem Verlöten müssen die Beinchen noch gekürzt werden.

![alt text](Bilder/IMG_8485.JPG)

### Akku

Der Akku wird mit Klettverschluss an der Platine fixiert. Dazu muss die Platine aus den PCBites gelöst werden.

![alt text](Bilder/IMG_8439.JPG)

![alt text](Bilder/IMG_8440.JPG)

Zuerst wird der **flauschige** Teil des Klettverschlusses auf den Akku geklebt.

![alt text](Bilder/IMG_8487.JPG)

Anschließend wird der andere Teil mit dem flauschigen Teil verbunden und die Schutzfolie vom Klebeband entfernt.

![alt text](Bilder/IMG_8488.JPG)

Jetzt wird der Akku mittig in das weiße Rechteck geklebt.

![alt text](Bilder/IMG_8489.JPG)

Zu guter Letzt wird der Stecker des Akkus in die Buchse J2 gesteckt.

![alt text](Bilder/IMG_8490.JPG)

Wenn der Schalter auf **On** gestellt ist, sollte die Platine nun irgendwie leuchten.

![alt text](Bilder/IMG_8492.JPG)

## Schritt 4: WLED

Auf dem Controller ist die Open Source Firmware "WLED", mit ein paar von uns konfigurierten Presets, installiert.

Auf dem Smartphone sollte ein WLAN-Access-Point zu sehen sein, der sich aus **Spiralboard-** und der Nummer auf dem ESP8266-Modul zusammensetzt. Das default Passwort ist **wled1234**.

Über die Website die sich öffnet, wenn eine Verbindung zu diesem Access-Point aufgebaut wird, kann die Anzeige auf dem Spiralboard gesteuert werden.

Die vorinstallierten Presets lassen sich durch einfachen Klick des Tasters umschalten und durch langen Klick schaltest du das Board in einen automatischen Wechselzyklus bei dem es alle 10 Sekunden das Preset wechselt.

Weitere Infos zu WLED gibt es hier: https://kno.wled.ge/

Du kannst das Board über WLED frei konfigurieren, updaten usw...
Wir empfehlen dir, das Board Zuhause mit deinem Heimnetzwerk zu verbinden, da es sich dann viel leichter konfigurieren lässt.

Wir wünschen dir viel Spaß mit deinem eigenen Spiralboard und hoffen es hat dir Spaß gemacht!


