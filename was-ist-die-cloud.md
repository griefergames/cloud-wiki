---
description: Informationen über den Aufbau und Hintergrund der Cloud
---

# Was ist die Cloud?

Die **Cloud** ist das Netzwerk von GrieferGames, welches auf der neusten Minecraft-Version läuft. Das Netzwerk ist getrennt vom 1.8-Netzwerk und hat somit eine eigene Wirtschaft und ist ein in sich geschlossenes System. Es gibt jedoch Verknüpfungspunkte der beiden Netzwerke, wie z.B.:

* gemeinsame Cooldowns auf Befehle (z.B. /freekiste)
* gemeinsame Events mit Belohnungen auf beiden Netzwerken

## Warum heißt das Netzwerk Cloud?

{% hint style="info" %}
Die aktuelle Server-Version der Cloud ist die: **1.19.2**
{% endhint %}

Zu Beginn des Netzwerks hieß das Netzwerk **1.16-Netzwerk**. Dieses wurde durch das Update zur Minecraft-Version 1.19 zum **1.19-Netzwerk**. Da dort immer wieder Verwirrungen der Namen auftauchten durch die Umstellung, haben wir den Internen Namen _**Cloud-Netzwerk**_ oder _**GGCloud**_ dann auch für die Namensgebung verwendet und haben somit nun einen versionsunabhängigen Namen für das Netzwerk.

## Warum Cloud?

Das Netzwerk ist eine Cloud. Wir haben bei diesem Netzwerk auf eine andere Technik gesetzt, statt der bisherigen Bereitstellung einzelner Citybuilds. Hier gibt es nur einen Citybuild, nämlich die Cloud.

### Die Struktur

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption><p>Netzwerk-Struktur der Citybuilds</p></figcaption></figure>

Der Citybuild- oder auch Plot-Bereich des Netzwerks ist in ein Raster gegliedert. Dieses Raster sind je eigene Regionen mit einem eigenen Namen. In der Mitte befindet sich der zentrale Spawn 100-100.&#x20;

Jede Region umfasst 200x200 Grundstücke und ca. eine Fläche von 10.000x10.000 Blöcken. Jede Region ist dabei ein eigener kleiner Minecraft-Server, der in den Grundfunktionen des Spiels eigenständig arbeitet. Jedoch ist jeder Server entsprechend der Koordinaten nebeneinander, sodass jede Koordinate auf dem Citybuild nur einmal existiert.

Wird also einmal der Platz knapp oder anhand der Spielerzahl stoßen die vorhandenen Regionen an ihre Grenzen, werden in einem Ring-Muster weitere Citybuild-Server um die bestehenden Server herum freigegeben. Somit kann hier auch kurzfristig neuer Platz geschaffen werden, ohne einen neuen Citybuild zu eröffnen, in dem an einer Stelle 200x200 Grundstücke erweitert werden.

#### Farm-Server

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption><p>Netzwerk-Struktur der Farm-Server</p></figcaption></figure>

Etwas anders sind die Farm--Server aufgestellt.

Diese befinden sich nicht in einem Raster, sondern sind einzelne Server, welche mit den gleichen Voraussetzungen erstellt werden, jedoch jeder für sich selbst arbeitet. Jeder Farm-Server besitzt seine eigene Welt, welche bei den Koordinaten 0;0 beginnt. Somit ist jeder Server für sich unabhängig und kein Netz wie die Citybuild Server.

Je nach Verwendung sind unterschiedlich viele Farm-Server aktiv. Die Anzahl kann bei steigendem Bedarf schnell erhöht werden und somit weitere Farmwelten zur Verfügung gestellt werden.

### Die Verbindung untereinander

Anders als bei einzelnen Servern, sind die Citybuild und Farm-Server untereinander verbunden.&#x20;

Auf der Cloud gibt es nur den globalen Chat. Das bedeutet alles was auf einem Citybuild- oder Farm-Server im Chat geschrieben wird, ist auf allen Servern sichtbar und so wird der Chat des einzelnen Servers zu einem Chat für das Netzwerk _(ausgenommen von dem globalen Chat, sind jedoch Event-Server & Minigame-Server)_.

Des Weiteren haben die Citybuild-Server noch die Besonderheit, dass diese untereinander voll erreichbar sind. Es kann also von jeder Region die Plot-Info eines Grundstücks abgerufen werden und ich kann mich auf jeder Region mit `/p h` zu meinem Grundstück teleportieren. Egal ob es in der selben Region liegt oder auf einer anderen. Der Server kümmert sich darum, dass der benötigte Wechsel der Region vorgenommen wird.

### Region wird vorbereitet

Wer nach einem Neustart oder in den Morgenstunden auf dem Server ist, kennt diese Anzeige:

XXX BILD - REGION WIRD GELADEN XXX

Da nicht jede Citybuild-Region dauerhaft benötigt wird, sind nur die Regionen aktiv, die auch gerade gebraucht wird. Ist kein Spieler dieser Region online und möchte auch niemand dort auf ein Grundstück, kann diese Region offline bleiben, bis diese gebraucht wird.&#x20;

Während diese Anzeige zu sehen ist, wird die entsprechende Region im Hintergrund gestartet und ihr werdet nach Abschluss dort hin teleportiert. Teilweise kann es jedoch vorkommen, dass die Nachricht erscheint, dass die Region mit Fehlern gestartet ist. Das kann unter anderem folgende Gründe haben:

* Der Server hat für die Updates länger gebraucht und ist nicht im erwarteten Zeitrahmen fertig geworden
* Der Server ist kurz davor heruntergefahren (z.B. kein Spieler mehr oder ein Crash)
* Der Server musste auf Resourcen der Cloud warten und konnte deshalb erst später anfangen zu starten

In diesen Fällen reicht es in der Regel aus, mit etwas Geduld den gewünschten Befehl erneut auszuführen. Das Problem sollte sich in der Regel innerhalb von 10 Minuten automatisch lösen. Dauert es mal länger, meldet dieses gerne auf dem GrieferGames Discord, dann können wir das prüfen und ggf. manuell reagieren.
