# Escape

Escape ist ein vielseitiges Minispiel, welches für verschiedene kleine Spielmodi verwendet werden kann. Um ein paar Beispiele zu geben:

* Escape Room
* Jump & Run
* Parkour

Das Spielprinzip von Escape sieht vor, dass ein Spieler an einem Punkt startet und das Ziel erreichen muss. Welche Hindernisse oder Aufgaben dem Spieler dabei gesetzt werden, ist dem Erbauer der Karte überlassen.

## Voraussetzungen in Escape

Im Modus Escape gelten folgende Bedingungen für die Spieler, die beim Bau der Map berücksichtigt werden müssen:

* Jeder Spieler befindet sich im Minecraft Abenteuermodus.
* Es kann mehrere Endpunkte geben.
* Das Spiel endet, sobald **ein Spieler** den Endpunkt erreicht hat.
* Die Spieler haben keine automatische Nachtsicht. Die Map kann also nach eigenem Ermessen ausgeleuchtet werden.
* Wenn mehrere Spawn-Punkte gesetzt sind, spawned jeder Spieler an einem anderen Spawn-Punkt.
* Es werden alle Inhalte von Kisten, Büchern etc. übernommen. Auch Karten sind möglich. Es ist jedoch nicht möglich, mit Karten zu interagieren.

## Was ist der Abenteuermodus?

Im Abenteuermodus ist ein Spieler eingeschränkt in dem, was er machen kann. Allgemein ist der Modus sehr ähnlich zum **Überlebensmodus**. Als teilnehmender Spieler hast du Hunger, erleidest Schaden in der Umgebung der Map und kannst gegebenenfalls auch sterben. Jedoch gibt es einen großen Unterschied: **Du kannst (grundsätzlich) keine Blöcke abbauen oder platzieren!** Es sei denn, ein Werkzeug oder Item hat einen bestimmten NBT-Tag, der besagt, welcher Block bzw. welches Item damit abgebaut werden kann. Dieses Tool/Item kann nichts Anderes zerstören.

Bei Blöcken oder Items sagt der NBT-Tag, worauf diese platziert werden können.

![Beispiel einer Spitzhacke zum Abbauen](<../../.gitbook/assets/0 (1) (2).png>) ![Beispiel eines Blocks zum Platzieren](../../.gitbook/assets/1.png)

Interagieren ist im Abenteuermodus möglich. Somit können Türen, Falltüren, Knöpfe, Kisten usw. einfach verwendet werden. Dies ermöglicht auch das Einschalten einer Redstoneanlage. Zusätzlich steht dem Spieler auch die Crafting-Funktion, um Items zu erstellen, zur Verfügung.

Durch das Verwenden des Abenteuermodus, kannst du sicherstellen, dass gewisse Bereiche oder ganze Maps nicht zerstört werden können. Dieser Modus wird auf GrieferGames für alle MiniGames verwendet, um so kein Zerstören der MiniGame Maps zu gewährleisten.

## Zielmarkierungen

Ziele sind im Escape-Modus über ![](../../.gitbook/assets/2.png) **Feinwägeplatten** (Gold-Druckplatten) festgelegt. Sobald ein Spieler eine solche Platte betritt, ist die Map abgeschlossen.

_Anders als bei anderen Markierungen bleiben die Platten bestehen und sind im Spiel als Ziel erkennbar._

## Adventure-Mode-Creator

Da die Items mit den Adventure-Tags nicht einfach so erstellt werden können, steht auf dem Server der Adventure-Mode-Creator unter `/adventuremodecreator` oder kurz `/amc` zur Verfügung. Mit diesem Tool kannst du die Adventure-Items komfortabel erstellen.

{% hint style="info" %}
Die Adventure-Tags gelten auf den Citybuild- und Farm-Servern nicht, da die Spieler nicht im Adventure-Spielmodus sind. Du kannst die erstellten Blöcke also ohne Einschränkungen platzieren oder abbauen.
{% endhint %}

