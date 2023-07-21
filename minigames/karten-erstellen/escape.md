---
description: Vielseitiges Escape / Rätsel Minispiel
---

# Escape

Escape ist ein vielseitiges Minispiel, welches für verschiedene kleine Spielmodi verwendet werden kann. Um ein paar Beispiele zu geben:

* Escape-Rooms
* Jump & Run
* Parcours

Das Spielprinzip von Escape sieht vor, dass ein Spieler an einem Punkt startet und das Ziel erreichen muss. Welche Hindernisse oder Aufgaben dem Spieler dabei gesetzt werden, ist dem Erbauer der Karte überlassen.

## Voraussetzungen in Escape <a href="#_dueiy2oyb3ts" id="_dueiy2oyb3ts"></a>

Im Modus Escape gelten folgende Bedingungen für die Spieler, die beim Bau der Map berücksichtigt werden müssen:

* Jeder Spieler befindet sich im [**Minecraft Adventure Mode**](escape.md#\_4hgifu6674mu)
* Es kann mehrere End-Punkte geben
* Das Spiel endet, sobald **ein Spieler** den Endpunkt erreicht hat
* Die Spieler haben keine automatische Nachtsicht. Die Map kann also nach eigenem Ermessen ausgeleuchtet werden.
* Wenn mehrere Spawn-Punkte gesetzt sind, spawned jeder Spieler an einem anderen Spawn-Punkt
* Es werden alle Inhalte von Kisten, Büchern etc. übernommen. Auch Karten sind möglich. Es ist jedoch nicht möglich mit Karten zu Interagieren.

## Was ist Adventure Mode? <a href="#_4hgifu6674mu" id="_4hgifu6674mu"></a>

Im Adventure Mode ist ein Spieler eingeschränkt in dem, was er machen kann. Allgemein ist der Modus sehr ähnlich zum **Survival-Mode (Überlebensmodus)**. Als Spieler hat man Hunger, erleidet Schaden von Ihrer Umwelt und kann gegebenenfalls auch sterben. Jedoch gibt es einengroßen Unterschied: **Man kann (grundsätzlich) keine Blöcke abbauen oder platzieren!** Es sei denn, ein Werkzeug oder Item hat einen bestimmten NBT Tag, dieser besagt, welcher Block bzw. welches Item damit abgebaut werden kann. Dieses Tool/Item kann nichts anderes zerstören.

Bei Blöcken oder Items sagt der NBT-Tag, worauf diese platziert werden können.

![Beispiel einer Spitzhacke zum Abbauen](<../../.gitbook/assets/0 (1).png>) ![Beispiel eines Blocks zum Platzieren](../../.gitbook/assets/1.png)

Interagieren ist im Adventure Mode möglich. Somit können Türen, Falltüren, Knöpfe, Kisten usw. einfach verwendet werden. Dies ermöglicht auch das Einschalten einer Redstone Anlage. Zusätzlich steht dem Spieler auch die Crafting-Funktion, um Items zu erstellen, zur Verfügung.

Durch das Verwenden des Adventure Modes, kann man sicherstellen, dass gewisse Bereiche oder ganze Maps nicht zerstört werden können. Dieser Modus wird auf GrieferGames für alle Minigames verwendet, um so kein Zerstören der Mini-Game Maps zu gewährleisten.

## Ziel-Markierungen <a href="#_urpfzuwptixh" id="_urpfzuwptixh"></a>

Ziele sind im Escape-Modus über ![](../../.gitbook/assets/2.png) **Feinwägeplatten** (Gold-Druckplatte) festgelegt. Sobald ein Spieler eine solche Platte betritt, ist die Map abgeschlossen.

_Anders als bei anderen Markierungen bleiben die Platten bestehen und sind im Spiel als Ziel erkennbar._

## Adventure-Mode-Creator <a href="#_h2u81ek28ic6" id="_h2u81ek28ic6"></a>

Da die Items mit den Adventure-Tags nicht einfach so erstellt werden können, steht auf dem Server der Adventure-Mode-Creator unter `/adventuremodecreator` oder kurz `/amc` zur Verfügung. Mit diesem Tool könnt ihr die Adventure-Items komfortabel erstellen.

{% hint style="info" %}
Die Adventure-Tags gelten auf den Citybuild- und Farm-Servern nicht, da die Spieler nicht im Adventure-Spielmodus sind. Ihr könnt die erstellten Blöcke also ohne Einschränkung platzieren oder abbauen.
{% endhint %}

### Auswahl des Items <a href="#_bar6hb3kqj5i" id="_bar6hb3kqj5i"></a>

![](<../../.gitbook/assets/3 (2).png>)

Als erstes müsst ihr das **Tool** oder den **Block** aus eurem Inventar auswählen, auf welchen Adventure-Tags hinzugefügt werden sollen. Auf Tools kann eine Abbauoption hinzugefügt werden und auf Blöcke eine Platzierungsoption.

{% hint style="info" %}
Wählt ihr ein zweites Mal das gleiche Tool, werden die vorhandenen Informationen erneut geladen.
{% endhint %}

### Hinzufügen der Blöcke <a href="#_9x5989n0hrh4" id="_9x5989n0hrh4"></a>

![](<../../.gitbook/assets/4 (2).png>)

Wählt nun im **Abbau- oder Platzierungs-Editor** die gewünschten Blöcke aus dem Inventar. Diese erscheinen dann im oberen Inventar. Wollt ihr einen Block wieder entfernen, könnt ihr diesen im oberen Inventar anklicken und damit entfernen.

### Item erstellen <a href="#_i39cn4v8gd4e" id="_i39cn4v8gd4e"></a>

Um nun das Item zu erstellen klickt auf den Bestätigen-Knopf (unten rechts) und das ausgewählte Item erhält die neuen Adventure-Informationen.

{% hint style="danger" %}
Das Item wird aktualisiert. Ihr erhaltet kein neues Item mit den neuen Informationen.
{% endhint %}

Nun könnt ihr das Item z.B. in einer Kiste o.ä. in eurer Map platzieren.

{% hint style="info" %}
Möchtet ihr die Tags wieder entfernt haben, könnt ihr über den Creator die Blöcke einfach entfernen und der Tag wird entsprechend wieder entfernt.
{% endhint %}

## Escape Command System <a href="#_f9q8vz18c6if" id="_f9q8vz18c6if"></a>

Da viele Singleplayer Escape-Maps gerne Command-Blöcke zum Erweitern der Möglichkeiten nutzen und wir diese Option auf GrieferGames nicht bieten können, gibt es hierfür ein eigenes Escape-Command-System.

### Platzieren von Befehlen <a href="#_piqyedk6goup" id="_piqyedk6goup"></a>

![Platzierter Escape-Command](<../../.gitbook/assets/5 (1).png>)

Befehle auf der Karte können mit einem ![](../../.gitbook/assets/6.png) **goldenen Befehlsblock** (CustomBlock, Ersatzblock Befehlsblock) und einem darauf stehenden ![](../../.gitbook/assets/7.png)**Schild** erstellt werden.

{% hint style="info" %}
Die platzierten Blöcke & Schilder werden nicht ersetzt, diese sollten also außerhalb des Sichtfeldes der Spieler platziert werden
{% endhint %}

Auf der Vorderseite des Schilds befindet sich ein “Trigger” und auf der Rückseite eine “Aktion”.

{% hint style="success" %}
Das System erkennt automatisch, wenn die Anweisungen vertauscht sind und führt diese trotzdem entsprechend aus.
{% endhint %}

### <mark style="color:orange;">Command-Trigger</mark> <a href="#_49gcccpj0xi7" id="_49gcccpj0xi7"></a>

Command-Trigger sind definierte Schlagworte, welche eine Aktion beschreiben, die durch den Spieler oder eine Mechanik ausgelöst wird. Die Trigger werden auf der Vorderseite des Schildes wie folgt notiert:

<figure><img src="../../.gitbook/assets/8.png" alt="" width="180"><figcaption><p>Trigger-Tag Beispielschild</p></figcaption></figure>

Die folgenden Trigger stehen zur Verfügung:

| Trigger-Tag | Beschreibung                                                                                                                                                                                                                    | Argument 1                                                                                      | Argument 2                                                                     |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| \[BREAK]    | Beim Abbau eines Blockes <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                               | Abgebautes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)        | _<mark style="color:green;">(optional)</mark>_ relative Koordinaten des Blocks |
| \[CRAFT]    | Beim Herstellen eines Items durch Crafting <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                             | Hergestelltes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)     | --                                                                             |
| \[PLACE]    | Beim Platzieren eines Blockes <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                                                                                                      | Platziertes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)       | _<mark style="color:green;">(optional)</mark>_ relative Koordinaten des Blocks |
| \[KILL]     | Beim Töten eines Monsters <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                              | Getöteter [Mob-Typ](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/EntityType.html) | --                                                                             |
| \[REDSTONE] | Wird durch ein Redstone-Signal ausgelöst                                                                                                                                                                                        | _<mark style="color:green;">(optional)</mark>_ Benötigte Redstone-Power                         | --                                                                             |
| \[VARIABLE] | Wenn eine Variable durch die <mark style="color:purple;">**SETVARIABLE**</mark><mark style="color:purple;">-Action</mark> geändert wird.                                                                                        | Variablen-Name                                                                                  | _<mark style="color:green;">(optional)</mark>_ Erforderlicher Wert             |
| \[USETIPP]  | Wenn ein Tipp genutzt wird.                                                                                                                                                                                                     | Tipp-Tag                                                                                        | --                                                                             |
| \[MOVE]     | <p>Wenn sich ein Spieler auf einen bestimmtem Block bewegt. <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line"><br><br><mark style="color:red;">Achtung:</mark> Es muss Argument 3 gesetzt werden.</p> | Relative Koordinaten zu einem Block                                                             | --                                                                             |

