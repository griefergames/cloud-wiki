---
description: >-
  Signieren ist eine Option, um ein Item mit einem Text und deiner Unterschrift
  zu versehen.
---

# Signieren von Items

{% hint style="info" %}
Dieser Befehl steht dir ab dem **Titan-Rang** zur Verfügung.
{% endhint %}

* Um ein Item zu signieren, muss dieses in der Hand gehalten werden. Dann kann mit dem Befehl `/sign <Nachricht>` eine Signatur hinzugefügt werden.

<figure><img src="../../.gitbook/assets/image (28) (1).png" alt=""><figcaption><p>Beispiel-Signierung eines Items</p></figcaption></figure>

* Jedes Item kann immer nur eine Signatur besitzen und diese kann nur vom Besitzer mit `/unsign` wieder entfernt werden.
* Wenn du gerne farbig signieren möchtest, kannst du die Minecraft-Farbcodes verwenden. Hierfür muss vor dem jeweiligen Wort oder Buchstaben folgendes stehen: `&\<Farbcode>TEXT`.
* Um deine Signierung **fett** zu schreiben, musst du lediglich nach der Farbe und vor dem Text ein **\&l** einfügen. Beispiel: `&\<Farbcode>**\&l**TEXT`.

<figure><img src="../../.gitbook/assets/Farbcodes.png" alt=""><figcaption></figcaption></figure>

Das Limit der Signierung beträgt 65 Zeichen, hierbei zählen aber die Farbcodes NICHT.

### Signieren mit Hexadezimal-Farben

* In der Signatur ist es ebenfalls möglich, Hexadezimal-Farben zu verwenden. Diese können mit `\&#\<Farbcode>` _(Bespiel für die Farbe "rot": `\&#ff0000`)_ hinzugefügt werden.
* Pass jedoch auf, dass die allgemeine Länge im Chat 256 Zeichen beträgt. Somit kann die Signierung inklusive Farbcodes nicht länger sein.

{% hint style="info" %}
Möchtest du Hexadezimal-Farben fett schreiben, muss vor jeder Farbe die Formatierung mit `\&r` zurückgesetzt werden.
{% endhint %}

### Farbverlauf-Signierung

Mit dem zusätzlichen Recht "Farbverlauf-Signierung" kann mit dem Befehl /signgradient ein Text mit einem Farbverlauf signiert werden. Dabei müssen Start- und Endfarbe im Hexadezimalformat hinterlegt werden.

`/signgradient 00FF00 FF0000 Das ist eine signierte Zeile mit Verlauf`

### 2. Zeile signieren

Im [Case-Opening](../features/case-opening.md) kann das Recht gewonnen werden, um eine zweite Zeile auf ein Item zu signieren.

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption><p>2. Zeile signieren-Item aus dem Case-Opening</p></figcaption></figure>

Um eine zweite Zeile hinzuzufügen, kann das Item noch einmal mit `/sign <Text>` signiert werden. Es kann nur auf Items eine 2. Zeile hinzugefügt werden, wenn die erste Signatur von einem selbst ist.

Das Datum der Signatur wird dabei aktualisiert. Der Name (inkl. Rang) bleibt erhalten.
