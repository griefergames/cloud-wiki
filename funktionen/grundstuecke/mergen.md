---
description: Verbinden von Grundstücken
---

# Mergen

Du hast die Möglichkeit, mehrere deiner Grundstücke zu verbinden und ein großes Grundstück daraus zu erstellen.

{% hint style="info" %}
Das Mergen auf Citybuild-Spawn-Regionen ist nicht möglich.
{% endhint %}

Um Grundstücke verbinden zu können, müssen diese nebeneinander liegen. Jeder Merge-Vorgang kostet <mark style="color:orange;">50.000 Dollar</mark>. Pro Merge-Vorgang wird immer eine Richtung zusammengefügt. Es werden also für quadratische Grundstücke in der Regel _**3 Merge-Vorgänge**_ benötigt.

## Die richtige Vorbereitung

Um Probleme oder Fehler zu vermeiden, gibt es ein paar Punkte, die du vor dem Merge-Vorgang vorbereiten kannst, um häufige Fehlerquellen auszuschließen.

* **Entferne alle Personen aus den Listen von Vertrauten, Helfern & Verbotenen**\
  &#xNAN;_&#x45;s passiert oft, dass die Listen sich nicht vollständig synchronisieren, wenn auf mehreren Grundstücken Spieler in den Listen sind._
* **Prüfe, ob du Wasser oder Lava an den Grundstücksrändern platziert hast**\
  Durch das Verbinden der Grundstücke wird die Straße zwischen den Grundstücken zu deinem Grundstück hinzugefügt. Es kann also passieren, dass Wasser oder Lava nach dem Vorgang fließen werden.
* **Alias temporär entfernen**\
  Manchmal passiert es, dass ein Alias auf nur einem Grundstück zurückbleibt. Deshalb empfehlen wir, den Alias für den Merge-Vorgang temporär zu entfernen und danach neu zu setzen.

{% hint style="danger" %}
Ränder, Wände sowie Streamer- & Admin-Ränder verschwinden beim Merge-Vorgang.
{% endhint %}

## Das Mergen

Beim Merge-Vorgang selbst ist es wichtig zu beachten, wie man wo steht.

Um Grundstücke zu mergen, muss der Befehl `/merge` eingegeben werden und die Ausführung mit `/merge confirm` bestätigt werden.

### Die Blickrichtung

Beim Mergen ist die Blickrichtung und die Position entscheidend. Es verbinden sich die Grundstücke ab dem Grundstück, auf dem du stehst, in der Blickrichtung.

Im folgenden Beispiel werden die <mark style="color:red;">rot markierten Grundstücke</mark> auf <mark style="color:red;">jeden Fall</mark> mit dem Grundstück verbunden. Das <mark style="color:blue;">blaue Grundstück</mark> ist in der entgegengesetzten Richtung. Dieses wird <mark style="color:blue;">in der Regel nicht</mark> mit verbunden, jedoch passiert dieses <mark style="color:blue;">ebenfalls in Ausnahmefällen</mark>.

<figure><img src="../../.gitbook/assets/image (29).png" alt="" width="375"><figcaption><p>Der erste Merge-Vorgang</p></figcaption></figure>

Wähle also die Position für den Merge-Vorgang so, dass möglichst viele Grundstücke in einem Merge-Vorgang zusammengefügt werden.

<figure><img src="../../.gitbook/assets/image (15).png" alt="" width="375"><figcaption><p>Schaubild 2. Merge-Vorgang</p></figcaption></figure>

Verbindest du von einem Merge-Grundstück weitere Grundstücke, wird von jedem Grundstück des Merge-Vorgangs aus die Aktion ausgeführt. Im obigen Beispiel ist zu sehen, dass beide Grundstücke angefügt werden. Die Straße zwischen den Grundstücken bleibt jedoch bestehen und muss mit einem Merge-Vorgang über die Straße entfernt werden.
