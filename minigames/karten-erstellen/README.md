---
description: Eigene Minigame Maps auf GrieferGames
---

# 🗺 Karten erstellen

Jeder Spieler hat die Möglichkeit seine eigenen Minigame-Karten zu erstellen, zu spielen und sogar für alle Spieler einzureichen.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption><p>Plot-Maps Menü</p></figcaption></figure>

{% hint style="info" %}
Im Folgenden finden sich die allgemeinen Informationen und eine Anleitung zum Erstellen von Plot-Maps. Für spielbezogene Anforderungen und Infos sollte die entsprechende Seite des Spiels besucht werden.
{% endhint %}

## Die Vorbereitung

Um eine neue Karte für ein Minigame zu erstellen, sollte man sich zuerst informieren, welche Anforderungen die Minigame-Maps haben. Wir versuchen die Anforderungen immer so gering und so einfach wie möglich zu halten.

### Größe des Plots

Bevor man also startet zu bauen, sollte man sich Informieren, welche Plot-Größe für das Minigame möglich bzw. benötigt ist. Diese kann je nach Minigame variieren.

Informationen zur Plot-Größe befinden sich in der Unterseite des Minigames oder im Menü, um eine neue Map zu erstellen.

<figure><img src="../../.gitbook/assets/javaw_rgKx0bWbGs.gif" alt=""><figcaption><p>Menüführung zur Plot-Größe</p></figcaption></figure>

## Minigame-Markierungen

{% hint style="warning" %}
Jedes Minigame kann zusätzlich zu den Standardmarkierungen noch Weitere besitzen.
{% endhint %}

Für ein Minigame werden ein paar Informationen benötigt, wie z.B. wo sollen die Spieler spawnen, gibt es einen Bereich "vor dem Spiel" und gibt es Bezugspunkte für das Spiel selbst.&#x20;

Diese Punkte werden bei den Minigames mit Blöcken markiert, welche im späteren Verlauf durch das System ersetzt werden.

### <img src="../../.gitbook/assets/image.png" alt="" data-size="line"> **Spender (Dropper)**

Mit Spendern werden die Spawn-Punkte für die Spieler markiert. Je nach Minigame ist ein Spawnpunkt erforderlich oder eine Vielzahl an Spawn-Punkten. **Die Ausrichtung der Spender gibt dabei die Blickrichtung der Spieler beim Spawn an.**

{% hint style="warning" %}
Wenn mehrere Spawn-Punkte gesetzt werden können, wird meist anhand der Spawn-Anzahl die **mögliche Spielerzahl** der Map berechnet.
{% endhint %}

### <img src="../../.gitbook/assets/image (3).png" alt="" data-size="line"> Werfer (Dispenser)

Für die meisten Spiele kann ein Vorab-Spawnpunkt gesetzt werden. An diesem Punkt spawnen die Spieler beim joinen auf den Server und warten dort auf den Start des Spiels. **Die Ausrichtung der Werfer gibt dabei die Blickrichtung der Spieler beim Spawn an.**

### <img src="../../.gitbook/assets/image (9).png" alt="" data-size="line"> Sicherheitskamera

Durch das Platzieren von Sicherheitskameras in der Map können Zuschauer-Punkte gesetzt werden. Als Zuschauer eines Minigames kann man sich zwischen den Kameras hin und her bewegen, um dem Spiel beizuwohnen.
