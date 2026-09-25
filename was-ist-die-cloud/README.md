---
description: Informationen über den Aufbau und Hintergrund der Cloud
---

# ☁️ Das Netzwerk

Die **Cloud** ist das Netzwerk von GrieferGames, das immer auf der neuesten Minecraft-Version läuft. Es ist vom 1.8-Netzwerk getrennt, hat somit eine eigene Wirtschaft und ist ein in sich geschlossenes System. Es gibt jedoch Verknüpfungspunkte zwischen den beiden Netzwerken, beispielsweise:

* gemeinsame Abklingzeiten auf Befehle (z. B. `/freekiste`)
* gemeinsame Events mit Belohnungen auf beiden Netzwerken

{% hint style="info" %}
Die aktuelle Server-Version der Cloud ist die **1.21.4**.
{% endhint %}

## Woher kommt der Name "Cloud"?

Zu Beginn hieß das Netzwerk **1.16-Netzwerk**. Mit dem Update auf die Minecraft-Version 1.19 wurde daraus das **1.19-Netzwerk**. Da die wechselnden Namen immer wieder für Verwirrung sorgten, haben wir den internen Namen _**Cloud-Netzwerk**_ bzw. _**GGCloud**_ auch offiziell übernommen. Seitdem hat das Netzwerk einen versionsunabhängigen Namen.

## Warum eine Cloud?

Das Netzwerk ist tatsächlich eine Cloud: Statt wie bisher einzelne Citybuild-Server bereitzustellen, haben wir bei diesem Netzwerk auf eine andere Technik gesetzt. Hier gibt es nur einen "Citybuild-Server", nämlich die Cloud.

### Die Struktur

#### Citybuild-Server

<figure><img src="../.gitbook/assets/image (27) (1).png" alt=""><figcaption><p>Netzwerkstruktur der Citybuild-Server</p></figcaption></figure>

Der Citybuild- bzw. Plot-Bereich des Netzwerks ist in ein Raster gegliedert. Jedes Feld dieses Rasters ist eine eigene Region mit eigenem Namen. In der Mitte befindet sich der zentrale Spawn 100-100.

Jede Region umfasst 200 x 200 Grundstücke auf einer Fläche von ca. 10.000 x 10.000 Blöcken. Dabei ist jede Region ein eigener kleiner Minecraft-Server, der die Grundfunktionen des Spiels eigenständig übernimmt. Die Server liegen jedoch entsprechend ihrer Koordinaten nebeneinander, sodass jede Koordinate auf dem Netzwerk nur einmal existiert.

Wird der Platz knapp oder stoßen die vorhandenen Regionen wegen der Spielerzahl an ihre Grenzen, werden in einem Ring-Muster weitere Server um die bestehenden herum freigegeben. So kann kurzfristig neuer Platz geschaffen werden, ohne einen neuen Citybuild zu eröffnen: Das Netzwerk wird einfach an einer Stelle um 200 x 200 Grundstücke erweitert.

#### Farm-Server

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Netzwerkstruktur der Farm-Server</p></figcaption></figure>

Etwas anders sind die Farm-Server aufgestellt: Sie liegen nicht in einem Raster, sondern sind einzelne Server, die zwar mit den gleichen Voraussetzungen erstellt werden, aber jeweils für sich arbeiten. Jeder Farm-Server besitzt seine eigene Welt, die bei den Koordinaten 0;0 beginnt. Die Farm-Server sind also voneinander unabhängig und bilden kein zusammenhängendes Netz wie die Citybuild-Server.

Je nach Auslastung sind unterschiedlich viele Farm-Server aktiv. Steigt der Bedarf, kann ihre Anzahl schnell erhöht werden, sodass weitere Farmwelten zur Verfügung stehen.

### Die Verbindung untereinander

Anders als einzelne, voneinander getrennte Server sind die Citybuild- und Farm-Server der Cloud untereinander verbunden.

Auf der Cloud gibt es nur den globalen Chat. Alles, was auf einem Citybuild- oder Farm-Server in den Chat geschrieben wird, ist auf allen Servern sichtbar – der Chat des einzelnen Servers wird so zum Chat für das ganze Netzwerk. _Ausgenommen vom globalen Chat sind jedoch Event- und Minigame-Server._

Außerdem sind die Citybuild-Server untereinander voll erreichbar. Die Plot-Info eines Grundstücks kann also von jeder Region aus abgerufen werden, und mit `/p h` könnt ihr euch von jeder Region aus zu eurem Grundstück teleportieren – egal, ob es in derselben oder in einer anderen Region liegt. Um den nötigen Wechsel der Region kümmert sich der Server automatisch.

### Vorbereitung der Region

Wer nach einem Neustart oder in den Morgenstunden auf dem Server ist, kennt die Anzeige, dass die Region geladen wird.

Da nicht jede Citybuild-Region dauerhaft benötigt wird, sind nur die Regionen aktiv, die auch gerade gebraucht werden. Ist kein Spieler dieser Region online und möchte auch niemand dort auf ein Grundstück, kann sie offline bleiben, bis sie wieder gebraucht wird.

Während diese Anzeige zu sehen ist, wird die entsprechende Region im Hintergrund gestartet und ihr werdet anschließend dorthin teleportiert. Manchmal erscheint jedoch die Nachricht, dass die Region mit Fehlern gestartet ist. Das kann unter anderem folgende Gründe haben:

* Der Server hat für die Updates länger gebraucht und ist nicht im erwarteten Zeitrahmen fertig geworden
* Der Server ist kurz zuvor heruntergefahren (z. B. weil kein Spieler mehr online war oder nach einem Crash)
* Der Server musste auf Ressourcen der Cloud warten und konnte deshalb erst später anfangen zu starten

In diesen Fällen reicht es meist, mit etwas Geduld den gewünschten Befehl erneut auszuführen. Das Problem sollte sich in der Regel innerhalb von 10 Minuten von selbst lösen. Dauert es länger, meldet es gerne auf dem [GrieferGames Discord](https://discord.griefergames.net). Dann können wir das prüfen und bei Bedarf manuell eingreifen.
