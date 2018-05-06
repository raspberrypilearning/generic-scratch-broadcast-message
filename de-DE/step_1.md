Ein Broadcast ist eine Möglichkeit, ein Signal von einem Sprite zu senden, das von allen Sprites gehört werden kann. Stellen Sie es sich vor wie eine Ansage über einen Lautsprecher.

### Sende eine Sendung

Sie können einen Broadcast senden, indem Sie einen Broadcast-Block erstellen und ihm einen Namen geben.

+ Suchen Sie den Broadcast-Block auf der Registerkarte Ereignisse.

+ Wählen Sie | 123_8_0_321 | neue Nachricht | 123_9_1_321 | Im Dropdown-Menü geben Sie Ihre Nachricht ein.

![Erstelle eine Sendung](images/create-a-broadcast.png)

Der Nachrichtentext kann beliebig sein, aber es ist nützlich, der Sendung eine sinnvolle Beschreibung zu geben. Was passiert, wenn die Nachricht empfangen wird, hängt von dem Code ab, den Sie schreiben.

### Empfangen Sie eine Sendung

Ein Sprite kann mit diesem Block auf eine Übertragung reagieren:

![Empfange eine Sendung](images/receive-a-broadcast.png)

Sie können Blöcke unterhalb dieses Blocks hinzufügen, um dem Sprite mitzuteilen, was zu tun ist, wenn es das Broadcast-Signal empfängt.

![Beispiel erhalten](images/receive-example.png)