### Auswahl des Items

![](<../../.gitbook/assets/3 (2).png>)

Als erstes musst du das **Tool** oder den **Block** aus deinem Inventar auswählen, auf die Adventure-Tags hinzugefügt werden sollen. Auf Tools kann eine Abbauoption hinzugefügt werden und auf Blöcke eine Platzierungsoption.

{% hint style="info" %}
Wählst du ein zweites Mal das gleiche Tool, werden die vorhandenen Informationen erneut geladen.
{% endhint %}

### Hinzufügen der Blöcke

![](<../../.gitbook/assets/4 (2).png>)

Wähle nun im **Abbau- oder Platzierungs-Editor** die gewünschten Blöcke aus dem Inventar. Diese erscheinen dann im oberen Inventar. Möchtest du einen Block wieder entfernen, kannst du diesen im oberen Inventar anklicken und damit entfernen.

### Item erstellen

Um nun das Item zu erstellen, klicke auf den Bestätigen-Knopf (unten rechts) und das ausgewählte Item erhält die neuen Adventure-Informationen.

{% hint style="danger" %}
Das Item wird aktualisiert. Du erhältst kein neues Item mit den neuen Informationen.
{% endhint %}

Nun kannst du das Item z. B. in einer Kiste o. Ä. in deiner Map platzieren.

{% hint style="info" %}
Möchtest du die Tags wieder entfernt haben, kannst du über den Creator die Blöcke einfach entfernen und der Tag wird entsprechend wieder entfernt.
{% endhint %}

## Escape-Befehlssystem

Da viele Einzelspieler-Escape-Maps gerne Befehlsblöcke zum Erweitern der Möglichkeiten nutzen und wir diese Option auf GrieferGames nicht bieten können, gibt es hierfür ein eigenes Escape-Befehlssystem.

### Platzieren von Befehlen

![Platzierter Escape-Befehl](<../../.gitbook/assets/5 (1).png>)

Befehle auf der Karte können mit einem ![](../../.gitbook/assets/6.png) **goldenen Befehlsblock** (CustomBlock, Ersatzblock Befehlsblock) und einem darauf stehenden ![](../../.gitbook/assets/7.png)**Schild** erstellt werden.

{% hint style="info" %}
Die platzierten Blöcke & Schilder werden nicht ersetzt – sie sollten also außerhalb des Sichtfeldes der Spieler platziert werden.
{% endhint %}

Auf der Vorderseite des Schilds befindet sich ein “Trigger” und auf der Rückseite eine “Aktion”.

{% hint style="success" %}
Das System erkennt automatisch, wenn die Anweisungen vertauscht sind und führt diese trotzdem entsprechend aus.
{% endhint %}

### <mark style="color:orange;">Command Trigger</mark>

Command Trigger sind definierte Schlagworte, welche eine Aktion beschreiben, die durch den Spieler oder eine Mechanik ausgelöst werden. Die Trigger werden auf der Vorderseite des Schildes wie folgt notiert:

<figure><img src="../../.gitbook/assets/8.png" alt="" width="180"><figcaption><p>Trigger-Tag Beispielschild</p></figcaption></figure>

Die folgenden Trigger stehen zur Verfügung:

