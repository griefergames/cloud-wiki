---
description: Funktion und Ablauf des Checkplot-Systems
---

# Grundstücke inaktiver Spieler beantragen

Wer kennt es nicht, man möchte sein Grundstück erweitern oder mergen, und im Weg liegt ein so gut wie leeres Grundstück von einem Spieler, den man noch nie gesehen hat.

Mit dem `/checkplot`-System ist es möglich, inaktive Grundstücke zu beantragen.

## Beantragen eines Grundstücks

Um ein Grundstück zu beantragen, stelle dich auf das Grundstück und gib `/checkplot` ein. Dann öffnet sich eine Übersicht des aktuellen Grundstücks.

<figure><img src="../../.gitbook/assets/image (23) (1).png" alt=""><figcaption><p>Checkplot-Ansicht</p></figcaption></figure>

{% hint style="info" %}
Wenn ein Grundstück nicht betreten werden kann, stelle dich neben das Grundstück und gib dort `/checkplot` ein.
{% endhint %}

In dieser Ansicht werden dir die Details, die für oder gegen einen Antrag sprechen, angezeigt.

1. **Besitzer des Grundstücks**\
   Hier wird der Besitzer des Grundstücks, der Alias des Grundstücks und der Zeitpunkt, wann der Spieler zuletzt online war, angezeigt.
2. **Informationen zur Spielzeit**\
   Hier wird angezeigt, ab wann das Grundstück übernommen werden kann. Ein **unbebautes** Grundstück kann **1 Monat** nach dem letzten Login des Besitzers übernommen werden, ein **bebautes** Grundstück in der Regel erst nach **3 Monaten**.
3. **Informationen zur Nachbarschaft**\
   Hier wird angezeigt, wie weit dein nächstes eigenes Grundstück entfernt ist. Einen Antrag kannst du nur stellen, wenn dir ein Grundstück gehört, das höchstens **3 Grundstücke** entfernt liegt.
4. **Information zum Antragsteller (dir)**\
   Hier wird angezeigt, wie viele Checkplot-Anträge aktuell von dir gelistet sind. Du kannst höchstens **5** offene Anträge gleichzeitig haben.

{% hint style="warning" %}
Verbundene (gemergte) Grundstücke und Grundstücke auf Spawn-Servern können nicht über `/checkplot` beantragt werden.
{% endhint %}

Je nachdem, ob die angezeigte Information einen Antrag ermöglicht oder nicht ermöglicht, wird in der Info Folgendes angezeigt:

![](<../../.gitbook/assets/image (27).png>) ![](<../../.gitbook/assets/image (29) (3).png>)

Wenn der Antrag möglich ist, wird unten rechts ein <img src="../../.gitbook/assets/image (26).png" alt="" data-size="line"> **Schild** angezeigt. Ist der Antrag nicht möglich, wird eine <img src="../../.gitbook/assets/image (24).png" alt="" data-size="line"> **Barriere** angezeigt.

Mit einem Klick auf das Schild und einer anschließenden Bestätigung kannst du den Antrag einreichen.

## Bearbeitung des Antrags

Den Status deiner Anträge kannst du jederzeit mit `/checkplot list` einsehen.

<figure><img src="../../.gitbook/assets/image (8) (1).png" alt=""><figcaption><p>Liste der Anträge</p></figcaption></figure>

Die Checkplot-Anträge werden mindestens einmal in der Woche bearbeitet. Du erhältst also zeitnah eine Nachricht darüber, ob du das Grundstück übernehmen kannst.

Solange dein Antrag noch nicht abgeschlossen ist, kannst du ihn in der Checkplot-Ansicht des Grundstücks über „**Checkplot-Antrag löschen**“ zurückziehen.

## Übernehmen des Grundstücks

Um das Grundstück eines angenommenen Antrags zu erhalten, gehe auf das entsprechende Grundstück und gib `/checkplot` ein. An der Stelle des <img src="../../.gitbook/assets/image (26).png" alt="" data-size="line"> Schildes befindet sich nun eine <img src="../../.gitbook/assets/image (37).png" alt="" data-size="line"> **Tür**, mit der das Grundstück in Besitz genommen werden kann.

Danach bestätigst du die Aktion und das Grundstück wird <mark style="color:green;">**gelöscht**</mark> und an dich überschrieben.

{% hint style="danger" %}
Nach der Annahme hast du **14 Tage** Zeit, das Grundstück zu übernehmen. Danach wird der Antrag automatisch abgelehnt.
{% endhint %}

{% hint style="warning" %}
Beim Übernehmen gelten dieselben Kosten wie bei `/p claim`: Besitzt du bereits **4 oder mehr** Grundstücke, werden **10.000 Dollar** fällig. Grundstücksgutscheine können hier nicht verwendet werden. Hast du dein Grundstückslimit erreicht, kannst du das Grundstück nicht übernehmen.
{% endhint %}

{% hint style="info" %}
Sollte es nicht möglich sein, ein Grundstück über das Checkplot-System zu beantragen, kann das Grundstück ggf. über das Ticket-System (Web oder Discord) erhalten werden.
{% endhint %}
