---
description: Eigene NPCs auf deinem Grundstück
---

# Plot NPC

<figure><img src="../../.gitbook/assets/image (44).png" alt="" width="263"><figcaption><p>Plot NPC</p></figcaption></figure>

Die Plot-NPCs können auf dem eigenen Grundstück platziert werden und werden dann an dieses Grundstück gebunden. Ein NPC kann verschiedene "Berufe" übernehmen, welche in den Einstellungen ausgewählt werden können. Ebenso kann der Plot-NPC verschiedene Optiken haben, welche ebenfalls gewählt werden können.

## Zugriff auf den NPC

Bei einigen "Berufen" möchte man den Zugriff ja auch für Spieler ermöglichen. Der Plot-NPC ist ohne weitere Einstellung von allen Spielern nutzbar, welche Rechte auf dem Grundstück haben. Möchte man den NPC auch für andere Spieler freigeben, so muss die Flag `npc-interaction` auf `true` gesetzt werden.

## NPC-Einstellungen

Um den NPC einzustellen, kann der NPC beim Ducken mit Rechtsklick angeklickt werden. Dann öffnet sich das Einstellungsfenster. Ebenfalls ist es möglich mit `/plotnpc` eine Übersicht der auf dem Plot befindlichen NPCs zu öffnen und die Einstellungen darüber zu öffnen.

{% hint style="info" %}
Der Plot-NPC kann nur vom Grundstücksbesitzer verwaltet werden.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (45).png" alt=""><figcaption><p>NPC Einstellungsmenü</p></figcaption></figure>

Im Einstellungsmenü befinden sich folgende Optionen:

* Art des NPCs ändern (Spieler oder verschiedene Tiere & Monster)
* NPC-Einstellungen (z.B. Skin, Pose oder ob nahende Spieler angesehen werden sollen)
* Name des NPCs (legt den Anzeigenamen über dem Kopf fest)
* NPC-Funktion (legt den "Beruf" des NPCs fest, welcher ausgeführt werden soll)
* NPC-Position (verschieben des NPCs und Anpassung z.B. der Blickrichtung)

### NPC-Arten

Standardmäßig ist ein Plot-NPC ein Spieler, welcher den Skin des Besitzers trägt. Neben der Option eines Spielers, stehen auch weitere Tiere & Monster zur Verfügung, welche in diesem Menü ausgewählt werden können.

{% hint style="info" %}
Die Items zum Freischalten der verschiedenen Tiere können in den Farmwelten erhalten werden, indem man diese Tiere / Monster in der Farmwelt tötet. Mit einer Wahrscheinlichkeit können diese dann ein Item für die Freischaltung droppen.
{% endhint %}

### NPC-Einstellungen

Hier können je nach NPC-Art verschiedene Einstellungen getroffen werden. Für einen "Spieler-NPC" stehen z.B. der Skin oder die Pose zur Verfügung.

Die Option **Spieler ansehen** legt fest, ob der NPC den Spieler anschaut oder weiter in seiner Position verbleibt.

{% hint style="info" %}
Nicht alle Einstellungen der Tiere / Monster sind hinzugefügt worden. Diese werden bei entsprechender Nachfrage (z.B. im Forum) hinzugefügt.
{% endhint %}

### NPC-Funktionen

Jeder NPC kann einen "Beruf" bzw. Funktion ausüben. Es gibt verschiedene Funktionen, die die NPCs übernehmen können. Die folgenden Funktionen gibt es aktuell:

<table><thead><tr><th width="198">Funktion</th><th width="358">Beschreibung</th><th>Erhalten durch</th></tr></thead><tbody><tr><td>Showcase</td><td>Ermöglicht den NPC als Showcase einer Kiste o.ä. zu verwenden, um diese nicht freigeben zu müssen.</td><td>Freigeschaltet für jeden Spieler</td></tr><tr><td>Händler</td><td>Ermöglicht den Zugriff auf den Händler auf dem Grundstück.</td><td>Händler sind, sofern nicht gesondert aufgeführt, für alle Spieler freigegeben.</td></tr><tr><td>Amin-Shop</td><td>Ermöglicht den Zugriff auf den Amin-Shop</td><td>--</td></tr><tr><td>Jobs</td><td>Ermöglicht den Zugriff &#x26; Verwendung des JobNPCs.</td><td>CaseOpening</td></tr><tr><td>MiniGames</td><td>Zugriff auf das Minigames-Inventar <br>(später weitere Optionen)</td><td>--</td></tr><tr><td>Abenteurer</td><td>Zugriff auf die Aufgaben des Abenteurers</td><td>--</td></tr></tbody></table>

#### Einstellungen in der Funktion

Manche Funktionen des Plot-NPCs benötigen weitere Einrichtung, wie z.B. die Showcase-Funktion. Um diese einzustellen, muss nach dem Auswählen der Funktion, erneut auf den Funktionsknopf gedrückt werden.

Dort können dann weitere Einstellungen für diese Option durchgeführt werden. Bei der Showcase-Funktion kann dort die Auswahl der Zielkiste gestartet werden.