| Trigger-Tag | Beschreibung                                                                                                                                                                                                                   | Argument 1                                                                                      | Argument 2                                                                     |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| \[BREAK]    | Beim Abbau eines Blocks <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                               | Abgebautes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)        | _<mark style="color:green;">(optional)</mark>_ relative Koordinaten des Blocks |
| \[CRAFT]    | Beim Herstellen eines Items durch Crafting <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                            | Hergestelltes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)     | --                                                                             |
| \[DISTANCE] | Wenn ein Spieler in der Distanz zum Schild ist ![](<../../.gitbook/assets/image (4) (1) (1) (1) (1) (1).png>)                                                                                                                  | Distanz in Blöcken                                                                              | --                                                                             |
| \[DROP]     | Wenn ein Spieler ein Item droppt <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                      | _<mark style="color:green;">(optional)</mark>_ Material, was gedroppt wird                      | _<mark style="color:green;">(optional)</mark>_ Item-Name                       |
| \[INIT]     | Wird beim Start des MiniGames ausgeführt                                                                                                                                                                                       | _<mark style="color:green;">(optional)</mark>_ Min. Spieler                                     | _<mark style="color:green;">(optional)</mark>_ Max. Spieler                    |
| \[INTERACT] | Wenn mit einem Block interagiert wird ![](<../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)                                                                                               | relative Koordinaten des Blocks                                                                 | --                                                                             |
| \[KILL]     | Beim Töten eines Monsters <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                             | Getöteter [Mob-Typ](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/EntityType.html) | --                                                                             |
| \[MOVE]     | <p>Wenn sich ein Spieler auf einen bestimmtem Block bewegt <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line"><br><br><mark style="color:red;">Achtung:</mark> Es muss Argument 3 gesetzt werden.</p> | Relative Koordinaten zu einem Block                                                             | --                                                                             |
| \[PICKUP]   | Wenn ein Spieler ein Item aufsammelt <img src="../../.gitbook/assets/image (26) (2).png" alt="" data-size="line"><img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                  | _<mark style="color:green;">(optional)</mark>_ Material, was gedroppt wird                      | _<mark style="color:green;">(optional)</mark>_ Item-Name                       |
| \[PLACE]    | Beim Platzieren eines Blocks <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line">                                                                                                                      | Platziertes [Material](https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html)       | _<mark style="color:green;">(optional)</mark>_ relative Koordinaten des Blocks |
| \[REDSTONE] | Wird durch ein Redstone-Signal ausgelöst                                                                                                                                                                                       | _<mark style="color:green;">(optional)</mark>_ Benötigte Redstone-Power                         | --                                                                             |
| \[TRIGGER]  | Wenn die Aktion "Trigger" ausgelöst wird                                                                                                                                                                                       | Trigger-Name                                                                                    | --                                                                             |
| \[VARIABLE] | Wenn eine Variable durch die <mark style="color:purple;">**SETVARIABLE**</mark><mark style="color:purple;">-Action</mark> geändert wird                                                                                        | Variablen-Name                                                                                  | _<mark style="color:green;">(optional)</mark>_ Erforderlicher Wert             |
| \[USETIPP]  | Wenn ein Tipp genutzt wird                                                                                                                                                                                                     | Tipp-Tag                                                                                        | --                                                                             |

{% hint style="warning" %}
Das **Argument 3** (letzte Zeile) gibt bei allen Triggern an, wie oft der Trigger ausgelöst werden darf. Es kann auch `%player%` verwendet werden, damit der Trigger so oft ausgeführt wird wie sich Spieler in der Lobby befinden.\
\
\&#xNAN;_Wird keine Zahl angegeben, kann der Trigger beliebig oft ausgeführt werden._
{% endhint %}

{% hint style="info" %}
Trigger, welche den Befehlsblock betreffen – wie z. B. **\[REDSTONE]** – müssen am Befehlsblock ausgelöst werden, nicht am Schild.
{% endhint %}

### <mark style="color:purple;">Befehlsaktionen</mark>

Befehlsaktionen sind definierte Schlagworte, welche eine Aktion beschreiben, die als Reaktion auf einen Trigger ausgeführt werden sollen. Die Aktionen werden auf der Rückseite des Schildes wie folgt notiert:

![Action-Tag Beispielschild](../../.gitbook/assets/9.png)

Die folgenden Aktionen stehen zur Verfügung:

