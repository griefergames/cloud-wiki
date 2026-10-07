---
description: Übersicht über die Nutzung und die Befehle
---

# In-Game-Geld $

<mark style="color:green;">**Handelbar**</mark> – **Die Hauptwährung im Spiel ist die In-Game-Währung „Dollar“ ($).** Sie kann In-Game mit anderen Spielern gehandelt werden.

Hauptsächlich kannst du dir Dollar auf dem Server verdienen, indem du mit anderen Spielern [handelst](../features/handel.md), einen Shop eröffnest und dort an andere Spieler verkaufst oder auch indem du Aufträge des [Job-Systems](../features/job-system.md) für andere Spieler erledigst.

Zum Start erhältst du nach Abschluss des [Mentorenprogramms](../features/mentorenprogramm.md) ein wenig Startgeld, indem du [Erfolge / Advancements](../features/erfolge-advancements.md) abschließt.

## Befehle

{% hint style="info" %}
`<>` = Verpflichtendes Argument\
`[]` = Optionales Argument\
_**Info:** Klammern müssen bei der Eingabe weggelassen werden!_
{% endhint %}

### Konto / Bargeld

Folgende Befehle verwalten dein Geld auf dem Konto.

* `/money` - Zeige deinen Kontostand an.\
  Dein Kontostand kann auch im Scoreboard abgelesen werden.
* `/moneylog` - Zeige deine letzten **30** Transaktionen im Chat an, einschließlich Datum, Herkunft, Geldmenge und Grund.
* `/moneylog gui` - Öffne deinen Moneylog als Menü.\
  Über **„Zahlungen filtern“** kannst du Zahlungen aus einzelnen Systemen aus- und wieder einblenden.
* `/pay <Spielername> <Geldmenge> [Grund]` - Sende dem angegebenen Spieler die angegebene Menge an Geld. Optional kann ein Grund hinzugefügt werden.\
  **Beispiel:** _`/pay CosmoHDx 200` um CosmoHDx 200 Dollar zu zahlen_
* `/pay * <Geldmenge>` - Verteile Geld an die Spieler, die gerade online sind. In einem Menü legst du fest, ob jeder Spieler den vollen Betrag erhält oder ob der Betrag aufgeteilt wird. Außerdem kannst du das Geld an eine bestimmte Anzahl zufällig ausgewählter Spieler schicken.\
  Jeder Spieler muss dabei mindestens **10 Dollar** erhalten. Für diesen Befehl benötigst du die **Pay-All-Rechte** aus dem [Case-Opening](../features/case-opening.md).

### Bank

Folgende Befehle verwalten dein Geld auf der Bank. Die Bank ist ein Zwischenspeicher, damit du dein Geld sicher ablegen kannst.

* `/bank guthaben` - Zeige dein Guthaben auf der Bank an.
* `/bank einzahlen <Geldmenge>` - Zahle die angegebene Menge Geld in die Bank ein.
* `/bank abheben <Geldmenge>` | `/bank auszahlen <Geldmenge>` - Hebe die angegebene Menge Geld von der Bank ab.
