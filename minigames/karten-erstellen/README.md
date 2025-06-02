---
description: Eigene MiniGame-Maps auf GrieferGames
---

# 🗺️ Karten erstellen

Jeder Spieler hat die Möglichkeit, seine eigenen MiniGame-Maps zu erstellen, zu spielen und sogar für alle Spieler einzureichen.

<figure><img src="../../.gitbook/assets/image (6) (2) (1).png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="info" %}
Im Folgenden finden sich die allgemeinen Informationen und eine Anleitung zum Erstellen von Plot-Maps. Für spielbezogene Anforderungen und Infos sollte die entsprechende Seite des Spiels besucht werden. Ist keine Seite des Spiels vorhanden, sind gesonderte Anforderungen zusätzlich zu den allgemeinen zu beachten.
{% endhint %}

## Die Vorbereitung

Um eine neue Map für ein MiniGame zu erstellen, solltest du dich zuerst informieren, welche Anforderungen die MiniGame-Maps haben. Wir versuchen die Anforderungen immer so gering und so einfach wie möglich zu halten.

### Größe des Grundstücks

Bevor du also mit dem Bau der Map startest, solltest du dich informieren, welche Plot-Größe für das MiniGame möglich bzw. benötigt ist. Diese kann je nach MiniGame variieren.

<figure><img src="../../.gitbook/assets/javaw_rgKx0bWbGs.gif" alt=""><figcaption><p>Menüführung zur Plot-Größe</p></figcaption></figure>

<table><thead><tr><th>MiniGame</th><th data-type="number">Min. Plot-Größe</th><th data-type="number">Max. Plot-Größe</th></tr></thead><tbody><tr><td>Lasertag</td><td>1</td><td>9</td></tr><tr><td>TNT-Run</td><td>1</td><td>9</td></tr><tr><td>Elytra-Flug</td><td>1</td><td>16</td></tr><tr><td>Escape</td><td>1</td><td>16</td></tr><tr><td>Color Battle</td><td>1</td><td>9</td></tr><tr><td>Builder Battle</td><td>1</td><td>4</td></tr><tr><td>TNT-Dodgeball</td><td>2</td><td>9</td></tr><tr><td>Mobarena</td><td>2</td><td>9</td></tr><tr><td>Schneeballschlacht</td><td>1</td><td>9</td></tr></tbody></table>

Informationen zur Plot-Größe befinden sich ebenfalls im Menü, um eine neue Map zu erstellen.

## MiniGame-Markierungen

{% hint style="warning" %}
Jedes MiniGame kann zusätzlich zu den Standardmarkierungen noch weitere besitzen.
{% endhint %}

Für ein MiniGame werden ein paar Informationen benötigt, wie zum Beispiel wo die Spieler spawnen sollen, ob es einen Bereich "vor dem Spiel" gibt und es Bezugspunkte für das Spiel selbst gibt.

Diese Punkte werden bei den MiniGames mit Blöcken markiert, welche im späteren Verlauf durch das System ersetzt werden.

### <img src="../../.gitbook/assets/image (11) (1) (1).png" alt="" data-size="line"> **Spender (Dropper)**

Mit Spendern werden die Spawn-Punkte für die Spieler markiert. Je nach MiniGame ist ein Spawn-Punkt erforderlich oder eine Vielzahl an Spawn-Punkten. **Die Ausrichtung der Spender gibt dabei die Blickrichtung der Spieler beim Spawn an.**

{% hint style="warning" %}
Wenn mehrere Spawn-Punkte gesetzt werden können, wird meist anhand der Spawn-Anzahl die **mögliche Spielerzahl** der Map berechnet.
{% endhint %}

{% hint style="info" %}
Wird der Spender in **ignore\_location** umbenannt, wird dieser nicht als Spawn-Punkt eingelesen, sondern als Spender-Block im Spiel verbleiben.
{% endhint %}

### <img src="../../.gitbook/assets/image (3) (2) (2).png" alt="" data-size="line"> Werfer (Dispenser)

Für die meisten Spiele kann ein Vorab-Spawnpunkt gesetzt werden. An diesem Punkt spawnen die Spieler beim Betreten auf den Server und warten dort auf den Start des Spiels. **Die Ausrichtung der Werfer gibt dabei die Blickrichtung der Spieler beim Spawn an.**

{% hint style="info" %}
Wird der Werfer in **ignore\_location** umbenannt, wird dieser nicht als Spawn-Punkt eingelesen, sondern als Spender-Block im Spiel verbleiben.
{% endhint %}

### <img src="../../.gitbook/assets/image (9) (2).png" alt="" data-size="line"> Sicherheitskamera

Durch das Platzieren von Sicherheitskameras in der Map können Zuschauerpunkte gesetzt werden. Als Zuschauer eines MiniGames kann man sich zwischen den Kameras hin und her bewegen, um dem Spiel beizuwohnen.

## Plot-Map-Menü

