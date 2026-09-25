---
description: Trichter neu verbunden
---

# 📥 Trichter-System

Auf GrieferGames wurden die Funktionen der Trichter erweitert. Dadurch entstehen viele neue Möglichkeiten und Verbesserungen.

## Allgemeine Trichter-Informationen

Auf GrieferGames sind die Trichter-Ticks angepasst, um die Serverlast durch Trichter zu reduzieren.

### Trichter-Tick

Die Häufigkeit, mit der die Trichter auf GrieferGames ticken, ist reduziert.

Ein Trichter tickt standardmäßig alle <mark style="color:red;">**8 Ticks**</mark> und verschiebt dabei <mark style="color:red;">**1 Item**</mark>. Auf GrieferGames tickt ein Trichter alle <mark style="color:green;">**80 Ticks**</mark> und verschiebt dabei <mark style="color:green;">**12 Items**</mark>. Wird in einem Tick kein Item verschoben, wartet der Trichter ebenfalls <mark style="color:green;">**80 Ticks**</mark>, bevor er erneut prüft, ob ein neues Item vorhanden ist.

## Die neuen Trichter-Optionen

Machst du beim Sneaken einen Rechtsklick auf einen platzierten Trichter, öffnet sich ein Optionsmenü für diesen Trichter.

<figure><img src="../../.gitbook/assets/image (94).png" alt=""><figcaption><p>Trichter-Hauptmenü</p></figcaption></figure>

Dieses Menü bietet verschiedene Einstellungsoptionen, welche im Folgenden erläutert werden.

### Item-Anzahl einstellen

Mit dem Button <img src="../../.gitbook/assets/image (11) (1).png" alt="" data-size="line"> kann die <mark style="color:orange;">Anzahl der transportierten Items</mark> festgelegt werden. **Standardeinstellung:** 12 Items

Folgende Optionen stehen zur Verfügung:

* 1 Item
* 12 Items
* 64 Items

{% hint style="info" %}
Es wird immer nur ein Stack gleichzeitig bewegt. Hat ein Stack weniger Items als die eingestellte Anzahl, wird nur die Anzahl dieses Stacks verschoben.
{% endhint %}

### Force Fast Tick

