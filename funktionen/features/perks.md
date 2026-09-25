---
description: Nützliche Spielunterstützungen für dich
---

# ⬆️ Perks

Mit Perks hast du die Möglichkeit, Effekte und kleine Funktionen für dich zu aktivieren, die dich beim Spielen unterstützen.

<div align="center"><img src="../../.gitbook/assets/unknown.png" alt=""></div>

Um das Hauptmenü zu öffnen, gib `/perks` ein oder öffne das Perks-Menü über das Hilfemenü `/?`.

## Die Perks

Im Hauptmenü findest du eine Übersicht über die existierenden Perks. Wenn du mit der Maus über ein Perk fährst, werden dir die Informationen zum Perk, die verbleibende Laufzeit und der aktuelle Status (aktiviert oder deaktiviert) angezeigt.

<figure><img src="../../.gitbook/assets/image (1) (3).png" alt=""><figcaption><p>Perk-Beschreibung (Plot-Fliegen)</p></figcaption></figure>

### Perks einlösen / erhalten

Die Perks können über einlösbare Items erhalten und verlängert werden.

<figure><img src="../../.gitbook/assets/image (2) (3).png" alt=""><figcaption><p>Beispiel: Item 14-Tage Plot-Fliegen</p></figcaption></figure>

Die Items gibt es je nach Perk mit verschiedenen Laufzeiten und an unterschiedlichen Stellen auf der Cloud, z. B. im [Case-Opening](case-opening.md), im [Adventure-Shop](die-handler.md#amin-shop) oder als [Belohnung für Erfolge](erfolge-advancements.md).

{% hint style="info" %}
Die Tage können nacheinander eingelöst werden und erhöhen die Gesamtlaufzeit des Perks. Es gibt hierbei keine Obergrenze der verfügbaren Tage.
{% endhint %}

{% hint style="warning" %}
Löst du ein Perk ein, das du noch nicht besessen hast oder das bereits abgelaufen war, wird es **nicht automatisch aktiviert**.
{% endhint %}

### Perks aktivieren / deaktivieren

Um ein Perk zu aktivieren oder zu deaktivieren, klicke im Perk-Menü `/perks` auf das gewünschte Perk. Das Perk zeigt seinen Status in der Item-Beschreibung (Lore) an. Zudem wird ein aktiviertes Perk im Menü verzaubert dargestellt.

### Laufzeitberechnung

Die Perks laufen immer pro Kalendertag der Aktivierung.

An jedem Tag, an dem du das Perk aktivierst oder dich mit aktiviertem Perk einloggst, wird ein Tag abgezogen. Das Perk läuft dann bis zum Ende des Kalendertages. Ein Perk wird also nur „berechnet“, wenn du es nutzt bzw. online bist.

{% hint style="info" %}
Aktivierst du ein Perk also nachts um 23 Uhr, beträgt die Laufzeit für diesen Tag nur noch eine Stunde. Bei einem Login nach 0 Uhr wird ein weiterer Tag abgezogen.
{% endhint %}

## Einstellungen Shulker-View + Litematica

{% hint style="danger" %}
Litematica führt Aktionen aus, die ein Spieler normalerweise nicht ausführen kann, und das in sehr großer Zahl. Ohne die folgende Einstellung können dadurch Shulker-Kisten durch einen Schutzmechanismus verloren gehen.
{% endhint %}

Damit Shulker-Kisten beim Öffnen mit aktivem Litematica nicht vom Schutz entfernt werden, musst du in Litematica eine Vorkehrung treffen.

In Litematica muss ein Slot im Menü deaktiviert werden. Das ist aktuell nur bei den **Hotbar-Slots** möglich, weshalb dort ein Slot gewählt werden muss. Nachdem der Slot für Litematica deaktiviert wurde, muss dieser Slot immer für das Öffnen der Shulker-Kisten verwendet werden.

### Wie deaktiviere ich Litematica-Slots?

1. Gehe im Litematica-Menü auf **Configuration menu**.

   <figure><img src="../../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>
2. Wähle den Reiter **Generic**.
3. Entferne in der Einstellung `pickBlockableSlots` einen Slot deiner Wahl.

{% hint style="info" %}
Wir empfehlen, **Slot 9** zu wählen – das ist der letzte Slot in deiner Hotbar.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>
