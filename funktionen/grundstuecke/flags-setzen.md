# Flags setzen

Auf dem Grundstück können Einstellungen in Form von sogenanten Flags gesetzt werden. Damit kann z.B. ein Verhalten angepasst oder eine Funktion freigegeben werden.

Der einfachste Weg Flags zu Verwalten ist, über das `/?` -Menü -> Grundstücke -> Flag-Verwaltung. \
Mehr dazu unter [Hilfe benutzen](hilfe-benutzen.md).

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>Flag-Übersicht</p></figcaption></figure>

Verzauberte Bücher stehen für Flags, welche gesetzt wurden. In der Beschreibung einer Flag wird die Funktion dieser Flag erklärt und der Status der Flag angezeigt. Mit einem Klick auf das Buch öffnet sich das Verwaltungsmenü für die Flag, welches je nach Art der Flag sich unterscheidet.

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Tooltip einer Flag</p></figcaption></figure>

### An/Aus (Boolean-Flag)

Eine Boolean-Flag kann entweder true oder false sein. true = an, false = aus.

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Boolean-Flag-Verwaltung</p></figcaption></figure>

Bei der Boolean-Flag stehen drei Buttons zur Auswahl:

* <mark style="color:green;">Aktivieren</mark>
* Flag entfernen (Barriere)
* <mark style="color:red;">Deaktivieren</mark>

### Block / Material Liste (List-Flag)

Eine List-Flag enthält eine Liste an Materialien oder Blöcken, wie z.B. die use-Flag.

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>List-Flag-Verwaltung</p></figcaption></figure>

Klicke in deinem Inventar einen Block an, um diesen hinzuzufügen. Klicke im oberen Menü einen Block an, um diesen zu entfernen. Mit einem Klick auf die Barriere, wird die Flag entfernt.

### Wert-Flags

Es gibt Flags, bei denen ein Wert hinterlegt werden kann. Wie z.B. die time-Flag oder die greeting-Flag. Hier können Texte oder andere Werte wie Zahlen etc. hinterlegt werden.

{% hint style="danger" %}
Diese Flags können aktuell nicht im Menü verwaltet werden, sondern müssen über den Befehl gesetzt werden `/p flag set <Flag-Name> <Wert>` _(z.B. /p flag set time 6000)_
{% endhint %}

