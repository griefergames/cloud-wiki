---
description: 3...2...1... Verkauft!
---

# Auktionshaus

Wertvolle Gegenstände verkaufen war noch nie so einfach. Das Auktionshaus verkauft eure wertvollsten Items an den Höchstbietenden.

<figure><img src="../../.gitbook/assets/image (59).png" alt=""><figcaption><p>Das Auktionshaus am Spawn</p></figcaption></figure>

Das Grundprinzip ist einfach: **Ware einstellen, warten, bieten lassen, kassieren** oder sich in den Bieterkrieg mit einreihen, gewinnen und abholen.

## Auktionsübersicht

<div align="center"><figure><img src="../../.gitbook/assets/image (60).png" alt="" width="174"><figcaption><p>Übersicht</p></figcaption></figure></div>

Ihr bekommt standardmäßig alle Auktionen angezeigt, aufsteigend nach der Restzeit der Auktion. Ihr erhaltet alle wichtigen Informationen zu einer Auktion direkt auf dem Item.

Hier habt ihr nun mehrere Optionen:

* **Klick auf ein Item:** Öffnet die Auktion dieses Items
* ![](<../../.gitbook/assets/image (67).png>)**Auktionshistorie:** Zeigt alle ausgelaufenen Auktionen der letzten 30 Tage
* ![](<../../.gitbook/assets/image (68).png>) **Meine beobachteten Auktionen:** Hier befinden sich alle Auktionen, bei denen ihr geboten habt
* ![](<../../.gitbook/assets/image (70).png>)**Filter:** Hier können bestimmte Materialien oder Kategorien gefiltert werden
* ![](<../../.gitbook/assets/image (72).png>)**Eigene Auktionen:** Hier befinden sich eure eigenen Auktionen und hier können neue Auktionen erstellt werden.

## Bieten

<figure><img src="../../.gitbook/assets/image (73).png" alt="" width="175"><figcaption><p>Auktionsfenster</p></figcaption></figure>

In der Auktionsansicht habt ihr die Möglichkeit, auf das Item zu bieten. Für das Bieten stehen zwei verschiedene Varianten zur Auswahl.

### Gebot

Mit einem Gebot wird der Betrag direkt geboten und der Auktionspreis erhöht sich auf diesen Betrag.

### Gebotslimit

Mit einem Gebotslimit erhöht sich der Betrag nur so weit, dass ihr Höchstbietender seid. Danach bietet das Gebotslimit automatisch für euch weiter, bis das Limit erreicht ist.

{% hint style="warning" %}
In beiden Fällen wird der **gebotene Betrag direkt von eurem Konto abgezogen**. Ihr erhaltet dieses zum Ende der Auktion zurück (bzw. das zu viel Gezahlte bei einem Limit). Das Geld kann während der Auktion nur entnommen werden, während man _**nicht**_ Höchstbietender ist.
{% endhint %}

### Geld abholen

Wurdet ihr Überboten und möchtet nicht weiter mitbieten, könnt ihr auch noch während der Auktion euer Geld wieder abholen. Hierfür geht ihr in die einzelne Auktion und drückt den Button "Geld abholen".

Wenn eine Auktion endet, werden alle Gelder an die nicht erfolgreichen Bieter zurückgezahlt. Ebenso werden ggf. Überschüsse des Gewinners eines Gebotslimits ausgezahlt.

{% hint style="info" %}
Diese Transaktionen finden automatisch im Hintergrund statt. Solltest du nicht online sein, können die Transaktionen im `/moneylog` nachvollzogen werden.
{% endhint %}

### Item abholen

Hast du eine Auktion gewonnen _(oder ist dein Item nicht verkauft worden)_ kannst du das Item in der Auktion abholen. Dazu öffne die gewünschte Auktion (über beobachtete Auktionen, Auktionshistorie oder Meine Auktionen) und klicke auf ![](<../../.gitbook/assets/image (54).png>), um das Item zu erhalten.

{% hint style="info" %}
Du brauchst einen freien Inventarplatz für das Item, auch wenn du bereits ein gleiches Item davon im Inventar hast.
{% endhint %}

{% hint style="warning" %}
Die auslaufenden Auktionen werden alle **15 Minuten** verarbeitet. Es befinden sich also zeitweise ausgelaufene Auktionen in der Übersicht.
{% endhint %}

## Auktion erstellen

Jeder Spieler kann eine neue Auktion erstellen. Dazu wähle im Hauptmenü ![](<../../.gitbook/assets/image (50).png>) Eigene Auktionen. Von dort kann über ![](<../../.gitbook/assets/image (51).png>) eine neue Auktion erstellt werden.

Wähle ein Item aus deinem Inventar, welches du im Auktionshaus anbieten möchtest.\
_&#x44;ieses erscheint dann oben als angezeigtes Item._

### Startpreis festlegen

