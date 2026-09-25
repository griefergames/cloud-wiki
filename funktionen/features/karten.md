# 🗺️ Karten

Motivkarten zu bauen braucht Zeit, Material und eine Menge Erfahrung.

Wäre es da nicht schön, sein Wunschmotiv schnell und einfach als Karte verfügbar zu haben und sein Heim damit zu dekorieren? Hier hilft der Kartengenerator! Auf dieser Seite erfahrt ihr, wie ihr mit dem Befehl `/createkarte` aus einer eigenen Bilddatei eine Minecraft-Karte erstellt.

## Das Recht für /createkarte

Um den Kartengenerator nutzen zu können, benötigt man das entsprechende Recht.

{% hint style="danger" %}
Derzeit ist dieses Recht nur begrenzt verfügbar und aus den Winter-Kisten erhältlich.
{% endhint %}

Hat man das Recht gewonnen und eingelöst, erhält man die Berechtigung, den Befehl `/createkarte` zu verwenden.

## Was geht, was nicht?

Der Kartengenerator hat einige Einschränkungen.

* Der Befehl hat einen Cooldown von 7 Tagen.
* Die erstellten Karten haben einen Kopierschutz (AntiCopy) vom Server, der sich nicht entfernen lässt.
* Die maximale Kartengröße beträgt 36 Teile und die Karte muss rechteckig sein.
  * Die Karte kann auch eine kleinere Größe haben und somit aus weniger Teilen bestehen.\
    Dies ermöglicht auch die Erstellung von Karten im Format 3x4 oder 4x4.
  * 36 Kartenteile sind auch in anderer Anordnung möglich, solange die Karte rechteckig ist.\
    Dies ermöglicht beispielsweise auch Karten im Format 3x12, 4x9 oder 6x6.

## Das Motiv vorbereiten

Der Kartengenerator nimmt eine vorgefertigte Grafik (Bilddatei) und wandelt diese in eine Minecraftkarte um.

Damit der Farbraum und die Kartengröße korrekt ermittelt werden können, ist etwas Vorarbeit nötig.

Höhe und Breite der Bilddatei müssen sich jeweils durch 128 Pixel teilen lassen, denn ein Kartenteil umfasst 128 x 128 Pixel. Eine Grafik für eine Karte mit 6x6 Kartenteilen benötigt also beispielsweise eine Größe von 768 x 768 px, eine Bilddatei für eine 3x4-Karte 384 x 512 px.

Minecraft-Karten können nur eine begrenzte Anzahl an Farben darstellen. Ist eine Farbe nicht umsetzbar, wird per Annäherung ein passender Farbwert ermittelt. Das geschieht automatisch und muss nicht vorher in der Bilddatei angepasst werden.

Jedoch führt dieser Vorgang zu einem Qualitätsverlust und kann ggf. zu "falschen" Farbwerten in der Karte führen.

## Das Motiv hochladen

Habt ihr eure Bilddatei vorbereitet und auf die korrekte Größe gebracht, müsst ihr diese im Internet hochladen, um sie für den Generator verfügbar zu machen. Hierfür wird der Dienst ImgBB verwendet.

Ladet die Bilddatei also auf der Seite [https://imgbb.com/](https://imgbb.com/) hoch.

Im nächsten Schritt benötigt ihr den Direktlink zur Grafik. Öffnet hierfür den „Betrachter-Link“, den ihr auf der Seite erhaltet, in einem neuen Tab/Fenster.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Führt einen Rechtsklick auf das Bild durch und wählt aus, dass das Bild in einem neuen Tab geöffnet wird.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Führt erneut einen Rechtsklick auf das Bild durch und wählt aus, dass ihr die Grafikadresse kopieren wollt.

<figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Der kopierte Link ist der Direktlink zu eurem hochgeladenen Bild und endet auf eine entsprechende Datei-Endung (`.jpg`, `.png`, `.gif` etc.).

## Die Karte erstellen

Im letzten Schritt könnt ihr die Karte auf unserem Netzwerk erstellen. Gebt hierfür den Befehl `/createkarte <Link>` ein. Den Platzhalter `<Link>` ersetzt ihr dabei durch die kopierte Adresse der Bilddatei.

Ihr erhaltet die entsprechenden Karten (je nach Größe des hochgeladenen Motivs) in euer Inventar. Achtet darauf, dass ihr genügend Platz in Hotbar und Inventar habt, um alle Kartenteile entgegenzunehmen.
