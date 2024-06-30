# Grundstücksrechte

## Helfer hinzufügen <a href="#helfer-hinzufugen" id="helfer-hinzufugen"></a>

Grundstücks-Helfer können auf deinem Grundstück bauen (Blöcke setzen, abbauen & interagieren), solange du auf dem jeweiligen Citybuild-Server online bist. Diese Spieler haben keinen Zugriff auf die Grundstück-Einstellungen.

Der Befehl lautet: `/p add <Spielername>`

## Vertrauten hinzufügen <a href="#vertrauten-hinzufugen" id="vertrauten-hinzufugen"></a>

Grundstück-Vertraute können jederzeit auf deinem Grundstück bauen (Blöcke setzen, abbauen & interagieren). Diese Spieler haben keinen Zugriff auf die Grundstück-Einstellungen.

Der Befehl lautet: `/p trust <Spielername>`

## Besitzer ändern <a href="#besitzer-andern" id="besitzer-andern"></a>

Du kannst die kompletten Rechte für das Grundstück an einen anderen Spieler übergeben. Du bist danach nicht mehr der Eigentümer des Grundstücks. Diese Methode wird beispielsweise verwendet, um ein Grundstück zu verkaufen.

Der Befehl lautet: `/setowner <Spielername>`

Anschließend bestätigen beide Spieler, dass die kompletten Grundstücksrechte übertragen werden sollen.

Der Befehl lautet: `/setowner confirm`

Geh vorsichtig mit dem Vergeben von Rechten um und gebe sie nur an Leute, denen du vertraust.

## Rechte entfernen <a href="#rechte-entfernen" id="rechte-entfernen"></a>

Du kannst die Rechte eines Spielers auch jederzeit wieder entfernen.

Der Befehl lautet: `/p remove <Spielername>`

## Zutritt verweigern <a href="#zutritt-verweigern" id="zutritt-verweigern"></a>

Nach Ausführung des Befehls kann der angegebene Spieler das Grundstück nicht mehr betreten.

Der Befehl lautet: `/p deny <Spielername>` oder `/p deny *`

Mit `*` wird **jeder** Spieler von deinem Grundstück ausgeschlossen – Spieler, die Baurechte haben, können weiterhin das Grundstück betreten.

## Zutritt zulassen <a href="#zutritt-zulassen" id="zutritt-zulassen"></a>

Ein Spieler war vom Grundstück ausgeschlossen und soll es wieder betreten können?

Der Befehl lautet: `/p undeny <Spielername>` oder `/p undeny *`

Hierbei gilt das Selbe, wie beim Ausschließen mit `*` – es erhält wieder jeder Spieler Zutritt zum Grundstück.

Der Befehl `/p undeny` ist ein Alias für den Befehl `/p remove`.

Wenn Helfer oder Vertraute gesetzt sind, werden diese daher beim "Freigeben" ebenfalls wieder zurückgesetzt. Der Befehl muss dann mehrfach wiederholt werden, um die einzelnen Kategorien (Helfer, Vertraute, Verboten) nacheinander zurückzusetzen.
