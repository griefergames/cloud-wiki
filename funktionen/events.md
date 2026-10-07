# ⭐ Events

Auf der Cloud befindet sich das zentrale Event-System von GrieferGames. Damit werden verschiedene Events veranstaltet, die unabhängig vom Spielfortschritt auf der Cloud oder der 1.8 sind.

Um auf einen Event-Server zu kommen, gib auf der Cloud den Befehl `/event` ein oder benutze das **Event-Portal am Spawn**. Im Event-Menü siehst du, welches Event gerade läuft. Das Betreten der Event-Server ist jedoch nur möglich, wenn dort aktuell ein Event läuft.

Während eines Events kannst du dich auch direkt über die Server-Adresse `event.griefergames.live` verbinden.

## Beitreten eines Events

Um einem Event beizutreten, laufe in eines der Netherportale am Event-Spawn, sobald du dich auf dem Event-Server befindest.

{% hint style="warning" %}
Achte dabei auf Chatausgaben oder lies die Ankündigung zum Event, falls du dir nicht sicher bist, wie das Event funktioniert.
{% endhint %}

## Belohnungen von Events

Das Event-System hat ein zentrales Belohnungssystem, das sowohl für die Cloud- als auch für die 1.8-Belohnungen genutzt wird.

Je nach Event werden die Belohnungen auf einer Version oder auf beiden Versionen vergeben.

{% hint style="info" %}
Es ist auch möglich, dass ein Event gleichzeitig auf der 1.8 stattfindet. Dann wird die Belohnung im Regelfall auf der Cloud vergeben.
{% endhint %}

Wird die Belohnung nur auf einer Version vergeben und ist die Version wählbar, kannst du mit dem Befehl `/eventbelohnung` auf dem Event-Server einstellen, auf welcher Version die Belohnung zugestellt werden soll.

### Abholen der Eventbelohnungen auf dem Citybuild

Um eine vergebene Belohnung auf dem Citybuild abzuholen, gib auf dem Citybuild den Befehl `/eventbelohnung` ein. Reicht dein Inventarplatz nicht für alle Belohnungen aus, schaffe Platz und gib den Befehl erneut ein.

{% hint style="info" %}
Deine Eventbelohnungen kann dir auch der [Allay-Lieferdienst](features/allay-lieferdienst.md) bringen. Dort erscheinen sie als „Eventbelohnung“.
{% endhint %}

{% hint style="danger" %}
Je nach Event werden die Belohnungen erst nach dem Ende des Events oder innerhalb von 30 Minuten nach Erreichen der Belohnung vergeben.
{% endhint %}

## Zusätzliche Befehle

Auf dem Event-Server stehen dir einige Standardbefehle vom Event-System zur Verfügung. Es kann jedoch sein, dass einzelne Befehle bei manchen Events deaktiviert sind.

### Ausblenden von Spielern

Bei Events, bei denen es darauf ankommt, dass du dich gut zurechtfindest (z. B. bei einem Jump & Run), gibt es den Befehl `/event toggleplayer`, um andere Spieler auszublenden.

### Zurück zum Event-Spawn

Mit `/event spawn` kommst du zurück zum Event-Spawn. Nicht zu verwechseln mit `/spawn`, das dich zurück zum Cloud-Citybuild-Spawn bringt.

## Event-Scoreboard

Das Event-System bietet für viele Events ein [Online-Scoreboard mit Rankings](https://event.griefergames.live/).

Außerdem ist das Scoreboard In-Game immer an das jeweilige Event angepasst. Dort findest du Informationen zu deinem aktuellen Stand im Event.

## Aktionen auf dem Citybuild

Zu manchen Events und Aktionen werden auch direkt auf dem Citybuild besondere Funktionen freigeschaltet. Dafür musst du nicht auf den Event-Server wechseln.

### Coinflip

Mit **Coinflip** wettest du um einen selbst gewählten Betrag gegen das System. Der Münzwurf läuft automatisch ab: Gewinnst du, verdoppelt sich dein Einsatz. Verlierst du, ist dein Einsatz weg.

Coinflip kannst du nur nutzen, solange es für ein Event oder eine Aktion freigeschaltet ist.

| Befehl              | Funktion                                                                         |
| ------------------- | -------------------------------------------------------------------------------- |
| /coinflip \<BETRAG> | Setzt den Betrag auf einen Münzwurf                                              |
| /coinflip status    | Zeigt deinen eigenen Coinflip-Umsatz und wie viel der Server an dir gewonnen hat |
| /coinflip bank      | Zeigt den Coinflip-Umsatz aller Spieler und den gesamten Server-Gewinn           |

Pro Wurf kannst du zwischen **1** und **500.000 Dollar** setzen. Der Einsatz wird von deinem Konto abgebucht, Geld auf der [Bank](waehrungen/in-game-geld-usd.md#bank) zählt dabei nicht. Zwischen zwei Coinflip-Befehlen musst du **3 Sekunden** warten.

{% hint style="danger" %}
Die Gewinnchance liegt leicht unter 50 %, das System hat also einen kleinen Vorteil. Die genaue Chance wird nicht bekannt gegeben.

Coinflip kann zum Verlust deines Vermögens führen!
{% endhint %}

### Server-Booster

Zu besonderen Events und Aktionen aktiviert der Server **Server-Booster**. Ein Booster wirkt auf dem ganzen Server, auf dem er aktiv ist, und jeder Spieler dort erhält den Effekt.

* **Abbau-Booster:** Du baust Blöcke schneller ab.
* **Fliegen-Booster:** Du kannst auf dem Server fliegen.
* **XP-Booster:** Besiegte Mobs lassen mehr Erfahrungspunkte fallen.

Booster werden in Stufen aktiviert. Beim Abbau- und beim XP-Booster wird die Wirkung mit jeder Stufe stärker.

Welche Booster gerade aktiv sind, siehst du beim Betreten eines Servers im Chat, zusammen mit ihrer Stufe. Mit `/booster` öffnest du die Übersicht **Server-Booster**. Dort siehst du bei jedem Booster, ob er aktiv ist, auf welcher Stufe und bis wann.

{% hint style="info" %}
Anders als auf der 1.8 kannst du Server-Booster auf der Cloud nicht selbst zünden.
{% endhint %}

{% hint style="warning" %}
Endet der Fliegen-Booster, wird dein Flug beendet. Bist du in diesem Moment in der Luft, fällst du herunter.
{% endhint %}