| Action-Tag       | Beschreibung                                                                                                                                                                                                                                              | Argumente                                                                                                                                                                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| \[BLOCK]         | Setzt einen Block                                                                                                                                                                                                                                         | <p>1: Relative Koordinate<br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p>                                                                                                                                                                                  |
| \[BLOCKROTATION] | Rotiert einen Block                                                                                                                                                                                                                                       | <p>1: Relative Koordinate<br>2: 0 = Uhrzeigersinn, 1 = gegen den Uhrzeigersinn</p>                                                                                                                                                                                                                            |
| \[CANBREAK]      | <p>Verändert das Item des Triggers und fügt die Option zum Abbauen hinzu<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1) (1) (1) (1).png" alt="" data-size="line"></p>                              | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>3: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p>              |
| \[EFFECT]        | <p>Gibt einem Spieler einen Trankeffekt<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line"> <em><mark style="color:orange;">für einen speziellen Spieler</mark></em></p> | <p>1: <a href="https://hub.spigotmc.org/javadocs/spigot/org/bukkit/potion/PotionEffectType.html">Effekt</a><br>2: <mark style="color:green;">(optional)</mark> Dauer in Sekunden<br>3: <mark style="color:green;">(optional)</mark> Alle Spieler 1/0</p>                                                      |
| \[ENCHANT]       | <p>Verändert das Item des Triggers und fügt eine Verzauberung hinzu<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1) (1) (1) (1).png" alt="" data-size="line"></p>                                   | <p>1: Verzauberung<br>2: <em><mark style="color:green;">(optional)</mark></em> Level</p>                                                                                                                                                                                                                      |
| \[FINISH]        | Beendet das MiniGame                                                                                                                                                                                                                                      | --                                                                                                                                                                                                                                                                                                            |
| \[HEAL]          | Heilt einen oder alle Spieler                                                                                                                                                                                                                             | <p>1: % Leben, die geheilt werden sollen<br>3: <mark style="color:green;">(optional)</mark> ALL = Alle Spieler</p>                                                                                                                                                                                            |
| \[MOB]           | Spawned einen Mob / Mobs                                                                                                                                                                                                                                  | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/EntityType.html">Mob-Typ</a><br>2: Relative Koordinaten<br>3: <em><mark style="color:green;">(optional)</mark></em> Menge</p>                                                                                                       |
| \[PLACEON]       | Verändert das Item des Triggers und fügt die Option zum Platzieren hinzu _<mark style="color:orange;">Benötigt</mark>_ <img src="../../.gitbook/assets/image (7) (1) (1) (1) (1).png" alt="" data-size="line">                                            | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>2: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a><br>3: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html">Material</a></p>              |
| \[RENAME]        | <p>Verändert das Item des Triggers und benennt es um<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (7) (1) (1) (1) (1).png" alt="" data-size="line"></p>                                                  | 1: Neuer Name                                                                                                                                                                                                                                                                                                 |
| \[RULE]          | Setzt eine Gamerul                                                                                                                                                                                                                                        | <p>1: Regel (GameRule)<br>2: Wert</p>                                                                                                                                                                                                                                                                         |
| \[SETRESPAWN]    | Setzt einen Respawn-Punkt                                                                                                                                                                                                                                 | <p>1: Ziel (relative Koordinaten)<br>2: <mark style="color:green;">(optional)</mark> "ALL" -> Für alle Spieler</p>                                                                                                                                                                                            |
| \[SETVARIABLE]   | Setzt eine Variable für die Nutzung des <mark style="color:orange;">**VARIABLE**</mark><mark style="color:orange;">-Triggers</mark>                                                                                                                       | <p>1: Variablen-Name<br>2: Wert oder Wertänderung (+10 / -7)</p>                                                                                                                                                                                                                                              |
| \[SOUND]         | Spielt einen Sound ab                                                                                                                                                                                                                                     | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Sound.html">Sound</a><br>2: <em><mark style="color:green;">(optional)</mark></em> relative Koordinaten<br>3: <em><mark style="color:green;">(optional)</mark></em> Lautstärke (1-10)</p>                                                   |
| \[TELEPORT]      | <p>Teleportiert Spieler<br><em><mark style="color:orange;">Benötigt</mark></em> <img src="../../.gitbook/assets/image (22) (1).png" alt="" data-size="line"> <em><mark style="color:orange;">für einen speziellen Spieler</mark></em></p>                 | <p>1: Ziel (relative Koordinaten)<br>2: <mark style="color:green;">(optional)</mark> Richtung als Zahl<br>3: <mark style="color:green;">(optional)</mark> Alle Spieler 1/0</p>                                                                                                                                |
| \[RUNTRIGGER]    | Löst den Trigger aus                                                                                                                                                                                                                                      | 1: Trigger-Name                                                                                                                                                                                                                                                                                               |
| \[VILLAGER]      | Spawned einen Dorfbewohner auf Level 1                                                                                                                                                                                                                    | <p>1: <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/Villager.Profession.html">Profession</a><br>2: Relative Koordinaten<br>3: <em><mark style="color:green;">(optional)</mark></em> <a href="https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/entity/Villager.Type.html">Typ</a></p> |
| \[TIPP]          | Fügt einen verfügbaren Tipp dem Spiel hinzu                                                                                                                                                                                                               | <p>1: Tipp-Tag<br>2: Relative Koordinaten zu einer Kiste, die Tipp-Items enthält<br>3: <em><mark style="color:green;">(optional)</mark></em> Verzögerung in Sekunden, bis der Tipp verfügbar ist</p>                                                                                                          |
| \[CANCELTIPP]    | Entfernt einen verfügbaren Tipp wieder                                                                                                                                                                                                                    | 1: Tipp-Tag                                                                                                                                                                                                                                                                                                   |