{% hint style="warning" %}
Das **Argument 3** (letzte Zeile) gibt bei allen Triggern an, wie oft der Trigger ausgelöst werden darf. Es kann auch `%player%` verwendet werden, dann kann der Trigger so oft ausgeführt werden, wie Spieler in der Lobby sind.\
\
_Wird keine Zahl angegeben, kann der Trigger beliebig oft ausgeführt werden._
{% endhint %}

{% hint style="info" %}
Trigger welche den Befehlsblock betreffen, wie z.B. **\[REDSTONE]** müssen am Befehlsblock ausgelöst werden, nicht am Schild.
{% endhint %}

### <mark style="color:purple;">Command-Aktionen</mark> <a href="#_qxsfd9w8ba60" id="_qxsfd9w8ba60"></a>

Command-Aktionen sind definierte Schlagworte, welche eine Aktion beschreiben, die als Reaktion auf einen Trigger ausgeführt werden soll. Die Aktionen werden auf der Rückseite des Schildes wie folgt notiert:

![Action-Tag Beispielschild](../../.gitbook/assets/9.png)

Die folgenden Aktionen stehen zur Verfügung:



| Action-Tag       | Beschreibung                                                                                                                                                                                                                              | Argumente                                                                                                                                                                                                                                                                                        |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| \[BLOCK]         | Setzt einen Block                                                                                                                                                                                                                         | <p>1: relative Koordinate<br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p>                                                                                                                                                                     |
| \[BLOCKROTATION] | Rotiert einen Block                                                                                                                                                                                                                       | <p>1: relative Koordinate<br>2: 0 = Uhrzeigersinn, 1 = gegen den Uhrzeigersinn</p>                                                                                                                                                                                                               |
| \[TELEPORT]      | <p>Teleportiert Spieler<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line"> <em><mark style="color:orange;">für einen Speziellen Spieler</mark></em></p> | <p>1: Ziel (relative Koordinaten)<br>2: <mark style="color:green;">(optional)</mark> Richtung als Zahl<br>3: <mark style="color:green;">(optional)</mark> Alle Spieler 1/0</p>                                                                                                                   |
| \[PLACEON]       | Verändert das Item des Triggers und fügt die Option zum Platzieren hinzu. _<mark style="color:orange;">Benötigt</mark>_ <img src="../../.gitbook/assets/image (7) (1).png" alt="" data-size="line">                                       | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>3: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p> |
| \[CANBREAK]      | <p>Verändert das Item des Triggers und fügt die Option zum Abbauen hinzu.<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1).png" alt="" data-size="line"></p>                         | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>3: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p> |
| \[ENCHANT]       | <p>Verändert das Item des Triggers und fügt ein Enchantment hinzu.<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1).png" alt="" data-size="line"></p>                                | <p>1: Enchantment<br>2: <em><mark style="color:green;">(optional)</mark></em> Level</p>                                                                                                                                                                                                          |
| \[RENAME]        | <p>Verändert das Item des Triggers und benennt es um.<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1).png" alt="" data-size="line"></p>                                             | 1: Neuer Name                                                                                                                                                                                                                                                                                    |
| \[MOB]           | Spawned einen Mob / Mobs                                                                                                                                                                                                                  | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/EntityType.html">Mob-Typ</a><br>2: relative Koordinaten<br>3: <em><mark style="color:green;">(optional)</mark></em> Menge</p>                                                                                          |
| \[SETVARIABLE]   | Setzt eine Variable für die Nutzung des <mark style="color:orange;">**VARIABLE**</mark><mark style="color:orange;">-Triggers</mark>                                                                                                       | <p>1: Variablen-Name<br>2: Wert oder Wertänderung (+10 / -10)</p>                                                                                                                                                                                                                                |
| \[SOUND]         | Spielt einen Sound ab                                                                                                                                                                                                                     | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Sound.html">Sound</a><br>2: <em><mark style="color:green;">(optional)</mark></em> relative Koordinaten<br>3: <em><mark style="color:green;">(optional)</mark></em> Lautstärke (1-10)</p>                                      |
| \[TIPP]          | Fügt einen verfügbaren Tipp dem Spiel hinzu.                                                                                                                                                                                              | <p>1: Tipp-Tag<br>2: relative Koordinaten zu einer Kiste, die Tipp-Items enthält<br>3: <em><mark style="color:green;">(optional)</mark></em> Verzögerung in Sekunden, bis der Tipp verfügbar ist</p>                                                                                             |
| \[CANCELTIPP]    | Entfernt einen verfügbaren Tipp wieder.                                                                                                                                                                                                   | 1: Tipp-Tag                                                                                                                                                                                                                                                                                      |

