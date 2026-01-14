---
description: Automatisches Einsammeln von Farm-Items auf dem Grundstück
---

# Farm-Sammler

Mit dem Farm-Sammler (Plot-Collector) können automatisch die generierten Items auf dem Grundstück eingelagert werden. Dieses reduziert die Anzahl an Trichtern, die für Farmen gebraucht werden.

<figure><img src="../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

Im Menü sind alle verfügbaren Materialien zu sehen. Ist ein Sammler aktiviert, ist das Material verzaubert und die Informationen zum Sammler werden auf dem Item angezeigt.

## Wie funktioniert das?

Das System sammelt automatisch die Items auf, welche natürlich oder durch Block-zu-Block-Interaktion (Kolben, Flug-Maschienen etc.) droppen. Also ein "magischer Trichter" für das gesamte Grundstück.

Ist ein Sammler aktiviert, droppen diese Items nicht mehr, sondern werden direkt in das dafür hinterlegte Lager geführt. Folgendes muss jedoch beachtet werden:

{% hint style="danger" %}
Ist das Lager voll oder nicht geladen, droppen die Items nicht. Der Abbau findet jedoch wie gewohnt statt. Die Lager werden **nicht automatisch geladen**, die Position sollte also klug gewählt werden.
{% endhint %}

{% hint style="info" %}
Items, die durch **Spieler-Interaktion** (z.B. selbst abbauen) abgebaut werden, werden **nie eingesammelt**. Das gilt auch für den Abbau von Kisten o.Ä.
{% endhint %}

## Sammler verwalten

<div align="left"><figure><img src="../../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure></div>

### Neuen Sammler aktivieren

Das Einsammeln wird pro Material aktiviert. Stelle dich dafür vor dein gewünschtes Lager und öffne das Sammler-Menü mit `/p collectors`  und führe für das gewünschte Material folgende Schritte aus:

1. Klicke das gewünschte Material im Menü an
2. Klicke (am besten mit Rechtsklick) auf das Lager (Truhe, Fass etc.), in den die Items fließen sollen
3. Fertig! Das war schon alles.

### Sammler deaktivieren

Um einen Sammler wieder zu entfernen, öffne das Menü mit `/p collectors` und führe folgende Schritte aus:

1. Klicke das gewünschte Material im Menü an.
2. Sobald sich das Fenster schließt, sneake einmal.
3. Fertig! Du erhältst eine Meldung: "Es ist nun kein Lager-Ziel festgelegt"

### Drop aktivieren / deaktivieren

Mit den Sammlern ist noch eine weitere Funktion verfügbar. Es kann jetzt der Drop von Farmen komplett deaktiviert werden.&#x20;

Wenn man z.B. keine Items mehr benötigt oder etwas umbauen will, kann man nun den Drop vollständig deaktivieren. Die Farm wächst normal weiter, jedoch werden die Items nicht mehr gedroppt und nicht mehr eingesammelt, währen der Drop deaktiviert ist.

Um einen Drop zu deaktivieren / aktivieren öffne das Menü mit `/p collectors` und Shift-Klicke auf das gewünschte Material, um den Drop-Modus zu wechseln.

{% hint style="info" %}
Standardmäßig ist der Drop immer aktiviert. Dieses Tool wird aber auch vom Team verwendet, um Drops von Farmen, die nicht aufgesammelt werden bzw. Spieler nicht mehr online sind, zu deaktiiveren.
{% endhint %}

## Sammler-Verpflichtung

Bei manchen Grundstücken kann es auf Grund der Größe oder Menge der Farmen notwendig sein, dass die Besitzer die Sammler verwenden, um die Server-Performance zu schonen.

Für diesen Fall kann vom Team eine Verpflichtung für den Sammler hinterlegt werden. Dieses ist im Menü `/p collectors` dann wie folgt ersichtlich:

<figure><img src="../../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Durch das Hinterlegen eines Ziels für den Drop, ist dann das Material automatisch wieder aktiviert und wird normal produziert. Eine nachträgliche Entfernung dieser Einstellung durch das Team ist nicht notwendig.
{% endhint %}
