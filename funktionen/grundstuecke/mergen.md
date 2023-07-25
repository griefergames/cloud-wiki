---
description: Zusammenfügen von Grundstücken
---

# Mergen

Du hast die Möglichkeit mehrere deiner Grundstücke zu verbinden und ein großes Grundstück daraus zu erstellen.

{% hint style="info" %}
Das Mergen auf Citybuild-Spawn-Regionen ist nicht möglich.
{% endhint %}

Um Grundstücke verbinden zu können, müssen diese nebeneinander liegen. Jeder Merge-Vorgang kostet <mark style="color:orange;">50.000$</mark>. Pro Merge-Vorgang wird immer eine Richtung zusammengefügt, es werden also in der Regel _**3 Merge-Vorgänge**_ benötigt.

## Die richtige Vorbereitung

Um Probleme oder Fehler zu vermeiden, gibt es ein paar Punkte, die man vor dem Merge-Vorgang vorbereiten kann, um häufige Fehlerquellen auszuschließen.

* **Entferne alle Personen aus den Listen von Vertrauten, Helfern & Verbotenen**\
  _Es passiert oft, dass die Listen sich nicht vollständig Synchronisieren, wenn auf mehreren Plots Spieler in den Listen sind._
* **Prüfe ob du Wasser oder Lava an den Grundstücksrändern platziert hast**\
  Durch das zusammenfügen der Grundstücke wird die Straße zwischen den Grundstücken zu deinem Grundstück. Es kann also passieren, dass Wasser oder Lava danach fließen.
* **Alias temporär entfernen**\
  Manchmal passiert es, dass ein Alias auf nur einem Grundstück zurückbleibt, deshalb empfehlen wir, das Alias für den Merge-Vorgang zu entfernen und danach neu zu setzen.

{% hint style="danger" %}
Ränder, Wände sowie Streamer- & Admin-Ränder verschwinden beim Mergevorgang.
{% endhint %}

## Das Mergen

Beim Merge-Vorgang selbst ist es wichtig zu beachten, wie man wo steht.

Um Grundstücke zu Mergen muss der Befehl `/merge` eingegeben werden und dieser mit `/merge confirm` bestätigt werden.

### Die Blickrichtung

Beim Mergen ist die Blickrichtung und die Position entscheidend. Es verbinden sich die Grundstücke ab dem Grundstück auf dem man steht in der Blickrichtung.

Im folgenden Beispiel werden die <mark style="color:red;">rot markierten Grundstücke</mark> auf <mark style="color:red;">jeden Fall</mark> an das Grundstück gemerged. Das <mark style="color:blue;">blaue Grundstück</mark> ist in der entgegengesetzten Richtung. Dieses wird <mark style="color:blue;">in der Regel nicht</mark> mit verbunden, jedoch passiert dieses <mark style="color:blue;">ebenfalls in Ausnahmefällen</mark>.

<figure><img src="../../.gitbook/assets/image (29).png" alt="" width="375"><figcaption><p>Der erste Merge-Vorgang</p></figcaption></figure>

Wählt also die Position für den Merge-Vorgang so, dass möglichst viele Grundstücke in einem Merge-Vorgang zusammengefügt werden.

<figure><img src="../../.gitbook/assets/image (15).png" alt="" width="375"><figcaption><p>Schaubild 2. Merge-Vorgang</p></figcaption></figure>

Merged man von einem Merge-Grundstück, wird von jedem Grundstück des Merges aus, die Aktion ausgeführt. Im obrigen Beispiel ist zu sehen, dass beide Grundstücke angefügt werden. Die Straße zwischen den Grundstücken bleibt jedoch bestehen und muss mit einem Merge-Vorgang über die Straße entfernt werden.

