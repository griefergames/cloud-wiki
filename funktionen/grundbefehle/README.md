---
description: Eine allgemeine Übersicht aller grundlegenden Befehle der Cloud
---

# ℹ️ Grundbefehle

Hier findest du einige Grundbefehle für das Spielen auf der GrieferGames Cloud. In den kommenden Seiten findest du noch weitere Befehle zu einzelnen Funktionen und Features.

## Allgemeine Befehle

<table><thead><tr><th width="226">Befehl</th><th>Beschreibung</th></tr></thead><tbody><tr><td>/?, /hilfe, /help</td><td>Rufe das Hilfemenü auf.<br><em>Im Hilfemenü findest du zu vielen Features und Funktionen eine Beschreibung oder eine direkte Verlinkung.</em></td></tr><tr><td>/spawn</td><td>Teleportiere dich zurück an den Server-Spawn.</td></tr><tr><td>/ec</td><td>Öffne deine mobile Endertruhe.<br>Mit <code>/ec </code><mark style="color:orange;"><code>Spielername</code></mark> kannst du dir eine fremde Endertruhe ansehen.</td></tr><tr><td>/invsee <mark style="color:orange;">Spielername</mark></td><td>Zeige dir das Inventar eines anderen Spielers an.</td></tr><tr><td>/craft</td><td>Öffne eine mobile Werkbank.</td></tr><tr><td>/tpa <mark style="color:orange;">Spielername</mark></td><td>Schicke eine Anfrage an einen Spieler, um dich zum Spieler zu teleportieren. <em>Die Anfrage muss der Spieler mit <code>/tpaccept</code> annehmen.</em></td></tr><tr><td>/tpahere <mark style="color:orange;">Spielername</mark></td><td>Schicke eine Anfrage an einen Spieler, damit er sich zu dir teleportiert. <em>Die Anfrage muss der Spieler mit <code>/tpaccept</code> annehmen.</em></td></tr><tr><td>/tpaccept</td><td>Nimm eine Teleportationsanfrage von <code>/tpa</code> oder <code>/tpahere</code> an.</td></tr><tr><td>/tpdeny</td><td>Lehne eine Teleportationsanfrage von <code>/tpa</code> oder <code>/tpahere</code> ab.</td></tr></tbody></table>

## Grundstücksbefehle

Befehle, in Bezug auf deine Grundstücke, findest du im Bereich [Grundstücke](../grundstuecke/).

## Homes

Um dir Positionen zu speichern, zu denen du zurückkehren kannst, kannst du dir sogenannte Homes setzen. Je nach Rang oder Bonus-Homes hast du eine unterschiedliche Anzahl an Homes zur Verfügung.

<table><thead><tr><th width="179">Befehl</th><th>Beschreibung</th></tr></thead><tbody><tr><td>/homes</td><td>Zeige die Liste deiner Homes an.</td></tr><tr><td>/home <mark style="color:purple;">Name</mark></td><td>Teleportiere dich zu deinem gespeicherten Home mit dem angegebenen Namen.</td></tr><tr><td>/sethome <mark style="color:purple;">Name</mark></td><td>Speichere ein neues Home mit diesem Namen an deiner aktuellen Position. Wenn bereits ein Home mit dem Namen existiert, wird es überschrieben.</td></tr><tr><td>/delhome <mark style="color:purple;">Name</mark></td><td>Lösche die gespeicherte Position mit diesem Namen.</td></tr></tbody></table>

{% hint style="info" %}
Bei einem Farmwelt-Reset (siehe [Die Farmwelten](../die-farmwelten.md)) werden alle deine Homes in Farmwelten gelöscht.
{% endhint %}

## Kommunikation

Kommunikation ist auf dem Server sehr wichtig und deshalb gibt es verschiedene Möglichkeiten, mit der Community zu kommunizieren.

{% hint style="info" %}
Zusätzlich zur In-Game-Kommunikation kannst du dich mit der Community auch im [Discord](https://discord.griefergames.net), TeamSpeak (IP: `ts.griefergames.net`) oder im [Forum](https://forum.griefergames.de) austauschen.
{% endhint %}

### Der globale Chat

Auf der GrieferGames Cloud gibt es einen globalen Chat, welcher über alle Regionen gemeinsam genutzt wird.

Wenn du ohne einen Befehl in den Chat schreibst, schreibst du im globalen Chat und die Spieler können deine Nachrichten sehen und dir antworten.

### Grundstücks-Chat

Jedes Grundstück hat einen eigenen Chat. Du kannst mit dem Befehl `/p chat` umstellen, ob du im globalen Chat oder im Grundstücks-Chat schreibst. Mehr Informationen dazu findest du im Bereich [Grundstücke](../grundstuecke/).

### Private Nachrichten

Um mit Spielern private Nachrichten auszutauschen, steht dir das `/msg` System zur Verfügung. Die Nachrichten zwischen dir und dem anderen Spieler könnt nur ihr beide lesen.

{% hint style="danger" %}
Beide Teilnehmer haben die Möglichkeit, Nachrichten im privaten Chat mit `/chatlog` zu melden. Achte also auch in privaten Nachrichten auf dein Chatverhalten.
{% endhint %}

Mit ` /msg`` `` `<mark style="color:orange;">`Spielername`</mark> <mark style="color:green;">`Nachricht`</mark> kannst du einen anderen Spieler eine Nachricht schreiben. Dieser Befehl wird dir ebenfalls vorgeschlagen, wenn du auf den Namen des Spielers im Chat klickst.

Um einer Person zu antworten, kannst du zusätzlich den Befehl ` /r`` `` `<mark style="color:green;">`Nachricht`</mark> verwenden. Dann wird die Nachricht an die letzte Person gesendet, die dir eine private Nachricht geschrieben hat.
