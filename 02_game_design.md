# 2. Game Design

## Cíl hry
Hráč musí v herním prostředí nalézt a sebrat **5 klíčových předmětů** (items). Po sebrání všech předmětů hra končí vítězstvím.

## Herní mechaniky a pravidla

### Hráč (Player)
* **Pohyb:** Chůze a běh.
* **Vybavení:** Baterka (Flashlight).
* **Akce:**
    * *Toggle Flashlight:* Zapnutí/vypnutí baterky (F).
    * *Interact:* Sebrání předmětu.

### Monstrum (Enemy)
* **Chování (AI):** Monstrum neustále pronásleduje hráče.
* **Speciální vlastnost (Light Freeze):** Pokud hráč posvítí baterkou přímo na monstrum, monstrum „zkamení“ a **nehýbe se**.
* **Obnovení pohybu:** Jakmile hráč uhne pohledem, zhasne baterku, monstrum se znovu rozběhne.

## Prostředí a Lore
Hra se odehrává v noci. Prostředí je tvořeno hustým lesem obklopujícím starou dřevěnou chatu. Viditelnost je omezena mlhou a tmou, což zvyšuje důležitost baterky. Hráč je ztracen a musí najít items, aby se dostal pryč.
