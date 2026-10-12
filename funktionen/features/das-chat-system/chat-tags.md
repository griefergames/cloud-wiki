# Chat-Tags

Mit den **Chat-Tags** könnt ihr verschiedene Inhalte direkt im Chat verlinken und für andere Spieler sichtbar machen. Die Tags funktionieren außerdem in eurem **Status** und in **privaten Nachrichten**.

## Verfügbare Chat-Tags

| Chat-Tag | Erklärung                           | Verfügbar für   |
| -------- | ----------------------------------- | --------------- |
| %inv%    | Zeigt das Inventar des Spielers     | Alle            |
| %ec%     | Zeigt die Enderchest                | Alle            |
| %armor%  | Zeigt die aktuelle Rüstung          | Alle            |
| %profil% | Verlinkt das Profil                 | Alle            |
| %item%   | Verlinkt das aktuell gehaltene Item | Alle            |

{% hint style="info" %}
Mit einem Spielernamen hinter dem Tag könnt ihr auch andere Spieler verlinken:

> `%inv:Spielername%`

So könnt ihr beispielsweise im Chat auf das Inventar eines anderen Spielers aufmerksam machen.
{% endhint %}

{% hint style="info" %}
Beim Tag `%item%` könnt ihr statt des Items in der Hand auch ein Item aus einem bestimmten Slot zeigen. Dafür schreibt ihr die Slot-Nummer hinter den Tag:

> `%item:4%` zeigt das Item in Slot 4.
{% endhint %}

## Einlösbare Rechte

Diese Tags stehen nur mit einem entsprechenden einlösbaren Recht zur Verfügung:

* **`%plot%`**\
  Teilt das Grundstück, auf dem ihr gerade steht.
* **`%here%`**\
  Andere Spieler können sich darüber direkt zu eurem Standort teleportieren!

{% hint style="info" %}
Bei allen Tags (außer `%here%`) ist es möglich, zusätzlich andere Spieler zu verlinken, z. B. `%inv:nutzername%` bzw. `%plot:alias/nutzername%`.
{% endhint %}
