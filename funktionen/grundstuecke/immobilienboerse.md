---
description: Grundstücke zum Verkauf anbieten und passende Grundstücke finden
---

# Immobilienbörse

In der **Immobilienbörse** kannst du deine Grundstücke zum Verkauf anbieten und nach Grundstücken anderer Spieler suchen.

Die Immobilienbörse öffnest du über einen NPC mit der Funktion **Immobilienbörse**. Diese Funktion kann auch ein [Plot-NPC](plot-npc.md) übernehmen.

## Angebote ansehen

Im Hauptmenü siehst du alle aktuellen Angebote. Auf jedem Angebot stehen der **Anbieter**, eine kurze **Beschreibung**, der **Preis** und die **Tags** des Grundstücks. Beim Preis siehst du außerdem, ob es sich um einen **Festpreis** handelt oder ob der Preis **verhandelbar** ist.

* **Linksklick:** Du wirst zum Grundstück teleportiert und kannst es dir vor Ort ansehen.
* **Rechtsklick:** Das Angebot kommt auf deine Beobachtungsliste oder wird wieder davon entfernt.

Deine beobachteten Angebote findest du unter „**Meine beobachteten Inserate**“. Über den **Filter** kannst du dir nur Angebote mit einem bestimmten Tag anzeigen lassen, z. B. Shop, Spawner oder Redstone.

In der **Angebotshistorie** findest du alle Angebote, die in den letzten **30 Tagen** abgelaufen sind oder beendet wurden.

{% hint style="info" %}
Gekauft wird ein Grundstück nicht direkt in der Immobilienbörse. Melde dich beim Anbieter, z. B. im Chat, und sprecht den Kauf miteinander ab. Das Grundstück überträgt der Anbieter anschließend mit `/setowner` an dich (siehe [Grundstücksrechte](grundstucksrechte.md#besitzer-andern)).
{% endhint %}

## Grundstück anbieten

1. „**Meine Angebote**“ öffnen und auf „**Angebot erstellen**“ klicken.
2. Die **ID** deines Grundstücks im Chat angeben, z. B. `45;22`. Die ID findest du mit `/p i` (siehe [Grundstücks-Information](../grundbefehle/grundstucks-befehle/grundstucks-information.md)).
3. Den **Preis** festlegen und auswählen, ob er als **Festpreis** oder als **verhandelbar** angezeigt wird.
4. Eine **Beschreibung** mit höchstens **50 Zeichen** schreiben.
5. **1 bis 3 Tags** auswählen.
6. Das Angebot erstellen und bestätigen.

{% hint style="warning" %}
* Du kannst nur Grundstücke anbieten, die dir gehören.
* Jedes Grundstück kann nur einmal gleichzeitig angeboten werden.
* Die Anzahl deiner aktiven Angebote ist begrenzt.
{% endhint %}

## Angebote verwalten

Unter „**Meine Angebote**“ findest du alle deine Angebote.

* **Linksklick:** Das Angebot wird nach einer Bestätigung beendet.
* **Rechtsklick:** Du kannst Preis, Beschreibung und Tags bearbeiten. Die Grundstücks-ID lässt sich nicht mehr ändern.

Ein Angebot läuft **30 Tage** und endet danach automatisch. Hast du dein Grundstück schon vorher verkauft, beende das Angebot bitte selbst.
