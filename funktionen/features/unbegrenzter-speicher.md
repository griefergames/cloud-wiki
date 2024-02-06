---
description: Das (fast) unendliche Lager auf GrieferGames
---

# Unbegrenzter Speicher

Auf dem Cloud-Netzwerk wurden **Unbegrenzte Speicher** eingeführt, um eine Alternative für die auf dem 1.8 Netzwerk verfügbaren Möglichkeiten der Komprimierung zu bieten.

![](<../../.gitbook/assets/0 (1) (1).png>)

### Funktion <a href="#_gj91v33yf85t" id="_gj91v33yf85t"></a>

In einem unbegrenzten Speicher können bis zu **2.147.483.647 Einheiten** eines Items gelagert werden. Hierbei kann pro Speicher nur **ein vorher definiertes Item** (siehe [Herstellung](unbegrenzter-speicher.md#herstellung)) gelagert werden.

Eine Verwendung mit Trichtern ist normal möglich. Hierbei werden die ersten 26 Slots normal befüllt. Der letzte Slot bleibt hierbei frei. Dort abgelegte Items werden in das zusätzliche Lager gelegt.

Die Menge wird im Titel unter “Storage:” angezeigt. Diese aktualisiert sich erst, wenn das Lager ein weiteres Mal geöffnet wird. Die Darstellung erfolgt ab 10.000 Items auf volle tausend Items abgerundeten Beträgen. Items aus dem zusätzlichen Lager können per Trichter entnommen werden oder rutschen in das verfügbare Interface nach, sobald du Items aus dem Lager “shiftest”, oder dieses aktualisierst, indem du ein Item aus deiner Hand in das Lager legst.

<figure><img src="../../.gitbook/assets/image (26) (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
<mark style="color:orange;">**Achtung:**</mark> Der unbegrenzte Speicher verhält sich zunächst wie ein normales Fass. So können grundsätzlich auch Items in die verfügbaren Slots gelegt werden, für die der zusätzliche Speicher nicht geeignet sind. Befindet sich auf einem der Slots ein nicht kompatibles Item, steht die Funktion des zusätzlichen Speichers nicht zur Verfügung.
{% endhint %}

{% hint style="danger" %}
<mark style="color:red;">**Warnung:**</mark> Werden Items mit zusätzlichen Eigenschaften (Signierungen, Verzauberungen o. Ä.) in den zusätzlichen Speicher gelegt, verlieren diese ihre Eigenschaften.
{% endhint %}

### Herstellung <a href="#_lvtgkg89rgtl" id="_lvtgkg89rgtl"></a>

Das Rezept zur Herstellung eines unbegrenzten Speichers benötigt 4 Truhen, 2 Netheritbarren, 1 Enderauge, 1 Fass (oder CustomBlock Kiste - siehe [Aussehen](unbegrenzter-speicher.md#aussehen)) und das zu lagernde Item.

<figure><img src="../../.gitbook/assets/image (37) (1).png" alt=""><figcaption><p>Herstellungsrezept</p></figcaption></figure>

{% hint style="info" %}
Der Gegenstand oben in der Mitte bestimmt den zu lagernden Gegenstand.
{% endhint %}

### Aussehen <a href="#_bu266jjz1kax" id="_bu266jjz1kax"></a>

![](../../.gitbook/assets/4.png)

Die Herstellung des unbegrenzten Speichers ist mit den [CustomBlock](../customblocks.md)-Kisten möglich. Dies ermöglicht zum Beispiel eine abwechslungsreiche Dekoration von Lagersystemen. Für Spieler, die keine [CustomBlocks](../customblocks.md) nutzen, werden die unbegrenzten Speicher als Fässer dargestellt.

{% hint style="info" %}
Stellst du den unbegrenzten Speicher mit Kisten der [CustomBlocks](../customblocks.md) her, dann kannst du diese auch separat mit der Use-Flag freigeben.
{% endhint %}

### Verfügbare Items <a href="#_6dwmq4tc4iw5" id="_6dwmq4tc4iw5"></a>

Unbegrenzte Speicher können grundsätzlich für alle stackbaren Items erstellt werden. Dadurch stehen zum Beispiel Speicher für Betten, Boote, Shulker, Werkzeuge, Waffen, Rüstungen, Lava-/Wassereimer, verzauberte Bücher, Tränke, Schallplatten und weitere nicht zur Verfügung.

#### Ausnahmen <a href="#_tsolmrcvxkro" id="_tsolmrcvxkro"></a>

Obwohl es sich um stackbare Items handelt, stehen weitere Items nicht zur Verfügung, wie zum Beispiel für Treppen, Stufen, Türen, Knöpfe, Zäune, Zauntore, Falltüren, Druckplatten und Beacons.

### Abbau <a href="#_565glmt1kiye" id="_565glmt1kiye"></a>

Der Abbau oder die Zerstörung von unbegrenzten Speichern ist nur möglich, wenn keine Items im zusätzlichen Speicher liegen. Dies wird durch eine Warnung im Chat angezeigt.

![](../../.gitbook/assets/5.png)

### Mögliche Fehlerquellen <a href="#_j9nv9090smll" id="_j9nv9090smll"></a>

#### Item-gebundener unbegrenzter Speicher <a href="#_8rubnj2rh3gc" id="_8rubnj2rh3gc"></a>

Ist ein unbegrenzter Speicher platziert, ist nicht mehr ersichtlich, für welches Item dieser hergestellt wurde. Dies kann durch Abbau herausgefunden werden. Liegen Items im zusätzlichen Speicher, kann davon ausgegangen werden, dass der unbegrenzte Speicher für das Item hergestellt wurde, welches sich in den sichtbaren Slots des Speichers befindet.

#### Spielsteine <a href="#_jc882zln8v5q" id="_jc882zln8v5q"></a>

Spielsteine werden von Trichterfiltern und Ähnlichem als das ursprüngliche Item erkannt. Diese werden aber in den letzten Slot des unbegrenzten Speichers und nicht in den zusätzlichen eingelagert und blockieren somit die weitere Funktion.

#### Verzauberte Items <a href="#_gh9hh12pzhi2" id="_gh9hh12pzhi2"></a>

Die Einlagerung mit Trichtern von verzauberten Items wird blockiert. Dies kann ggf. dazu führen, dass der Slot des Trichters blockiert wird.

#### Freigabe (“Use”) Flags <a href="#_wxvj8kmznmto" id="_wxvj8kmznmto"></a>

Werden die unbegrenzten Speicher mit Fässern (und nicht mit [CustomBlocks](../customblocks.md)) hergestellt, wirkt die Freigabe-Flag für normale Fässer (“use barrel”) auch für die unbegrenzten Speicher.
