---
description: >-
  Übersicht über Änderungen, welche das Standardverhalten von Minecraft
  verändern
---

# 🦾 Mechanik-Änderungen

Auf GrieferGames verhalten sich einige Spielmechaniken anders als im Standard-Minecraft. Hier findest du eine Übersicht dieser Änderungen.

## Trichter-Geschwindigkeiten

Die Trichter-Ticks und -Geschwindigkeiten sind auf GrieferGames angepasst. Mehr dazu findest du auf der Seite zum [Trichter-System](../features/trichter-system.md).

## Komposter

Ein Komposter nimmt auf GrieferGames bis zu **64 Items** auf einmal an. So passt er zu den größeren Stapeln, die [Trichter](../features/trichter-system.md#item-anzahl-einstellen) hier verschieben: Ein Trichter gibt bei jedem Tick bis zu seiner eingestellten Item-Anzahl auf einmal in den Komposter.

Wird der Komposter dabei voll, werden die übrigen Items trotzdem verwertet. Beim Leeren bekommst du dafür für jede weitere volle Füllung **1 zusätzliches Knochenmehl**.

{% hint style="warning" %}
Auch ein Rechtsklick gibt den ganzen Stapel aus deiner Hand auf einmal in den Komposter. Nimm nur so viele Items in die Hand, wie du kompostieren möchtest.
{% endhint %}

## Bergungskompass

Der Bergungskompass wurde an das Cloud-Netzwerk angepasst. Siehe [Bergungskompass](bergungskompass.md).

## Todeskisten

Beim Tod werden Items nicht gedroppt, sondern in einer Todeskiste am Todespunkt aufbewahrt.

{% hint style="info" %}
Diese Kiste kann sowohl in der Farmwelt als auch in der Grundstückswelt von allen Spielern geöffnet werden (auch wenn diese auf dem Grundstück nicht vertraut sind).
{% endhint %}

{% hint style="danger" %}
Ist am Todespunkt kein Platz für eine Todeskiste oder stirbt der Spieler in Lava oder Feuer, wird keine Todeskiste erstellt und die Items werden normal gedroppt.
{% endhint %}

## Mobs in Fahrzeugen (Farmwelten)

Bei allen Mobs (Tiere & Monster) in Fahrzeugen ist die AI deaktiviert. Sie wird deaktiviert, sobald ein Mob in das Fahrzeug einsteigt, und wieder aktiviert, wenn er es verlässt oder das Fahrzeug zerstört wird.

Das ist insbesondere beim Handeln mit Dorfbewohnern wichtig, da innerhalb von Fahrzeugen keine neuen Trades etc. generiert werden.

## Shulker-Änderungen

Es wurden ebenfalls Änderungen an Shulker-Kisten vorgenommen.

### Drop-Rate

Die Drop-Rate der Shulker-Schalen ist gegenüber der Standardwahrscheinlichkeit reduziert.

{% hint style="success" %}
_Die Droprate wurde in **Absprache mit der Community** zur Einführung der Shulker-Kisten geändert. GrieferGames hat Shulker-Kisten auf Wunsch der Community über normales Farmen verfügbar gemacht, statt sie über Kisten, Events oder eigene Rezepte herauszugeben._
{% endhint %}

### Shulker-Farmen

Die Shulker-Farmen, die du auf YouTube o. Ä. findest, funktionieren auf GrieferGames nicht. Du kannst die Farm zwar bauen, wirst im Betrieb aber schnell feststellen, dass keine neuen Shulker dazukommen.

### Inhalte von Shulker-Kisten

Minecraft selbst verbietet nur, Shulker-Kisten in Shulker-Kisten abzulegen. Wir haben diese Beschränkung erweitert: Auch Bücher können nicht in Shulker-Kisten abgelegt werden.

{% hint style="warning" %}
Es gibt Möglichkeiten, Bücher in eine Shulker-Kiste zu bekommen. Du bekommst sie dann jedoch nicht wieder aus der Shulker-Kiste heraus. Das Team kann dir dabei nicht helfen.
{% endhint %}

### Abbau von Shulker-Kisten

Wenn eine Shulker-Kiste abgebaut wird, wird diese direkt ins Inventar gelegt und muss nicht eingesammelt werden. So wird der Verlust von Shulker-Kisten verhindert.

## Pigman-Farmen auf Citybuild-Regionen

Das Farmen von Pigmen über Netherportale ist auf der Cloud grundsätzlich möglich. Aufgrund der zu hohen Anzahl an Farmen wurde am 24. April 2023 jedoch eine Änderung eingeführt.

Weitere Informationen zur Pigman-Farm gibt es auf der Unterseite [Pigman-Farmen](pigman-farmen.md).

## Mobs auf Grundstücken

Mobs auf Grundstücken haben reduzierte AI-Optionen. Zusätzlich kann mit Mobs nicht interagiert werden (Melken, Anleinen, Füttern etc.).

## Deaktivierte Blöcke

* Kartentische sind aufgrund der modifizierten [Karten](../features/karten.md) deaktiviert.

## Änderungen in Farmwelten

* Die Netherdecke kann nicht betreten werden.
* Der Enderdrache ist nicht vorhanden.
* Die Anzahl der Dorfbewohner ist limitiert.
* In den Endcitys befinden sich keine Elytren.

## Sitzen auf Treppen

Auf GrieferGames kannst du dich auf Treppen setzen. Mache dazu mit leerer Hand einen Rechtsklick auf eine Treppe.

Das funktioniert auch bei den Stühlen, Sofas, Parkbänken und Barstühlen aus den [CustomBlocks](../../allgemein/clients-and-modifikationen/customblocks.md).

* Über dem Sitzplatz muss Luft sein.
* Auf Stufen kannst du dich nicht setzen.

Zum Aufstehen sneakst du. Du landest dann wieder an der Stelle, von der aus du dich hingesetzt hast.

### Kupfer oxidieren

Kupfer kannst du an der Werkbank altern lassen. Lege dazu 8 Kupferblöcke rund um eine Wasserflasche:

* 8 Kupferblöcke ergeben 8 angelaufene Kupferblöcke.
* 8 angelaufene Kupferblöcke ergeben 8 verwitterte Kupferblöcke.
* 8 verwitterte Kupferblöcke ergeben 8 oxidierte Kupferblöcke.

Kupfertüren und Kupferfalltüren bringst du eine Stufe weiter, indem du sie zusammen mit einer Wasserflasche in die Werkbank legst.

### Holz in der Steinsäge

In der Steinsäge kannst du Stämme und Holz direkt weiterverarbeiten, ohne vorher Bretter herzustellen.

| Aus 1 Stamm | Menge |
| ----------- | ----- |
| Bretter | 4 |
| Stufen | 8 |
| Treppen | 3 |
| Zäune | 3 |
| Zauntor | 1 |
| Türen | 2 |
| Falltüren | 3 |
| Schilder | 3 |
| Druckplatten | 2 |
| Knöpfe | 4 |
| Boot | 1 |
| Leitern | 4 |
| Schüsseln | 4 |
| Stöcke | 8 |

Aus 1 Brett erhältst du in der Steinsäge wahlweise 2 Stufen, 2 Stöcke, 1 Knopf, 1 Leiter oder 1 Schüssel.

{% hint style="info" %}
Nicht jede Holzart hat jedes Ergebnis. Aus Karmesin- und Wirrstämmen gibt es z. B. kein Boot.
{% endhint %}
