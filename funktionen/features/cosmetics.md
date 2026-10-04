# ✨ Cosmetics

Mit dem Cosmetics-System kann die Optik der getragenen Rüstung durch kosmetische Rüstungen verändert werden. Zusätzlich kannst du einen Ballon und ein Cosmetic auf dem Rücken tragen.

<figure><img src="../../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption><p>Cosmetics-Menü</p></figcaption></figure>

Die kosmetische Rüstung kann unter `/cosmetics` hinzugefügt oder entfernt werden. Klicke auf ein Rüstungsteil in deinem Inventar und es wird in den Cosmetic-Slots hinterlegt. Ist dort bereits eine Rüstung hinterlegt, wird diese zurück in dein Inventar gelegt. Zusätzlich kann kosmetische Rüstung auch im Slot der Schildhand hinterlegt werden.

## Sichtbarkeit der Rüstung

Die kosmetische Rüstung ist für alle Spieler sichtbar, welche das [Ressourcenpaket](../ressourcenpaket.md) aktiviert und geladen haben. Außerdem muss im jeweiligen Rüstungsslot eine echte Rüstung angelegt sein.

{% hint style="warning" %}
Ist keine Rüstung in einem Slot angelegt, wird dieser Slot nicht durch die kosmetische Rüstung ersetzt.
{% endhint %}

{% hint style="danger" %}
Ist eine Elytra angelegt, wird diese nicht ersetzt. Sofern Verzauberungen oder Attribute für den Client benötigt werden (Swift-Sneak o. Ä.), werden diese Verzauberungen & Attribute auf der kosmetischen Rüstung mitgesendet.
{% endhint %}

## Rüstung ausblenden

{% hint style="warning" %}
Zum Ausblenden der Rüstung benötigst du ein zusätzliches Recht. Ohne dieses Recht ist der Knopf im Menü gesperrt.
{% endhint %}

Um ein Rüstungsteil auszublenden, klicke auf den <img src="../../.gitbook/assets/image (7) (1).png" alt="" data-size="line">-Knopf vor dem entsprechenden Slot. Um die Rüstung wieder sichtbar zu machen, klicke auf den <img src="../../.gitbook/assets/image (8).png" alt="" data-size="line">-Knopf.

Diese Funktion blendet nicht nur die kosmetische Rüstung, sondern auch die normale Rüstung in den Rüstungsslots aus. Es ist also nicht sichtbar, dass eine Rüstung getragen wird.

## Ballon und Rücken-Cosmetics

Neben den Rüstungsslots gibt es in `/cosmetics` Slots für Cosmetics, die du zusätzlich tragen kannst:

* **Ballon Cosmetic:** Ein Ballon schwebt neben dir.
* **Rücken Cosmetic:** Du trägst ein Cosmetic wie Flügel oder einen Rucksack auf dem Rücken.

Passende Cosmetics erkennst du an der Beschreibung des Items, z. B. „Nutze es in /cosmetics als Ballon“. Du legst sie wie die Rüstung mit einem Klick aus deinem Inventar an. Anders als bei der Rüstung musst du dafür nichts im jeweiligen Slot tragen.

Mit dem Knopf **Cosmetic Verstecken** neben dem Slot blendest du den Ballon oder das Rücken-Cosmetic aus, ohne es abzulegen.

{% hint style="info" %}
Ist ein Slot für dich nicht freigeschaltet, zeigt das Menü den Hinweis „Du hast keinen Zugriff auf diesen Slot“.
{% endhint %}