Mit der <img src="../../.gitbook/assets/image (12) (1).png" alt="" data-size="line"> <mark style="color:orange;">Force Fast Tick</mark>-Option ist es möglich, die Tick-Geschwindigkeit auf den Standard zurückzusetzen (siehe [Trichter-Tick](trichter-system.md#trichter-tick)). Diese Möglichkeit wird für manche Redstone-Schaltungen benötigt, die sich nicht anders umsetzen lassen. Der Großteil der Schaltungen lässt sich jedoch so umbauen, dass sie auch auf GrieferGames funktionieren.

{% hint style="warning" %}
Diese Option steht nur der Administration oder bei aktivierter `hopper-fast-tick`-Flag auf dem Grundstück zur Verfügung. Diese Flag wird in seltenen Ausnahmefällen vergeben und kann über das Ticket-System beantragt werden.
{% endhint %}

### Sammelradius

Über die Einstellungsoptionen <img src="../../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> kann der Sammelradius eingestellt werden. Der Sammelradius bestimmt den Umkreis, aus dem herumliegende Items vom Trichter eingesammelt werden.

Der maximale Sammelradius beträgt <mark style="color:orange;">**15 Blöcke**</mark> und ist zusätzlich durch die <mark style="color:orange;">**Plot-Grenze begrenzt**</mark>.

{% hint style="info" %}
Radius 0 deaktiviert das Einsammeln von Items aus der Luft.
{% endhint %}

### Verbundener Trichter

Über die <img src="../../.gitbook/assets/image (11).png" alt="" data-size="line"> <mark style="color:orange;">**Trichterverbindung**</mark> kann das Ziel des Trichters direkt ausgewählt werden. Das Ziel kann in einem Umkreis von <mark style="color:orange;">**30 Blöcken**</mark> gewählt werden.

{% hint style="info" %}
Trichter können mit allen Blöcken verbunden werden, die ein Inventar haben – also mit allen Blöcken, in die ein Trichter auch standardmäßig weiterleiten kann.
{% endhint %}

Um einen Trichter zu verbinden, klicke auf <img src="../../.gitbook/assets/image (11).png" alt="" data-size="line"> und anschließend mit leerer Hand per Rechtsklick auf den Block, der verbunden werden soll.

Der Verbindungsmodus wird beendet, wenn du erneut auf denselben Trichter klickst oder die Entfernung zu groß wird.

{% hint style="success" %}
Der Radius kann ggf. durch weitere Rechte erweitert sein, z. B. auf die Simulation- oder View-Distance.
{% endhint %}

### Mehrfachverbindungen

Über die <img src="../../.gitbook/assets/image (29) (3) (1).png" alt="" data-size="line"> <mark style="color:orange;">**Mehrfachverbindungen**</mark> können mehrere Endpunkte anhand von Materialien für den Trichter festgelegt werden.

#### Übersicht über bestehende Verbindungen

<figure><img src="../../.gitbook/assets/image (98).png" alt=""><figcaption><p>Übersicht der Mehrfachverbindungen</p></figcaption></figure>

In dieser Ansicht sind die bereits eingerichteten Verbindungen zu sehen. Pro Material kann ein Endpunkt als Ziel existieren. Mit einem Klick auf das Material kann der Endpunkt entfernt werden.

Mit einem Klick auf <img src="../../.gitbook/assets/image (12).png" alt="" data-size="line"> <mark style="color:orange;">**Verbindungsmodus starten**</mark> kann der Verbindungsmodus für Mehrfachverbindungen gestartet werden.

#### Endpunkte hinzufügen / Verbindungsmodus

Sobald der Verbindungsmodus aktiv ist, können neue Verbindungen hinzugefügt werden, indem du mit dem gewünschten Material in der Hand auf einen möglichen Endpunkt (siehe [Verbundener Trichter](trichter-system.md#verbundener-trichter)) klickst.

<figure><img src="../../.gitbook/assets/image (5) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Die Verbindung wird dann hinzugefügt und im Chat bestätigt. Anschließend kann das nächste Material hinterlegt werden.

Der Verbindungsmodus wird durch das Sneaken beendet.

### Verbindungs-Aufteilung (Split)

Dieser Modus ermöglicht es, dass Gegenstände auf mehrere Anlagen aufgeteilt werden, wenn diese z. B. aus einem [Unbegrenzten Speicher](unbegrenzter-speicher.md) mit einem Trichter gezogen werden.

<figure><img src="../../.gitbook/assets/image (99).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Diese Option ist ausschließlich zum Verteilen von Items auf verschiedene Anlagen gedacht und nicht zur freien Verwendung für beliebige Konstruktionen.

Für eine anderweitige Verwendung musst du im Ticket-System eine Einzelfallgenehmigung anfragen.
{% endhint %}

Die Aufteilung kann bis zu 10 Ziele mit gleicher Geschwindigkeit beliefern. Mit jedem weiteren Ziel wird die Geschwindigkeit pro Ziel etwas langsamer.

Die Items werden "im Kreis" an die Ziele verteilt. Ist ein Ziel voll, wird es übersprungen und im nächsten Tick normal das nächste Ziel beliefert.

### Optische Anzeige

Mit einem Klick auf <img src="../../.gitbook/assets/image (34).png" alt="" data-size="line"> <mark style="color:orange;">**Optische Anzeige**</mark> werden die Verbindungen und der Sammelradius des Trichters mit Partikeln angezeigt.

<figure><img src="../../.gitbook/assets/image (6) (2).png" alt="" width="375"><figcaption><p>Optische Anzeige</p></figcaption></figure>

## Item-Filter

Mit dem Trichter-System ist es ebenfalls möglich, die Items zu filtern, welche in den Trichter aufgenommen werden sollen.

{% hint style="info" %}
Die Filter bestimmen, welche Items ein Trichter "einsaugt" oder aus anderen Inventaren entnimmt. Legst du Items direkt in den Trichter, werden die Filter nicht berücksichtigt.
{% endhint %}

Die folgenden Filter-Optionen lassen sich miteinander kombinieren.

Die Filter können mit einem Shift-Klick auf das <img src="../../.gitbook/assets/image (37) (2).png" alt="" data-size="line"> Filter-Icon entfernt werden. Das Icon wechselt je nach gefiltertem Material.

### Materialfilter

<figure><img src="../../.gitbook/assets/image (95).png" alt=""><figcaption><p>Beispiel Materialfilter auf Grasblock</p></figcaption></figure>

Um ein Material für den Trichter zu filtern, kann das Material im Hauptmenü aus dem eigenen Inventar ausgewählt werden. Das gefilterte Material ist dann an der Stelle des <img src="../../.gitbook/assets/image (37) (2).png" alt="" data-size="line"> zu sehen.

Mit einem Klick auf das gefilterte Material oder <img src="../../.gitbook/assets/image (37) (2).png" alt="" data-size="line"> öffnet sich das Filter-Menü mit den folgenden Optionen.

<figure><img src="../../.gitbook/assets/image (96).png" alt=""><figcaption><p>Filter-Übersicht</p></figcaption></figure>

### Verzauberungsfilter

Mit einem Klick auf den <img src="../../.gitbook/assets/image (34) (1).png" alt="" data-size="line"> <mark style="color:orange;">**Verzauberungsfilter**</mark> aktiviert sich der Verzauberungsfilter. Bei einem weiteren Klick öffnet sich das Menü mit den filterbaren Verzauberungen.

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Übersichtsseite Verzauberungen</p></figcaption></figure>

In dieser Ansicht können nun die Verzauberungen angewählt werden, welche auf dem Item vorhanden sein müssen. Mit **Rechtsklick** wird die gewünschte Verzauberungsstufe erhöht, mit einem **Linksklick** verringert. Mit einem **Shift-Klick** wird die Verzauberung aus dem Filter entfernt.

{% hint style="warning" %}
Werden mehrere Verzauberungen gewählt, müssen alle Verzauberungen auf dem Item vorhanden sein. Es muss auch die entsprechende Stufe der Verzauberung vorhanden sein.
{% endhint %}

Zusätzlich zum Verzauberungsfilter steht mit dem <img src="../../.gitbook/assets/image (37) (2).png" alt="" data-size="line"> unter dem <img src="../../.gitbook/assets/image (34) (1).png" alt="" data-size="line"> der Filter "keine Verzauberung" zur Verfügung.

### Effektfilter

Mit einem Klick auf den <img src="../../.gitbook/assets/image (7) (1) (2).png" alt="" data-size="line"> <mark style="color:orange;">**Effektfilter**</mark> aktiviert sich der Effektfilter. Bei einem weiteren Klick öffnet sich das Menü mit den filterbaren Effekten.

<figure><img src="../../.gitbook/assets/image (39).png" alt=""><figcaption><p>Übersichtsseite Effekte</p></figcaption></figure>

In dieser Ansicht können nun die Effekte angewählt werden, welche auf dem Item vorhanden sein müssen. Mit dem Anklicken des Effekts wird der Filter aktiviert oder deaktiviert.

{% hint style="warning" %}
Werden mehrere Effekte gewählt, müssen alle Effekte auf dem Item vorhanden sein.
{% endhint %}

Zusätzlich zum Effektfilter steht mit dem <img src="../../.gitbook/assets/image (37) (2).png" alt="" data-size="line"> unter dem <img src="../../.gitbook/assets/image (7) (1) (2).png" alt="" data-size="line"> der Filter "keine Effekte" zur Verfügung.

### Signierungsfilter

Mit einem Klick auf den <img src="../../.gitbook/assets/image (24) (1) (2).png" alt="" data-size="line"> <mark style="color:orange;">**Signierungsfilter**</mark> aktiviert sich der Signierungsfilter. Bei einem weiteren Klick öffnet sich das Menü für die Einstellung der Signierung.

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption><p>Einstellungsmenü Signierungen</p></figcaption></figure>

Die folgenden Optionen der Signierung können eingestellt werden:

* <img src="../../.gitbook/assets/image (8) (2) (2).png" alt="" data-size="line"> **Signierung von:** Filtert, welcher Spieler die Signierung erstellt haben muss
* <img src="../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt="" data-size="line"> **Signierung am:** Filtert, an welchem Datum die Signierung erstellt wurde
* <img src="../../.gitbook/assets/image (22).png" alt="" data-size="line"> **Signierung:** Filtert den Text der Signierung

{% hint style="info" %}
Der Text der Signierung muss die eingestellten Zeichen bzw. den eingestellten Text nur enthalten, aber nicht vollständig übereinstimmen.
{% endhint %}

### Beschreibungsfilter

Dieser Abschnitt folgt bald. Auf der Cloud ist dieser Filter aufgrund der internationalisierten (übersetzten) Beschreibungen aktuell nicht möglich.

### Namensfilter

Dieser Abschnitt folgt bald. Auf der Cloud ist dieser Filter aufgrund der internationalisierten (übersetzten) Namen aktuell nicht eindeutig.