Du kannst der Auktion einen Startpreis geben. Die Auktion startet dann automatisch auf diesem Preis und ab dort kann geboten werden. Standardmäßig ist der Startpreis auf 0 Dollar, somit ist das niedrigste Gebot 1 Dollar.

### Sofortkaufpreis festlegen

Wird in einer Auktion ein Sofortkaufpreis hinterlegt, ist es möglich, das Item für den Preis sofort zu kaufen. Ebenfalls wird das Item für diesen Preis automatisch verkauft, sobald ein Gebot diesen Preis erreicht. Somit wird das Item höchstens zu diesem Sofortkaufpreis verkauft.

### Laufzeit festlegen

Hier kann angegeben werden, wie lange die Auktion im Auktionshaus bleiben soll. Nach Ablauf der Laufzeit gewinnt der Höchstbietende die Auktion. Man sollte also darauf achten, wie lange man die Auktion einstellen will, da ggf. der Höchstbietende sonst lange Zeit auf den Gewinn der Auktion warten muss. **Das Erreichen des Sofortkaufpreises beendet die Auktion sofort.**

Folgende Laufzeitstufen gibt es:\
1 Stunde, 3 Stunden, 6 Stunden, 12 Stunden, 24 Stunden _**(Standard)**_, 48 Stunden _(2 Tage)_, 120 Stunden _(5 Tage)_ , 168 Stunden _(7 Tage)_

### Auktion bestätigen & erstellen

Wenn alle gewünschten Einstellungen getroffen sind, kann die Auktion mit Klick auf "Bestätigen" erstellt werden.

Je nach Einstellung fällt dort eine **Gebühr** für das Erstellen der Auktion von **10 %** an. Dafür ausschlaggebend ist der höchste eingestellte Preis (Mindestpreis, Sofortkaufpreis). Diese Gebühr muss beim Erstellen gezahlt werden und wird nicht erstattet, falls das Item nicht verkauft wird.

## Auktion zurückziehen

Verklickt? Falsch eingestellt? Oder das Item doch anderweitig verkauft?\
Dann kannst du die Auktion zurückziehen.

Gehe dazu in deine Auktion und klicke auf ![](<../../.gitbook/assets/image (53).png>), um die Auktion zurückzuziehen.

{% hint style="danger" %}
Es fällt eine **Strafgebühr** von **10 % auf das aktuelle Gebot** an!\
Je höher das Item also bereits geboten wurde, desto teurer wird das Zurückziehen.
{% endhint %}

## Auktionshistorie

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

Die Auktionshistorie zeigt die Auktionen der letzten 30 Tage an. Hier können auch Auktionen angesehen werden, in welchen man nicht involviert (bieten, verkaufen) war.

{% hint style="info" %}
Zusätzlich zu den letzten 30 Tagen befinden sich hier auch ältere Auktionen, bei denen noch Werte (Items, Geld) zum Abholen vorhanden sind.
{% endhint %}

## Auktionen filtern

In einigen Menüs stehen ![](<../../.gitbook/assets/image (56).png>) Filter zur Verfügung.

Hier kann per Klick auf ein Item im Inventar auf einen Item-Typ gefiltert werden. (Z. B. Feder -> Zeigt auch Fly+-Flags oder Fly-Perks an). Zusätzlich kann per Klick auf den Filter-Button eine vorgegebene Kategorie gewählt werden. Im Filtermenü kann mit Klick auf den ![](<../../.gitbook/assets/image (58).png>) Kein-Filter-Button, ein gesetzter Filter (auch Item-Typ-Filter) aufgehoben werden.

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption><p>Filtermenü</p></figcaption></figure>

Die folgenden Filter stehen aktuell zur Verfügung:

* **Einlösbare Items:** Filtert alle Items, welche mit Rechtsklick eingelöst werden können / einen Sicherheitscode besitzen.
* **Rüstungen:** Filtert alle Items, welche eine Rüstung sind bzw. Rüstungswerte besitzen.
* **Waffen:** Filtert alle Items, die Waffen sind bzw. Waffenwerte besitzen.
* **Werkzeuge:** Filtert alle Items, die Werkzeuge sind.
* **Köpfe:** Filtert alle Items, die Köpfe sind.
* **Prefixe:** Filtert alle Items, die Prefixe sind.
* **Perks:** Filtert alle Items, die im Bereich [Perks ](perks.md)einlösbar sind.
* **Rand-Items & Wand-Items:** Filtert alle Items, die Wand-/Rand-Items sind.
* **Verzaubert:** Filtert alle Items, die verzaubert sind (enthält auch Werkzeuge etc.).

{% hint style="info" %}
Items können sich in mehreren Kategorien gleichzeitig befinden. (Z. B. ist ein Prefix sowohl ein Prefix, als auch verzaubert oder befindet sich je nach Item in weiteren Kategorien.)
{% endhint %}

{% hint style="success" %}
Weitere Vorschläge für Kategorien können im Forum in den Vorschlägen eingereicht werden.
{% endhint %}
