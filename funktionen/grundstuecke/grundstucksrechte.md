# Grundstücksrechte

## Helfer hinzufügen <a href="#helfer-hinzufugen" id="helfer-hinzufugen"></a>

Grundstücks-Helfer können auf deinem Grundstück bauen (Blöcke setzen, abbauen & interagieren), solange du auf dem jeweiligen Citybuild-Server online bist. Diese Spieler haben keinen Zugriff auf die Grundstückseinstellungen.

Befehl: `/p add <Spieler>`

## Vertraute hinzufügen <a href="#vertrauten-hinzufugen" id="vertrauten-hinzufugen"></a>

Grundstücks-Vertraute können jederzeit auf deinem Grundstück bauen (Blöcke setzen, abbauen & interagieren). Diese Spieler haben keinen Zugriff auf die Grundstückseinstellungen.

Befehl: `/p trust <Spieler>`

## Besitzer ändern <a href="#besitzer-andern" id="besitzer-andern"></a>

Du kannst die kompletten Rechte für das Grundstück an einen anderen Spieler übergeben. Du bist danach nicht mehr der Eigentümer des Grundstücks. Diese Methode wird beispielsweise verwendet, um ein Grundstück zu verkaufen.

Befehl: `/setowner <Spieler>`

Anschließend bestätigen beide Spieler, dass die kompletten Grundstücksrechte übertragen werden sollen.

Befehl: `/setowner confirm`

Geh vorsichtig mit dem Vergeben von Rechten um und gib sie nur an Leute, denen du vertraust.

## Rechte entfernen <a href="#rechte-entfernen" id="rechte-entfernen"></a>

Du kannst die Rechte eines Spielers auch jederzeit wieder entfernen.

Befehl: `/p remove <Spieler>`

## Zutritt verweigern <a href="#zutritt-verweigern" id="zutritt-verweigern"></a>

Nach Ausführung des Befehls kann der angegebene Spieler das Grundstück nicht mehr betreten.

Befehl: `/p deny <Spieler>` oder `/p deny *`

Mit `*` wird **jeder** Spieler von deinem Grundstück ausgeschlossen. Spieler, die Baurechte haben, können weiterhin das Grundstück betreten.

## Zutritt zulassen <a href="#zutritt-zulassen" id="zutritt-zulassen"></a>

Ein Spieler war vom Grundstück ausgeschlossen und soll es wieder betreten können?

Befehl: `/p undeny <Spieler>` oder `/p undeny *`

Hierbei gilt das Selbe, wie beim Ausschließen mit `*` – es erhält wieder jeder Spieler Zutritt zum Grundstück.

Der Befehl `/p undeny` ist ein Alias für den Befehl `/p remove`.

Wenn Helfer oder Vertraute gesetzt sind, werden diese daher beim "Freigeben" ebenfalls wieder zurückgesetzt. Der Befehl muss dann mehrfach wiederholt werden, um die einzelnen Kategorien (Helfer, Vertraute, Verboten) nacheinander zurückzusetzen.
