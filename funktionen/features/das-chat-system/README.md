# 💭 Chat-System

Auf dem Server kannst du auf verschiedene Arten mit deinen Mitspielern schreiben.

Eine Übersicht aller Möglichkeiten findest du in diesem Artikel. Weitere Funktionen im Chat findest du unter [Chat-Tags](chat-tags.md) und [Emojis](emojis.md).

## Chat-Codes

Im Chat können verschiedene Codes verwendet werden, um Nachrichten farbig darzustellen oder zu formatieren. Dazu wird der jeweilige Code vor den gewünschten Text gesetzt.

{% hint style="info" %}
Farbige Chatnachrichten (Farbcodes) sind unter anderem ein Vorteil des [Premium-Rangs](../../grundbefehle/range/premium-rang.md) (30 Tage, Shop).
{% endhint %}

Die Nachricht „Ich verkaufe mein Grundstück“ in grüner Farbe sieht vor dem Abschicken zum Beispiel so aus:

<figure><img src="../../../.gitbook/assets/AdXK2Os.png" alt=""><figcaption></figcaption></figure>

Eine Übersicht aller Chat-Codes (Farben, Formatierungen) findest du hier:

<table><thead><tr><th>Code</th><th>Farbe / Effekt</th></tr></thead><tbody><tr><td>&#x26;0</td><td>Schwarz</td></tr><tr><td>&#x26;1</td><td>Dunkelblau</td></tr><tr><td>&#x26;2</td><td>Dunkelgrün</td></tr><tr><td>&#x26;3</td><td>Dunkelcyan</td></tr><tr><td>&#x26;4</td><td>Dunkelrot</td></tr><tr><td>&#x26;5</td><td>Dunkellila</td></tr><tr><td>&#x26;6</td><td>Gold</td></tr><tr><td>&#x26;7</td><td>Grau</td></tr><tr><td>&#x26;8</td><td>Dunkelgrau</td></tr><tr><td>&#x26;9</td><td>Blau</td></tr><tr><td>&#x26;a</td><td>Grün</td></tr><tr><td>&#x26;b</td><td>Cyan</td></tr><tr><td>&#x26;c</td><td>Rot</td></tr><tr><td>&#x26;d</td><td>Pink</td></tr><tr><td>&#x26;e</td><td>Gelb</td></tr><tr><td>&#x26;f</td><td>Weiß</td></tr><tr><td>&#x26;k</td><td>Zufallstext / Wechselnde Zeichen</td></tr><tr><td>&#x26;l</td><td>Fett</td></tr><tr><td>&#x26;m</td><td>Durchgestrichen</td></tr><tr><td>&#x26;n</td><td>Unterstrichen</td></tr><tr><td>&#x26;o</td><td>Kursiv</td></tr></tbody></table>

## Öffentlicher Chat

Der öffentliche Chat ist der Chat, in dem du schreibst, sobald du auf dem Cloud-Netzwerk bist. Dieser Chat kann von jedem Spieler auf der Cloud gelesen werden, der gerade online ist.

## Plot-Chat

Der Grundstückschat (auch Plot-Chat genannt) ist ein Chat, bei dem nur die Mitspieler auf einem Grundstück die geschriebenen Nachrichten lesen und auf diese antworten können.

Hierfür musst du auf einem Grundstück stehen und den Plot-Chat mit `/p chat` aktivieren. Alle von dir darauf folgenden Nachrichten werden nun in den Plot-Chat geschrieben.

Bei allen Nachrichten aus dem Grundstückschat steht vor dem Spielernamen in Klammern, dass sie aus dem Plot-Chat stammen und auf welchem Grundstück (ID) sie geschrieben wurden.

Um den Plot-Chat wieder zu deaktivieren, musst du denselben Befehl `/p chat` noch einmal eingeben. Dabei wird dir im Chat jeweils angezeigt, ob der Plot-Chat aktiviert oder deaktiviert ist.

## Privater Chat

Zum Handeln oder ganz allgemein möchte man gelegentlich privat mit einem Spieler schreiben. Dafür gibt es private Nachrichten.

Mit `/msg <Spieler> <Nachricht>` kannst du mit jedem Spieler auf dem Citybuild-Server privat schreiben.

Das heißt, dass nur dieser Spieler die Nachricht sieht.\
Dieser Spieler kann dir dann auf dieselbe Weise zurückschreiben.

Mit dem Befehl `/r <Nachricht>` antwortest du direkt der letzten Person, mit der du privat geschrieben hast.

{% hint style="warning" %}
Schreibt dich in der Zwischenzeit aber ein anderer Spieler an (z. B. weil du mit zwei Spielern gleichzeitig schreibst), bekommt dieser Spieler deine Antwort, da er nun die letzte Person ist, die dir privat geschrieben hat.
{% endhint %}

Die Nachrichten werden unterschiedlich angezeigt, je nachdem, ob du sie versendet oder erhalten hast.

Sendest du eine Nachricht, wird angezeigt, dass sie von dir an einen Empfänger geht: `[mir -> Empfänger]`. Umgekehrt kommt eine Nachricht vom Absender zu dir: `[Absender -> mir]`.

Falls du nicht direkt angeschrieben werden willst, kannst du das mit dem Befehl `/msgtoggle` umstellen. Du kannst dann zwar anderen Spielern schreiben, sie können dir dann jedoch nicht antworten. Rückgängig machst du das, indem du den Befehl `/msgtoggle` noch einmal eingibst.

## Spieler ausblenden

Wenn dich die Nachrichten eines Spielers stören, kannst du diese auch ausblenden. Dafür gibst du einfach `/ignore <NAME>` im Chat ein. Nun siehst du keine Chatnachrichten dieses Spielers mehr.

Du siehst jedoch weiterhin andere Aktionen des Spielers (z. B. Statusnachricht, Abstimmungen etc.).

Wenn du die Chat-Nachrichten des Spielers wieder sehen willst, gibst du den gleichen Befehl noch einmal ein.

Mit `/ignore` siehst du eine Liste aller Spieler, die du ignoriert hast.

## Chat-Sperren

Du kannst nicht im Chat schreiben und erhältst eine Fehlermeldung?\
Dafür kann es mehrere Gründe geben:

* Der Chat in den Chateinstellungen ist auf „Nur Befehle“ gestellt.
* Dein Account wurde durch ein Teammitglied oder einen Spieler mit dem Mute-Perk stummgeschaltet.
* Du befindest dich in der Lobby oder im Portalraum, wo der Chat komplett deaktiviert ist.
* In deiner Nachricht befinden sich ein oder mehrere Wörter, die vom Team verboten wurden und somit auf die Blacklist gesetzt worden sind.
