---
description: Trichter neu verbunden
---

# Tricher-System

Auf GrieferGames wurden die Funktionen der Trichter erweitert und damit entstehen viele neue Möglichkeiten und auch Verbesserungen.

## Allgemeine Trichter-Informationen

Auf GrieferGames sind die Trichter-Ticks angepasst, um den Performance-Verbrauch von Trichtern zu reduzieren.&#x20;

### Trichter-Tick

Die Häufigkeit mit der die Trichter auf GrieferGames Ticken ist reduziert.&#x20;

Ein Trichter tickt im Standard alle <mark style="color:red;">**8 Ticks**</mark> und verschiebt dabei <mark style="color:red;">**1 Item**</mark>. Auf GrieferGames Tickt ein Trichter alle <mark style="color:green;">**80 Ticks**</mark> und verschiebt dabei <mark style="color:green;">**12 Items**</mark>. Wird in einem Tick kein Item Verschoben, wartet der Trichter ebenfalls <mark style="color:green;">**80 Ticks**</mark> bevor er erneut prüft, ob ein neues Item vorhanden ist.

## Die neuen Trichter-Optionen

Klickt man beim Sneaken mit Rechtsklick auf einen platzierten Trichter, öffnet sich ein Optionsmenü für diesen Trichter.

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption><p>Trichter Hauptmenü</p></figcaption></figure>

Dieses Menü bietet verschiedene Einstellungsoptionen, welche im Folgenden erläutert werden.

### Item-Anzahl einstellen

Mit dem Button <img src="../../.gitbook/assets/image (23).png" alt="" data-size="line">kann die <mark style="color:orange;">Anzahl der transportierten Items</mark> festgelegt werden.\
**Standardeinstellung:** 12 Items

Folgende Optionen stehen zur Verfügung:

* 1 Item
* 12 Items
* 64 Items

{% hint style="info" %}
Es wird immer nur ein Stack gleichzeitig bewegt. Hat ein Stack weniger Items, als die eingestellte Anzahl, wird nur die Anzahl dieses Stacks verschoben.
{% endhint %}

### Force Fast Tick

Mit der <img src="../../.gitbook/assets/image (12).png" alt="" data-size="line"> <mark style="color:orange;">Force Fast Tick</mark> Option ist es Möglich die Tick-Geschwindigkeit auf den Standard zurück zu setzen (siehe [Trichter-Tick](tricher-system.md#trichter-tick)). Diese Möglichkeit wird für manche Redstone-Schaltungen benötigt, welche sich nicht anders realisieren lassen. Der Großteil der Schaltungen lässt sich jedoch so umbauen, dass diese auch auf GrieferGames funktionieren.

{% hint style="warning" %}
Diese Option steht nur der Administration zur Verfügung oder bei aktivierter `hopper-fast-tick`-Flag auf dem Grundstück. Diese Flag wird in seltenen Ausnahmefällen vergeben und kann über das Ticket-System beantragt werden.
{% endhint %}

