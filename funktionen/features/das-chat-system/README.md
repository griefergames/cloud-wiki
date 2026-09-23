# 💭 Chat-System

Auf dem Server kannst du auf verschiedene Arten mit deinen Mitspielern schreiben.

Eine Übersicht aller Möglichkeiten findest du hier in diesem Artikel.

### Chat-Codes

Im Chat können verschiedene Codes verwendet werden, um Nachrichten farbig darzustellen oder zu formatieren. Dazu wird der jeweilige Code vor den gewünschten Text gesetzt.

Bei der Nachricht "Ich verkaufe mein Grundstück" in grüner Farbe würde das dann bevor du es in den Chat abschickst so aussehen:

<figure><img src="../../../.gitbook/assets/AdXK2Os.png" alt=""><figcaption></figcaption></figure>

Eine Übersicht aller Chat-Codes (Farben, Formatierungen) findest du hier:

<table><thead><tr><th>Code</th><th>Farbe / Effekt</th><th data-hidden></th></tr></thead><tbody><tr><td>&#x26;0</td><td>Schwarz</td><td></td></tr><tr><td>&#x26;1</td><td>Dunkelblau</td><td></td></tr><tr><td>&#x26;2</td><td>Dunkelgrün</td><td></td></tr><tr><td>&#x26;3</td><td>Dunkelcyan</td><td></td></tr><tr><td>&#x26;4</td><td>Dunkelrot</td><td></td></tr><tr><td>&#x26;5</td><td>Dunkellila</td><td></td></tr><tr><td>&#x26;6</td><td>Gold</td><td></td></tr><tr><td>&#x26;7</td><td>Grau</td><td></td></tr><tr><td>&#x26;8</td><td>Dunkelgrau</td><td></td></tr><tr><td>&#x26;9</td><td>Blau</td><td></td></tr><tr><td>&#x26;a</td><td>Grün</td><td></td></tr><tr><td>&#x26;b</td><td>Cyan</td><td></td></tr><tr><td>&#x26;c</td><td>Rot</td><td></td></tr><tr><td>&#x26;d</td><td>Pink</td><td></td></tr><tr><td>&#x26;e</td><td>Gelb</td><td></td></tr><tr><td>&#x26;f</td><td>Weiß</td><td></td></tr><tr><td>&#x26;k</td><td>Zufallstext / Wechselnde Zeichen</td><td></td></tr><tr><td>&#x26;l</td><td>Fett</td><td></td></tr><tr><td>&#x26;m</td><td>Durchgestrichen</td><td></td></tr><tr><td>&#x26;n</td><td>Unterstrichen</td><td></td></tr><tr><td>&#x26;o</td><td>Kursiv</td><td></td></tr></tbody></table>

### Öffentlicher Chat

Der öffentliche Chat ist der Chat, in dem du schreibst, sobald du auf dem Cloud-Netzwerk bist. Dieser Chat kann von jedem Spieler auf der Cloud gelesen werden, welcher gerade online ist.

### Plot-Chat

Der Grundstückschat (auch Plot-Chat genannt) ist ein Chat, bei welchem nur die Mitspieler auf einem Grundstück die geschriebenen Nachrichten lesen und auf diese antworten können.

Hierfür musst du auf einem Grundstück stehen und den Plot-Chat mit `/p chat` aktivieren. Alle von dir darauf folgenden Nachrichten werden nun in den Plot-Chat geschrieben.

Alle Nachrichten aus dem Grundstückschat haben vor dem Spielernamen in Klammern, dass diese aus dem Plot-Chat sind und auf welchem Grundstück (ID) die Nachrichten geschrieben werden.

Um den Plot-Chat wieder zu deaktivieren, musst du den selben Befehl `/p chat` noch einmal eingeben. Hierbei steht dann auch immer im Chat, ob der Plot-Chat aktiviert oder deaktiviert ist.

### Privater Chat

Zum Handeln oder allgemein braucht man gelegentlich die Funktion, mit einem Spieler privat zu schreiben. Dafür gibt es private Nachrichten.

Mit `/msg <Spieler> <Nachricht>` kannst du mit jedem Spieler auf dem Citybuild-Server privat schreiben.

Das heißt, dass nur dieser Spieler die Nachricht sieht.\
Dieser Spieler kann dir dann auf dieselbe Weise wieder eine Nachricht zurück schreiben.

Mit dem Befehl `/r <Nachricht>` antwortest du der letzten Person, mit welcher du privat geschrieben hast, direkt.

{% hint style="warning" %}
Sollte dich in der Zeit aber ein anderer Spieler anschreiben, da du vielleicht mit zwei Spielern gleichzeitig schreibst, bekommt dieser Spieler die Nachricht, da dieser Spieler die letzte Person ist, welche mit dir privat geschrieben hat.
{% endhint %}

Die Nachrichten werden anders angezeigt, je nachdem ob du die Nachricht versendet hast oder ob du sie erhältst.

Wenn du eine Nachricht sendest steht da, dass die Nachricht von dir zu einem Empfänger geht `[mir -> Empfänger]`. Andersrum kommt die Nachricht vom Absender zu dir `[Absender -> mir]`.

Falls du nicht direkt angeschrieben werden willst, kannst du das mit dem Befehl `/msgtoggle` umstellen. Du kannst dann zwar anderen Spielern schreiben, sie können dir dann jedoch nicht antworten. Rückgängig machst du das, indem du den Befehl `/msgtoggle` noch einmal eingibst.

### Spieler ausblenden

Wenn dich die Nachrichten eines Spielers stören, kannst du diese auch ausblenden. Dafür gibst du einfach `/ignore <NAME>` im Chat ein. Nun siehst du keine Chatnachrichten dieses Spielers mehr.

Du siehst jedoch weitere Aktionen des Spielers (bspw. Statusnachricht, Abstimmungen, etc.)

Wenn du die Chat-Nachrichten des Spielers wieder sehen willst, gibst du den gleichen Befehl noch einmal ein.

Mit `/ignore` siehst du eine Liste von allen Spielern, welche du ignoriert hast.
