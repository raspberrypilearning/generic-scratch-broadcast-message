En udsendelse er en måde at sende et signal fra en sprite, som kan høres af alle sprites. Tænk på det som en meddelelse om en højttaler.

### Send en udsendelse

Du kan sende en udsendelse ved at oprette en broadcast-blok og give det et navn.

+ Find udsendelsesblokken i fanen Begivenheder.

+ Vælg **ny meddelelse** i rullemenuen, og indtast derefter din besked.

![Opret en udsendelse](images/create-a-broadcast.png)

Meddelelsesteksten kan være alt, hvad du kan lide, men det er nyttigt at give udsendelsen en fornuftig beskrivelse. Hvad der sker, når meddelelsen er modtaget afhænger af koden, du skriver.

### Modtag en udsendelse

En sprite kan reagere på en udsendelse ved at bruge denne blok:

![Modtag en udsendelse](images/receive-a-broadcast.png)

Du kan tilføje blokke under denne blok for at fortælle sprite hvad du skal gøre, når det modtager udsendelsessignalet.

![Modtag eksempel](images/receive-example.png)