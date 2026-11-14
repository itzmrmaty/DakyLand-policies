# Zásady ochrany soukromí DakyLandu

Bot ukládá do místní SQLite databáze identifikátory serveru, vlastníka, kanálu, rolí, sledovaných účtů, videí, streamů a odeslaných oznámení. Používá je k uložení nastavení, prevenci duplicit a úpravě oznámení.

Při zapnutých textových příkazech bot přijímá obsah zpráv z dostupných kanálů a rozpoznává příkazy !m a jejich argumenty. Běžné zprávy do databáze neukládá. Hudební fronta je v paměti do ukončení relace. Odkaz nebo název skladby se používá k načtení zvuku z YouTube. Při výběru role bot zpracuje identifikátor člena a role, aby roli přidal nebo odebral na Discordu.

Bot získává veřejná data z YouTube, TikToku a Kicku. Provozní záznamy mohou obsahovat čas, typ příkazu a identifikátory serveru, účtu, streamu nebo oznámení. Správce instalace určuje dobu uchování databáze a záznamů. Bot nemá automatickou dobu výmazu uloženého nastavení a historie oznámení.

O přístup, opravu nebo smazání údajů požádej správce konkrétní instalace. U instalace od autora můžeš o soukromý kontakt požádat přes správce Discord serveru nebo účet [itzmrmaty](https://github.com/itzmrmaty).

[Podmínky používání](TERMS.md)