Das Plot-Map-Menü befindet sich im Hauptmenü der `/minigames` unter <img src="../../.gitbook/assets/image (25).png" alt="" data-size="line"> **Plot-Maps**. In der Liste findest du deine erstellten Maps und deren Status. Hier werden auch fehlende Markierungen oder Probleme mit deiner Map angezeigt.

<figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Plot-Map-Informationen</p></figcaption></figure>

* **Bereit:** Gibt an, ob die Map spielbereit ist. Ist eine Map nicht spielbereit, wird diese ggf. noch vorbereitet oder enthält Fehler.
* **Bewertung:** Hier ist die Zusammenfassung deiner Map-Bewertungen zusehen, wenn die Map bereits bewertet wurde.
* <mark style="color:red;">**Fehler:**</mark> Hier werden Fehler der Map angezeigt, welche beim Generieren der Map festgestellt wurden. Beispiel: <img src="../../.gitbook/assets/image (38) (1).png" alt="" data-size="line">
* **Community-Map:** Zeigt an, ob deine Map als Community-Map für alle verfügbar ist bzw. wie der Status deiner Einsendung ist.

### Neue Map einreichen / Map aktualisieren

Um eine neue Map einzureichen oder eine eingereichte Map zu aktualisieren, drücke im Plot-Map-Menü auf <img src="../../.gitbook/assets/image (32).png" alt="" data-size="line"> **Neue Map erstellen**.

<figure><img src="../../.gitbook/assets/image (20) (2).png" alt=""><figcaption><p>Ansicht "Neue Map erstellen"</p></figcaption></figure>

Wähle dort zuerst das Spiel aus, indem du auf das Spiel-Icon klickst. Beim Klick wird zum nächsten Spiel umgeschaltet. Im zweiten Slot wird die Information zur Grundstücksgröße angezeigt. Der Dritte gibt an, ob die Map erstellt werden kann oder nicht.

<figure><img src="../../.gitbook/assets/image (5) (2).png" alt=""><figcaption><p>Fehlermeldung beim Erstellen des Grundstücks</p></figcaption></figure>

Kannst du die Map erstellen, wird die Anzeige grün und mit einem Klick auf den grünen Knopf wird die Erstellung bestätigt.

<figure><img src="../../.gitbook/assets/image (39) (1) (1).png" alt="" width="281"><figcaption><p>Button zum Erstellen des Grundstücks als Map</p></figcaption></figure>

Danach kopiert das MiniGame-System dein Grundstück, welches durch zwei Chatausgaben angezeigt wird:

<figure><img src="../../.gitbook/assets/image (33).png" alt="" width="372"><figcaption><p>Chatausgabe "Map erstellen"</p></figcaption></figure>

Sobald die MiniGame-Map erstellt wurde, beginnt das System im Hintergrund zu arbeiten und die Map vorzubereiten. Der Status kann dann im Plot-Map-Menü verfolgt werden.

{% hint style="danger" %}
**Achtung:** Es kann zu jedem Grundstück nur eine Map pro MiniGame existieren. Die Map wird anhand der Plot-ID identifiziert und somit kann die Map auch nach dem ersten Einreichen durch "Map neu erstellen" aktualisiert werden.
{% endhint %}

{% hint style="info" %}
Die Verbindung zwischen Grundstück und MiniGame-Map wird bei erfolgreich angenommenen Community-Maps aufgehoben. Ist eine Map als Community-Map angenommen, kann diese nicht mehr vom Ersteller bearbeitet werden. _Das Grundstück kann dann jedoch erneut verwendet werden._
{% endhint %}

### Informationen der Map bearbeiten

Um Informationen deiner Map, wie zum Beispiel den Namen zu bearbeiten, klicke im Plot-Map-Menü auf die gewünschte Map.

<figure><img src="../../.gitbook/assets/image (26) (2) (1).png" alt=""><figcaption><p>Map-Einstellungen</p></figcaption></figure>

* **Namensschild:** Namen der Map bearbeiten
* **Game-Icon:** Info zum gewählten Spiel (kann nicht geändert werden)
* **Map-Icon:** Zeigt das Icon der Plot-Map an (kann über Auswahl eines Items im Inventar geändert werden)
* **Kartentisch:** Community-Map-Status bzw. Einreichen als Community-Map
* **Barriere:** Map löschen

### Als Community-Map einreichen

Möchtest du eine Map als Community-Map einreichen, damit die Map von allen gespielt werden kann und auch in öffentlichen Lobbys zur Verfügung steht, klicke auf den Kartentisch in den Map-Einstellungen. Damit wird die Map eingereicht.

#### Ablauf der Community-Maps

1. Einreichen der Map durch den Erbauer
2. Testen der Map durch zum Beispiel Streamer, Teammitglieder o. Ä.
3. Annehmen der Map als Community-Map durch das MiniGame-Team (sollte die Map nicht passend sein, kann sie an dieser Stelle auch abgelehnt werden)

Sobald die Map als Community-Map angenommen ist, kann diese nicht mehr aktualisiert werden. Der Name des Erbauers bleibt jedoch weiterhin in der Map sichtbar.
