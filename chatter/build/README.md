# Chatter Bauanleitung

* [Einführung](#einführung)
* [Hier sind die Werkzeuge!](#hier-sind-die-werkzeuge)
* [Zusammenbau](#zusammenbau)
* [Der erste Test](#der-erste-test)
* [Wie geht's weiter?](#)

## Einführung

### Aller Anfang ist leicht

**Willkommen bei der CircuitMess Chatter Bauanleitung!**

In dieser Bauanleitung erfährst du, wie du ein Kommunikationsgerät zusammen baust, mit dem du drahtlos und verschlüsselt kommunizieren kannst.
Mit Chatter lernst du, wie du deinen privaten SMS-Kommunikator erstellst, wie LoRa funktioniert, wie du benutzerdefinierte Apps programmierst und auf deinen Chatter lädst und was Privatsphäre im Jahr 2022 bedeutet.

![Chatter](images/chatter.jpg)

#### Altersgruppe

Wie auf der Schachtel beschrieben, ist Chatter für alle **ab 11 Jahren** geeignet.

Du solltest einige der Montageschritte mit Vorsicht angehen - also sorge dafür, dass ein Erwachsener einspringt, wenn du später beim Löten oder Anziehen der Schrauben Hilfe brauchst. Es ist in Ordnung, wenn du um Hilfe bittest.

Aber keine Sorge! Wir gehen den Zusammenbau Schritt für Schritt durch und geben dabei einige nützliche Tipps. Wir geben dir einen Hinweis, wenn du beim Zusammenbau etwas Wichtiges beachten musst.

#### Aufbauzeit

Für den vollständigen Zusammenbau deines Chatters solltest du **etwa 4 Stunden** einplanen.

Natürlich hängt die Montagezeit von deinen Vorkenntnissen und deiner Erfahrung ab. Wenn du noch keine Erfahrung hast, mach' dir keine Sorgen! Es kann sein, dass du etwas länger brauchst, um dich einzuarbeiten und die anfänglichen Schwierigkeiten zu überwinden.

#### Benötigte Fertigkeiten

Du musst keine besonderen Fertigkeiten haben, um dich an diesem Selbstbauprojekt zu versuchen.

Das Hauptziel ist es, Spaß zu haben und etwas Neues zu lernen.

Also pass gut auf, lies alle Anweisungen und mach' dich bereit Spaß zu haben!
Dies ist eine großartige Gelegenheit und dein erster Schritt in deiner großen Ingenieurskarriere.

#### Lernen mit Chatter

Wie bereits erwähnt, wirst du in den folgenden Stunden mit Chatter einige nützliche Dinge lernen.

Diese Punkte hier wirst du lernen:

* Wie du dir deinen eigenen privaten SMS-Kommunikator erstellst
* Was Privatsphäre im Jahr 2022 bedeutet und wie du digital kommunizieren kannst ohne das Internet zu verwenden
* Wie LoRa funktioniert
* Wie Chatter Nachrichten verschlüsselt und entschlüsselt und wie er sich mit anderen Chattern verbindet
* Wie man eigene Apps programmiert und auf seinen Chatter lädt

### Woraus besteht der Bausatz?

Lass' uns alle Teile kennen lernen, die du bekommen hast!

![Chatter Bausatz](images/box1.jpg)

![Teile des Bausatzes](images/box2.jpg)

Öffne deine Chatter-Box und überprüfe, ob alle Komponenten enthalten sind. Lege alles auf eine saubere Oberfläche, vergleiche die Teile mit dem Foto und der Liste weiter unten.

Sollte etwas fehlen, kontaktiere uns bitte unter **<contact@circuitmess.com>**. Bitte schicke uns ein Foto von allem, was im Karton war, und wir werden uns so schnell wie möglich bei dir melden, um das Problem zu lösen.

![Teile des Bausatzes](images/parts.jpg)

Hier ist die Liste der Komponenten:

1. Batteriehalterungen
2. Acryl-Gehäuse
3. Platine mit eingebautem Kommunikationsmodul
4. USB-C-Kabel für die Programmierung
5. Batterien
6. Bildschirm-Platine
7. Taster
8. Tastenkappen
9. Piezo-Summer
10. Metallbolzen
11. Abstandshalter aus Messing
12. Antenne
13. Ein-/Aus-Schalter
14. Aufkleber

## Hier sind die Werkzeuge!

### Benötigte Werkzeuge

In diesem Kapitel erklären wir dir, welche Werkzeuge du für den Zusammenbau deines Chatter benötigst.

Wenn du das **CircuitMess Tools-Paket** besitzt und vor dir liegen hast - dann solltest du bereit sein!

Falls du den Chatter-Bausatz ohne das Werkzeugpaket erhalten hast, ist dies ein guter Zeitpunkt, um sich einige der Werkzeuge auszuleihen oder sie zu kaufen.

Die folgenden, unbedingt benötigten Werkzeuge sind unverzichtbar, wenn du elektronische Geräte zusammenbaust, reparierst oder modifizierst und sind das Handwerkszeug für jeden Maker/Hardware-Hacker/Modder/Elektriker.

![Benötigte Werkzeuge](images/tools.png)

1. Lötkolben
2. Entlöt-Vakuumwerkzeug (Lötsauger)
3. Lötkolbenständer
4. Eine kleine Rolle mit kolophoniumhaltigem Lot
5. Reinigungsschwamm
6. Kreuzschlitzschraubendreher
7. Seitenschneider
8. Spitzzange

#### Lötkolben

Dies ist das wichtigste Werkzeug im Arsenal eines Bastlers.

Für den Zusammenbau von Chatter reicht jeder Lötkolben der Einstiegsklasse aus.

Wenn du vor hast, in die Welt der Heimwerkerprojekte einzutauchen, solltest du einen teureren Lötkolben mit mehr Funktionen in Betracht ziehen. Lötkolben mit austauschbaren Spitzen sind zum Beispiel besonders nützlich, wenn du viel mit kleineren Bauteilen arbeiten möchtest.

Im nächsten Kapitel findest du eine Anleitung zum richtigen Löten und zur Pflege deines Lötkolbens.

![Lötkolben aus dem Tools-Paket](images/iron.png)

#### Lötschwamm

Dieses kleine Stück macht nicht viel her, bis man es in Wasser einweicht. Dann verwandelt es sich in einen super Lötzinn-Reinigungsschwamm! Benutze ihn, nachdem du ein paar Lötstellen gelötet hast, um das überschüssige Lot von der Spitze deines Lötkolbens zu entfernen. Achte darauf, dass der Schwamm weder tropfnass noch staubtrocken ist - er sollte feucht sein.

#### Seitenschneider

Mit einem Seitenschneider wie diesem kannst du die Beine von gelöteten Bauteilen abschneiden und Drähte kürzen.

Wir bevorzugen die auf dem Bild gezeigte Zange (Plato, Modell 170), aber auch jedes andere Modell ist geeignet.

![Seitenschneider/Zange](images/zange.png)

#### Spitzzange

Eine solche Zange brauchst du beim Zusammenbau des Gehäuses oder beim Einstecken kniffliger Stecker!

Sie ist generell hilfreich bei feinmechanischen Arbeiten.

![Spitzzange](images/zange2.png)

#### Kreuzschlitz - Schraubendreher

Für die Montage des Gehäuses benötigst du diesen Kreuzschlitzschraubendreher.

Ein handelsüblicher 2,0 mm - Kreuzschlitzschraubendreher sollte ausreichen.

![Kreuzschlitzschraubendreher](images/screwdriver.png)

#### Entlöt-Vakuumwerkzeug (Lötsauger)

Dieses Werkzeug ist nützlich, um Lötfehler zu beseitigen. Für die Montage selbst ist es nicht notwendig.

Wenn du vor hast, in Zukunft etwas zu hacken, zu modden oder Hardware zu reparieren, ist es immer eine gute Idee, dieses Werkzeug zu haben.

![Lötsauger](images/vacuum.png)

### Zusätzliche nützliche Werkzeuge

#### Helfende dritte Hand mit Lupe

Dies könnte deine Löterfahrung ein wenig angenehmer machen, besonders wenn du kompliziertere Projekte durchführen möchtest.

![Dritte Hand mit Lupe](images/helping-hand.png)

#### Multimeter

Ein Multimeter kann für viele Dinge verwendet werden: zum Prüfen kniffliger Verbindungen, zum Messen der Batteriespannung, zum Testen von Widerständen und Kondensatoren, zum Messen des Stromverbrauchs und vielem mehr.

Es ist ein nützliches Werkzeug, wenn du herausfinden willst, was bei einem Elektronik-Bausatz schief gelaufen ist.

![Multimeter](images/multimeter.png)

#### Lötdocht

Du kannst den Lötdocht zusammen mit dem Entlöt-Vakuumwerkzeug verwenden, um Lötfehler zu beseitigen. Lege ihn einfach auf die fehlerhafte Lötstelle und drücke mit einem heißen Lötkolben darauf. Dann saugt er das überschüssige Lot auf wie ein Schwamm!

Nützlich zum Korrigieren von Lötstellen, die mit einem Lötsauger nicht leicht zu erreichen sind.

![Lötdocht](images/wick.png)

## Zusammenbau

### Einführung in das Löten

Eines der Dinge, die du beim Zusammenbau deines Chatters tun wirst, ist löten!

Hast du das schon einmal gemacht? Wenn nicht, empfehlen wir, dir die folgenden Links anzusehen, die zu nützlichen Anleitungen und Blogs zum Thema Löten führen. Du wirst nur 10 Minuten brauchen, um dich in die Materie einzuarbeiten und um zu verstehen, wie es gemacht wird.

Hier sind die Links (englisch):

* [Adafruits Video Tutorial mit Collin Cunningham](https://www.youtube.com/watch?v=QKbJxytERvg) - Ein Tutorial mit Collin Cunningham, einem super charismatischen Elektronik-Guru.
* [Adafruits Löt Tutorial](https://learn.adafruit.com/adafruit-guide-excellent-soldering?view=all) - Ein großartiges und ausführliches Video-Tutorial. Ein absolutes Muss, auch wenn Du schon weißt, wie man lötet. Besonders zu empfehlen ist der Abschnitt "Häufige Fehler beim Löten" am Ende.
* [Sparkfuns Video-Tutorial zum Löten](https://www.youtube.com/watch?v=f95i88OSWB4) - Ein weiteres gut gemachtes Video-Tutorial zum Thema Löten.
* [Sparkfuns Standard Soldering Tutorial](https://learn.sparkfun.com/tutorials/how-to-solder-through-hole-soldering) - Ein detailliertes Tutorial von Sparkfun.

![Anlöten eines Tasters](images/solder.jpg)

### Löt-Regeln

Es gibt einige Regeln für das Löten, die jeder, unabhängig von seinem Kenntnisstand, stets beachten sollte:

* **Atme niemals die Dämpfe ein, die der Lötkolben produziert!**
  Diese können gefährlich sein, also atme sie bitte nicht ein.

* **Berühre niemals die Spitze des Lötkolbens!**
  Auch wenn der Lötkolben ausgeschaltet oder ganz von der Stromquelle getrennt ist, kann er noch sehr heiß sein und daher bei Berührung sehr unangenehme Schmerzen verursachen.
  Halte den Lötkolben immer so, dass die Spitze von deinen Händen weg zeigt.
  Wenn du mit dem Löten fertig bist, trenne den Lötkolben von der Stromquelle und lasse ihn mindestens fünf Minuten abkühlen, bevor du ihn wieder verstaust.

* **Reinige den Lötkolben!**
  Der Schwamm ist dein bester Freund beim Löten. Verwende ihn häufig und reinige deinen Lötkolben, wenn du einfach und problemlos löten möchtest.
  Halte dazu ein Ende des Schwamms vorsichtig mit einer Hand fest und wische die Spitze des Lötkolbens am anderen Ende des Schwamms ab, um das überschüssige Lot zu entfernen. Wiederhole dies so lange bis die Spitze des Lötkolbens schön sauber ist.

* **Prüfe deine Lötstellen. Zweimal!** (mindestens)
  Die meisten Fehlfunktionen in der Welt der Elektronik sind auf schlechte Lötstellen zurückzuführen. Unabhängig davon, ob es sich um dein erstes oder 100. Lötprojekt handelt solltest du deine Lötstellen immer mehrmals überprüfen, bevor du zum nächsten Schritt übergehst.

* **Bewahre den Lötkolben auf dem Ständer auf**, wenn du ihn nicht benutzt.

* **Verwende die richtige Menge Lötzinn!**
  Achte darauf, dass du gerade genug Lot verwendest. Nicht zu viel, aber auch nicht zu wenig, denn beides kann dazu führen, dass dein Bausatz dann nicht funktioniert.

* **Lass keine Lot-Reste auf der Platine!**
  Das Lötzinn sollte sich nur auf den Teilen befinden, an denen die Stifte mit der Platine verbunden sind. Halte den Rest der Platine sauber! Kleine Löttropfen auf der ganzen Platine sind ein absolutes Tabu!

**Bitte lies dir diese Regeln jetzt noch ein paar Mal durch, damit du sie nicht vergisst!**

Verwende dieses Foto, um eine Vorstellung von guten und schlechten Lötstellen zu bekommen (Danke an Adafruit für dieses tolle Foto!):

![Verschiedene Lötpunkte](images/adafruit.jpg)

* Cold Joint - Kalte Lötstelle
* Insufficient Wetting - Unzureichende "Benetzung" des Lötstelle; zu wenig Lot
* Too Much Solder - Zu viel Lot
* OK - Super. Alles richtig!

Wenn du diese Regeln befolgst, sollte dir das Löten leicht von der Hand gehen.

### Verwendung des Lötkolbens

Der Lötkolben ist sehr einfach zu benutzen, aber nur, wenn er richtig benutzt wird.

Wenn du das CircuitMess-Werkzeugpaket mit deinem Chatter-Bausatz gekauft hast, hast du einen weißen Lötkolben mit einem Temperaturregler erhalten.

Erinnerst du dich an die zuvor erwähnten Regeln? Gut! Lass uns jetzt die Anweisungen zur Verwendung des Lötkolbens durchgehen...

Wenn du deinen Lötkolben zum ersten Mal benutzt oder Hilfe bei der Reinigung der Spitze brauchst, schau dir unser (englisches) [Video-Tutorial](https://www.youtube.com/watch?v=JPFH4m-Pa00) an.

![Lötkolben](images/iron.png)

#### Schritt 1 - Einstecken

Lege den Lötkolben auf einen Lötkolbenständer und schließen Sie ihn an eine Steckdose an.

![Schritt 1 - Einstecken](images/step1.png)

#### Schritt 2 - Wähle die richtige Temperatur

Stelle die Temperatur auf **350 °C** ein, indem du den Temperaturregler am Lötkolben drehst.
Achte darauf, dass der kleine schwarze Pfeil auf die richtige Temperatur zeigt, wie auf dem Foto zu sehen.

Dein Lötkolben ist jetzt einsatzbereit, aber lass ihm ein bis zwei Minuten Zeit, damit er sich aufheizen kann.

![Schritt 2 - Die richtige Temperatur](images/step2.png)

#### Schritt 3 - Vergiss nicht, ihn auszuschalten, wenn du fertig bist

Wenn du mit dem Löten fertig bist, ziehe den Stecker aus der Steckdose, um den Lötkolben auszuschalten.

Bitte benutze den Metallständer immer dann, wenn du den Lötkolben nicht benutzt.
Damit stellst du sicher, dass deine Unterlage oder die Platine nicht verbrennen.

**Achte darauf, nach dem Ausschalten die Spitze des Lötkolbens mindestens fünf Minuten lang nicht zu berühren.**

![Schritt 3 - Ausschalten](images/step3.png)

### Teil 1 - Löten der Bauteile

Jetzt, wo du weißt, wie man lötet, können wir es gleich ausprobieren. Bist du bereit?

Schau' dir vor dem Löten noch einmal unser Video-Tutorial an, um sicher zu gehen, dass du alles richtig machst.

#### Ein/Aus-Schalter

Die ersten Komponenten, die wir verwenden werden, sind Platine und Schalter.

![Platine und Schalter](images/solder1.jpg)

Bevor du dieses Teil einlötest, versuche es ein paar Mal umzuschalten.Jedes Mal, wenn sich der Zustand des Schalters ändert, solltest du ein leises Klicken hören. Bis jetzt macht er noch nichts, aber schon bald wird er deinem Chatter Leben einhauchen, wann immer du es möchtest.

Nimm den Schalter und stecke die Stifte durch die Löcher, so dass der Schalter auf dem vorderen Teil der Platine liegt und die Stifte hinten herausragen.

Der Einbau kann ein wenig Kraft erfordern. Versuche mit dem Schalter leicht hin- und her zu wackeln bis er richtig passt.

![Schalter eingebaut](images/solder2.jpg)

Wenn alles in Ordnung zu sein scheint, drehe die Leiterplatte um.

![Leiterplatte von hinten](images/solder3.jpg)

Nimm den Lötkolben vom Ständer und beginne die Stifte an der richtigen Stelle einzulöten.

Das Löten dieser Stifte erfordert ein wenig mehr Präzision, da sie dicht beieinander liegen, so dass es viel leichter ist, sie versehentlich zu überbrücken.

![Löten des Schalters](images/solder4.jpg)

Vergiss nicht, den Schalter an beide Chatter zu löten!

Wir haben gleichzeitig gelötet, aber du kannst auch erst den einen Chatter und dann den anderen anlöten.

So sollten die Lötstellen jetzt aussehen:

![Schalter eingelötet](images/solder5.jpg)

#### Taster

Jetzt ist es an der Zeit, die **Taster** zu verlöten!

Taster sind die am häufigsten verwendeten Eingabegeräte, und es gibt insgesamt 13 von ihnen auf jedem Chatter.

Die Tasten bestehen aus zwei Teilen - **den mechanischen Tastern und den Tastenkappen**. Die Taster funktionieren auch ohne die Kappen, aber wenn man sie mit den Kappen drückt, fühlt sich das viel schöner an und sie sehen viel cooler aus.

Wie auch immer, wir lassen die Kappen erst einmal beiseite und konzentrieren uns auf das Löten der Taster.

![Taster und Leiterplatte](images/btn1.jpg)

Als Erstes musst du jeden einzelnen Taster auf der Platine platzieren. Sie sollten vertikal auf der Platine platziert werden.

**Vergewissere dich vor dem Einlöten der Taster, dass sie senkrecht auf der Platine stehen. Dies ist sehr wichtig, da du sonst Probleme haben wirst, die Leiterplatte in das Gehäuse einzubauen, wenn die Tasten schief sind.**

![Taster auf der Leiterplatte](images/btn2.jpg)

Nachdem du die Bauteile an den richtigen Stellen platziert hast (Stifte durch die winzigen Löcher), lege die Leiterplatte vor dir auf die Arbeitsfläche und nimm den Lötkolben zur Hand.

![Löten der Taster](images/btn3.jpg)

So sollte die Leiterplatte aussehen, nachdem du alle Taster eingelötet hast. Prüfe bitte, ob du alle Tasten drücken kannst.

![Leiterplatten mit Tastern von hinten](images/btn4.jpg)

![Leiterplatten mit Tastern](images/btn5.jpg)

#### Piezo-Summer

Als nächstes werden wir einen Summer anlöten.

Der **Piezo-Summer** auf dem Gerät kann viele verschiedene Pieptöne, Summtöne und andere verrückte Geräusche erzeugen.

Er ist nicht so leistungsfähig wie ein echter Lautsprecher, aber er ist trotzdem ein nützliches Bauteil, wenn man nur einige Geräusche erzeugen will.

![Leiterplatte und Summer](images/buzz1.jpg)

Und noch einmal ist es Zeit zum Löten!

Die Position des Summers ist nicht wichtig. Stecke die Stifte einfach in die Löcher der Leiterplatte.

![Summer auf der Leiterplatte](images/buzz2.jpg)

Achte darauf, die Lötkolbenspitze zwischen dem Löten der Stifte zu reinigen. Achte auch darauf, die Stifte nicht zu überbrücken.

![Einlöten des Summers](images/buzz3.jpg)

So sollten deine Chatter im Moment aussehen:

![Einlötete Summer von vorn](images/buzz4.jpg)

![Leiterplatte von hinten](images/buzz5.jpg)

#### Antenne

Es ist Zeit für die Antenne!

Du hast dich wahrscheinlich gefragt, was dieses **spiralförmige goldene Ding** ist - die Antwort ist: **die Antenne**.

![Antenne und Leiterplatte](images/ant1.jpg)

Es könnte einige Probleme mit dem Löten dieses Teils auf Ihrem Chatter geben, also bitte lies die folgenden Anweisungen sorgfältig.

Als erstes musst du **ein wenig Lötzinn auf die Vorderseite der Platine auftragen**, wie auf dem Foto gezeigt.

![Lötzinn auf Leiterplatte auftragen](images/ant2.jpg)

**Während das Lötzinn noch warm ist, musst du den abgerundeten Teil der Antenne durch das kleine Loch stecken**, auf das wir vorher das Lötzinn aufgetragen haben.

Wie du wahrscheinlich schon weißt, sollte der Stift auf der Rückseite des Chatters herauskommen.

![Antenne und Leiterplatte](images/ant3.jpg)

Der knifflige Teil hierbei ist, dass du auf der Vorderseite der Platine löten musst.

![Antenne auf Vorderseite anlöten](images/ant4.jpg)

**Bitte beachte, dass du die Antenne und den ersten Teil des Chips verlöten musst.** Schaue dir das Foto unten an, um zu sehen, wie es aussehen soll.

![Antenne und Lora-Chip](images/ant5.jpg)

**Aufpassen! Du darfst die Antenne nur mit dem ersten Teil des Chips verbinden, wie auf dem Foto gezeigt!**

![Richtiger Pin für die Antenne](images/ant6.jpg)

Deine Chatter sollten so aussehen, wenn du die Schritte richtig ausgeführt hast:

![Antennen verlötet](images/ant7.jpg)

#### Batteriehalter

Das letzte Teil, das wir anlöten werden, ist der **Batteriehalter**. Hier siehst du den Batteriehalter für drei AAA-Batterien.

![Batteriehalter](images/bat1.jpg)

**Im Gegensatz zu allen anderen Teilen wird dieses Teil auf der Rückseite der Leiterplatte angebracht.** Die Stifte sollten durch die Löcher gehen und von der Vorderseite zu sehen sein.

![Batteriehalter von der Seite](images/bat2.jpg)

Nimm wieder den Lötkolben zur Hand und löte die beiden Stifte ein. Einfacher geht's nicht!

![Batteriehalter einlöten](images/bat3.jpg)

**Herzlichen Glückwunsch!** Du hast alle Lötarbeiten gemeistert!

Das bedeutet, dass der schwierige Teil des Zusammenbaus vorbei ist!
Reinige den Lötkolben, ziehe den Stecker und lege ihn auf den Metallständer, weg vom Chatter.

Das Wichtigste ist jetzt, sicherzustellen, dass es keine Überbrückungen gibt.

Hier ist noch einmal das Foto von Adafruit; sieh es dir genau an und vergleiche die Lötstellen mit denen, die du angefertigt hast.

![Lötstellen](images/adafruit.jpg)

### Teil 2 - Gehäuse

Willkommen zum nächsten Schritt, in dem du sehen wirst, wie du das Gehäuse für deinen Chatter zusammenbauen kannst!

Wie du wahrscheinlich schon bemerkt hast, hast du sechs Acrylgehäuse in deinem Karton - drei für jeden Chatter.

Diese Teile solltest du haben:

![Gehäuseteile](images/case1.jpg)

Als Erstes musst du **die blauen Schutzfolien abziehen**.

Wie du sehen kannst, hat jedes der Acrylgehäuseteile auf beiden Seiten eine Schutzfolie, die abgezogen werden muss. Aktuell sind die Gehäuseteile noch nicht vollständig durchsichtig, aber sie sollten es sein, sobald du diesen Schritt beendet hast!

![Gehäuseteile mit Folie](images/case2.jpg)

![Gehäuseteile ohne Folie](images/case3.jpg)

#### Gehäuserückseite

Als erstes werden wir ein Acrylgehäuse auf der Rückseite deines Chatters anbringen.

Die Acrylplatte, die du jetzt brauchst, ist leicht zu finden - es ist jene mit den vielen Löchern darin.
Bitte nimm das auf dem Foto unten abgebildete Gehäuse und lege es auf die Platine.

![Gehäuse Rückseite](images/case4.jpg)

Nimm nun die **vier goldenen Abstandshalter** und **vier kleine Schrauben**.

![Abstandshalter und kleine Schrauben](images/case5.jpg)

**Es gibt zwei verschiedene Größen von Schrauben. Achte darauf, die richtigen zu verwenden!**

Die goldenen Abstandshalter werden auf der Vorderseite angebracht, während die Schrauben auf der Rückseite angebracht werden.

![Schrauben anbringen](images/case6.jpg)

Dieser Teil kann ein wenig knifflig sein.

Um es etwas zu leichter zu machen, kannst du die Schrauben und Abstandshalter gleichzeitig einsetzen. Wie bereits erwähnt, gehen die Schrauben durch die vier Löcher auf der Rückseite, während die Abstandshalter auf der Vorderseite angebracht werden.

Folge den Fotos:

![Abstandshalter anbringen](images/case7.jpg)

Sobald sie verbunden sind, nimm einen Schraubenzieher und ziehe jede kleinen Schraube an, um die Gehäuserückseite an der Leiterplatte zu befestigen.

![Schrauben anziehen](images/case8.jpg)

![Schrauben anziehen](images/case9.jpg)

Wiederhole diesen Vorgang für alle vier Löcher auf der Rückseite des Chatters, bis es so aussieht:

![Rückseite fertig](images/case10.jpg)

#### Vorderseite und Anzeige

Nimm nun das größte Gehäuseteil und den Bildschirm.

![Vorderseite und Bildschirm](images/front1.jpg)

Auf der linken und rechten Seite des Bildschirms befinden sich zwei Aufkleber. Von diesen muss die Schutzfolie abgezogen werden.

![Schutzfolie abziehen](images/front2.jpg)

![Bildschirm ohne Schutzfolie](images/front3.jpg)

Nimm nun das große Gehäuse und stecke das orangefarbene Anschlusskabel, das mit dem Bildschirm verbunden ist, durch das Gehäuse, wie auf dem Foto unten gezeigt:

![Anschlusskabel](images/front4.jpg)

Achte darauf, dass sich der Bildschirm auf der richtigen Seite befindet, denn er wird gleich auf das Gehäuse geklebt.

![Bildschirm auf Gehäuse](images/front5.jpg)

Du kannst nun den Bildschirm und das Gehäuse zur Seite legen.

**Nimm die Leiterplatte und folge den nächsten Schritten sorgfältig.**

Es gibt ein **kleines graues Teil**, das sich an der Stelle befindet, wo der Bildschirm hingehört. Du musst das graue Teil langsam aus dem Schlitz herausziehen, aber nicht ganz. Ziehe es gerade so weit heraus, dass das orangefarbene Anschlusskabel, das mit dem Bildschirm verbunden ist, hineingesteckt werden kann.

![Bildschirm-Stecker öffnen](images/front6.jpg)

Nimm danach das Gehäuse mit dem Bildschirm und stecke das orangefarbene Anschlusskabel zwischen den grauen Verschluss und den Schlitz.

![Anschlusskabel einstecken](images/front7.jpg)

Schließe den grauen Verschluss indem du ihn an die Stelle zurück drückst, an der er sich vorher befand. Vergewissere dich, dass er wieder einrastet.

![Verbindung einrasten](images/front8.jpg)

![Verbindung von der Seite](images/front9.jpg)

Platziere das Gehäuse so auf dem Chatter wie unten gezeigt:

![Gehäuse aufsetzen](images/front10.jpg)

Wieder einmal ist es Zeit für kleine Schrauben. Nimm zwei davon und stecke sie in die beiden Löcher unten an der Vorderseite.

![Gehäuse verschrauben](images/front11.jpg)

Nimm den Schraubenzieher und zieh alles fest an.

![Schrauben anziehen](images/front12.jpg)

Die Chatter sollten jetzt so aussehen:

![Gehäuse verschraubt](images/front13.jpg)

Jetzt ist es an der Zeit, die **Schutzfolie vom Bildschirm abzuziehen**.

![Schutzfolie abzuziehen](images/front14.jpg)

#### Tasten

Wir haben **Aufkleber** vorbereitet, damit du weißt, welcher Knopf für welchen Buchstaben oder welche Zahl steht.

![Aufkleber](images/sticker1.jpg)

Ziehe die Aufkleber vom Papier ab und platziere sie so auf dem Chatter:

![Aufkleber anziehen](images/sticker2.jpg)

![Aufkleber auf dem Chatter](images/sticker3.jpg)

Es ist Zeit für das letzte Gehäuse.

Du solltest nur noch dieses eine Gehäuse und große Schrauben haben. Du wirst zwei große Schrauben pro Chatter verwenden.

![Gehäuse für Bildschirm und Schrauben](images/cover1.jpg)

Stülpe das Gehäuse so über den Bildschirm:

![Gehäuse für Bildschirm anbringen](images/cover2.jpg)

Nimm zwei große Schrauben und stecke sie in die Löcher ganz links und ganz rechts.

![Bildschirm-Gehäuse verschrauben](images/cover3.jpg)

Ziehe die Schrauben wieder mit dem Schraubenzieher an.

![Schrauben anziehen](images/cover4.jpg)

**Herzlichen Glückwunsch, du bist zum letzten Teil des Zusammenbaus von Chatter gekommen.**

Bringe nun die **Tastenkappen** an.
Dieser Teil ist nicht so notwendig wie die anderen Teile, aber er wird dir das Leben leichter machen.

Es sollten **17 Tastenkappen** pro Chatter sein, aber eine hiervon ist ein zusätzliches Ersatzteil, falls du eine von ihnen verlierst.

![Tastenkappen](images/cap1.jpg)

Lege je eine Kappe oben auf jeden Taster und achte darauf, dass sie mit einem "Klick" einrasten!

![Tastenkappen aufsetzen](images/cap2.jpg)

**Herzlichen Glückwunsch! Wir sind am Ende angelangt.**
**Du hast deine Chatter zusammengebaut!**

Sie sollten so aussehen, wenn du alle Regeln befolgst hast:

![Chatter fertig zusammengebaut](images/final.jpg)

#### Batterie

**Jetzt kannst Du die Batterien einlegen und die Chatter einschalten!**

![Batterien einlegen](images/bat.jpg)

**Aufpassen! Achte auf die Polarität der Batterien!**

Die Batterien sind mit zwei Symbolen gekennzeichnet, die die Polarität der Batterie angeben: **Plus (+) und Minus (-)**.

Der Plus-Teil (+) hat am Ende eine kleine Metallwölbung, während der Minus-Teil (-) eine kleine Delle hat. Das ist sehr wichtig, denn beim Einsetzen der Batterien musst du darauf achten, welche Seite wohin gehört.

**Dieser Teil ist wirklich wichtig:**
Nimm eine Batterie und lege sie so in einen der beiden äußeren Schlitze, dass das Minus-Symbol (-) näher an der kleinen Feder liegt und das Plus-Symbol (+) von ihr wegschaut. Achte beim Einsetzen darauf, zuerst den Minus (-) -Teil einzuführen, so dass du die Feder mit der Batterie zusammendrücken und dann den anderen Teil leicht in die Halterung einführen kannst.

## Der erste Test

Nachdem wir nun alles gelötet und zusammengebaut haben, ist es an der Zeit zu überprüfen, ob alles richtig funktioniert.

### Schalte deinen Chatter ein!

Du kannst ihn einschalten, indem du den Ein-Aus-Knopf auf der linken Seite verschiebst.

Nachdem dein Chatter eingeschaltet ist, wird ein erster Test angezeigt.

Dieser Test sieht so aus und dient dazu, die Tasten zu überprüfen:

![Tastentest](images/test1.jpg)

Du musst nun jede einzelne der Tasten drücken. Wenn eine Taste richtig funktioniert, wird der Kreis auf deinem Bildschirm grün. Auf den folgenden Fotos kannst du sehen, wie alles aussehen sollte.

![Alle Tasten überprüfen](images/test2.jpg)

Wenn du erfolgreich überprüft hast, dass alle Tasten funktionieren, wird der Summer einen Ton abspielen.
Wenn du diesen Ton hörst, kannst du eine beliebige Taste drücken, um den Test zu beenden und das Gerät zu starten.

![Tastentest erfolgreich](images/test3.jpg)

Wenn alles in Ordnung ist, sollte das Menü von Chatter wie folgt aussehen:

![Menü von Chatter](images/inbox.jpg)

Herzlichen Glückwunsch! Du hast es bis zum Ende der Bauanleitung geschafft!

Im folgenden Kapitel erfährst du, was als Nächstes auf dich wartet.