{% hint style="info" %}
Argumente, die **Koordinaten** angeben, müssen immer **relativ zur Position des Befehlsblocks** angegeben werden und nicht in Citybuild-Koordinaten. Dieses gilt für X-, Y- und Z-Achse.\
\
**Beispiel:** _Ist die gewünschte X-Koordinate auf dem CB 254 und der Befehlsblock befindet sich auf CB-X-Koordinate 200, ist der einzutragende Wert 54._
{% endhint %}

## Das Tipp-System

In schwierigen Situationen ist manchmal ein Tipp sehr wertvoll, um ein Rätsel zu lösen oder den nächsten Schritt zu erkennen.

Über die Trigger gibt es die Möglichkeit, Tipps in das Spiel einfließen zu lassen.

### Einen Tipp erstellen

Um einen Tipp zu erstellen, benötigt es lediglich einen Befehl mit der Aktion <mark style="color:purple;">\[TIPP]</mark>. Dort wird eine Kiste in relativen Koordinaten angegeben. Den Inhalt dieser Kiste erhält der Spieler, wenn der den Tipp mit dem Befehl `/tipp` abruft.

{% hint style="info" %}
Die Kiste wird beim Abrufen des Tipps geleert.\
\&#xNAN;_Es ist also möglich, eine im Rätsel verwendete Kiste zu verwenden._
{% endhint %}

{% hint style="success" %}
Es können alle Arten von "Kisten" verwendet werden. Dieses gilt auch für Trichter etc.
{% endhint %}

### Hintergrund-Infos zum Tipp-System

Es gibt immer nur einen verfügbaren Tipp. Der letzte Tipp, welcher aktiviert wurde (sowohl direkt als auch mit Verzögerung) ist für die Spieler verfügbar.

Wurde der Tipp verwendet, ist kein Tipp verfügbar, bis die Verzögerung eines Tipps abläuft oder ein weiterer Tipp aktiviert wird.

{% hint style="info" %}
**Tipp-Tipp:** Über den Trigger <mark style="color:orange;">\[USETIPP]</mark> können Tipp-Ketten erstellt werden, welche nur beim Verwenden des vorherigen Tipps ausgelöst werden.
{% endhint %}
