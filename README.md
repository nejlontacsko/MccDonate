# MccDonate
MicroCoin Donate Stream Overlay

Ezt a rövidke HTML oldalt használva egy, a MicroCoin (MCC) hálózatát használó támogató rendszer kap egy streamer vagy YouTuber.

## Hogyan használd?

1. Töltsd le az állományokat és mentsd le őket egy mappába egymás mellé!
2. OBS Stúdióban a források közé vegyél fel egy "Böngésző" típusút!
3. Nevezd el úgy, hogy később is megismerd!
4. Pipáld be a "Helyi fájl" felíratú checkboxot, majd a "Local file" mező végében található "Tallózás" gombbal keresd meg, hogy hova mentetted, a `.html` kiterjesztésű fájlt!
5. Az alapján, hogy milyen hosszúságú üzeneteket vársz a nézőidtől, állítsd be a szélességet és a magasságot! (de minimum legyen `600x400`!)
6. Az "Egyéni CSS" mezőben kell lennie egy sornak, abban a `margin: 0px auto` lehet érdekes, itt pixelben finomhangolni, hogy mekkora margókkal jelenjen meg az üzenet. Ha esetleg mégis üres lenne ez a mező, akkor másold be ezt:
`body { background-color: rgba(0, 0, 0, 0); margin: 0px auto; overflow: hidden; }`
7. "OK" megnyomása után már a képen meg kell jelennie egy átlátszó rétegnek piros szegélyekkel. Ezt helyezdel nagyjából a képernyő közepére, a tetejéhez igazítva, szerintem ott jól néz ki.
8. Hamarosan fel kell ugrania a képen egy `Csatlakoztatva!` vagy egy `Hiba lépett fel!` üzenetnek. Előbbi jelzi, hogy látja a Rider szervert és készen áll az alkalmazás az utalások fogadására. Utóbbi esetén nyisd meg hagyományos böngészőben (pl. Google Chrome-ban), majd az "F12" billentyű leütése utána, a Console lapon kell látnod a hibát. Ha nem érted vagy nem tudod megoldani akkor keress bátran! Ha itt a csatlakoztatva üzenet jelenik meg, akkor egyszerűen próbáld újra az OBS-ben, mert már ott is jónak kell már lennie!
9. Használd egészséggel és fejezd ki hálád a támogatást küldő nézőidnek! :)

### Youtube tutorial
_hamarosan_

### Konfiguráció
_hamarosan_
