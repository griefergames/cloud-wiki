---
description: Signieren ist eine Option, um ein Item mit einem Text und deiner Unterschrift zu versehen.
---

# Signieren von Items

{% hint style="info" %}
Dieser Befehl steht dir ab dem [**Titan-Rang**](range/titan-rang.md) zur Verfügung.
{% endhint %}

## Item signieren

Um ein Item zu signieren, halte es in der Hand und füge mit dem Befehl `/sign <Nachricht>` eine Signatur hinzu.

<figure><img src="../../.gitbook/assets/image (28) (1).png" alt=""><figcaption><p>Beispiel-Signierung eines Items</p></figcaption></figure>

* Jedes Item kann immer nur eine Signatur besitzen. Diese kann nur vom Besitzer mit `/unsign` wieder entfernt werden.
* Das Limit der Signierung beträgt 65 Zeichen, Farbcodes zählen dabei **nicht** mit.

### Farbig und fett signieren

* Wenn du farbig signieren möchtest, kannst du die Minecraft-Farbcodes verwenden. Setze dafür vor das jeweilige Wort oder den Buchstaben den Farbcode: `&<Farbcode>TEXT`.
* Um deine Signierung **fett** zu schreiben, füge nach der Farbe und vor dem Text ein `&l` ein. Beispiel: `&<Farbcode>&lTEXT`.

<figure><img src="../../.gitbook/assets/Farbcodes.png" alt=""><figcaption></figcaption></figure>

## Signieren mit Hexadezimal-Farben

* In der Signatur ist es ebenfalls möglich, Hexadezimal-Farben zu verwenden. Diese können mit `&#<Farbcode>` hinzugefügt werden _(Beispiel für die Farbe „Rot“: `&#ff0000`)_.
* Beachte jedoch, dass eine Chatnachricht maximal 256 Zeichen lang sein kann. Die Signierung kann inklusive Farbcodes also nicht länger sein.

{% hint style="info" %}
Möchtest du Hexadezimal-Farben fett schreiben, muss vor jeder Farbe die Formatierung mit `&r` zurückgesetzt werden.
{% endhint %}

## Farbverlauf-Signierung

Mit dem zusätzlichen Recht "Farbverlauf-Signierung" kann mit dem Befehl `/signgradient` ein Text mit einem Farbverlauf signiert werden. Dabei müssen Start- und Endfarbe im Hexadezimalformat hinterlegt werden.

`/signgradient 00FF00 FF0000 Das ist eine signierte Zeile mit Verlauf`

## 2. Zeile signieren

Im [Case-Opening](../features/case-opening.md) kann das Recht gewonnen werden, um eine zweite Zeile auf ein Item zu signieren.

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption><p>2. Zeile signieren-Item aus dem Case-Opening</p></figcaption></figure>

Um eine zweite Zeile hinzuzufügen, kann das Item noch einmal mit `/sign <Text>` signiert werden. Eine zweite Zeile kann nur hinzugefügt werden, wenn die erste Signatur von dir selbst stammt.

Das Datum der Signatur wird dabei aktualisiert. Der Name (inkl. Rang) bleibt erhalten.
