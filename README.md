JoinLeftPlugin
Jednoduchý Minecraft plugin pro Paper / Spigot server, který upravuje zprávy při připojení a odpojení hráče pomocí config.yml.

Funkce
- Vlastní join message
- Vlastní quit message
- Nastavení přes config
- Podpora barev (&a, &c, &e...)
- Placeholder %player% pro jméno hráče
- /reloadconfig command pro reload configu bez restartu serveru

---

Instalace
Stáhni .jar pluginu
Nahraj soubor do složky:

/plugins/


Restartuj server
Hotovo

---

Config
Po prvním spuštění se vytvoří config.yml:

join-message: "&eHráč %player% se připojil"

quit-message: "&cHráč %player% se odpojil"


Placeholdery
| Placeholder | Popis |
|---|---|
| %player% | Jméno hráče |

Barvy
Používej Minecraft color codes:

&a zelená
&c červená
&e žlutá
&6 zlatá
&b světle modrá


Příklad:

join-message: "&aVítej %player% na serveru!"

quit-message: "&c%player% odešel."


---

Commandy
/reloadconfig
Reloadne config pluginu bez restartu serveru.

Permission:

joinleftplugin.reload


---

Autor
Lakas988