{% hint style="info" %}
Argumente die **Koordinaten** angeben, müssen immer **relativ zur Position des Befehlsblocks** angegeben werden und nicht in Citybuild-Coordinaten. Dieses gilt für X-, Y- und Z-Achse.\
\
**Beispiel:** _Ist die gewünschte X-Koordinate auf dem CB 254 und der Befehlsblock befindet sich auf CB-X-Koordinate 200 ist der einzutragende Wert 54._
{% endhint %}

## Das Tipp-System

In schwierigen Situationen ist manchmal ein Tipp sehr wertvoll, um ein Rätsel zu lösen oder den nächsten Schritt zu erkennen.

Über die Trigger gibt es die Möglichkeit Tipps in das Spiel einfließen zu lassen.&#x20;

### Einen Tipp erstellen

Um einen Tipp zu erstellen, benötigt es lediglich einen Command mit der Aktion <mark style="color:purple;">\[TIPP]</mark>. Dort wird eine Kiste in relativen Koordinaten angegeben. Den Inhalt dieser Kiste erhält der Spieler, wenn der den Tipp mit dem Befehl `/tipp` abruft.&#x20;

{% hint style="info" %}
Die Kiste wird beim Abrufen des Tipps geleert. \
_Es ist also möglich eine im Rätsel verwendete Kiste zu verwenden._
{% endhint %}

{% hint style="success" %}
Es können alle Arten von "Kisten" verwendet werden. Dieses gilt auch für Trichter etc.
{% endhint %}

### Hintergrund-Infos zum Tipp-System

Es gibt immer nur einen verfügbaren Tipp. Der letzte Tipp, welcher aktiviert wurde (sowohl direkt, als auch mit Verzögerung) ist für die Spieler verfügbar.

Wurde der Tipp verwendet, ist kein Tipp verfügbar, bis die Verzögerung eines Tipps abläuft oder ein weiterer Tipp aktiviert wird.

{% hint style="info" %}
**Tipp-Tipp:** Über den Trigger <mark style="color:orange;">\[USETIPP]</mark> können Tipp-Ketten erstellt werden, welche nur beim Verwenden des vorherigen Tipps ausgelöst werden.
{% endhint %}
