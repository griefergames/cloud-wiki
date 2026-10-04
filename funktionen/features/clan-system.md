# 👥 Clan-System

In einem Clan kann man sich mit anderen Spielern zusammentun, um gemeinsam zu spielen, sich gegenseitig zu unterstützen und gemeinsame Ziele zu erreichen.

Wer einen Clan gründet, erhält die Owner-Rolle. Welche Aufgaben und Rechte die übrigen Mitglieder haben, legt ihr über die [Clan-Rollen](clan-system.md#clan-rollen) fest.

Die maximale Anzahl von Mitgliedern richtet sich nach dem [Rang](../grundbefehle/range/README.md) des Spielers, der den Clan gründet. Sie wird bei der Gründung festgelegt und kann danach mit speziellen Items zusätzlich erhöht werden.

{% hint style="info" %}
Jeder Spieler kann einen Clan für 100.000$ erstellen.
{% endhint %}

{% hint style="warning" %}
Sonderrechte (z. B. zusätzliche Clan-Mitglieder, zusätzliche Clan-Homes, Clan-Farbcodes, Clan-Sondercodes) werden dem derzeitigen Clan hinterlegt und können nicht in einen neuen Clan mitgenommen werden.

Die Items können von jedem Mitglied des Clans eingelöst werden.
{% endhint %}

## Clan-Befehle

| Befehl                            | Erklärung                                  | Bilder                                                                                                                    |
| --------------------------------- | ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- |
| /clan                             | Zeigt das Clan-Menü                        | ![](<../../.gitbook/assets/image (106).png>)                                                                              |
| /clan info \<Clan-Tag>            | Öffnet die Info eines bestimmten Clans     | ![](<../../.gitbook/assets/image (105).png>)                                                                              |
| /clan invite \<NAME>              | Lade einen Spieler in den Clan ein         |                                                                                                                           |
| /clan kick \<NAME>                | Entferne einen Spieler aus dem Clan        |                                                                                                                           |
| /clan leave                       | Verlasse deinen Clan                       |                                                                                                                           |
| /clan einzahlen \<SUMME> \<GRUND> | Zahle Geld auf das Clan-Konto ein          | <img src="../../.gitbook/assets/image (100).png" alt="" data-size="original">![](<../../.gitbook/assets/image (102).png>) |
| /clan auszahlen \<SUMME> \<GRUND> | Hebe Geld von dem Clan-Konto ab            | ![](../../.gitbook/assets/RWawaoI.png)![](../../.gitbook/assets/FhR5NId.png)                                              |
| /clan moneylog                    | Zeigt die Historie der Clan-Bank an        | ![](<../../.gitbook/assets/image (103).png>)                                                                              |
| /clan guthaben                    | Zeigt das Guthaben der Clan-Bank an        | ![](<../../.gitbook/assets/image (82).png>)                                                                               |
| /clan sethome \<NAME>             | Setze ein Clan-Home                        |                                                                                                                           |
| /clan delhome \<NAME>             | Löscht ein Clan-Home                       |                                                                                                                           |
| /clan home \<NAME>                | Teleportiert zum ausgewählten Clan-Home    |                                                                                                                           |
| /clan homes                       | Zeigt eine Übersicht der Clan-Homes an     | ![](<../../.gitbook/assets/image (104).png>)                                                                              |

{% hint style="info" %}
Ein Clan wird nicht von der Administration übertragen. Bereits vergebene Clan-Namen werden nicht neu vergeben.
{% endhint %}

{% hint style="danger" %}
Verlasst ihr als letzter Spieler mit der Owner-Rolle den Clan, wird der Clan gelöscht. Das kann nicht rückgängig gemacht werden. Soll der Clan bestehen bleiben, weist vorher einem anderen Mitglied die Owner-Rolle zu.
{% endhint %}

## Clan-Name und Clan-Tag

Bei der Gründung legt ihr einen **Clan-Namen** und einen **Clan-Tag** fest. Der Clan-Tag erscheint im Chat vor den Namen eurer Mitglieder.

* Der Clan-Name darf höchstens **32 Zeichen** lang sein, der Clan-Tag höchstens **6 Zeichen**.
* Als Sonderzeichen sind nur #, \_ und . erlaubt.
* Farben und Formatierungen im Clan-Tag schaltet ihr mit den besonderen Clan-Items „Bunte Clan-Tags“ und „Clan-Tag-Sondercodes“ frei. Im Clan-Namen sind sie nicht möglich.

Name und Tag könnt ihr später in den Einstellungen unter `/clan` ändern, sofern eure Rolle das passende Recht hat. Nach der Gründung und nach jeder Änderung geht das erst wieder nach **24 Stunden**.

## Clan-Konto

Einzahlen und das Guthaben ansehen können alle Mitglieder. Geld abheben und mit `/clan moneylog` die letzten **30 Buchungen** ansehen können nur Rollen mit dem Recht „Clan-Konto verwalten“.

## Clan-Homes

Clan-Homes können alle Mitglieder nutzen. Setzen und löschen dürfen sie nur Rollen mit dem Recht „Clan-Homes verwalten“.

* Ein Clan kann zunächst **3 Clan-Homes** besitzen. Mit einem speziellen Item lässt sich die Anzahl dauerhaft erhöhen.
* Der Name eines Clan-Homes darf höchstens **25 Zeichen** lang sein.

{% hint style="warning" %}
Clan-Homes lassen sich nur dort setzen, wo auch normale Homes erlaubt sind.
{% endhint %}

## Clan-Rollen

Mit den **Clan-Rollen** könnt ihr selbst entscheiden, wer in eurem Clan welche Aufgaben und Rechte übernehmen darf. So könnt ihr euer Clan-System ganz nach euren eigenen Vorstellungen aufbauen.

Die Symbole eures Clans und eurer Rollen könnt ihr selbst anpassen und verändern. Auch die Rollen könnt ihr individuell gestalten, umbenennen und mit den gewünschten Rechten ausstatten.

Zu Beginn stehen euch bereits vier Clan-Rollen zur Verfügung:

* Owner
* Admin
* Support
* Member

Die vorgegebenen Rollen sind dabei nur ein Vorschlag. Ihr könnt sie jederzeit nach euren Vorstellungen verändern, löschen oder durch eigene Rollen ergänzen. Baut euch das System also gerne so, wie es am besten zu eurem Clan passt.

Ihr könnt jederzeit **neue Rollen erstellen** und nicht mehr benötigte Rollen wieder löschen.

{% hint style="info" %}
Jede Rolle muss mindestens einem Mitglied zugewiesen sein, bevor ihr eine neue Rolle erstellen könnt.
{% endhint %}

{% hint style="warning" %}
Die Owner-Rolle ist immer die höchste Rolle und kann nicht gelöscht werden. Die Rolle, die neue Mitglieder automatisch erhalten (zu Beginn „Member“), lässt sich ebenfalls nicht löschen. Andere Rollen könnt ihr nur löschen, wenn ihnen kein Mitglied mehr zugewiesen ist.
{% endhint %}

### Rechte der Clan-Rollen verwalten

Für jede Rolle könnt ihr individuell festlegen, welche Rechte sie besitzen soll. Aktuell können folgende Rechte vergeben werden:

* Clan-Namen bearbeiten
* Clan-Tag bearbeiten
* Einladungen verwalten
* Mitglieder kicken
* Rollen zuweisen
* Rollen erstellen
* Clan-Homes verwalten
* Clan-Konto verwalten

So könnte man z. B. festlegen, dass nur Clan-Admins Rollen verwalten dürfen, während Clan-Supporter lediglich Einladungen verwalten können.

{% hint style="info" %}
Rollen zuweisen und Mitglieder kicken könnt ihr nur bei Mitgliedern, deren Rolle unter eurer eigenen steht.
{% endhint %}
